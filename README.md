Site metrics exporter for Prometheus
====================================

Exports site metrics using PhantomAS into Prometheus scraper format.

```
$ docker build .
$ docker run -p 9149:9149 
$ curl -s 'http://localhost:9149/?url=https://torchbox.com/'
requests 50
gzip_requests 11
post_requests 1
https_requests 50
not_found 0
body_size 378885
content_length 4745796
http_traffic_completed 3311
time_to_first_byte 536
time_to_last_byte 562
ajax_requests 2
html_count 5
html_size 15602
css_count 1
css_size 156053
js_count 12
js_size 71955
json_count 1
json_size 65
image_count 22
image_size 4345705
video_count 0
video_size 0
webfont_count 8
webfont_size 156416
base64_count 0
base64_size 0
other_count 1
other_size 0
cache_hits 28
cache_misses 1
cache_passes 0
caching_not_specified 0
caching_too_short 9
caching_disabled 4
old_caching_headers 40
console_messages 0
cookies_sent 0
cookies_recv 102
domains_with_cookies 1
document_cookies_length 77
document_cookies_count 3
document_height 5606
comments_size 58
white_spaces_size 9260
d_o_melements_count 249
d_o_melement_max_depth 10
nodes_with_inline_c_s_s 0
images_scaled_down 0
images_without_dimensions 2
d_o_mid_duplicated 2
hidden_content_size 716
hidden_images 1
d_o_mmutations_inserts 36
d_o_mmutations_removes 31
d_o_mmutations_attributes 15
d_o_mqueries 72
d_o_mqueries_without_results 14
d_o_mqueries_by_id 3
d_o_mqueries_by_class_name 15
d_o_mqueries_by_tag_name 52
d_o_mqueries_by_query_selector_all 2
d_o_minserts 50
d_o_mqueries_duplicated 9
d_o_mqueries_avoidable 42
domains 18
max_requests_per_domain 22
median_requests_per_domain 1
events_bound 13
events_dispatched 0
events_scroll_bound 0
global_variables 22
global_variables_falsy 0
headers_count 792
headers_sent_count 160
headers_recv_count 632
headers_size 27248
headers_sent_size 5621
headers_recv_size 21627
headers_bigger_than_content 11
j_query_version 1.10.2
j_query_versions_loaded 1
j_query_on_d_o_m_ready_functions 5
j_query_window_on_load_functions 0
j_query_sizzle_calls 21
j_query_event_triggers 1
j_query_d_o_m_reads 0
j_query_d_o_m_writes 1
j_query_d_o_m_write_read_switches 0
document_write_calls 0
eval_calls 0
js_errors 0
closed_connections 0
lazy_loadable_images_below_the_fold 12
local_storage_entries 0
redirects 4
redirects_time 963
repaints 0
first_paint 0
requests_to_first_paint 0
domains_to_first_paint 0
requests_to_dom_content_loaded 9
domains_to_dom_content_loaded 5
requests_to_dom_complete 48
domains_to_dom_complete 17
assets_not_gzipped 5
assets_with_query_string 10
assets_with_cookies 1
small_images 6
small_css_files 0
small_js_files 5
multiple_requests 0
time_to_first_css 723
time_to_first_js 659
time_to_first_image 1544
dom_interactive 828
dom_content_loaded 819
dom_content_loaded_end 933
dom_complete 2628
time_backend 17
time_frontend 83
requests_with_timeout 0
status_codes_trail 200
window_alerts 0
window_confirms 0
window_prompts 0
body_h_t_m_l_size 22805
iframes_count 0
smallest_response 0
biggest_response 907420
fastest_response 36
slowest_response 998
smallest_latency 35
biggest_latency 696
median_response 527
median_latency 469
```
