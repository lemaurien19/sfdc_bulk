# sfdc_bulk
edited sfdc_bulk from d. rauscher

added method "get_result_id_or_list" which checks how many result ids are retrieved.
if more than 1, keeps result as a list ['somesalesforceid','anotherid'] and returns it.
if only 1 result is retrieved, returns it as a string to be used with existin method 'get_query_result'.
