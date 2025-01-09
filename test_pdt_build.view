view: test_pdt_build {
  derived_table: {
    publish_as_db_view: yes
    sql: SELECT * FROM `turnkey-slice-432515-a4.cmek_test1.citibike_stations` limit 1002 ;;
    sql_trigger_value: select CURRENT_TIMESTAMP - 1  ;;
  }
  dimension: station_id {
    sql: ${TABLE}.station_id ;;
    type: string
  }
}
