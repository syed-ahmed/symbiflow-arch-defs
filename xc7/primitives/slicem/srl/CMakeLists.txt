add_file_target(FILE srlc32e_vpr.model.xml SCANNER_TYPE xml)
add_file_target(FILE srlc32e_vpr.pb_type.xml SCANNER_TYPE xml)

add_file_target(FILE ntemplate.N_srl.pb_type.xml SCANNER_TYPE xml)

n_template(
  NAME N_srl.pb_type.xml
  PREFIXES a;b;c;d
  SRCS ntemplate.N_srl.pb_type.xml
)

