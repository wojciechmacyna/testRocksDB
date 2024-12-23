add_executable(column_families_example
  column_families_example.cc)
target_link_libraries(column_families_example
  ${ROCKSDB_LIB})

