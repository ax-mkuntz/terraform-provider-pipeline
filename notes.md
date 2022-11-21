https://github.com/hashicorp/terraform-plugin-sdk/blob/main/helper/schema/field_writer_map.go#L72

2022/11/21 13:57:09 [ERROR] setting state: form_json_values.0.label: can only set full list

		keyBase := fmt.Sprintf("form_json_values.%d.", i)
		errors = append(errors, setValue(keyBase+"label", it.Label)...)