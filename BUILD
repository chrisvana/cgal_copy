[
  { "cmake": {
    "name": "cgal_make",
    "cmake_args" : [ "-DBOOST_ROOT=$ROOT_DIR/$BOOST_ROOT",
                     "-DBOOST_INCLUDEDIR=$ROOT_DIR/$BOOST_INCLUDEDIR",
                     "-DBoost_NO_SYSTEM_PATHS=TRUE",
                     "-DGMP_INCLUDE_DIR=$ROOT_DIR/$GMP_INCLUDE",
                     "-DGMP_LIB_DIR=$ROOT_DIR/$GMP_LIB",
                     "-DMPFR_INCLUDE_DIR=$ROOT_DIR/$MPFR_INCLUDE",
                     "-DMPFR_LIB_DIR=$ROOT_DIR/$MPFR_LIB"
    ],
    "dependencies": [ "../boost:boost", "../mpfa:mpfa", "../gmp:gmp" ],
    "make_target": "",
    "outs": [
     ],
    "licenses": [ "http://opensource.org/licenses/BSL-1.0",
                  "http://opensource.org/licenses/gpl-3.0",
                  "http://opensource.org/licenses/lgpl-3.0",
                  "http://opensource.org/licenses/MIT" ]
  } },
  { "cc_library": {
     "name": "cgal",
     "cc_objects": [
     ],
     "strict_file_mode": false,
     "include_dirs": [ "." ],
     "dependencies": [ ":cgal_make" ],
     "cc_linker_args": [ "-lz" ]
  } }
]
