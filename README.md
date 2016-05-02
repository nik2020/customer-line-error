# customer-line-error
} elseif (($custom_field['type'] == 'text' &&
 !empty($custom_field['validation']) && 
$custom_field['location'] == 'address') && 
!filter_var($value['custom_field'][$custom_field['custom_field_id']], 

FILTER_VALIDATE_REGEXP, array('options' => array('regexp' => $custom_field

['validation'])))) {
