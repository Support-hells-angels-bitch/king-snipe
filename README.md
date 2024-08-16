# king-snipe


function() {

    var data = {
        "resource": {
            "version": "1",

            "macros": [{
                "function": "__e"
            }, {
                "vtp_signal": 1,
                "function": "__c",
                "vtp_value": 1
            }, {
                "function": "__c",
                "vtp_value": ""
            }, {
                "function": "__c",
                "vtp_value": 0
            }, {
                "vtp_signal": 1,
                "function": "__c",
                "vtp_value": 1
            }, {
                "function": "__c",
                "vtp_value": ""
            }, {
                "function": "__c",
                "vtp_value": 0
            }],
            "tags": [{
                "function": "__ogt_1p_data_v2",
                "priority": 15,
                "vtp_isAutoEnabled": true,
                "vtp_autoCollectExclusionSelectors": ["list", ["map", "exclusionSelector", ""]],
                "vtp_isEnabled": true,
                "vtp_cityType": "CSS_SELECTOR",
                "vtp_manualEmailEnabled": false,
                "vtp_firstNameType": "CSS_SELECTOR",
                "vtp_countryType": "CSS_SELECTOR",
                "vtp_cityValue": "",
                "vtp_emailType": "CSS_SELECTOR",
                "vtp_regionType": "CSS_SELECTOR",
                "vtp_autoEmailEnabled": true,
                "vtp_postalCodeValue": "",
                "vtp_lastNameValue": "",
                "vtp_phoneType": "CSS_SELECTOR",
                "vtp_phoneValue": "",
                "vtp_streetType": "CSS_SELECTOR",
                "vtp_autoPhoneEnabled": false,
                "vtp_postalCodeType": "CSS_SELECTOR",
                "vtp_emailValue": "",
                "vtp_firstNameValue": "",
                "vtp_streetValue": "",
                "vtp_lastNameType": "CSS_SELECTOR",
                "vtp_autoAddressEnabled": false,
                "vtp_regionValue": "",
                "vtp_countryValue": "",
                "vtp_isAutoCollectPiiEnabledFlag": false,
                "tag_id": 10
            }, {
                "function": "__ccd_ga_first",
                "priority": 14,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 26
            }, {
                "function": "__set_product_settings",
                "priority": 13,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "vtp_foreignTldMacroResult": ["macro", 5],
                "vtp_isChinaVipRegionMacroResult": ["macro", 6],
                "tag_id": 25
            }, {
                "function": "__ccd_ga_ads_link",
                "priority": 12,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 24
            }, {
                "function": "__ogt_google_signals",
                "priority": 11,
                "vtp_googleSignals": "ENABLED",
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "vtp_serverMacroResult": ["macro", 4],
                "tag_id": 23
            }, {
                "function": "__ccd_ga_regscope",
                "priority": 10,
                "vtp_settingsTable": ["list", ["map", "redactFieldGroup", "DEVICE_AND_GEO", "disallowAllRegions", false, "disallowedRegions", ""], ["map", "redactFieldGroup", "GOOGLE_SIGNALS", "disallowAllRegions", false, "disallowedRegions", ""]],
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 22
            }, {
                "function": "__ccd_em_download",
                "priority": 9,
                "vtp_includeParams": true,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 21
            }, {
                "function": "__ccd_em_outbound_click",
                "priority": 8,
                "vtp_includeParams": true,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 20
            }, {
                "function": "__ccd_em_page_view",
                "priority": 7,
                "vtp_historyEvents": true,
                "vtp_includeParams": true,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 19
            }, {
                "function": "__ccd_em_scroll",
                "priority": 6,
                "vtp_includeParams": true,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 18
            }, {
                "function": "__ccd_em_site_search",
                "priority": 5,
                "vtp_searchQueryParams": "SearchableText",
                "vtp_includeParams": true,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 17
            }, {
                "function": "__ccd_em_video",
                "priority": 4,
                "vtp_includeParams": true,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 16
            }, {
                "function": "__ccd_conversion_marking",
                "priority": 3,
                "vtp_conversionRules": ["list", ["map", "matchingRules", "{\"type\":5,\"args\":[{\"stringValue\":\"purchase\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"], ["map", "matchingRules", "{\"type\":5,\"args\":[{\"stringValue\":\"bank_robbers_app_pageview\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"], ["map", "matchingRules", "{\"type\":5,\"args\":[{\"stringValue\":\"visit_duration\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"], ["map", "matchingRules", "{\"type\":5,\"args\":[{\"stringValue\":\"pages_screens_per_session\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"]],
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 15
            }, {
                "function": "__ogt_event_create",
                "priority": 2,
                "vtp_eventName": "bank_robbers_app_pageview",
                "vtp_isCopy": true,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "vtp_precompiledRule": ["map", "new_event_name", "bank_robbers_app_pageview", "merge_source_event_params", true, "event_name_predicate", ["map", "values", ["list", ["map", "type", "event_name"], ["map", "type", "const", "const_value", "page_view"]], "type", "eq"], "conditions", ["list", ["map", "predicates", ["list", ["map", "values", ["list", ["map", "type", "event_param", "event_param", ["map", "param_name", "page_path"]], ["map", "type", "const", "const_value", "\/news\/apps\/bank-robbers-app"]], "type", "swi"]]]], "event_param_ops", ["list", ["map", "edit_param", ["map", "param_name", "value", "param_value", ["map", "type", "const", "const_value", "0.0"]]], ["map", "edit_param", ["map", "param_name", "currency", "param_value", ["map", "type", "const", "const_value", "USD"]]]]],
                "tag_id": 14
            }, {
                "function": "__ccd_auto_redact",
                "priority": 1,
                "vtp_redactEmail": false,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 13
            }, {
                "function": "__gct",
                "vtp_trackingId": "G-DBEM2FVVRF",
                "vtp_sessionDuration": 0,
                "vtp_googleSignals": ["macro", 1],
                "vtp_foreignTld": ["macro", 2],
                "vtp_restrictDomain": ["macro", 3],
                "tag_id": 7
            }, {
                "function": "__ccd_ga_last",
                "priority": 0,
                "vtp_instanceDestinationId": "G-DBEM2FVVRF",
                "tag_id": 12
            }],
            "predicates": [{
                "function": "_eq",
                "arg0": ["macro", 0],
                "arg1": "gtm.js"
            }, {
                "function": "_eq",
                "arg0": ["macro", 0],
                "arg1": "gtm.init"
            }],
            "rules": [[["if", 0], ["add", 15]], [["if", 1], ["add", 0, 16, 14, 13, 12, 11, 10, 9, 8, 7, 6, 5, 4, 3, 2, 1]]]
        },
        "runtime": [[50, "__c", [46, "a"], [36, [17, [15, "a"], "value"]]], [50, "__ccd_auto_redact", [46, "a"], [50, "v", [46, "bk"], [36, [2, [15, "bk"], "replace", [7, [15, "u"], "\\$1"]]]], [50, "w", [46, "bk"], [52, "bl", ["c", [15, "bk"]]], [52, "bm", [7]], [65, "bn", [2, [15, "bl"], "split", [7, ""]], [46, [53, [52, "bo", [7, ["v", [15, "bn"]]]], [52, "bp", ["d", [15, "bn"]]], [22, [12, [15, "bp"], [45]], [46, [36, ["d", ["v", [15, "bk"]]]]]], [22, [21, [15, "bp"], [15, "bn"]], [46, [2, [15, "bo"], "push", [7, [15, "bp"]]], [22, [21, [15, "bn"], [2, [15, "bn"], "toLowerCase", [7]]], [46, [2, [15, "bo"], "push", [7, ["d", [2, [15, "bn"], "toLowerCase", [7]]]]]], [46, [22, [21, [15, "bn"], [2, [15, "bn"], "toUpperCase", [7]]], [46, [2, [15, "bo"], "push", [7, ["d", [2, [15, "bn"], "toUpperCase", [7]]]]]]]]]]], [22, [18, [17, [15, "bo"], "length"], 1], [46, [2, [15, "bm"], "push", [7, [0, [0, "(?:", [2, [15, "bo"], "join", [7, "|"]]], ")"]]]], [46, [2, [15, "bm"], "push", [7, [16, [15, "bo"], 0]]]]]]]], [36, [2, [15, "bm"], "join", [7, ""]]]], [50, "x", [46, "bk", "bl", "bm"], [52, "bn", ["z", [15, "bk"], [15, "bm"]]], [22, [28, [15, "bn"]], [46, [36, [15, "bk"]]]], [22, [28, [17, [15, "bn"], "search"]], [46, [36, [15, "bk"]]]], [41, "bo"], [3, "bo", [17, [15, "bn"], "search"]], [65, "bp", [15, "bl"], [46, [53, [52, "bq", [7, ["v", [15, "bp"]], ["w", [15, "bp"]]]], [65, "br", [15, "bq"], [46, [53, [52, "bs", [30, [16, [15, "t"], [15, "br"]], [43, [15, "t"], [15, "br"], ["b", [0, [0, "([?&]", [15, "br"]], "=)([^&]*)"], "gi"]]]], [3, "bo", [2, [15, "bo"], "replace", [7, [15, "bs"], [0, "$1", [15, "r"]]]]]]]]]]], [22, [20, [15, "bo"], [17, [15, "bn"], "search"]], [46, [36, [15, "bk"]]]], [22, [20, [16, [15, "bo"], 0], "&"], [46, [3, "bo", [2, [15, "bo"], "substring", [7, 1]]]]], [22, [21, [16, [15, "bo"], 0], "?"], [46, [3, "bo", [0, "?", [15, "bo"]]]]], [22, [20, [15, "bo"], "?"], [46, [3, "bo", ""]]], [43, [15, "bn"], "search", [15, "bo"]], [36, ["ba", [15, "bn"], [15, "bm"]]]], [50, "z", [46, "bk", "bl"], [22, [20, [15, "bl"], [17, [15, "s"], "PATH"]], [46, [3, "bk", [0, [15, "y"], [15, "bk"]]]]], [36, ["g", [15, "bk"]]]], [50, "ba", [46, "bk", "bl"], [41, "bm"], [3, "bm", ""], [22, [20, [15, "bl"], [17, [15, "s"], "URL"]], [46, [53, [41, "bn"], [3, "bn", ""], [22, [30, [17, [15, "bk"], "username"], [17, [15, "bk"], "password"]], [46, [3, "bn", [0, [15, "bn"], [0, [0, [0, [17, [15, "bk"], "username"], [39, [17, [15, "bk"], "password"], ":", ""]], [17, [15, "bk"], "password"]], "@"]]]]], [3, "bm", [0, [0, [0, [17, [15, "bk"], "protocol"], "//"], [15, "bn"]], [17, [15, "bk"], "host"]]]]]], [36, [0, [0, [0, [15, "bm"], [17, [15, "bk"], "pathname"]], [17, [15, "bk"], "search"]], [17, [15, "bk"], "hash"]]]], [50, "bb", [46, "bk", "bl"], [41, "bm"], [3, "bm", [2, [15, "bk"], "replace", [7, [15, "n"], [15, "r"]]]], [22, [30, [20, [15, "bl"], [17, [15, "s"], "URL"]], [20, [15, "bl"], [17, [15, "s"], "PATH"]]], [46, [53, [52, "bn", ["z", [15, "bm"], [15, "bl"]]], [22, [20, [15, "bn"], [44]], [46, [36, [15, "bm"]]]], [52, "bo", [17, [15, "bn"], "search"]], [52, "bp", [2, [15, "bo"], "replace", [7, [15, "o"], [15, "r"]]]], [22, [20, [15, "bo"], [15, "bp"]], [46, [36, [15, "bm"]]]], [43, [15, "bn"], "search", [15, "bp"]], [3, "bm", ["ba", [15, "bn"], [15, "bl"]]]]]], [36, [15, "bm"]]], [50, "bc", [46, "bk"], [22, [20, [15, "bk"], [15, "q"]], [46, [36, [17, [15, "s"], "PATH"]]], [46, [22, [21, [2, [15, "p"], "indexOf", [7, [15, "bk"]]], [27, 1]], [46, [36, [17, [15, "s"], "URL"]]], [46, [36, [17, [15, "s"], "TEXT"]]]]]]], [50, "bd", [46, "bk", "bl"], [41, "bm"], [3, "bm", false], [52, "bn", ["f", [15, "bk"]]], [38, [15, "bn"], [46, "string", "array", "object"], [46, [5, [46, [52, "bo", ["bb", [15, "bk"], [15, "bl"]]], [22, [21, [15, "bk"], [15, "bo"]], [46, [36, [15, "bo"]]]], [4]]], [5, [46, [53, [41, "bp"], [3, "bp", 0], [63, [7, "bp"], [23, [15, "bp"], [17, [15, "bk"], "length"]], [33, [15, "bp"], [3, "bp", [0, [15, "bp"], 1]]], [46, [53, [52, "bq", ["bd", [16, [15, "bk"], [15, "bp"]], [17, [15, "s"], "TEXT"]]], [22, [21, [15, "bq"], [44]], [46, [43, [15, "bk"], [15, "bp"], [15, "bq"]], [3, "bm", true]]]]]]], [4]]], [5, [46, [54, "bp", [15, "bk"], [46, [53, [52, "bq", ["bd", [16, [15, "bk"], [15, "bp"]], [17, [15, "s"], "TEXT"]]], [22, [21, [15, "bq"], [44]], [46, [43, [15, "bk"], [15, "bp"], [15, "bq"]], [3, "bm", true]]]]]], [4]]]]], [36, [39, [15, "bm"], [15, "bk"], [44]]]], [50, "bj", [46, "bk", "bl"], [52, "bm", [30, [2, [15, "bk"], "getMetadata", [7, [15, "bi"]]], [7]]], [22, [20, [2, [15, "bm"], "indexOf", [7, [15, "bl"]]], [27, 1]], [46, [2, [15, "bm"], "push", [7, [15, "bl"]]]]], [2, [15, "bk"], "setMetadata", [7, [15, "bi"], [15, "bm"]]]], [52, "b", ["require", "internal.createRegex"]], [52, "c", ["require", "decodeUriComponent"]], [52, "d", ["require", "encodeUriComponent"]], [52, "e", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "f", ["require", "getType"]], [52, "g", ["require", "parseUrl"]], [52, "h", ["require", "internal.registerCcdCallback"]], [52, "i", [17, [15, "a"], "instanceDestinationId"]], [52, "j", [17, [15, "a"], "redactEmail"]], [52, "k", [17, [15, "a"], "redactQueryParams"]], [52, "l", [39, [15, "k"], [2, [15, "k"], "split", [7, ","]], [7]]], [52, "m", "is_sgtm_prehit"], [22, [1, [28, [17, [15, "l"], "length"]], [28, [15, "j"]]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "n", ["b", "[A-Z0-9._%+-]+@[A-Z0-9.-]+\\.[A-Z]{2,}", "gi"]], [52, "o", ["b", [0, "([A-Z0-9._-]|%25|%2B)+%40[A-Z0-9.-]", "+\\.[A-Z]{2,}"], "gi"]], [52, "p", [7, "page_location", "page_referrer", "page_path", "link_url", "video_url", "form_destination"]], [52, "q", "page_path"], [52, "r", "(redacted)"], [52, "s", [8, "TEXT", 0, "URL", 1, "PATH", 2]], [52, "t", [8]], [52, "u", ["b", "([\\\\^$.|?*+(){}]|\\[|\\[)", "g"]], [52, "y", "http://."], [52, "be", 15], [52, "bf", 16], [52, "bg", 23], [52, "bh", 24], [52, "bi", "event_usage"], ["h", [15, "i"], [51, "", [7, "bk"], [22, [15, "j"], [46, [53, [52, "bl", [2, [15, "bk"], "getHitKeys", [7]]], [65, "bm", [15, "bl"], [46, [53, [22, [20, [15, "bm"], "_sst_parameters"], [46, [6]]], [52, "bn", [2, [15, "bk"], "getHitData", [7, [15, "bm"]]]], [22, [28, [15, "bn"]], [46, [6]]], [52, "bo", ["bc", [15, "bm"]]], [52, "bp", ["bd", [15, "bn"], [15, "bo"]]], [22, [21, [15, "bp"], [44]], [46, [2, [15, "bk"], "setHitData", [7, [15, "bm"], [15, "bp"]]], ["bj", [15, "bk"], [39, [2, [15, "bk"], "getMetadata", [7, [15, "m"]]], [15, "bg"], [15, "be"]]]]]]]]]]], [22, [17, [15, "l"], "length"], [46, [65, "bl", [15, "p"], [46, [53, [52, "bm", [2, [15, "bk"], "getHitData", [7, [15, "bl"]]]], [22, [28, [15, "bm"]], [46, [6]]], [52, "bn", [39, [20, [15, "bl"], [15, "q"]], [17, [15, "s"], "PATH"], [17, [15, "s"], "URL"]]], [52, "bo", ["x", [15, "bm"], [15, "l"], [15, "bn"]]], [22, [21, [15, "bo"], [15, "bm"]], [46, [2, [15, "bk"], "setHitData", [7, [15, "bl"], [15, "bo"]]], ["bj", [15, "bk"], [39, [2, [15, "bk"], "getMetadata", [7, [15, "m"]]], [15, "bh"], [15, "bf"]]]]]]]]]]]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_conversion_marking", [46, "a"], [22, [30, [28, [17, [15, "a"], "conversionRules"]], [20, [17, [17, [15, "a"], "conversionRules"], "length"], 0]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "b", ["require", "internal.copyPreHit"]], [52, "c", ["require", "internal.evaluateBooleanExpression"]], [52, "d", ["require", "internal.registerCcdCallback"]], [52, "e", "is_conversion"], [52, "f", "is_first_visit"], [52, "g", "is_first_visit_conversion"], [52, "h", "is_session_start"], [52, "i", "is_session_start_conversion"], [52, "j", "first_visit"], [52, "k", "session_start"], [41, "l"], [41, "m"], ["d", [17, [15, "a"], "instanceDestinationId"], [51, "", [7, "n"], [52, "o", [8, "preHit", [15, "n"]]], [65, "p", [17, [15, "a"], "conversionRules"], [46, [22, ["c", [17, [15, "p"], "matchingRules"], [15, "o"]], [46, [2, [15, "n"], "setMetadata", [7, [15, "e"], true]], [4]]]]], [22, [2, [15, "n"], "getMetadata", [7, [15, "f"]]], [46, [22, [28, [15, "l"]], [46, [53, [52, "p", ["b", [15, "n"], [8, "omitHitData", true, "omitMetadata", true]]], [2, [15, "p"], "setEventName", [7, [15, "j"]]], [3, "l", [8, "preHit", [15, "p"]]]]]], [65, "p", [17, [15, "a"], "conversionRules"], [46, [22, ["c", [17, [15, "p"], "matchingRules"], [15, "l"]], [46, [2, [15, "n"], "setMetadata", [7, [15, "g"], true]], [4]]]]]]], [22, [2, [15, "n"], "getMetadata", [7, [15, "h"]]], [46, [22, [28, [15, "m"]], [46, [53, [52, "p", ["b", [15, "n"], [8, "omitHitData", true, "omitMetadata", true]]], [2, [15, "p"], "setEventName", [7, [15, "k"]]], [3, "m", [8, "preHit", [15, "p"]]]]]], [65, "p", [17, [15, "a"], "conversionRules"], [46, [22, ["c", [17, [15, "p"], "matchingRules"], [15, "m"]], [46, [2, [15, "n"], "setMetadata", [7, [15, "i"], true]], [4]]]]]]]]], [2, [15, "a"], "gtmOnSuccess", [7]], [36]], [50, "__ccd_em_download", [46, "a"], [50, "r", [46, "x"], [36, [1, [15, "x"], [21, [2, [2, [15, "x"], "toLowerCase", [7]], "match", [7, [15, "q"]]], [45]]]]], [50, "s", [46, "x"], [52, "y", [2, [17, [15, "x"], "pathname"], "split", [7, "."]]], [52, "z", [39, [18, [17, [15, "y"], "length"], 1], [16, [15, "y"], [37, [17, [15, "y"], "length"], 1]], ""]], [36, [16, [2, [15, "z"], "split", [7, "/"]], 0]]], [50, "t", [46, "x"], [36, [39, [12, [2, [17, [15, "x"], "pathname"], "substring", [7, 0, 1]], "/"], [17, [15, "x"], "pathname"], [0, "/", [17, [15, "x"], "pathname"]]]]], [50, "u", [46, "x"], [41, "y"], [3, "y", ""], [22, [1, [15, "x"], [17, [15, "x"], "href"]], [46, [53, [41, "z"], [3, "z", [2, [17, [15, "x"], "href"], "indexOf", [7, "#"]]], [3, "y", [39, [23, [15, "z"], 0], [17, [15, "x"], "href"], [2, [17, [15, "x"], "href"], "substring", [7, 0, [15, "z"]]]]]]]], [36, [15, "y"]]], [50, "w", [46, "x"], [52, "y", [8]], [43, [15, "y"], [15, "j"], true], [43, [15, "y"], [15, "f"], true], [43, [15, "x"], "eventMetadata", [15, "y"]]], [52, "b", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "c", ["require", "internal.getProductSettingsParameter"]], [52, "d", ["require", "templateStorage"]], [52, "e", [15, "__module_ccdEmDownloadActivity"]], [52, "f", "speculative"], [52, "g", "ae_block_downloads"], [52, "h", "file_download"], [52, "i", "isRegistered"], [52, "j", "em_event"], [52, "k", [17, [15, "a"], "instanceDestinationId"]], [22, ["c", [15, "k"], [15, "g"]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [2, [15, "e"], "registerDownloadActivityCallback", [7, [15, "k"], [17, [15, "a"], "includeParams"]]], [22, [2, [15, "d"], "getItem", [7, [15, "i"]]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "l", ["require", "internal.addDataLayerEventListener"]], [52, "m", ["require", "internal.enableAutoEventOnLinkClick"]], [52, "n", ["require", "internal.getDestinationIds"]], [52, "o", ["require", "parseUrl"]], [52, "p", ["require", "internal.sendGtagEvent"]], [52, "q", [0, "^(pdf|xlsx?|docx?|txt|rtf|csv|exe|key|pp(s|t|tx)|7z|pkg|rar|gz|zip|avi|", "mov|mp4|mpe?g|wmv|midi?|mp3|wav|wma)$"]], [52, "v", ["m", [8, "checkValidation", true]]], [22, [28, [15, "v"]], [46, [2, [15, "a"], "gtmOnFailure", [7]], [36]]], [2, [15, "d"], "setItem", [7, [15, "i"], true]], ["l", "gtm.linkClick", [51, "", [7, "x", "y"], ["y"], [52, "z", [8, "eventId", [16, [15, "x"], "gtm.uniqueEventId"]]], [22, [16, [15, "b"], "enableDeferAllEnhancedMeasurement"], [46, [43, [15, "z"], "deferrable", true]]], [52, "ba", [16, [15, "x"], "gtm.elementUrl"]], [52, "bb", ["o", [15, "ba"]]], [22, [28, [15, "bb"]], [46, [36]]], [52, "bc", ["s", [15, "bb"]]], [22, [28, ["r", [15, "bc"]]], [46, [36]]], [52, "bd", [8, "link_id", [16, [15, "x"], "gtm.elementId"], "link_url", ["u", [15, "bb"]], "link_text", [16, [15, "x"], "gtm.elementText"], "file_name", ["t", [15, "bb"]], "file_extension", [15, "bc"]]], ["w", [15, "z"]], ["p", ["n"], [15, "h"], [15, "bd"], [15, "z"]]], [15, "v"]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_em_outbound_click", [46, "a"], [50, "s", [46, "y"], [22, [28, [15, "y"]], [46, [36, [44]]]], [41, "z"], [3, "z", ""], [22, [1, [15, "y"], [17, [15, "y"], "href"]], [46, [53, [41, "ba"], [3, "ba", [2, [17, [15, "y"], "href"], "indexOf", [7, "#"]]], [3, "z", [39, [23, [15, "ba"], 0], [17, [15, "y"], "href"], [2, [17, [15, "y"], "href"], "substring", [7, 0, [15, "ba"]]]]]]]], [36, [15, "z"]]], [50, "t", [46, "y"], [22, [28, [15, "y"]], [46, [36, [44]]]], [41, "z"], [3, "z", [17, [15, "y"], "hostname"]], [52, "ba", [2, [15, "z"], "match", [7, "^www\\d*\\."]]], [22, [1, [15, "ba"], [16, [15, "ba"], 0]], [46, [3, "z", [2, [15, "z"], "substring", [7, [17, [16, [15, "ba"], 0], "length"]]]]]], [36, [15, "z"]]], [50, "u", [46, "y"], [22, [28, [15, "y"]], [46, [36, false]]], [52, "z", [2, [17, [15, "y"], "hostname"], "toLowerCase", [7]]], [41, "ba"], [3, "ba", [2, ["t", ["q", ["p"]]], "toLowerCase", [7]]], [41, "bb"], [3, "bb", [37, [17, [15, "z"], "length"], [17, [15, "ba"], "length"]]], [22, [1, [18, [15, "bb"], 0], [29, [2, [15, "ba"], "charAt", [7, 0]], "."]], [46, [32, [15, "bb"], [3, "bb", [37, [15, "bb"], 1]]], [3, "ba", [0, ".", [15, "ba"]]]]], [22, [1, [19, [15, "bb"], 0], [12, [2, [15, "z"], "indexOf", [7, [15, "ba"], [15, "bb"]]], [15, "bb"]]], [46, [36, false]]], [36, true]], [50, "x", [46, "y"], [52, "z", [8]], [43, [15, "z"], [15, "j"], true], [43, [15, "z"], [15, "f"], true], [43, [15, "y"], "eventMetadata", [15, "z"]]], [52, "b", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "c", ["require", "internal.getProductSettingsParameter"]], [52, "d", ["require", "templateStorage"]], [52, "e", [15, "__module_ccdEmOutboundClickActivity"]], [52, "f", "speculative"], [52, "g", "ae_block_outbound_click"], [52, "h", "click"], [52, "i", "isRegistered"], [52, "j", "em_event"], [52, "k", [17, [15, "a"], "instanceDestinationId"]], [22, ["c", [15, "k"], [15, "g"]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [2, [15, "e"], "registerOutbackClickActivityCallback", [7, [15, "k"], [17, [15, "a"], "includeParams"]]], [22, [2, [15, "d"], "getItem", [7, [15, "i"]]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "l", ["require", "internal.addDataLayerEventListener"]], [52, "m", ["require", "internal.enableAutoEventOnLinkClick"]], [52, "n", ["require", "internal.getDestinationIds"]], [52, "o", ["require", "internal.getRemoteConfigParameter"]], [52, "p", ["require", "getUrl"]], [52, "q", ["require", "parseUrl"]], [52, "r", ["require", "internal.sendGtagEvent"]], [52, "v", ["o", [15, "k"], "cross_domain_conditions"]], [52, "w", ["m", [8, "affiliateDomains", [15, "v"], "checkValidation", true, "waitForTags", false]]], [22, [28, [15, "w"]], [46, [2, [15, "a"], "gtmOnFailure", [7]], [36]]], [2, [15, "d"], "setItem", [7, [15, "i"], true]], ["l", "gtm.linkClick", [51, "", [7, "y", "z"], [52, "ba", ["q", [16, [15, "y"], "gtm.elementUrl"]]], [22, [28, ["u", [15, "ba"]]], [46, ["z"], [36]]], [52, "bb", [8, "link_id", [16, [15, "y"], "gtm.elementId"], "link_classes", [16, [15, "y"], "gtm.elementClasses"], "link_url", ["s", [15, "ba"]], "link_domain", ["t", [15, "ba"]], "outbound", true]], [43, [15, "bb"], "event_callback", [15, "z"]], [52, "bc", [8, "eventId", [16, [15, "y"], "gtm.uniqueEventId"]]], [22, [16, [15, "b"], "enableDeferAllEnhancedMeasurement"], [46, [43, [15, "bc"], "deferrable", true]]], ["x", [15, "bc"]], ["r", ["n"], [15, "h"], [15, "bb"], [15, "bc"]]], [15, "w"]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_em_page_view", [46, "a"], [50, "s", [46, "t"], [52, "u", [8]], [43, [15, "u"], [15, "k"], true], [43, [15, "u"], [15, "g"], true], [43, [15, "t"], "eventMetadata", [15, "u"]]], [22, [28, [17, [15, "a"], "historyEvents"]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "b", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "c", ["require", "internal.getProductSettingsParameter"]], [52, "d", ["require", "internal.setRemoteConfigParameter"]], [52, "e", ["require", "templateStorage"]], [52, "f", [15, "__module_ccdEmPageViewActivity"]], [52, "g", "speculative"], [52, "h", "ae_block_history"], [52, "i", "page_view"], [52, "j", "isRegistered"], [52, "k", "em_event"], [52, "l", [17, [15, "a"], "instanceDestinationId"]], [22, ["c", [15, "l"], [15, "h"]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [2, [15, "f"], "registerPageViewActivityCallback", [7, [15, "l"]]], [22, [2, [15, "e"], "getItem", [7, [15, "j"]]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "m", ["require", "internal.addDataLayerEventListener"]], [52, "n", ["require", "internal.enableAutoEventOnHistoryChange"]], [52, "o", ["require", "internal.getDestinationIds"]], [52, "p", ["require", "internal.sendGtagEvent"]], [52, "q", [8, "interval", 1000, "useV2EventName", true]], [52, "r", ["n", [15, "q"]]], [22, [28, [15, "r"]], [46, [2, [15, "a"], "gtmOnFailure", [7]], [36]]], [2, [15, "e"], "setItem", [7, [15, "j"], true]], ["m", "gtm.historyChange-v2", [51, "", [7, "t", "u"], ["u"], [52, "v", [16, [15, "t"], "gtm.oldUrl"]], [22, [20, [16, [15, "t"], "gtm.newUrl"], [15, "v"]], [46, [36]]], [52, "w", [16, [15, "t"], "gtm.historyChangeSource"]], [22, [1, [1, [21, [15, "w"], "pushState"], [21, [15, "w"], "popstate"]], [21, [15, "w"], "replaceState"]], [46, [36]]], [52, "x", [8]], [22, [17, [15, "a"], "includeParams"], [46, [43, [15, "x"], "page_location", [16, [15, "t"], "gtm.newUrl"]], [43, [15, "x"], "page_referrer", [15, "v"]]]], [52, "y", [8, "eventId", [16, [15, "t"], "gtm.uniqueEventId"]]], [22, [16, [15, "b"], "enableDeferAllEnhancedMeasurement"], [46, [43, [15, "y"], "deferrable", true]]], ["s", [15, "y"]], ["p", ["o"], [15, "i"], [15, "x"], [15, "y"]]], [15, "r"]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_em_scroll", [46, "a"], [50, "q", [46, "r"], [52, "s", [8]], [43, [15, "s"], [15, "j"], true], [43, [15, "s"], [15, "f"], true], [43, [15, "r"], "eventMetadata", [15, "s"]]], [52, "b", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "c", ["require", "internal.getProductSettingsParameter"]], [52, "d", ["require", "templateStorage"]], [52, "e", [15, "__module_ccdEmScrollActivity"]], [52, "f", "speculative"], [52, "g", "ae_block_scroll"], [52, "h", "scroll"], [52, "i", "isRegistered"], [52, "j", "em_event"], [52, "k", [17, [15, "a"], "instanceDestinationId"]], [22, ["c", [15, "k"], [15, "g"]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [2, [15, "e"], "registerScrollActivityCallback", [7, [15, "k"], [17, [15, "a"], "includeParams"]]], [22, [2, [15, "d"], "getItem", [7, [15, "i"]]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "l", ["require", "internal.addDataLayerEventListener"]], [52, "m", ["require", "internal.enableAutoEventOnScroll"]], [52, "n", ["require", "internal.getDestinationIds"]], [52, "o", ["require", "internal.sendGtagEvent"]], [52, "p", ["m", [8, "verticalThresholdUnits", "PERCENT", "verticalThresholds", 90]]], [22, [28, [15, "p"]], [46, [2, [15, "a"], "gtmOnFailure", [7]], [36]]], [2, [15, "d"], "setItem", [7, [15, "i"], true]], ["l", "gtm.scrollDepth", [51, "", [7, "r", "s"], ["s"], [52, "t", [8, "eventId", [16, [15, "r"], "gtm.uniqueEventId"]]], [22, [16, [15, "b"], "enableDeferAllEnhancedMeasurement"], [46, [43, [15, "t"], "deferrable", true]]], [52, "u", [8, "percent_scrolled", [16, [15, "r"], "gtm.scrollThreshold"]]], ["q", [15, "t"]], ["o", ["n"], [15, "h"], [15, "u"], [15, "t"]]], [15, "p"]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_em_site_search", [46, "a"], [52, "b", ["require", "getQueryParameters"]], [52, "c", ["require", "internal.sendGtagEvent"]], [52, "d", ["require", "getContainerVersion"]], [52, "e", [15, "__module_ccdEmSiteSearchActivity"]], [52, "f", [2, [15, "e"], "getSearchTerm", [7, [17, [15, "a"], "searchQueryParams"], [15, "b"]]]], [52, "g", [30, [17, [15, "a"], "instanceDestinationId"], [17, ["d"], "containerId"]]], [52, "h", [8, "deferrable", true, "eventId", [17, [15, "a"], "gtmEventId"], "eventMetadata", [8, "em_event", true]]], [22, [15, "f"], [46, [53, [52, "i", [39, [28, [28, [17, [15, "a"], "includeParams"]]], [2, [15, "e"], "buildEventParams", [7, [15, "f"], [17, [15, "a"], "additionalQueryParams"], [15, "b"]]], [8]]], ["c", [15, "g"], "view_search_results", [15, "i"], [15, "h"]]]]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_em_video", [46, "a"], [50, "s", [46, "t"], [52, "u", [8]], [43, [15, "u"], [15, "l"], true], [43, [15, "u"], [15, "f"], true], [43, [15, "t"], "eventMetadata", [15, "u"]]], [52, "b", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "c", ["require", "internal.getProductSettingsParameter"]], [52, "d", ["require", "templateStorage"]], [52, "e", [15, "__module_ccdEmVideoActivity"]], [52, "f", "speculative"], [52, "g", "ae_block_video"], [52, "h", "video_start"], [52, "i", "video_progress"], [52, "j", "video_complete"], [52, "k", "isRegistered"], [52, "l", "em_event"], [52, "m", [17, [15, "a"], "instanceDestinationId"]], [22, ["c", [15, "m"], [15, "g"]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [2, [15, "e"], "registerVideoActivityCallback", [7, [15, "m"], [17, [15, "a"], "includeParams"]]], [22, [2, [15, "d"], "getItem", [7, [15, "k"]]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "n", ["require", "internal.addDataLayerEventListener"]], [52, "o", ["require", "internal.enableAutoEventOnYouTubeActivity"]], [52, "p", ["require", "internal.getDestinationIds"]], [52, "q", ["require", "internal.sendGtagEvent"]], [52, "r", ["o", [8, "captureComplete", true, "captureStart", true, "progressThresholdsPercent", [7, 10, 25, 50, 75]]]], [22, [28, [15, "r"]], [46, [2, [15, "a"], "gtmOnFailure", [7]], [36]]], [2, [15, "d"], "setItem", [7, [15, "k"], true]], ["n", "gtm.video", [51, "", [7, "t", "u"], ["u"], [52, "v", [16, [15, "t"], "gtm.videoStatus"]], [41, "w"], [22, [20, [15, "v"], "start"], [46, [3, "w", [15, "h"]]], [46, [22, [20, [15, "v"], "progress"], [46, [3, "w", [15, "i"]]], [46, [22, [20, [15, "v"], "complete"], [46, [3, "w", [15, "j"]]], [46, [36]]]]]]], [52, "x", [8, "video_current_time", [16, [15, "t"], "gtm.videoCurrentTime"], "video_duration", [16, [15, "t"], "gtm.videoDuration"], "video_percent", [16, [15, "t"], "gtm.videoPercent"], "video_provider", [16, [15, "t"], "gtm.videoProvider"], "video_title", [16, [15, "t"], "gtm.videoTitle"], "video_url", [16, [15, "t"], "gtm.videoUrl"], "visible", [16, [15, "t"], "gtm.videoVisible"]]], [52, "y", [8, "eventId", [16, [15, "t"], "gtm.uniqueEventId"]]], [22, [16, [15, "b"], "enableDeferAllEnhancedMeasurement"], [46, [43, [15, "y"], "deferrable", true]]], ["s", [15, "y"]], ["q", ["p"], [15, "w"], [15, "x"], [15, "y"]]], [15, "r"]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_ga_ads_link", [46, "a"], [52, "b", ["require", "internal.CrossContainerSchema"]], [52, "c", ["require", "internal.GtagSchema"]], [52, "d", ["require", "internal.copyFromCrossContainerData"]], [52, "e", ["require", "internal.registerCcdCallback"]], [52, "f", ["require", "internal.setInCrossContainerData"]], [52, "g", ["require", "internal.setProductSettingsParameter"]], [52, "h", "event_usage"], [52, "i", 27], ["g", [17, [15, "a"], "instanceDestinationId"], "ga4_ads_linked", true], ["e", [17, [15, "a"], "instanceDestinationId"], [51, "", [7, "j"], [41, "k"], [3, "k", [2, [15, "j"], "getHitData", [7, [17, [17, [15, "c"], "EventParameters"], "USER_ID"]]]], [22, [28, [15, "k"]], [46, [53, [52, "n", [30, [2, [15, "j"], "getHitData", [7, [17, [17, [15, "c"], "EventParameters"], "USER_PROPERTIES"]]], [8]]], [3, "k", [16, [15, "n"], [17, [17, [15, "c"], "EventParameters"], "USER_ID"]]]]]], [22, [28, [15, "k"]], [46, [36]]], [52, "l", ["d", [17, [15, "b"], "SHARED_USER_ID"]]], [22, [15, "l"], [46, [36]]], ["f", [17, [15, "b"], "SHARED_USER_ID"], [15, "k"]], ["f", [17, [15, "b"], "SHARED_USER_ID_SOURCE"], [17, [15, "a"], "instanceDestinationId"]], [52, "m", ["d", [17, [15, "b"], "SHARED_USER_ID_REQUESTED"]]], [22, [15, "m"], [46, [53, [52, "n", [30, [2, [15, "j"], "getMetadata", [7, [15, "h"]]], [7]]], [22, [23, [2, [15, "n"], "indexOf", [7, [15, "i"]]], 0], [46, [2, [15, "n"], "push", [7, [15, "i"]]], [2, [15, "j"], "setMetadata", [7, [15, "h"], [15, "n"]]]]]]]]]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_ga_first", [46, "a"], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_ga_last", [46, "a"], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ccd_ga_regscope", [46, "a"], [52, "b", [15, "__module_ccdGaRegionScopedSettings"]], [52, "c", [2, [15, "b"], "extractRedactedLocations", [7, [15, "a"]]]], [2, [15, "b"], "applyRegionScopedSettings", [7, [15, "a"], [15, "c"]]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__e", [46, "a"], [36, [13, [41, "$0"], [3, "$0", ["require", "internal.getEventData"]], ["$0", "event"]]]], [50, "__ogt_1p_data_v2", [46, "a"], [50, "j", [46, "m", "n", "o"], [22, [20, [16, [15, "n"], "type"], [15, "o"]], [46, [22, [28, [15, "m"]], [46, [3, "m", [8]]]], [22, [28, [16, [15, "m"], [15, "o"]]], [46, [43, [15, "m"], [15, "o"], [16, [15, "n"], "userData"]]]]]], [36, [15, "m"]]], [50, "k", [46, "m", "n"], [52, "o", [16, [15, "a"], [15, "m"]]], [41, "p"], [22, [20, [15, "o"], "CSS_SELECTOR"], [46, [3, "p", "css_selector"]], [46, [22, [20, [15, "o"], "JS_VAR"], [46, [3, "p", "js_variable"]]]]], [36, [8, "selector_type", [15, "p"], "value", [16, [15, "a"], [15, "n"]]]]], [50, "l", [46, "m", "n", "o", "p"], [22, [28, [16, [15, "a"], [15, "p"]]], [46, [36]]], [43, [15, "m"], [15, "n"], ["k", [15, "o"], [15, "p"]]]], [22, [28, [17, [15, "a"], "isEnabled"]], [46, [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [52, "b", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "c", ["require", "internal.getDestinationIds"]], [52, "d", ["require", "internal.getProductSettingsParameter"]], [52, "e", ["require", "internal.detectUserProvidedData"]], [52, "f", ["require", "internal.setRemoteConfigParameter"]], [52, "g", ["require", "internal.registerCcdCallback"]], [52, "h", [30, ["c"], [7]]], [52, "i", [8, "enable_code", true]], [22, [17, [15, "a"], "isAutoEnabled"], [46, [53, [52, "m", [7]], [22, [1, [17, [15, "a"], "autoCollectExclusionSelectors"], [17, [17, [15, "a"], "autoCollectExclusionSelectors"], "length"]], [46, [53, [41, "o"], [3, "o", 0], [63, [7, "o"], [23, [15, "o"], [17, [17, [15, "a"], "autoCollectExclusionSelectors"], "length"]], [33, [15, "o"], [3, "o", [0, [15, "o"], 1]]], [46, [53, [52, "p", [17, [16, [17, [15, "a"], "autoCollectExclusionSelectors"], [15, "o"]], "exclusionSelector"]], [22, [15, "p"], [46, [2, [15, "m"], "push", [7, [15, "p"]]]]]]]]]]], [52, "n", [39, [17, [15, "a"], "isAutoCollectPiiEnabledFlag"], [17, [15, "a"], "autoEmailEnabled"], true]], [43, [15, "i"], "auto_detect", [8, "email", [15, "n"], "phone", [17, [15, "a"], "autoPhoneEnabled"], "address", [17, [15, "a"], "autoAddressEnabled"], "exclude_element_selectors", [15, "m"]]]]]], [22, [17, [15, "a"], "isManualEnabled"], [46, [53, [52, "m", [8]], [22, [17, [15, "a"], "manualEmailEnabled"], [46, ["l", [15, "m"], "email", "emailType", "emailValue"]]], [22, [17, [15, "a"], "manualPhoneEnabled"], [46, ["l", [15, "m"], "phone", "phoneType", "phoneValue"]]], [22, [17, [15, "a"], "manualAddressEnabled"], [46, [53, [52, "n", [8]], ["l", [15, "n"], "first_name", "firstNameType", "firstNameValue"], ["l", [15, "n"], "last_name", "lastNameType", "lastNameValue"], ["l", [15, "n"], "street", "streetType", "streetValue"], ["l", [15, "n"], "city", "cityType", "cityValue"], ["l", [15, "n"], "region", "regionType", "regionValue"], ["l", [15, "n"], "country", "countryType", "countryValue"], ["l", [15, "n"], "postal_code", "postalCodeType", "postalCodeValue"], [43, [15, "m"], "name_and_address", [7, [15, "n"]]]]]], [43, [15, "i"], "selectors", [15, "m"]]]]], [65, "m", [15, "h"], [46, [53, [41, "n"], [3, "n", [15, "i"]], [22, [1, [20, [2, [15, "m"], "indexOf", [7, "G-"]], 0], [28, [16, [15, "b"], "enableEuidAutoMode"]]], [46, [53, [52, "q", [8, "enable_code", true, "selectors", [16, [15, "i"], "selectors"]]], [3, "n", [15, "q"]]]]], ["f", [15, "m"], "user_data_settings", [15, "n"]], [52, "o", [16, [15, "n"], "auto_detect"]], [22, [28, [15, "o"]], [46, [6]]], [52, "p", [51, "", [7, "q"], [52, "r", [2, [15, "q"], "getMetadata", [7, "user_data_from_automatic"]]], [22, [15, "r"], [46, [36, [15, "r"]]]], [52, "s", ["e", [8, "excludeElementSelectors", [16, [15, "o"], "exclude_element_selectors"], "fieldFilters", [8, "email", [16, [15, "o"], "email"], "phone", [16, [15, "o"], "phone"], "address", [16, [15, "o"], "address"]]]]], [52, "t", [1, [15, "s"], [16, [15, "s"], "elements"]]], [52, "u", [8]], [22, [1, [15, "t"], [18, [17, [15, "t"], "length"], 0]], [46, [53, [41, "v"], [53, [41, "w"], [3, "w", 0], [63, [7, "w"], [23, [15, "w"], [17, [15, "t"], "length"]], [33, [15, "w"], [3, "w", [0, [15, "w"], 1]]], [46, [53, [52, "x", [16, [15, "t"], [15, "w"]]], ["j", [15, "u"], [15, "x"], "email"], [22, [16, [15, "b"], "enableAutoPiiOnPhoneAndAddress"], [46, ["j", [15, "u"], [15, "x"], "phone_number"], [3, "v", ["j", [15, "v"], [15, "x"], "first_name"]], [3, "v", ["j", [15, "v"], [15, "x"], "last_name"]], [3, "v", ["j", [15, "v"], [15, "x"], "country"]], [3, "v", ["j", [15, "v"], [15, "x"], "postal_code"]]]]]]]], [22, [1, [15, "v"], [28, [16, [15, "u"], "address"]]], [46, [43, [15, "u"], "address", [15, "v"]]]]]]], [2, [15, "q"], "setMetadata", [7, "user_data_from_automatic", [15, "u"]]], [36, [15, "u"]]]], ["g", [15, "m"], [51, "", [7, "q"], [2, [15, "q"], "setMetadata", [7, "user_data_from_automatic_getter", [15, "p"]]]]]]]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ogt_event_create", [46, "a"], [50, "r", [46, "s", "t"], [22, [28, [2, [15, "c"], "preHitMatchesRule", [7, [15, "s"], [16, [15, "t"], [15, "n"]], [30, [16, [15, "t"], [15, "o"]], [7]]]]], [46, [36, false]]], [52, "u", [16, [15, "t"], [15, "p"]]], [22, [2, [15, "c"], "isEventNameFalsyOrReserved", [7, [15, "u"]]], [46, [36]]], [52, "v", [28, [16, [15, "t"], [15, "q"]]]], [52, "w", [30, [2, [15, "s"], "getMetadata", [7, [15, "j"]]], [7]]], [22, [20, [2, [15, "w"], "indexOf", [7, [15, "k"]]], [27, 1]], [46, [2, [15, "w"], "push", [7, [15, "k"]]]]], [2, [15, "s"], "setMetadata", [7, [15, "j"], [15, "w"]]], [52, "x", ["b", [15, "s"], [8, "omitHitData", [15, "v"], "omitEventContext", [15, "v"], "omitMetadata", true]]], [2, [15, "c"], "applyParamOperations", [7, [15, "x"], [15, "t"]]], [2, [15, "x"], "setEventName", [7, [15, "u"]]], [2, [15, "x"], "setMetadata", [7, [15, "m"], true]], [2, [15, "x"], "setMetadata", [7, [15, "j"], [7, [15, "l"]]]], ["d", [15, "x"]]], [52, "b", ["require", "internal.copyPreHit"]], [52, "c", [15, "__module_eventEditingAndSynthesis"]], [52, "d", ["require", "internal.processAsNewEvent"]], [52, "e", ["require", "internal.registerCcdCallback"]], [52, "f", ["require", "templateStorage"]], [52, "g", [17, [15, "a"], "instanceDestinationId"]], [41, "h"], [3, "h", [2, [15, "f"], "getItem", [7, [15, "g"]]]], [41, "i"], [3, "i", [28, [28, [15, "h"]]]], [22, [15, "i"], [46, [2, [15, "h"], "push", [7, [17, [15, "a"], "precompiledRule"]]], [2, [15, "a"], "gtmOnSuccess", [7]], [36]]], [2, [15, "f"], "setItem", [7, [15, "g"], [7, [17, [15, "a"], "precompiledRule"]]]], [52, "j", "event_usage"], [52, "k", 1], [52, "l", 11], [52, "m", "is_syn"], [52, "n", "event_name_predicate"], [52, "o", "conditions"], [52, "p", "new_event_name"], [52, "q", "merge_source_event_params"], ["e", [15, "g"], [51, "", [7, "s"], [22, [2, [15, "s"], "getMetadata", [7, [15, "m"]]], [46, [36]]], [52, "t", [2, [15, "f"], "getItem", [7, [15, "g"]]]], [66, "u", [15, "t"], [46, ["r", [15, "s"], [15, "u"]]]]]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__ogt_google_signals", [46, "a"], [52, "b", ["require", "internal.setProductSettingsParameter"]], [52, "c", ["require", "getContainerVersion"]], [52, "d", [30, [17, [15, "a"], "instanceDestinationId"], [17, ["c"], "containerId"]]], ["b", [15, "d"], "google_signals", [20, [17, [15, "a"], "googleSignals"], "ENABLED"]], ["b", [15, "d"], "google_ng", [20, [17, [15, "a"], "googleSignals"], "NON_GAIA_REMARKETING"]], [2, [15, "a"], "gtmOnSuccess", [7]]], [50, "__set_product_settings", [46, "a"], [2, [15, "a"], "gtmOnSuccess", [7]]], [52, "__module_eventEditingAndSynthesis", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "bc", [46, "bp", "bq"], [52, "br", [30, [16, [15, "bq"], [15, "i"]], [7]]], [66, "bs", [15, "br"], [46, [22, [16, [15, "bs"], [15, "j"]], [46, [53, [52, "bt", [16, [16, [15, "bs"], [15, "j"]], [15, "l"]]], [52, "bu", ["bh", [15, "bp"], [16, [16, [15, "bs"], [15, "j"]], [15, "m"]]]], [2, [15, "bp"], "setHitData", [7, [15, "bt"], ["bd", [15, "bu"]]]]]], [46, [22, [16, [15, "bs"], [15, "k"]], [46, [53, [52, "bt", [16, [16, [15, "bs"], [15, "k"]], [15, "l"]]], [2, [15, "bp"], "setHitData", [7, [15, "bt"], [44]]]]]]]]]]], [50, "bd", [46, "bp"], [22, [28, [15, "bp"]], [46, [36, [15, "bp"]]]], [52, "bq", ["c", [15, "bp"]]], [52, "br", [21, [15, "bq"], [15, "bq"]]], [22, [15, "br"], [46, [36, [15, "bp"]]]], [36, [15, "bq"]]], [50, "be", [46, "bp", "bq", "br"], [22, [1, [15, "bq"], [28, ["bg", [15, "bp"], [15, "bq"]]]], [46, [36, false]]], [22, [30, [28, [15, "br"]], [20, [17, [15, "br"], "length"], 0]], [46, [36, true]]], [53, [41, "bs"], [3, "bs", 0], [63, [7, "bs"], [23, [15, "bs"], [17, [15, "br"], "length"]], [33, [15, "bs"], [3, "bs", [0, [15, "bs"], 1]]], [46, [53, [52, "bt", [30, [16, [16, [15, "br"], [15, "bs"]], [15, "q"]], [7]]], [22, ["bf", [15, "bp"], [15, "bt"]], [46, [36, true]]]]]]], [36, false]], [50, "bf", [46, "bp", "bq"], [53, [41, "br"], [3, "br", 0], [63, [7, "br"], [23, [15, "br"], [17, [15, "bq"], "length"]], [33, [15, "br"], [3, "br", [0, [15, "br"], 1]]], [46, [53, [52, "bs", [16, [15, "bq"], [15, "br"]]], [52, "bt", ["bg", [15, "bp"], [15, "bs"], false]], [22, [16, [15, "b"], "enableUrlDecodeEventUsage"], [46, [53, [52, "bu", [16, [30, [16, [15, "bs"], [15, "t"]], [7]], 0]], [22, [1, [1, [15, "bu"], [20, [16, [15, "bu"], [15, "u"]], [15, "p"]]], [21, [2, [15, "bb"], "indexOf", [7, [16, [16, [15, "bu"], [15, "p"]], [15, "o"]]]], [27, 1]]], [46, [53, [52, "bv", ["bg", [15, "bp"], [15, "bs"], true]], [22, [21, [15, "bt"], [15, "bv"]], [46, [53, [52, "bw", [30, [2, [15, "bp"], "getMetadata", [7, [15, "y"]]], [7]]], [2, [15, "bw"], "push", [7, [39, [15, "bt"], [15, "ba"], [15, "z"]]]], [2, [15, "bp"], "setMetadata", [7, [15, "y"], [15, "bw"]]]]]]]]]]]], [22, [28, [15, "bt"]], [46, [36, false]]]]]]], [36, true]], [50, "bg", [46, "bp", "bq", "br"], [52, "bs", [30, [16, [15, "bq"], [15, "t"]], [7]]], [41, "bt"], [3, "bt", ["bh", [15, "bp"], [16, [15, "bs"], 0]]], [41, "bu"], [3, "bu", ["bh", [15, "bp"], [16, [15, "bs"], 1]]], [22, [1, [15, "br"], [15, "bt"]], [46, [3, "bt", [30, ["h", [15, "bt"]], [15, "bt"]]]]], [22, [1, [16, [15, "b"], "enableDecodeUri"], [15, "bu"]], [46, [53, [52, "ca", [16, [30, [16, [15, "bq"], [15, "t"]], [7]], 0]], [22, [1, [1, [15, "ca"], [20, [16, [15, "ca"], [15, "u"]], [15, "p"]]], [21, [2, [15, "bb"], "indexOf", [7, [16, [16, [15, "ca"], [15, "p"]], [15, "o"]]]], [27, 1]]], [46, [53, [52, "cb", [2, [15, "bu"], "indexOf", [7, "?"]]], [22, [20, [15, "cb"], [27, 1]], [46, [3, "bu", [30, ["h", [15, "bu"]], [15, "bu"]]]], [46, [53, [52, "cc", [2, [15, "bu"], "substring", [7, 0, [15, "cb"]]]], [3, "bu", [0, [30, ["h", [15, "cc"]], [15, "cc"]], [2, [15, "bu"], "substring", [7, [15, "cb"]]]]]]]]]]]]]], [52, "bv", [16, [15, "bq"], [15, "s"]]], [22, [30, [30, [30, [20, [15, "bv"], "eqi"], [20, [15, "bv"], "swi"]], [20, [15, "bv"], "ewi"]], [20, [15, "bv"], "cni"]], [46, [22, [15, "bt"], [46, [3, "bt", [2, ["e", [15, "bt"]], "toLowerCase", [7]]]]], [22, [15, "bu"], [46, [3, "bu", [2, ["e", [15, "bu"]], "toLowerCase", [7]]]]]]], [41, "bw"], [3, "bw", false], [38, [15, "bv"], [46, "eq", "eqi", "sw", "swi", "ew", "ewi", "cn", "cni", "lt", "le", "gt", "ge", "re", "rei"], [46, [5, [46]], [5, [46, [3, "bw", [20, ["e", [15, "bt"]], ["e", [15, "bu"]]]], [4]]], [5, [46]], [5, [46, [3, "bw", [20, [2, ["e", [15, "bt"]], "indexOf", [7, ["e", [15, "bu"]]]], 0]], [4]]], [5, [46]], [5, [46, [41, "bx"], [3, "bx", ["e", [15, "bt"]]], [41, "by"], [3, "by", ["e", [15, "bu"]]], [52, "bz", [37, [17, [15, "bx"], "length"], [17, [15, "by"], "length"]]], [3, "bw", [1, [19, [15, "bz"], 0], [20, [2, [15, "bx"], "indexOf", [7, [15, "by"], [15, "bz"]]], [15, "bz"]]]], [4]]], [5, [46]], [5, [46, [3, "bw", [19, [2, ["e", [15, "bt"]], "indexOf", [7, ["e", [15, "bu"]]]], 0]], [4]]], [5, [46, [3, "bw", [23, ["c", [15, "bt"]], ["c", [15, "bu"]]]], [4]]], [5, [46, [3, "bw", [24, ["c", [15, "bt"]], ["c", [15, "bu"]]]], [4]]], [5, [46, [3, "bw", [18, ["c", [15, "bt"]], ["c", [15, "bu"]]]], [4]]], [5, [46, [3, "bw", [19, ["c", [15, "bt"]], ["c", [15, "bu"]]]], [4]]], [5, [46, [22, [21, [15, "bt"], [44]], [46, [53, [52, "ca", ["f", [15, "bu"]]], [22, [15, "ca"], [46, [3, "bw", ["g", [15, "ca"], [15, "bt"]]]]]]]], [4]]], [5, [46, [22, [21, [15, "bt"], [44]], [46, [53, [52, "ca", ["f", [15, "bu"], "i"]], [22, [15, "ca"], [46, [3, "bw", ["g", [15, "ca"], [15, "bt"]]]]]]]], [4]]], [9, [46]]]], [22, [28, [28, [16, [15, "bq"], [15, "r"]]]], [46, [36, [28, [15, "bw"]]]]], [36, [15, "bw"]]], [50, "bh", [46, "bp", "bq"], [22, [28, [15, "bq"]], [46, [36, [44]]]], [38, [16, [15, "bq"], [15, "u"]], [46, "event_name", "const", "event_param"], [46, [5, [46, [36, [2, [15, "bp"], "getEventName", [7]]]]], [5, [46, [36, [16, [15, "bq"], [15, "n"]]]]], [5, [46, [52, "br", [16, [16, [15, "bq"], [15, "p"]], [15, "o"]]], [22, [20, [15, "br"], [15, "w"]], [46, [36, ["bk", [15, "bp"]]]]], [22, [20, [15, "br"], [15, "v"]], [46, [36, ["bl", [15, "bp"]]]]], [36, [2, [15, "bp"], "getHitData", [7, [15, "br"]]]]]], [9, [46, [36, [44]]]]]]], [50, "bj", [46, "bp"], [22, [28, [15, "bp"]], [46, [36, [15, "bp"]]]], [52, "bq", [2, [15, "bp"], "split", [7, "&"]]], [52, "br", [7]], [43, [15, "bq"], 0, [2, [16, [15, "bq"], 0], "substring", [7, 1]]], [53, [41, "bs"], [3, "bs", 0], [63, [7, "bs"], [23, [15, "bs"], [17, [15, "bq"], "length"]], [33, [15, "bs"], [3, "bs", [0, [15, "bs"], 1]]], [46, [53, [52, "bt", [16, [15, "bq"], [15, "bs"]]], [52, "bu", [2, [15, "bt"], "indexOf", [7, "="]]], [52, "bv", [39, [19, [15, "bu"], 0], [2, [15, "bt"], "substring", [7, 0, [15, "bu"]]], [15, "bt"]]], [22, [28, [16, [15, "bi"], [15, "bv"]]], [46, [2, [15, "br"], "push", [7, [16, [15, "bq"], [15, "bs"]]]]]]]]]], [22, [17, [15, "br"], "length"], [46, [36, [0, "?", [2, [15, "br"], "join", [7, "&"]]]]]], [36, ""]], [50, "bk", [46, "bp"], [52, "bq", [2, [15, "bp"], "getHitData", [7, [15, "w"]]]], [22, [15, "bq"], [46, [36, [15, "bq"]]]], [52, "br", [2, [15, "bp"], "getHitData", [7, [15, "x"]]]], [22, [21, [40, [15, "br"]], "string"], [46, [36, [44]]]], [52, "bs", ["d", [15, "br"]]], [22, [28, [15, "bs"]], [46, [36, [44]]]], [41, "bt"], [3, "bt", [17, [15, "bs"], "pathname"]], [22, [16, [15, "b"], "enableDecodeUri"], [46, [3, "bt", [30, ["h", [15, "bt"]], [15, "bt"]]]]], [36, [0, [15, "bt"], ["bj", [17, [15, "bs"], "search"]]]]], [50, "bl", [46, "bp"], [52, "bq", [2, [15, "bp"], "getHitData", [7, [15, "v"]]]], [22, [15, "bq"], [46, [36, [15, "bq"]]]], [52, "br", [2, [15, "bp"], "getHitData", [7, [15, "x"]]]], [22, [21, [40, [15, "br"]], "string"], [46, [36, [44]]]], [52, "bs", ["d", [15, "br"]]], [22, [28, [15, "bs"]], [46, [36, [44]]]], [36, [17, [15, "bs"], "hostname"]]], [50, "bo", [46, "bp"], [22, [28, [15, "bp"]], [46, [36, true]]], [3, "bp", ["e", [15, "bp"]]], [66, "bq", [15, "bn"], [46, [22, [20, [2, [15, "bp"], "indexOf", [7, [15, "bq"]]], 0], [46, [36, true]]]]], [22, [18, [2, [15, "bm"], "indexOf", [7, [15, "bp"]]], [27, 1]], [46, [36, true]]], [36, false]], [52, "b", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "c", ["require", "makeNumber"]], [52, "d", ["require", "parseUrl"]], [52, "e", ["require", "makeString"]], [52, "f", ["require", "internal.createRegex"]], [52, "g", ["require", "internal.testRegex"]], [52, "h", ["require", "decodeUriComponent"]], [52, "i", "event_param_ops"], [52, "j", "edit_param"], [52, "k", "delete_param"], [52, "l", "param_name"], [52, "m", "param_value"], [52, "n", "const_value"], [52, "o", "param_name"], [52, "p", "event_param"], [52, "q", "predicates"], [52, "r", "negate"], [52, "s", "type"], [52, "t", "values"], [52, "u", "type"], [52, "v", "page_hostname"], [52, "w", "page_path"], [52, "x", "page_location"], [52, "y", "event_usage"], [52, "z", 20], [52, "ba", 21], [52, "bb", [7, [15, "w"], [15, "x"], "page_referrer"]], [52, "bi", [8, "__utma", 1, "__utmb", 1, "__utmc", 1, "__utmk", 1, "__utmv", 1, "__utmx", 1, "__utmz", 1, "__ga", 1, "_gac", 1, "_gl", 1, "dclid", 1, "gbraid", 1, "gclid", 1, "gclsrc", 1, "utm_campaign", 1, "utm_content", 1, "utm_expid", 1, "utm_id", 1, "utm_medium", 1, "utm_nooverride", 1, "utm_referrer", 1, "utm_source", 1, "utm_term", 1, "wbraid", 1]], [52, "bm", [7, "app_remove", "app_store_refund", "app_store_subscription_cancel", "app_store_subscription_convert", "app_store_subscription_renew", "first_open", "first_visit", "in_app_purchase", "session_start", "user_engagement"]], [52, "bn", [7, "_", "ga_", "google_", "gtag.", "firebase_"]], [36, [8, "applyParamOperations", [15, "bc"], "preHitMatchesRule", [15, "be"], "resolveValue", [15, "bh"], "isEventNameFalsyOrReserved", [15, "bo"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_activities", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "b", [46, "c", "d"], [36, [39, [15, "d"], ["d", [15, "c"]], [15, "c"]]]], [36, [8, "withRequestContext", [15, "b"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_ccdEmDownloadActivity", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "h", [46, "i", "j"], ["c", [15, "i"], [51, "", [7, "k"], [22, [30, [21, [2, [15, "k"], "getEventName", [7]], [15, "f"]], [28, [2, [15, "k"], "getMetadata", [7, [15, "g"]]]]], [46, [36]]], [22, ["b", [15, "i"], [15, "e"]], [46, [2, [15, "k"], "abort", [7]], [36]]], [2, [15, "k"], "setMetadata", [7, [15, "d"], false]], [22, [28, [15, "j"]], [46, [2, [15, "k"], "setHitData", [7, "link_id", [44]]], [2, [15, "k"], "setHitData", [7, "link_url", [44]]], [2, [15, "k"], "setHitData", [7, "link_text", [44]]], [2, [15, "k"], "setHitData", [7, "file_name", [44]]], [2, [15, "k"], "setHitData", [7, "file_extension", [44]]]]]]]], [52, "b", ["require", "internal.getProductSettingsParameter"]], [52, "c", ["require", "internal.registerCcdCallback"]], [52, "d", "speculative"], [52, "e", "ae_block_downloads"], [52, "f", "file_download"], [52, "g", "em_event"], [36, [8, "registerDownloadActivityCallback", [15, "h"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_ccdEmOutboundClickActivity", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "h", [46, "i", "j"], ["c", [15, "i"], [51, "", [7, "k"], [22, [30, [21, [2, [15, "k"], "getEventName", [7]], [15, "f"]], [28, [2, [15, "k"], "getMetadata", [7, [15, "g"]]]]], [46, [36]]], [22, ["b", [15, "i"], [15, "e"]], [46, [2, [15, "k"], "abort", [7]], [36]]], [2, [15, "k"], "setMetadata", [7, [15, "d"], false]], [22, [28, [15, "j"]], [46, [2, [15, "k"], "setHitData", [7, "link_id", [44]]], [2, [15, "k"], "setHitData", [7, "link_classes", [44]]], [2, [15, "k"], "setHitData", [7, "link_url", [44]]], [2, [15, "k"], "setHitData", [7, "link_domain", [44]]], [2, [15, "k"], "setHitData", [7, "outbound", [44]]]]]]]], [52, "b", ["require", "internal.getProductSettingsParameter"]], [52, "c", ["require", "internal.registerCcdCallback"]], [52, "d", "speculative"], [52, "e", "ae_block_outbound_click"], [52, "f", "click"], [52, "g", "em_event"], [36, [8, "registerOutbackClickActivityCallback", [15, "h"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_ccdEmPageViewActivity", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "j", [46, "k"], ["c", [15, "k"], [51, "", [7, "l"], [22, [30, [21, [2, [15, "l"], "getEventName", [7]], [15, "h"]], [28, [2, [15, "l"], "getMetadata", [7, [15, "i"]]]]], [46, [36]]], [22, ["b", [15, "k"], [15, "g"]], [46, [2, [15, "l"], "abort", [7]], [36]]], [22, [28, [2, [15, "l"], "getMetadata", [7, [15, "f"]]]], [46, ["d", [15, "k"], "page_referrer", [2, [15, "l"], "getHitData", [7, "page_referrer"]]]]], [2, [15, "l"], "setMetadata", [7, [15, "e"], false]]]]], [52, "b", ["require", "internal.getProductSettingsParameter"]], [52, "c", ["require", "internal.registerCcdCallback"]], [52, "d", ["require", "internal.setRemoteConfigParameter"]], [52, "e", "speculative"], [52, "f", "is_sgtm_prehit"], [52, "g", "ae_block_history"], [52, "h", "page_view"], [52, "i", "em_event"], [36, [8, "registerPageViewActivityCallback", [15, "j"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_ccdEmSiteSearchActivity", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "b", [46, "d", "e"], [52, "f", [2, [30, [15, "d"], ""], "split", [7, ","]]], [53, [41, "g"], [3, "g", 0], [63, [7, "g"], [23, [15, "g"], [17, [15, "f"], "length"]], [33, [15, "g"], [3, "g", [0, [15, "g"], 1]]], [46, [53, [52, "h", ["e", [2, [16, [15, "f"], [15, "g"]], "trim", [7]]]], [22, [21, [15, "h"], [44]], [46, [36, [15, "h"]]]]]]]]], [50, "c", [46, "d", "e", "f"], [52, "g", [8, "search_term", [15, "d"]]], [52, "h", [2, [30, [15, "e"], ""], "split", [7, ","]]], [53, [41, "i"], [3, "i", 0], [63, [7, "i"], [23, [15, "i"], [17, [15, "h"], "length"]], [33, [15, "i"], [3, "i", [0, [15, "i"], 1]]], [46, [53, [52, "j", [2, [16, [15, "h"], [15, "i"]], "trim", [7]]], [52, "k", ["f", [15, "j"]]], [22, [21, [15, "k"], [44]], [46, [43, [15, "g"], [0, "q_", [15, "j"]], [15, "k"]]]]]]]], [36, [15, "g"]]], [36, [8, "getSearchTerm", [15, "b"], "buildEventParams", [15, "c"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_ccdEmScrollActivity", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "h", [46, "i", "j"], ["c", [15, "i"], [51, "", [7, "k"], [22, [30, [21, [2, [15, "k"], "getEventName", [7]], [15, "f"]], [28, [2, [15, "k"], "getMetadata", [7, [15, "g"]]]]], [46, [36]]], [22, ["b", [15, "i"], [15, "e"]], [46, [2, [15, "k"], "abort", [7]], [36]]], [2, [15, "k"], "setMetadata", [7, [15, "d"], false]], [22, [28, [15, "j"]], [46, [2, [15, "k"], "setHitData", [7, "percent_scrolled", [44]]]]]]]], [52, "b", ["require", "internal.getProductSettingsParameter"]], [52, "c", ["require", "internal.registerCcdCallback"]], [52, "d", "speculative"], [52, "e", "ae_block_scroll"], [52, "f", "scroll"], [52, "g", "em_event"], [36, [8, "registerScrollActivityCallback", [15, "h"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_ccdEmVideoActivity", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "j", [46, "k", "l"], ["c", [15, "k"], [51, "", [7, "m"], [52, "n", [2, [15, "m"], "getEventName", [7]]], [52, "o", [30, [30, [20, [15, "n"], [15, "f"]], [20, [15, "n"], [15, "g"]]], [20, [15, "n"], [15, "h"]]]], [22, [30, [28, [15, "o"]], [28, [2, [15, "m"], "getMetadata", [7, [15, "i"]]]]], [46, [36]]], [22, ["b", [15, "k"], [15, "e"]], [46, [2, [15, "m"], "abort", [7]], [36]]], [2, [15, "m"], "setMetadata", [7, [15, "d"], false]], [22, [28, [15, "l"]], [46, [2, [15, "m"], "setHitData", [7, "video_current_time", [44]]], [2, [15, "m"], "setHitData", [7, "video_duration", [44]]], [2, [15, "m"], "setHitData", [7, "video_percent", [44]]], [2, [15, "m"], "setHitData", [7, "video_provider", [44]]], [2, [15, "m"], "setHitData", [7, "video_title", [44]]], [2, [15, "m"], "setHitData", [7, "video_url", [44]]], [2, [15, "m"], "setHitData", [7, "visible", [44]]]]]]]], [52, "b", ["require", "internal.getProductSettingsParameter"]], [52, "c", ["require", "internal.registerCcdCallback"]], [52, "d", "speculative"], [52, "e", "ae_block_video"], [52, "f", "video_start"], [52, "g", "video_progress"], [52, "h", "video_complete"], [52, "i", "em_event"], [36, [8, "registerVideoActivityCallback", [15, "j"]]]], [36, ["a"]]]], ["$0"]]], [52, "__module_ccdGaRegionScopedSettings", [13, [41, "$0"], [3, "$0", [51, "", [7], [50, "a", [46], [50, "n", [46, "q", "r", "s"], [50, "x", [46, "z"], [52, "ba", [16, [15, "m"], [15, "z"]]], [22, [28, [15, "ba"]], [46, [36]]], [53, [41, "bb"], [3, "bb", 0], [63, [7, "bb"], [23, [15, "bb"], [17, [15, "ba"], "length"]], [33, [15, "bb"], [3, "bb", [0, [15, "bb"], 1]]], [46, [53, [52, "bc", [16, [15, "ba"], [15, "bb"]]], ["u", [15, "t"], [17, [15, "bc"], "name"], [17, [15, "bc"], "value"]]]]]]], [50, "y", [46, "z"], [22, [30, [28, [15, "v"]], [21, [17, [15, "v"], "length"], 2]], [46, [36, false]]], [41, "ba"], [3, "ba", [16, [15, "z"], [15, "w"]]], [22, [20, [15, "ba"], [44]], [46, [3, "ba", [16, [15, "z"], [15, "v"]]]]], [36, [28, [28, [15, "ba"]]]]], [22, [28, [15, "r"]], [46, [36]]], [52, "t", [30, [17, [15, "q"], "instanceDestinationId"], [17, ["d"], "containerId"]]], [52, "u", ["i", [15, "g"], [15, "s"]]], [52, "v", [13, [41, "$0"], [3, "$0", ["i", [15, "e"], [15, "s"]]], ["$0"]]], [52, "w", [13, [41, "$0"], [3, "$0", ["i", [15, "f"], [15, "s"]]], ["$0"]]], [53, [41, "z"], [3, "z", 0], [63, [7, "z"], [23, [15, "z"], [17, [15, "r"], "length"]], [33, [15, "z"], [3, "z", [0, [15, "z"], 1]]], [46, [53, [52, "ba", [16, [15, "r"], [15, "z"]]], [22, [30, [17, [15, "ba"], "disallowAllRegions"], ["y", [17, [15, "ba"], "disallowedRegions"]]], [46, ["x", [17, [15, "ba"], "redactFieldGroup"]]]]]]]]], [50, "o", [46, "q"], [52, "r", [8]], [22, [28, [15, "q"]], [46, [36, [15, "r"]]]], [52, "s", [2, [15, "q"], "split", [7, ","]]], [53, [41, "t"], [3, "t", 0], [63, [7, "t"], [23, [15, "t"], [17, [15, "s"], "length"]], [33, [15, "t"], [3, "t", [0, [15, "t"], 1]]], [46, [53, [52, "u", [2, [16, [15, "s"], [15, "t"]], "trim", [7]]], [22, [28, [15, "u"]], [46, [6]]], [52, "v", [2, [15, "u"], "split", [7, "-"]]], [52, "w", [16, [15, "v"], 0]], [52, "x", [39, [20, [17, [15, "v"], "length"], 2], [15, "u"], [44]]], [22, [30, [28, [15, "w"]], [21, [17, [15, "w"], "length"], 2]], [46, [6]]], [22, [1, [21, [15, "x"], [44]], [30, [23, [17, [15, "x"], "length"], 4], [18, [17, [15, "x"], "length"], 6]]], [46, [6]]], [43, [15, "r"], [15, "u"], true]]]]], [36, [15, "r"]]], [50, "p", [46, "q"], [22, [28, [17, [15, "q"], "settingsTable"]], [46, [36, [7]]]], [52, "r", [8]], [53, [41, "s"], [3, "s", 0], [63, [7, "s"], [23, [15, "s"], [17, [17, [15, "q"], "settingsTable"], "length"]], [33, [15, "s"], [3, "s", [0, [15, "s"], 1]]], [46, [53, [52, "t", [16, [17, [15, "q"], "settingsTable"], [15, "s"]]], [52, "u", [17, [15, "t"], "redactFieldGroup"]], [22, [28, [16, [15, "m"], [15, "u"]]], [46, [6]]], [43, [15, "r"], [15, "u"], [8, "redactFieldGroup", [15, "u"], "disallowAllRegions", false, "disallowedRegions", [8]]], [52, "v", [16, [15, "r"], [15, "u"]]], [22, [17, [15, "t"], "disallowAllRegions"], [46, [43, [15, "v"], "disallowAllRegions", true], [6]]], [43, [15, "v"], "disallowedRegions", ["o", [17, [15, "t"], "disallowedRegions"]]]]]]], [36, [2, [15, "b"], "values", [7, [15, "r"]]]]], [52, "b", ["require", "Object"]], [52, "c", [13, [41, "$0"], [3, "$0", ["require", "internal.getFlags"]], ["$0"]]], [52, "d", ["require", "getContainerVersion"]], [52, "e", ["require", "internal.getCountryCode"]], [52, "f", ["require", "internal.getRegionCode"]], [52, "g", ["require", "internal.setRemoteConfigParameter"]], [52, "h", [15, "__module_activities"]], [52, "i", [17, [15, "h"], "withRequestContext"]], [41, "j"], [41, "k"], [41, "l"], [52, "m", [8, "GOOGLE_SIGNALS", [7, [8, "name", "allow_google_signals", "value", false]], "DEVICE_AND_GEO", [7, [8, "name", "geo_granularity", "value", true], [8, "name", "redact_device_info", "value", true]]]], [36, [8, "applyRegionScopedSettings", [15, "n"], "extractRedactedLocations", [15, "p"]]]], [36, ["a"]]]], ["$0"]]]
        ],
        "entities": {
            "__c": {
                "2": true,
                "4": true
            },
            "__ccd_auto_redact": {
                "2": true,
                "4": true
            },
            "__ccd_conversion_marking": {
                "2": true,
                "4": true
            },
            "__ccd_em_download": {
                "2": true,
                "4": true
            },
            "__ccd_em_outbound_click": {
                "2": true,
                "4": true
            },
            "__ccd_em_page_view": {
                "2": true,
                "4": true
            },
            "__ccd_em_scroll": {
                "2": true,
                "4": true
            },
            "__ccd_em_site_search": {
                "2": true,
                "4": true
            },
            "__ccd_em_video": {
                "2": true,
                "4": true
            },
            "__ccd_ga_ads_link": {
                "2": true,
                "4": true
            },
            "__ccd_ga_first": {
                "2": true,
                "4": true
            },
            "__ccd_ga_last": {
                "2": true,
                "4": true
            },
            "__ccd_ga_regscope": {
                "2": true,
                "4": true
            },
            "__e": {
                "2": true,
                "4": true
            },
            "__ogt_1p_data_v2": {
                "2": true
            },
            "__ogt_event_create": {
                "2": true,
                "4": true
            },
            "__ogt_google_signals": {
                "2": true,
                "4": true
            },
            "__set_product_settings": {
                "2": true,
                "4": true
            }

        },
        "blob": {
            "1": "1"
        },
        "permissions": {
            "__c": {},
            "__ccd_auto_redact": {},
            "__ccd_conversion_marking": {},
            "__ccd_em_download": {
                "listen_data_layer": {
                    "accessType": "specific",
                    "allowedEvents": ["gtm.linkClick"]
                },
                "access_template_storage": {},
                "detect_link_click_events": {
                    "allowWaitForTags": ""
                }
            },
            "__ccd_em_outbound_click": {
                "get_url": {
                    "urlParts": "any",
                    "queriesAllowed": "any"
                },
                "listen_data_layer": {
                    "accessType": "specific",
                    "allowedEvents": ["gtm.linkClick"]
                },
                "access_template_storage": {},
                "detect_link_click_events": {
                    "allowWaitForTags": ""
                }
            },
            "__ccd_em_page_view": {
                "listen_data_layer": {
                    "accessType": "specific",
                    "allowedEvents": ["gtm.historyChange-v2"]
                },
                "access_template_storage": {},
                "detect_history_change_events": {}
            },
            "__ccd_em_scroll": {
                "listen_data_layer": {
                    "accessType": "specific",
                    "allowedEvents": ["gtm.scrollDepth"]
                },
                "process_dom_events": {
                    "targets": [{
                        "targetType": "window",
                        "eventName": "resize"
                    }, {
                        "targetType": "window",
                        "eventName": "scroll"
                    }, {
                        "targetType": "window",
                        "eventName": "scrollend"
                    }]
                },
                "access_template_storage": {},
                "detect_scroll_events": {}
            },
            "__ccd_em_site_search": {
                "get_url": {
                    "urlParts": "any",
                    "queriesAllowed": "any"
                },
                "read_container_data": {}
            },
            "__ccd_em_video": {
                "listen_data_layer": {
                    "accessType": "specific",
                    "allowedEvents": ["gtm.video"]
                },
                "access_template_storage": {},
                "detect_youtube_activity_events": {
                    "allowFixMissingJavaScriptApi": false
                }
            },
            "__ccd_ga_ads_link": {},
            "__ccd_ga_first": {},
            "__ccd_ga_last": {},
            "__ccd_ga_regscope": {
                "read_container_data": {}
            },
            "__e": {
                "read_event_data": {
                    "eventDataAccess": "specific",
                    "keyPatterns": ["event"]
                }
            },
            "__ogt_1p_data_v2": {
                "detect_user_provided_data": {
                    "limitDataSources": true,
                    "allowAutoDataSources": true,
                    "allowManualDataSources": false,
                    "allowCodeDataSources": false
                }
            },
            "__ogt_event_create": {
                "access_template_storage": {}
            },
            "__ogt_google_signals": {
                "read_container_data": {}
            },
            "__set_product_settings": {}

        }
        ,
        "security_groups": {
            "google": ["__c", "__ccd_auto_redact", "__ccd_conversion_marking", "__ccd_em_download", "__ccd_em_outbound_click", "__ccd_em_page_view", "__ccd_em_scroll", "__ccd_em_site_search", "__ccd_em_video", "__ccd_ga_ads_link", "__ccd_ga_first", "__ccd_ga_last", "__ccd_ga_regscope", "__e", "__ogt_1p_data_v2", "__ogt_event_create", "__ogt_google_signals", "__set_product_settings"
            ]

        }

    };

    var ba, ca = function(a) {
        var b = 0;
        return function() {
            return b < a.length ? {
                done: !1,
                value: a[b++]
            } : {
                done: !0
            }
        }
    }, da = typeof Object.defineProperties == "function" ? Object.defineProperty : function(a, b, c) {
        if (a == Array.prototype || a == Object.prototype)
            return a;
        a[b] = c.value;
        return a
    }
    , ea = function(a) {
        for (var b = ["object" == typeof globalThis && globalThis, a, "object" == typeof window && window, "object" == typeof self && self, "object" == typeof global && global], c = 0; c < b.length; ++c) {
            var d = b[c];
            if (d && d.Math == Math)
                return d
        }
        throw Error("Cannot find global object");
    }, fa = ea(this), ia = function(a, b) {
        if (b)
            a: {
                for (var c = fa, d = a.split("."), e = 0; e < d.length - 1; e++) {
                    var f = d[e];
                    if (!(f in c))
                        break a;
                    c = c[f]
                }
                var g = d[d.length - 1]
                  , k = c[g]
                  , m = b(k);
                m != k && m != null && da(c, g, {
                    configurable: !0,
                    writable: !0,
                    value: m
                })
            }
    };
    ia("Symbol", function(a) {
        if (a)
            return a;
        var b = function(f, g) {
            this.j = f;
            da(this, "description", {
                configurable: !0,
                writable: !0,
                value: g
            })
        };
        b.prototype.toString = function() {
            return this.j
        }
        ;
        var c = "jscomp_symbol_" + (Math.random() * 1E9 >>> 0) + "_"
          , d = 0
          , e = function(f) {
            if (this instanceof e)
                throw new TypeError("Symbol is not a constructor");
            return new b(c + (f || "") + "_" + d++,f)
        };
        return e
    });
    ia("Symbol.iterator", function(a) {
        if (a)
            return a;
        for (var b = Symbol("Symbol.iterator"), c = "Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "), d = 0; d < c.length; d++) {
            var e = fa[c[d]];
            typeof e === "function" && typeof e.prototype[b] != "function" && da(e.prototype, b, {
                configurable: !0,
                writable: !0,
                value: function() {
                    return ja(ca(this))
                }
            })
        }
        return b
    });
    var ja = function(a) {
        var b = {
            next: a
        };
        b[Symbol.iterator] = function() {
            return this
        }
        ;
        return b
    }
      , ka = function(a) {
        return a.raw = a
    }
      , na = function(a, b) {
        a.raw = b;
        return a
    }
      , oa = function(a) {
        var b = typeof Symbol != "undefined" && Symbol.iterator && a[Symbol.iterator];
        if (b)
            return b.call(a);
        if (typeof a.length == "number")
            return {
                next: ca(a)
            };
        throw Error(String(a) + " is not an iterable or ArrayLike");
    }
      , pa = function(a) {
        for (var b, c = []; !(b = a.next()).done; )
            c.push(b.value);
        return c
    }
      , qa = function(a) {
        return a instanceof Array ? a : pa(oa(a))
    }
      , ra = typeof Object.assign == "function" ? Object.assign : function(a, b) {
        for (var c = 1; c < arguments.length; c++) {
            var d = arguments[c];
            if (d)
                for (var e in d)
                    Object.prototype.hasOwnProperty.call(d, e) && (a[e] = d[e])
        }
        return a
    }
    ;
    ia("Object.assign", function(a) {
        return a || ra
    });
    var sa = typeof Object.create == "function" ? Object.create : function(a) {
        var b = function() {};
        b.prototype = a;
        return new b
    }
    , ta;
    if (typeof Object.setPrototypeOf == "function")
        ta = Object.setPrototypeOf;
    else {
        var ua;
        a: {
            var va = {
                a: !0
            }
              , wa = {};
            try {
                wa.__proto__ = va;
                ua = wa.a;
                break a
            } catch (a) {}
            ua = !1
        }
        ta = ua ? function(a, b) {
            a.__proto__ = b;
            if (a.__proto__ !== b)
                throw new TypeError(a + " is not extensible");
            return a
        }
        : null
    }
    var xa = ta
      , za = function(a, b) {
        a.prototype = sa(b.prototype);
        a.prototype.constructor = a;
        if (xa)
            xa(a, b);
        else
            for (var c in b)
                if (c != "prototype")
                    if (Object.defineProperties) {
                        var d = Object.getOwnPropertyDescriptor(b, c);
                        d && Object.defineProperty(a, c, d)
                    } else
                        a[c] = b[c];
        a.bo = b.prototype
    }
      , Aa = function() {
        this.K = !1;
        this.D = null;
        this.xb = void 0;
        this.j = 1;
        this.Ca = this.O = 0;
        this.H = null
    }
      , Ba = function(a) {
        if (a.K)
            throw new TypeError("Generator is already running");
        a.K = !0
    };
    Aa.prototype.W = function(a) {
        this.xb = a
    }
    ;
    var Ca = function(a, b) {
        a.H = {
            Sj: b,
            mm: !0
        };
        a.j = a.O || a.Ca
    };
    Aa.prototype.return = function(a) {
        this.H = {
            return: a
        };
        this.j = this.Ca
    }
    ;
    var Da = function(a, b) {
        a.j = 4;
        return {
            value: b
        }
    }
      , Ea = function(a) {
        a.O = 0;
        var b = a.H.Sj;
        a.H = null;
        return b
    }
      , Ga = function(a) {
        this.j = new Aa;
        this.D = a
    }
      , Ja = function(a, b) {
        Ba(a.j);
        var c = a.j.D;
        if (c)
            return Ha(a, "return"in c ? c["return"] : function(d) {
                return {
                    value: d,
                    done: !0
                }
            }
            , b, a.j.return);
        a.j.return(b);
        return Ia(a)
    }
      , Ha = function(a, b, c, d) {
        try {
            var e = b.call(a.j.D, c);
            if (!(e instanceof Object))
                throw new TypeError("Iterator result " + e + " is not an object");
            if (!e.done)
                return a.j.K = !1,
                e;
            var f = e.value
        } catch (g) {
            return a.j.D = null,
            Ca(a.j, g),
            Ia(a)
        }
        a.j.D = null;
        d.call(a.j, f);
        return Ia(a)
    }
      , Ia = function(a) {
        for (; a.j.j; )
            try {
                var b = a.D(a.j);
                if (b)
                    return a.j.K = !1,
                    {
                        value: b.value,
                        done: !1
                    }
            } catch (d) {
                a.j.xb = void 0,
                Ca(a.j, d)
            }
        a.j.K = !1;
        if (a.j.H) {
            var c = a.j.H;
            a.j.H = null;
            if (c.mm)
                throw c.Sj;
            return {
                value: c.return,
                done: !0
            }
        }
        return {
            value: void 0,
            done: !0
        }
    }
      , Ka = function(a) {
        this.next = function(b) {
            var c;
            Ba(a.j);
            a.j.D ? c = Ha(a, a.j.D.next, b, a.j.W) : (a.j.W(b),
            c = Ia(a));
            return c
        }
        ;
        this.throw = function(b) {
            var c;
            Ba(a.j);
            a.j.D ? c = Ha(a, a.j.D["throw"], b, a.j.W) : (Ca(a.j, b),
            c = Ia(a));
            return c
        }
        ;
        this.return = function(b) {
            return Ja(a, b)
        }
        ;
        this[Symbol.iterator] = function() {
            return this
        }
    }
      , La = function(a) {
        function b(d) {
            return a.next(d)
        }
        function c(d) {
            return a.throw(d)
        }
        new Promise(function(d, e) {
            function f(g) {
                g.done ? d(g.value) : Promise.resolve(g.value).then(b, c).then(f, e)
            }
            f(a.next())
        }
        )
    }
      , Ma = function() {
        for (var a = Number(this), b = [], c = a; c < arguments.length; c++)
            b[c - a] = arguments[c];
        return b
    };
    /*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
    var Oa = this || self
      , Pa = function(a) {
        return a
    };
    var Qa = function(a, b) {
        this.type = a;
        this.data = b
    };
    var Ra = function() {
        this.j = {};
        this.H = {}
    };
    ba = Ra.prototype;
    ba.get = function(a) {
        return this.j["dust." + a]
    }
    ;
    ba.set = function(a, b) {
        a = "dust." + a;
        this.H.hasOwnProperty(a) || (this.j[a] = b)
    }
    ;
    ba.Zh = function(a, b) {
        this.set(a, b);
        this.H["dust." + a] = !0
    }
    ;
    ba.has = function(a) {
        return this.j.hasOwnProperty("dust." + a)
    }
    ;
    ba.Hf = function(a) {
        a = "dust." + a;
        this.H.hasOwnProperty(a) || delete this.j[a]
    }
    ;
    var Ta = function() {};
    Ta.prototype.reset = function() {}
    ;
    var Ua = function(a, b) {
        this.O = a;
        this.parent = b;
        this.j = this.D = void 0;
        this.K = !1;
        this.H = function(c, d, e) {
            return c.apply(d, e)
        }
        ;
        this.values = new Ra
    };
    Ua.prototype.add = function(a, b) {
        Va(this, a, b, !1)
    }
    ;
    var Va = function(a, b, c, d) {
        a.K || (d ? a.values.Zh(b, c) : a.values.set(b, c))
    };
    Ua.prototype.set = function(a, b) {
        this.K || (!this.values.has(a) && this.parent && this.parent.has(a) ? this.parent.set(a, b) : this.values.set(a, b))
    }
    ;
    Ua.prototype.get = function(a) {
        return this.values.has(a) ? this.values.get(a) : this.parent ? this.parent.get(a) : void 0
    }
    ;
    Ua.prototype.has = function(a) {
        return !!this.values.has(a) || !(!this.parent || !this.parent.has(a))
    }
    ;
    var Wa = function(a) {
        var b = new Ua(a.O,a);
        a.D && (b.D = a.D);
        b.H = a.H;
        b.j = a.j;
        return b
    };
    Ua.prototype.sd = function() {
        return this.O
    }
    ;
    Ua.prototype.Ma = function() {
        this.K = !0
    }
    ;
    function Xa(a, b) {
        for (var c, d = 0; d < b.length && !(c = Ya(a, b[d]),
        c instanceof Qa); d++)
            ;
        return c
    }
    function Ya(a, b) {
        try {
            var c = a.get(String(b[0]));
            if (!c || typeof c.invoke !== "function")
                throw Error("Attempting to execute non-function " + b[0] + ".");
            return c.invoke.apply(c, [a].concat(b.slice(1)))
        } catch (e) {
            var d = a.D;
            d && d(e, b.context ? {
                id: b[0],
                line: b.context.line
            } : null);
            throw e;
        }
    }
    ;var Za = function() {
        this.D = new Ta;
        this.j = new Ua(this.D)
    };
    ba = Za.prototype;
    ba.sd = function() {
        return this.D
    }
    ;
    ba.execute = function(a) {
        var b = Array.prototype.slice.call(arguments, 0);
        return this.Xh(b)
    }
    ;
    ba.Xh = function() {
        for (var a, b = 0; b < arguments.length; b++)
            a = Ya(this.j, arguments[b]);
        return a
    }
    ;
    ba.Xk = function(a) {
        var b = Wa(this.j);
        b.j = a;
        for (var c, d = 1; d < arguments.length; d++)
            c = Ya(b, arguments[d]);
        return c
    }
    ;
    ba.Ma = function() {
        this.j.Ma()
    }
    ;
    var $a = function() {
        Ra.call(this);
        this.D = !1
    };
    za($a, Ra);
    var ab = function(a, b) {
        var c = [], d;
        for (d in a.j)
            if (a.j.hasOwnProperty(d))
                switch (d = d.substr(5),
                b) {
                case 1:
                    c.push(d);
                    break;
                case 2:
                    c.push(a.get(d));
                    break;
                case 3:
                    c.push([d, a.get(d)])
                }
        return c
    };
    $a.prototype.set = function(a, b) {
        this.D || Ra.prototype.set.call(this, a, b)
    }
    ;
    $a.prototype.Zh = function(a, b) {
        this.D || Ra.prototype.Zh.call(this, a, b)
    }
    ;
    $a.prototype.Hf = function(a) {
        this.D || Ra.prototype.Hf.call(this, a)
    }
    ;
    $a.prototype.Ma = function() {
        this.D = !0
    }
    ;
    /*
 jQuery (c) 2005, 2012 jQuery Foundation, Inc. jquery.org/license.
*/
    var cb = /\[object (Boolean|Number|String|Function|Array|Date|RegExp)\]/
      , db = function(a) {
        if (a == null)
            return String(a);
        var b = cb.exec(Object.prototype.toString.call(Object(a)));
        return b ? b[1].toLowerCase() : "object"
    }
      , eb = function(a, b) {
        return Object.prototype.hasOwnProperty.call(Object(a), b)
    }
      , fb = function(a) {
        if (!a || db(a) != "object" || a.nodeType || a == a.window)
            return !1;
        try {
            if (a.constructor && !eb(a, "constructor") && !eb(a.constructor.prototype, "isPrototypeOf"))
                return !1
        } catch (c) {
            return !1
        }
        for (var b in a)
            ;
        return b === void 0 || eb(a, b)
    }
      , h = function(a, b) {
        var c = b || (db(a) == "array" ? [] : {}), d;
        for (d in a)
            if (eb(a, d)) {
                var e = a[d];
                db(e) == "array" ? (db(c[d]) != "array" && (c[d] = []),
                c[d] = h(e, c[d])) : fb(e) ? (fb(c[d]) || (c[d] = {}),
                c[d] = h(e, c[d])) : c[d] = e
            }
        return c
    };
    function gb(a) {
        if (a == void 0 || Array.isArray(a) || fb(a))
            return !0;
        switch (typeof a) {
        case "boolean":
        case "number":
        case "string":
        case "function":
            return !0
        }
        return !1
    }
    function hb(a) {
        return typeof a === "number" && a >= 0 && isFinite(a) && a % 1 === 0 || typeof a === "string" && a[0] !== "-" && a === "" + parseInt(a)
    }
    ;var ib = function(a) {
        this.j = [];
        this.H = !1;
        this.D = new $a;
        a = a || [];
        for (var b in a)
            a.hasOwnProperty(b) && (hb(b) ? this.j[Number(b)] = a[Number(b)] : this.D.set(b, a[b]))
    };
    ba = ib.prototype;
    ba.toString = function(a) {
        if (a && a.indexOf(this) >= 0)
            return "";
        for (var b = [], c = 0; c < this.j.length; c++) {
            var d = this.j[c];
            d === null || d === void 0 ? b.push("") : d instanceof ib ? (a = a || [],
            a.push(this),
            b.push(d.toString(a)),
            a.pop()) : b.push(String(d))
        }
        return b.join(",")
    }
    ;
    ba.set = function(a, b) {
        if (!this.H)
            if (a === "length") {
                if (!hb(b))
                    throw Error("RangeError: Length property must be a valid integer.");
                this.j.length = Number(b)
            } else
                hb(a) ? this.j[Number(a)] = b : this.D.set(a, b)
    }
    ;
    ba.get = function(a) {
        return a === "length" ? this.length() : hb(a) ? this.j[Number(a)] : this.D.get(a)
    }
    ;
    ba.length = function() {
        return this.j.length
    }
    ;
    ba.Qb = function() {
        for (var a = ab(this.D, 1), b = 0; b < this.j.length; b++)
            a.push(b + "");
        return new ib(a)
    }
    ;
    var jb = function(a, b) {
        hb(b) ? delete a.j[Number(b)] : a.D.Hf(b)
    };
    ba = ib.prototype;
    ba.pop = function() {
        return this.j.pop()
    }
    ;
    ba.push = function() {
        return this.j.push.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.shift = function() {
        return this.j.shift()
    }
    ;
    ba.splice = function(a, b) {
        return new ib(this.j.splice.apply(this.j, arguments))
    }
    ;
    ba.unshift = function() {
        return this.j.unshift.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.has = function(a) {
        return hb(a) && this.j.hasOwnProperty(a) || this.D.has(a)
    }
    ;
    ba.Ma = function() {
        this.H = !0;
        Object.freeze(this.j);
        this.D.Ma()
    }
    ;
    function kb(a) {
        for (var b = [], c = 0; c < a.length(); c++)
            a.has(c) && (b[c] = a.get(c));
        return b
    }
    ;var lb = function() {
        $a.call(this)
    };
    za(lb, $a);
    lb.prototype.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    var mb = function(a) {
        for (var b = ab(a, 3), c = new ib, d = 0; d < b.length; d++) {
            var e = new ib(b[d]);
            c.push(e)
        }
        return c
    };
    function nb() {
        for (var a = ob, b = {}, c = 0; c < a.length; ++c)
            b[a[c]] = c;
        return b
    }
    function pb() {
        var a = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
        a += a.toLowerCase() + "0123456789-_";
        return a + "."
    }
    var ob, qb;
    function rb(a) {
        ob = ob || pb();
        qb = qb || nb();
        for (var b = [], c = 0; c < a.length; c += 3) {
            var d = c + 1 < a.length
              , e = c + 2 < a.length
              , f = a.charCodeAt(c)
              , g = d ? a.charCodeAt(c + 1) : 0
              , k = e ? a.charCodeAt(c + 2) : 0
              , m = f >> 2
              , n = (f & 3) << 4 | g >> 4
              , p = (g & 15) << 2 | k >> 6
              , q = k & 63;
            e || (q = 64,
            d || (p = 64));
            b.push(ob[m], ob[n], ob[p], ob[q])
        }
        return b.join("")
    }
    function sb(a) {
        function b(m) {
            for (; d < a.length; ) {
                var n = a.charAt(d++)
                  , p = qb[n];
                if (p != null)
                    return p;
                if (!/^[\s\xa0]*$/.test(n))
                    throw Error("Unknown base64 encoding at char: " + n);
            }
            return m
        }
        ob = ob || pb();
        qb = qb || nb();
        for (var c = "", d = 0; ; ) {
            var e = b(-1)
              , f = b(0)
              , g = b(64)
              , k = b(64);
            if (k === 64 && e === -1)
                return c;
            c += String.fromCharCode(e << 2 | f >> 4);
            g !== 64 && (c += String.fromCharCode(f << 4 & 240 | g >> 2),
            k !== 64 && (c += String.fromCharCode(g << 6 & 192 | k)))
        }
    }
    ;var tb = {};
    function ub(a, b) {
        tb[a] = tb[a] || [];
        tb[a][b] = !0
    }
    function vb(a) {
        var b = tb[a];
        if (!b || b.length === 0)
            return "";
        for (var c = [], d = 0, e = 0; e < b.length; e++)
            e % 8 === 0 && e > 0 && (c.push(String.fromCharCode(d)),
            d = 0),
            b[e] && (d |= 1 << e % 8);
        d > 0 && c.push(String.fromCharCode(d));
        return rb(c.join("")).replace(/\.+$/, "")
    }
    function wb() {
        for (var a = [], b = tb.fdr || [], c = 0; c < b.length; c++)
            b[c] && a.push(c);
        return a.length > 0 ? a : void 0
    }
    ;var xb = []
      , yb = {};
    function zb(a) {
        return xb[a] === void 0 ? !1 : xb[a]
    }
    ;function Ab() {}
    function Bb(a) {
        return typeof a === "function"
    }
    function l(a) {
        return typeof a === "string"
    }
    function Cb(a) {
        return typeof a === "number" && !isNaN(a)
    }
    function Db(a) {
        return Array.isArray(a) ? a : [a]
    }
    function Eb(a, b) {
        if (a && Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                if (a[c] && b(a[c]))
                    return a[c]
    }
    function Fb(a, b) {
        if (!Cb(a) || !Cb(b) || a > b)
            a = 0,
            b = 2147483647;
        return Math.floor(Math.random() * (b - a + 1) + a)
    }
    function Gb(a, b) {
        for (var c = new Hb, d = 0; d < a.length; d++)
            c.set(a[d], !0);
        for (var e = 0; e < b.length; e++)
            if (c.get(b[e]))
                return !0;
        return !1
    }
    function z(a, b) {
        for (var c in a)
            Object.prototype.hasOwnProperty.call(a, c) && b(c, a[c])
    }
    function Ib(a) {
        return !!a && (Object.prototype.toString.call(a) === "[object Arguments]" || Object.prototype.hasOwnProperty.call(a, "callee"))
    }
    function Jb(a) {
        return Math.round(Number(a)) || 0
    }
    function Kb(a) {
        return "false" === String(a).toLowerCase() ? !1 : !!a
    }
    function Lb(a) {
        var b = [];
        if (Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                b.push(String(a[c]));
        return b
    }
    function Mb(a) {
        return a ? a.replace(/^\s+|\s+$/g, "") : ""
    }
    function Nb() {
        return new Date(Date.now())
    }
    function Ob() {
        return Nb().getTime()
    }
    var Hb = function() {
        this.prefix = "gtm.";
        this.values = {}
    };
    Hb.prototype.set = function(a, b) {
        this.values[this.prefix + a] = b
    }
    ;
    Hb.prototype.get = function(a) {
        return this.values[this.prefix + a]
    }
    ;
    function Pb(a, b, c) {
        return a && a.hasOwnProperty(b) ? a[b] : c
    }
    function Qb(a) {
        var b = a;
        return function() {
            if (b) {
                var c = b;
                b = void 0;
                try {
                    c()
                } catch (d) {}
            }
        }
    }
    function Rb(a, b) {
        for (var c in b)
            b.hasOwnProperty(c) && (a[c] = b[c])
    }
    function Sb(a, b) {
        for (var c = [], d = 0; d < a.length; d++)
            c.push(a[d]),
            c.push.apply(c, b[a[d]] || []);
        return c
    }
    function Tb(a, b) {
        return a.length >= b.length && a.substring(0, b.length) === b
    }
    function Ub(a, b) {
        return a.length >= b.length && a.substring(a.length - b.length, a.length) === b
    }
    function Vb(a, b) {
        var c = G;
        b = b || [];
        for (var d = c, e = 0; e < a.length - 1; e++) {
            if (!d.hasOwnProperty(a[e]))
                return;
            d = d[a[e]];
            if (b.indexOf(d) >= 0)
                return
        }
        return d
    }
    function Wb(a, b) {
        for (var c = {}, d = c, e = a.split("."), f = 0; f < e.length - 1; f++)
            d = d[e[f]] = {};
        d[e[e.length - 1]] = b;
        return c
    }
    var Xb = /^\w{1,9}$/;
    function Yb(a, b) {
        a = a || {};
        b = b || ",";
        var c = [];
        z(a, function(d, e) {
            Xb.test(d) && e && c.push(d)
        });
        return c.join(b)
    }
    function Zb(a, b) {
        function c() {
            e && ++d === b && (e(),
            e = null,
            c.done = !0)
        }
        var d = 0
          , e = a;
        c.done = !1;
        return c
    }
    function $b(a) {
        if (!a)
            return a;
        var b = a;
        if (zb(3))
            try {
                b = decodeURIComponent(a)
            } catch (d) {}
        var c = b.split(",");
        return c.length === 2 && c[0] === c[1] ? c[0] : a
    }
    ;var ac, bc = function() {
        if (ac === void 0) {
            var a = null
              , b = Oa.trustedTypes;
            if (b && b.createPolicy) {
                try {
                    a = b.createPolicy("goog#html", {
                        createHTML: Pa,
                        createScript: Pa,
                        createScriptURL: Pa
                    })
                } catch (c) {
                    Oa.console && Oa.console.error(c.message)
                }
                ac = a
            } else
                ac = a
        }
        return ac
    };
    var cc = function(a) {
        this.j = a
    };
    cc.prototype.toString = function() {
        return this.j + ""
    }
    ;
    var dc = function(a) {
        return a instanceof cc && a.constructor === cc ? a.j : "type_error:TrustedResourceUrl"
    }
      , ec = {}
      , fc = function(a) {
        var b = a
          , c = bc()
          , d = c ? c.createScriptURL(b) : b;
        return new cc(d,ec)
    };
    /*

 SPDX-License-Identifier: Apache-2.0
*/
    var gc = ka([""])
      , hc = na(["\x00"], ["\\0"])
      , ic = na(["\n"], ["\\n"])
      , jc = na(["\x00"], ["\\u0000"]);
    function kc(a) {
        return a.toString().indexOf("`") === -1
    }
    kc(function(a) {
        return a(gc)
    }) || kc(function(a) {
        return a(hc)
    }) || kc(function(a) {
        return a(ic)
    }) || kc(function(a) {
        return a(jc)
    });
    var lc = function(a) {
        this.j = a
    };
    lc.prototype.toString = function() {
        return this.j
    }
    ;
    var mc = new lc("about:invalid#zClosurez");
    var nc = function(a) {
        this.wm = a
    };
    function oc(a) {
        return new nc(function(b) {
            return b.substr(0, a.length + 1).toLowerCase() === a + ":"
        }
        )
    }
    var pc = [oc("data"), oc("http"), oc("https"), oc("mailto"), oc("ftp"), new nc(function(a) {
        return /^[^:]*([/?#]|$)/.test(a)
    }
    )];
    function qc(a, b) {
        b = b === void 0 ? pc : b;
        if (a instanceof lc)
            return a;
        for (var c = 0; c < b.length; ++c) {
            var d = b[c];
            if (d instanceof nc && d.wm(a))
                return new lc(a)
        }
    }
    function rc(a) {
        var b;
        b = b === void 0 ? pc : b;
        return qc(a, b) || mc
    }
    var sc = /^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
    function tc(a) {
        var b;
        if (a instanceof lc)
            if (a instanceof lc)
                b = a.j;
            else
                throw Error("");
        else
            b = sc.test(a) ? a : void 0;
        return b
    }
    ;var vc = function() {
        this.j = uc[0].toLowerCase()
    };
    vc.prototype.toString = function() {
        return this.j
    }
    ;
    var wc = Array.prototype.indexOf ? function(a, b) {
        return Array.prototype.indexOf.call(a, b, void 0)
    }
    : function(a, b) {
        if (typeof a === "string")
            return typeof b !== "string" || b.length != 1 ? -1 : a.indexOf(b, 0);
        for (var c = 0; c < a.length; c++)
            if (c in a && a[c] === b)
                return c;
        return -1
    }
    ;
    var xc = {}
      , yc = function(a) {
        this.j = a
    };
    yc.prototype.toString = function() {
        return this.j.toString()
    }
    ;
    function zc(a, b) {
        var c = [new vc];
        if (c.length === 0)
            throw Error("");
        var d = c.map(function(f) {
            var g;
            if (f instanceof vc)
                g = f.j;
            else
                throw Error("");
            return g
        })
          , e = b.toLowerCase();
        if (d.every(function(f) {
            return e.indexOf(f) !== 0
        }))
            throw Error('Attribute "' + b + '" does not match any of the allowed prefixes.');
        a.setAttribute(b, "true")
    }
    ;function Ac(a, b) {
        var c = tc(b);
        c !== void 0 && (a.action = c)
    }
    ;"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON", "INPUT"]);
    function Bc(a) {
        return a === null ? "null" : a === void 0 ? "undefined" : a
    }
    ;var G = window
      , H = document
      , Cc = navigator
      , Dc = function() {
        var a;
        try {
            a = Cc.serviceWorker
        } catch (b) {
            return
        }
        return a
    }
      , Ec = H.currentScript
      , Fc = Ec && Ec.src
      , Gc = function(a, b) {
        var c = G[a];
        G[a] = c === void 0 ? b : c;
        return G[a]
    };
    function Hc(a) {
        return (Cc.userAgent || "").indexOf(a) !== -1
    }
    var Ic = {
        async: 1,
        nonce: 1,
        onerror: 1,
        onload: 1,
        src: 1,
        type: 1
    }
      , Jc = {
        onload: 1,
        src: 1,
        width: 1,
        height: 1,
        style: 1
    };
    function Kc(a, b, c) {
        b && z(b, function(d, e) {
            d = d.toLowerCase();
            c.hasOwnProperty(d) || a.setAttribute(d, e)
        })
    }
    var Lc = function(a, b, c, d, e) {
        var f = H.createElement("script");
        Kc(f, d, Ic);
        f.type = "text/javascript";
        f.async = d && d.async === !1 ? !1 : !0;
        var g;
        g = fc(Bc(a));
        f.src = dc(g);
        var k, m, n, p = (n = (m = (f.ownerDocument && f.ownerDocument.defaultView || window).document).querySelector) == null ? void 0 : n.call(m, "script[nonce]");
        (k = p ? p.nonce || p.getAttribute("nonce") || "" : "") && f.setAttribute("nonce", k);
        b && (f.onload = b);
        c && (f.onerror = c);
        if (e)
            e.appendChild(f);
        else {
            var q = H.getElementsByTagName("script")[0] || H.body || H.head;
            q.parentNode.insertBefore(f, q)
        }
        return f
    }
      , Mc = function() {
        if (Fc) {
            var a = Fc.toLowerCase();
            if (a.indexOf("https://") === 0)
                return 2;
            if (a.indexOf("http://") === 0)
                return 3
        }
        return 1
    }
      , Nc = function(a, b, c, d, e) {
        var f;
        f = f === void 0 ? !0 : f;
        var g = e
          , k = !1;
        g || (g = H.createElement("iframe"),
        k = !0);
        Kc(g, c, Jc);
        d && z(d, function(n, p) {
            g.dataset[n] = p
        });
        f && (g.height = "0",
        g.width = "0",
        g.style.display = "none",
        g.style.visibility = "hidden");
        a !== void 0 && (g.src = a);
        if (k) {
            var m = H.body && H.body.lastChild || H.body || H.head;
            m.parentNode.insertBefore(g, m)
        }
        b && (g.onload = b);
        return g
    }
      , Oc = function(a, b, c, d) {
        var e = new Image(1,1);
        Kc(e, d, {});
        e.onload = function() {
            e.onload = null;
            b && b()
        }
        ;
        e.onerror = function() {
            e.onerror = null;
            c && c()
        }
        ;
        e.src = a;
        return e
    }
      , Pc = function(a, b, c, d) {
        a.addEventListener ? a.addEventListener(b, c, !!d) : a.attachEvent && a.attachEvent("on" + b, c)
    }
      , Qc = function(a, b, c) {
        a.removeEventListener ? a.removeEventListener(b, c, !1) : a.detachEvent && a.detachEvent("on" + b, c)
    }
      , I = function(a) {
        G.setTimeout(a, 0)
    }
      , Rc = function(a, b) {
        return a && b && a.attributes && a.attributes[b] ? a.attributes[b].value : null
    }
      , Sc = function(a) {
        function b(e) {
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && (e = e.replace(/(\xa0+|\s{2,}|\n|\r\t)/g, " "));
            return e
        }
        var c = b(a.innerText || a.textContent || "");
        if (zb(10)) {
            var d = b(a.textContent || "");
            ub("TAGGING", 26);
            d !== c && ub("TAGGING", 25)
        }
        return c
    }
      , Tc = function(a) {
        var b = H.createElement("div"), c = b, d, e = Bc("A<div>" + a + "</div>"), f = bc(), g = f ? f.createHTML(e) : e;
        d = new yc(g,xc);
        if (c.nodeType === 1) {
            var k = c.tagName;
            if (k === "SCRIPT" || k === "STYLE")
                throw Error("");
        }
        c.innerHTML = d instanceof yc && d.constructor === yc ? d.j : "type_error:SafeHtml";
        b = b.lastChild;
        for (var m = []; b.firstChild; )
            m.push(b.removeChild(b.firstChild));
        return m
    }
      , Uc = function(a, b, c) {
        c = c || 100;
        for (var d = {}, e = 0; e < b.length; e++)
            d[b[e]] = !0;
        for (var f = a, g = 0; f && g <= c; g++) {
            if (d[String(f.tagName).toLowerCase()])
                return f;
            f = f.parentElement
        }
        return null
    }
      , Vc = function(a) {
        var b;
        try {
            b = Cc.sendBeacon && Cc.sendBeacon(a)
        } catch (c) {
            ub("TAGGING", 15)
        }
        b || Oc(a)
    }
      , Wc = function(a, b) {
        try {
            return Cc.sendBeacon(a, b)
        } catch (c) {
            ub("TAGGING", 15)
        }
        return !1
    }
      , Xc = {
        cache: "no-store",
        credentials: "include",
        keepalive: !0,
        method: "POST",
        mode: "no-cors",
        redirect: "follow"
    }
      , Zc = function(a, b, c) {
        if (Yc()) {
            var d = Object.assign({}, Xc);
            b && (d.body = b);
            c && (c.attributionReporting && (d.attributionReporting = c.attributionReporting),
            c.browsingTopics && (d.browsingTopics = c.browsingTopics));
            try {
                var e = G.fetch(a, d);
                e && e.catch(Ab);
                return !0
            } catch (f) {}
        }
        if (c && c.noFallback)
            return !1;
        if (b)
            return Wc(a, b);
        Vc(a);
        return !0
    }
      , Yc = function() {
        return typeof G.fetch === "function"
    }
      , $c = function(a, b) {
        var c = a[b];
        c && typeof c.animVal === "string" && (c = c.animVal);
        return c
    }
      , ad = function() {
        var a = G.performance;
        if (a && Bb(a.now))
            return a.now()
    }
      , bd = function() {
        return G.performance || void 0
    };
    function cd(a, b) {
        return this.evaluate(a) && this.evaluate(b)
    }
    function dd(a, b) {
        return this.evaluate(a) === this.evaluate(b)
    }
    function ed(a, b) {
        return this.evaluate(a) || this.evaluate(b)
    }
    function fd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        return String(a).indexOf(String(b)) > -1
    }
    function gd(a, b) {
        var c = String(this.evaluate(a))
          , d = String(this.evaluate(b));
        return c.substring(0, d.length) === d
    }
    function hd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        switch (a) {
        case "pageLocation":
            var c = G.location.href;
            b instanceof lb && b.get("stripProtocol") && (c = c.replace(/^https?:\/\//, ""));
            return c
        }
    }
    ;var id = function(a, b) {
        $a.call(this);
        this.bk = a;
        this.uh = b
    };
    za(id, $a);
    ba = id.prototype;
    ba.toString = function() {
        return this.bk
    }
    ;
    ba.getName = function() {
        return this.bk
    }
    ;
    ba.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    ba.invoke = function(a) {
        return this.uh.apply(new jd(this,a), Array.prototype.slice.call(arguments, 1))
    }
    ;
    ba.ib = function(a) {
        try {
            return this.invoke.apply(this, Array.prototype.slice.call(arguments, 0))
        } catch (b) {}
    }
    ;
    var jd = function(a, b) {
        this.uh = a;
        this.F = b
    };
    jd.prototype.evaluate = function(a) {
        var b = this.F;
        return Array.isArray(a) ? Ya(b, a) : a
    }
    ;
    jd.prototype.getName = function() {
        return this.uh.getName()
    }
    ;
    jd.prototype.sd = function() {
        return this.F.sd()
    }
    ;
    var kd = function() {
        this.map = new Map
    };
    kd.prototype.set = function(a, b) {
        this.map.set(a, b)
    }
    ;
    kd.prototype.get = function(a) {
        return this.map.get(a)
    }
    ;
    var ld = function() {
        this.keys = [];
        this.values = []
    };
    ld.prototype.set = function(a, b) {
        this.keys.push(a);
        this.values.push(b)
    }
    ;
    ld.prototype.get = function(a) {
        var b = this.keys.indexOf(a);
        if (b > -1)
            return this.values[b]
    }
    ;
    function md() {
        try {
            return Map ? new kd : new ld
        } catch (a) {
            return new ld
        }
    }
    ;var nd = function(a) {
        if (a instanceof nd)
            return a;
        if (gb(a))
            throw Error("Type of given value has an equivalent Pixie type.");
        this.value = a
    };
    nd.prototype.getValue = function() {
        return this.value
    }
    ;
    nd.prototype.toString = function() {
        return String(this.value)
    }
    ;
    var pd = function(a) {
        $a.call(this);
        this.promise = a;
        this.set("then", od(this));
        this.set("catch", od(this, !0));
        this.set("finally", od(this, !1, !0))
    };
    za(pd, lb);
    var od = function(a, b, c) {
        b = b === void 0 ? !1 : b;
        c = c === void 0 ? !1 : c;
        return new id("",function(d, e) {
            b && (e = d,
            d = void 0);
            c && (e = d);
            d instanceof id || (d = void 0);
            e instanceof id || (e = void 0);
            var f = Wa(this.F)
              , g = function(m) {
                return function(n) {
                    return c ? (m.invoke(f),
                    a.promise) : m.invoke(f, n)
                }
            }
              , k = a.promise.then(d && g(d), e && g(e));
            return new pd(k)
        }
        )
    };
    function J(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m = ab(g, 1), n = 0; n < m.length; n++)
                k[m[n]] = f(g.get(m[n]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (g instanceof ib) {
                var m = [];
                d.set(g, m);
                for (var n = g.Qb(), p = 0; p < n.length(); p++)
                    m[n.get(p)] = f(g.get(n.get(p)));
                return m
            }
            if (g instanceof pd)
                return g.promise;
            if (g instanceof lb) {
                var q = {};
                d.set(g, q);
                e(g, q);
                return q
            }
            if (g instanceof id) {
                var r = function() {
                    for (var u = Array.prototype.slice.call(arguments, 0), v = 0; v < u.length; v++)
                        u[v] = qd(u[v], b, c);
                    var w = new Ua(b ? b.sd() : new Ta);
                    b && (w.j = b.j);
                    return f(g.invoke.apply(g, [w].concat(u)))
                };
                d.set(g, r);
                e(g, r);
                return r
            }
            var t = !1;
            switch (c) {
            case 1:
                t = !0;
                break;
            case 2:
                t = !1;
                break;
            case 3:
                t = !1;
                break;
            default:
            }
            if (g instanceof nd && t)
                return g.getValue();
            switch (typeof g) {
            case "boolean":
            case "number":
            case "string":
            case "undefined":
                return g;
            case "object":
                if (g === null)
                    return null
            }
        };
        return f(a)
    }
    function qd(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m in g)
                g.hasOwnProperty(m) && k.set(m, f(g[m]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (Array.isArray(g) || Ib(g)) {
                var m = new ib([]);
                d.set(g, m);
                for (var n in g)
                    g.hasOwnProperty(n) && m.set(n, f(g[n]));
                return m
            }
            if (fb(g)) {
                var p = new lb;
                d.set(g, p);
                e(g, p);
                return p
            }
            if (typeof g === "function") {
                var q = new id("",function() {
                    for (var x = Array.prototype.slice.call(arguments, 0), y = 0; y < x.length; y++)
                        x[y] = J(this.evaluate(x[y]), b, c);
                    return f((0,
                    this.F.H)(g, g, x))
                }
                );
                d.set(g, q);
                e(g, q);
                return q
            }
            var v = typeof g;
            if (g === null || v === "string" || v === "number" || v === "boolean")
                return g;
            var w = !1;
            switch (c) {
            case 1:
                w = !0;
                break;
            case 2:
                w = !1;
                break;
            default:
            }
            if (g !== void 0 && w)
                return new nd(g)
        };
        return f(a)
    }
    ;function rd() {
        var a = !1;
        return a
    }
    ;var sd = {
        supportedMethods: "concat every filter forEach hasOwnProperty indexOf join lastIndexOf map pop push reduce reduceRight reverse shift slice some sort splice unshift toString".split(" "),
        concat: function(a) {
            for (var b = [], c = 0; c < this.length(); c++)
                b.push(this.get(c));
            for (var d = 1; d < arguments.length; d++)
                if (arguments[d]instanceof ib)
                    for (var e = arguments[d], f = 0; f < e.length(); f++)
                        b.push(e.get(f));
                else
                    b.push(arguments[d]);
            return new ib(b)
        },
        every: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                if (this.has(d) && !b.invoke(a, this.get(d), d, this))
                    return !1;
            return !0
        },
        filter: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && b.invoke(a, this.get(e), e, this) && d.push(this.get(e));
            return new ib(d)
        },
        forEach: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                this.has(d) && b.invoke(a, this.get(d), d, this)
        },
        hasOwnProperty: function(a, b) {
            return this.has(b)
        },
        indexOf: function(a, b, c) {
            var d = this.length()
              , e = c === void 0 ? 0 : Number(c);
            e < 0 && (e = Math.max(d + e, 0));
            for (var f = e; f < d; f++)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        join: function(a, b) {
            for (var c = [], d = 0; d < this.length(); d++)
                c.push(this.get(d));
            return c.join(b)
        },
        lastIndexOf: function(a, b, c) {
            var d = this.length()
              , e = d - 1;
            c !== void 0 && (e = c < 0 ? d + c : Math.min(c, e));
            for (var f = e; f >= 0; f--)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        map: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && (d[e] = b.invoke(a, this.get(e), e, this));
            return new ib(d)
        },
        pop: function() {
            return this.pop()
        },
        push: function(a) {
            return this.push.apply(this, Array.prototype.slice.call(arguments, 1))
        },
        reduce: function(a, b, c) {
            var d = this.length(), e, f = 0;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: Reduce on List with no elements.");
                for (var g = 0; g < d; g++)
                    if (this.has(g)) {
                        e = this.get(g);
                        f = g + 1;
                        break
                    }
                if (g === d)
                    throw Error("TypeError: Reduce on List with no elements.");
            }
            for (var k = f; k < d; k++)
                this.has(k) && (e = b.invoke(a, e, this.get(k), k, this));
            return e
        },
        reduceRight: function(a, b, c) {
            var d = this.length(), e, f = d - 1;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: ReduceRight on List with no elements.");
                for (var g = 1; g <= d; g++)
                    if (this.has(d - g)) {
                        e = this.get(d - g);
                        f = d - (g + 1);
                        break
                    }
                if (g > d)
                    throw Error("TypeError: ReduceRight on List with no elements.");
            }
            for (var k = f; k >= 0; k--)
                this.has(k) && (e = b.invoke(a, e, this.get(k), k, this));
            return e
        },
        reverse: function() {
            for (var a = kb(this), b = a.length - 1, c = 0; b >= 0; b--,
            c++)
                a.hasOwnProperty(b) ? this.set(c, a[b]) : jb(this, c);
            return this
        },
        shift: function() {
            return this.shift()
        },
        slice: function(a, b, c) {
            var d = this.length();
            b === void 0 && (b = 0);
            b = b < 0 ? Math.max(d + b, 0) : Math.min(b, d);
            c = c === void 0 ? d : c < 0 ? Math.max(d + c, 0) : Math.min(c, d);
            c = Math.max(b, c);
            for (var e = [], f = b; f < c; f++)
                e.push(this.get(f));
            return new ib(e)
        },
        some: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                if (this.has(d) && b.invoke(a, this.get(d), d, this))
                    return !0;
            return !1
        },
        sort: function(a, b) {
            var c = kb(this);
            b === void 0 ? c.sort() : c.sort(function(e, f) {
                return Number(b.invoke(a, e, f))
            });
            for (var d = 0; d < c.length; d++)
                c.hasOwnProperty(d) ? this.set(d, c[d]) : jb(this, d);
            return this
        },
        splice: function(a, b, c) {
            return this.splice.apply(this, Array.prototype.splice.call(arguments, 1, arguments.length - 1))
        },
        toString: function() {
            return this.toString()
        },
        unshift: function(a) {
            return this.unshift.apply(this, Array.prototype.slice.call(arguments, 1))
        }
    };
    var td = function(a) {
        var b;
        b = Error.call(this, a);
        this.message = b.message;
        "stack"in b && (this.stack = b.stack)
    };
    za(td, Error);
    var wd = {
        charAt: 1,
        concat: 1,
        indexOf: 1,
        lastIndexOf: 1,
        match: 1,
        replace: 1,
        search: 1,
        slice: 1,
        split: 1,
        substring: 1,
        toLowerCase: 1,
        toLocaleLowerCase: 1,
        toString: 1,
        toUpperCase: 1,
        toLocaleUpperCase: 1,
        trim: 1
    }
      , xd = new Qa("break")
      , yd = new Qa("continue");
    function zd(a, b) {
        return this.evaluate(a) + this.evaluate(b)
    }
    function Ad(a, b) {
        return this.evaluate(a) && this.evaluate(b)
    }
    function Bd(a, b, c) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        c = this.evaluate(c);
        if (!(c instanceof ib))
            throw Error("Error: Non-List argument given to Apply instruction.");
        if (a === null || a === void 0) {
            var d = "TypeError: Can't read property " + b + " of " + a + ".";
            if (rd())
                throw new td(d);
            throw Error(d);
        }
        var e = typeof a === "number";
        if (typeof a === "boolean" || e) {
            if (b === "toString") {
                if (e && c.length()) {
                    var f = J(c.get(0));
                    try {
                        return a.toString(f)
                    } catch (y) {}
                }
                return a.toString()
            }
            var g = "TypeError: " + a + "." + b + " is not a function.";
            if (rd())
                throw new td(g);
            throw Error(g);
        }
        if (typeof a === "string") {
            if (wd.hasOwnProperty(b)) {
                var k = 2;
                k = 1;
                var m = J(c, void 0, k);
                return qd(a[b].apply(a, m), this.F)
            }
            var n = "TypeError: " + b + " is not a function";
            if (rd())
                throw new td(n);
            throw Error(n);
        }
        if (a instanceof ib) {
            if (a.has(b)) {
                var p = a.get(b);
                if (p instanceof id) {
                    var q = kb(c);
                    q.unshift(this.F);
                    return p.invoke.apply(p, q)
                }
                var r = "TypeError: " + b + " is not a function";
                if (rd())
                    throw new td(r);
                throw Error(r);
            }
            if (sd.supportedMethods.indexOf(b) >= 0) {
                var t = kb(c);
                t.unshift(this.F);
                return sd[b].apply(a, t)
            }
        }
        if (a instanceof id || a instanceof lb) {
            if (a.has(b)) {
                var u = a.get(b);
                if (u instanceof id) {
                    var v = kb(c);
                    v.unshift(this.F);
                    return u.invoke.apply(u, v)
                }
                var w = "TypeError: " + b + " is not a function";
                if (rd())
                    throw new td(w);
                throw Error(w);
            }
            if (b === "toString")

            Ua.prototype.Ma = function() {
        this.K = !0
    }
    ;
    function Xa(a, b) {
        for (var c, d = 0; d < b.length && !(c = Ya(a, b[d]),
        c instanceof Qa); d++)
            ;
        return c
    }
    function Ya(a, b) {
        try {
            var c = a.get(String(b[0]));
            if (!c || typeof c.invoke !== "function")
                throw Error("Attempting to execute non-function " + b[0] + ".");
            return c.invoke.apply(c, [a].concat(b.slice(1)))
        } catch (e) {
            var d = a.D;
            d && d(e, b.context ? {
                id: b[0],
                line: b.context.line
            } : null);
            throw e;
        }
    }
    ;var Za = function() {
        this.D = new Ta;
        this.j = new Ua(this.D)
    };
    ba = Za.prototype;
    ba.sd = function() {
        return this.D
    }
    ;
    ba.execute = function(a) {
        var b = Array.prototype.slice.call(arguments, 0);
        return this.Xh(b)
    }
    ;
    ba.Xh = function() {
        for (var a, b = 0; b < arguments.length; b++)
            a = Ya(this.j, arguments[b]);
        return a
    }
    ;
    ba.Xk = function(a) {
        var b = Wa(this.j);
        b.j = a;
        for (var c, d = 1; d < arguments.length; d++)
            c = Ya(b, arguments[d]);
        return c
    }
    ;
    ba.Ma = function() {
        this.j.Ma()
    }
    ;
    var $a = function() {
        Ra.call(this);
        this.D = !1
    };
    za($a, Ra);
    var ab = function(a, b) {
        var c = [], d;
        for (d in a.j)
            if (a.j.hasOwnProperty(d))
                switch (d = d.substr(5),
                b) {
                case 1:
                    c.push(d);
                    break;
                case 2:
                    c.push(a.get(d));
                    break;
                case 3:
                    c.push([d, a.get(d)])
                }
        return c
    };
    $a.prototype.set = function(a, b) {
        this.D || Ra.prototype.set.call(this, a, b)
    }
    ;
    $a.prototype.Zh = function(a, b) {
        this.D || Ra.prototype.Zh.call(this, a, b)
    }
    ;
    $a.prototype.Hf = function(a) {
        this.D || Ra.prototype.Hf.call(this, a)
    }
    ;
    $a.prototype.Ma = function() {
        this.D = !0
    }
    ;
    /*
 jQuery (c) 2005, 2012 jQuery Foundation, Inc. jquery.org/license.
*/
    var cb = /\[object (Boolean|Number|String|Function|Array|Date|RegExp)\]/
      , db = function(a) {
        if (a == null)
            return String(a);
        var b = cb.exec(Object.prototype.toString.call(Object(a)));
        return b ? b[1].toLowerCase() : "object"
    }
      , eb = function(a, b) {
        return Object.prototype.hasOwnProperty.call(Object(a), b)
    }
      , fb = function(a) {
        if (!a || db(a) != "object" || a.nodeType || a == a.window)
            return !1;
        try {
            if (a.constructor && !eb(a, "constructor") && !eb(a.constructor.prototype, "isPrototypeOf"))
                return !1
        } catch (c) {
            return !1
        }
        for (var b in a)
            ;
        return b === void 0 || eb(a, b)
    }
      , h = function(a, b) {
        var c = b || (db(a) == "array" ? [] : {}), d;
        for (d in a)
            if (eb(a, d)) {
                var e = a[d];
                db(e) == "array" ? (db(c[d]) != "array" && (c[d] = []),
                c[d] = h(e, c[d])) : fb(e) ? (fb(c[d]) || (c[d] = {}),
                c[d] = h(e, c[d])) : c[d] = e
            }
        return c
    };
    function gb(a) {
        if (a == void 0 || Array.isArray(a) || fb(a))
            return !0;
        switch (typeof a) {
        case "boolean":
        case "number":
        case "string":
        case "function":
            return !0
        }
        return !1
    }
    function hb(a) {
        return typeof a === "number" && a >= 0 && isFinite(a) && a % 1 === 0 || typeof a === "string" && a[0] !== "-" && a === "" + parseInt(a)
    }
    ;var ib = function(a) {
        this.j = [];
        this.H = !1;
        this.D = new $a;
        a = a || [];
        for (var b in a)
            a.hasOwnProperty(b) && (hb(b) ? this.j[Number(b)] = a[Number(b)] : this.D.set(b, a[b]))
    };
    ba = ib.prototype;
    ba.toString = function(a) {
        if (a && a.indexOf(this) >= 0)
            return "";
        for (var b = [], c = 0; c < this.j.length; c++) {
            var d = this.j[c];
            d === null || d === void 0 ? b.push("") : d instanceof ib ? (a = a || [],
            a.push(this),
            b.push(d.toString(a)),
            a.pop()) : b.push(String(d))
        }
        return b.join(",")
    }
    ;
    ba.set = function(a, b) {
        if (!this.H)
            if (a === "length") {
                if (!hb(b))
                    throw Error("RangeError: Length property must be a valid integer.");
                this.j.length = Number(b)
            } else
                hb(a) ? this.j[Number(a)] = b : this.D.set(a, b)
    }
    ;
    ba.get = function(a) {
        return a === "length" ? this.length() : hb(a) ? this.j[Number(a)] : this.D.get(a)
    }
    ;
    ba.length = function() {
        return this.j.length
    }
    ;
    ba.Qb = function() {
        for (var a = ab(this.D, 1), b = 0; b < this.j.length; b++)
            a.push(b + "");
        return new ib(a)
    }
    ;
    var jb = function(a, b) {
        hb(b) ? delete a.j[Number(b)] : a.D.Hf(b)
    };
    ba = ib.prototype;
    ba.pop = function() {
        return this.j.pop()
    }
    ;
    ba.push = function() {
        return this.j.push.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.shift = function() {
        return this.j.shift()
    }
    ;
    ba.splice = function(a, b) {
        return new ib(this.j.splice.apply(this.j, arguments))
    }
    ;
    ba.unshift = function() {
        return this.j.unshift.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.has = function(a) {
        return hb(a) && this.j.hasOwnProperty(a) || this.D.has(a)
    }
    ;
    ba.Ma = function() {
        this.H = !0;
        Object.freeze(this.j);
        this.D.Ma()
    }
    ;
    function kb(a) {
        for (var b = [], c = 0; c < a.length(); c++)
            a.has(c) && (b[c] = a.get(c));
        return b
    }
    ;var lb = function() {
        $a.call(this)
    };
    za(lb, $a);
    lb.prototype.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    var mb = function(a) {
        for (var b = ab(a, 3), c = new ib, d = 0; d < b.length; d++) {
            var e = new ib(b[d]);
            c.push(e)
        }
        return c
    };
    function nb() {
        for (var a = ob, b = {}, c = 0; c < a.length; ++c)
            b[a[c]] = c;
        return b
    }
    function pb() {
        var a = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
        a += a.toLowerCase() + "0123456789-_";
        return a + "."
    }
    var ob, qb;
    function rb(a) {
        ob = ob || pb();
        qb = qb || nb();
        for (var b = [], c = 0; c < a.length; c += 3) {
            var d = c + 1 < a.length
              , e = c + 2 < a.length
              , f = a.charCodeAt(c)
              , g = d ? a.charCodeAt(c + 1) : 0
              , k = e ? a.charCodeAt(c + 2) : 0
              , m = f >> 2
              , n = (f & 3) << 4 | g >> 4
              , p = (g & 15) << 2 | k >> 6
              , q = k & 63;
            e || (q = 64,
            d || (p = 64));
            b.push(ob[m], ob[n], ob[p], ob[q])
        }
        return b.join("")
    }
    function sb(a) {
        function b(m) {
            for (; d < a.length; ) {
                var n = a.charAt(d++)
                  , p = qb[n];
                if (p != null)
                    return p;
                if (!/^[\s\xa0]*$/.test(n))
                    throw Error("Unknown base64 encoding at char: " + n);
            }
            return m
        }
        ob = ob || pb();
        qb = qb || nb();
        for (var c = "", d = 0; ; ) {
            var e = b(-1)
              , f = b(0)
              , g = b(64)
              , k = b(64);
            if (k === 64 && e === -1)
                return c;
            c += String.fromCharCode(e << 2 | f >> 4);
            g !== 64 && (c += String.fromCharCode(f << 4 & 240 | g >> 2),
            k !== 64 && (c += String.fromCharCode(g << 6 & 192 | k)))
        }
    }
    ;var tb = {};
    function ub(a, b) {
        tb[a] = tb[a] || [];
        tb[a][b] = !0
    }
    function vb(a) {
        var b = tb[a];
        if (!b || b.length === 0)
            return "";
        for (var c = [], d = 0, e = 0; e < b.length; e++)
            e % 8 === 0 && e > 0 && (c.push(String.fromCharCode(d)),
            d = 0),
            b[e] && (d |= 1 << e % 8);
        d > 0 && c.push(String.fromCharCode(d));
        return rb(c.join("")).replace(/\.+$/, "")
    }
    function wb() {
        for (var a = [], b = tb.fdr || [], c = 0; c < b.length; c++)
            b[c] && a.push(c);
        return a.length > 0 ? a : void 0
    }
    ;var xb = []
      , yb = {};
    function zb(a) {
        return xb[a] === void 0 ? !1 : xb[a]
    }
    ;function Ab() {}
    function Bb(a) {
        return typeof a === "function"
    }
    function l(a) {
        return typeof a === "string"
    }
    function Cb(a) {
        return typeof a === "number" && !isNaN(a)
    }
    function Db(a) {
        return Array.isArray(a) ? a : [a]
    }
    function Eb(a, b) {
        if (a && Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                if (a[c] && b(a[c]))
                    return a[c]
    }
    function Fb(a, b) {
        if (!Cb(a) || !Cb(b) || a > b)
            a = 0,
            b = 2147483647;
        return Math.floor(Math.random() * (b - a + 1) + a)
    }
    function Gb(a, b) {
        for (var c = new Hb, d = 0; d < a.length; d++)
            c.set(a[d], !0);
        for (var e = 0; e < b.length; e++)
            if (c.get(b[e]))
                return !0;
        return !1
    }
    function z(a, b) {
        for (var c in a)
            Object.prototype.hasOwnProperty.call(a, c) && b(c, a[c])
    }
    function Ib(a) {
        return !!a && (Object.prototype.toString.call(a) === "[object Arguments]" || Object.prototype.hasOwnProperty.call(a, "callee"))
    }
    function Jb(a) {
        return Math.round(Number(a)) || 0
    }
    function Kb(a) {
        return "false" === String(a).toLowerCase() ? !1 : !!a
    }
    function Lb(a) {
        var b = [];
        if (Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                b.push(String(a[c]));
        return b
    }
    function Mb(a) {
        return a ? a.replace(/^\s+|\s+$/g, "") : ""
    }
    function Nb() {
        return new Date(Date.now())
    }
    function Ob() {
        return Nb().getTime()
    }
    var Hb = function() {
        this.prefix = "gtm.";
        this.values = {}
    };
    Hb.prototype.set = function(a, b) {
        this.values[this.prefix + a] = b
    }
    ;
    Hb.prototype.get = function(a) {
        return this.values[this.prefix + a]
    }
    ;
    function Pb(a, b, c) {
        return a && a.hasOwnProperty(b) ? a[b] : c
    }
    function Qb(a) {
        var b = a;
        return function() {
            if (b) {
                var c = b;
                b = void 0;
                try {
                    c()
                } catch (d) {}
            }
        }
    }
    function Rb(a, b) {
        for (var c in b)
            b.hasOwnProperty(c) && (a[c] = b[c])
    }
    function Sb(a, b) {
        for (var c = [], d = 0; d < a.length; d++)
            c.push(a[d]),
            c.push.apply(c, b[a[d]] || []);
        return c
    }
    function Tb(a, b) {
        return a.length >= b.length && a.substring(0, b.length) === b
    }
    function Ub(a, b) {
        return a.length >= b.length && a.substring(a.length - b.length, a.length) === b
    }
    function Vb(a, b) {
        var c = G;
        b = b || [];
        for (var d = c, e = 0; e < a.length - 1; e++) {
            if (!d.hasOwnProperty(a[e]))
                return;
            d = d[a[e]];
            if (b.indexOf(d) >= 0)
                return
        }
        return d
    }
    function Wb(a, b) {
        for (var c = {}, d = c, e = a.split("."), f = 0; f < e.length - 1; f++)
            d = d[e[f]] = {};
        d[e[e.length - 1]] = b;
        return c
    }
    var Xb = /^\w{1,9}$/;
    function Yb(a, b) {
        a = a || {};
        b = b || ",";
        var c = [];
        z(a, function(d, e) {
            Xb.test(d) && e && c.push(d)
        });
        return c.join(b)
    }
    function Zb(a, b) {
        function c() {
            e && ++d === b && (e(),
            e = null,
            c.done = !0)
        }
        var d = 0
          , e = a;
        c.done = !1;
        return c
    }
    function $b(a) {
        if (!a)
            return a;
        var b = a;
        if (zb(3))
            try {
                b = decodeURIComponent(a)
            } catch (d) {}
        var c = b.split(",");
        return c.length === 2 && c[0] === c[1] ? c[0] : a
    }
    ;var ac, bc = function() {
        if (ac === void 0) {
            var a = null
              , b = Oa.trustedTypes;
            if (b && b.createPolicy) {
                try {
                    a = b.createPolicy("goog#html", {
                        createHTML: Pa,
                        createScript: Pa,
                        createScriptURL: Pa
                    })
                } catch (c) {
                    Oa.console && Oa.console.error(c.message)
                }
                ac = a
            } else
                ac = a
        }
        return ac
    };
    var cc = function(a) {
        this.j = a
    };
    cc.prototype.toString = function() {
        return this.j + ""
    }
    ;
    var dc = function(a) {
        return a instanceof cc && a.constructor === cc ? a.j : "type_error:TrustedResourceUrl"
    }
      , ec = {}
      , fc = function(a) {
        var b = a
          , c = bc()
          , d = c ? c.createScriptURL(b) : b;
        return new cc(d,ec)
    };
    /*

 SPDX-License-Identifier: Apache-2.0
*/
    var gc = ka([""])
      , hc = na(["\x00"], ["\\0"])
      , ic = na(["\n"], ["\\n"])
      , jc = na(["\x00"], ["\\u0000"]);
    function kc(a) {
        return a.toString().indexOf("`") === -1
    }
    kc(function(a) {
        return a(gc)
    }) || kc(function(a) {
        return a(hc)
    }) || kc(function(a) {
        return a(ic)
    }) || kc(function(a) {
        return a(jc)
    });
    var lc = function(a) {
        this.j = a
    };
    lc.prototype.toString = function() {
        return this.j
    }
    ;
    var mc = new lc("about:invalid#zClosurez");
    var nc = function(a) {
        this.wm = a
    };
    function oc(a) {
        return new nc(function(b) {
            return b.substr(0, a.length + 1).toLowerCase() === a + ":"
        }
        )
    }
    var pc = [oc("data"), oc("http"), oc("https"), oc("mailto"), oc("ftp"), new nc(function(a) {
        return /^[^:]*([/?#]|$)/.test(a)
    }
    )];
    function qc(a, b) {
        b = b === void 0 ? pc : b;
        if (a instanceof lc)
            return a;
        for (var c = 0; c < b.length; ++c) {
            var d = b[c];
            if (d instanceof nc && d.wm(a))
                return new lc(a)
        }
    }
    function rc(a) {
        var b;
        b = b === void 0 ? pc : b;
        return qc(a, b) || mc
    }
    var sc = /^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
    function tc(a) {
        var b;
        if (a instanceof lc)
            if (a instanceof lc)
                b = a.j;
            else
                throw Error("");
        else
            b = sc.test(a) ? a : void 0;
        return b
    }
    ;var vc = function() {
        this.j = uc[0].toLowerCase()
    };
    vc.prototype.toString = function() {
        return this.j
    }
    ;
    var wc = Array.prototype.indexOf ? function(a, b) {
        return Array.prototype.indexOf.call(a, b, void 0)
    }
    : function(a, b) {
        if (typeof a === "string")
            return typeof b !== "string" || b.length != 1 ? -1 : a.indexOf(b, 0);
        for (var c = 0; c < a.length; c++)
            if (c in a && a[c] === b)
                return c;
        return -1
    }
    ;
    var xc = {}
      , yc = function(a) {
        this.j = a
    };
    yc.prototype.toString = function() {
        return this.j.toString()
    }
    ;
    function zc(a, b) {
        var c = [new vc];
        if (c.length === 0)
            throw Error("");
        var d = c.map(function(f) {
            var g;
            if (f instanceof vc)
                g = f.j;
            else
                throw Error("");
            return g
        })
          , e = b.toLowerCase();
        if (d.every(function(f) {
            return e.indexOf(f) !== 0
        }))
            throw Error('Attribute "' + b + '" does not match any of the allowed prefixes.');
        a.setAttribute(b, "true")
    }
    ;function Ac(a, b) {
        var c = tc(b);
        c !== void 0 && (a.action = c)
    }
    ;"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON", "INPUT"]);
    function Bc(a) {
        return a === null ? "null" : a === void 0 ? "undefined" : a
    }
    ;var G = window
      , H = document
      , Cc = navigator
      , Dc = function() {
        var a;
        try {
            a = Cc.serviceWorker
        } catch (b) {
            return
        }
        return a
    }
      , Ec = H.currentScript
      , Fc = Ec && Ec.src
      , Gc = function(a, b) {
        var c = G[a];
        G[a] = c === void 0 ? b : c;
        return G[a]
    };
    function Hc(a) {
        return (Cc.userAgent || "").indexOf(a) !== -1
    }
    var Ic = {
        async: 1,
        nonce: 1,
        onerror: 1,
        onload: 1,
        src: 1,
        type: 1
    }
      , Jc = {
        onload: 1,
        src: 1,
        width: 1,
        height: 1,
        style: 1
    };
    function Kc(a, b, c) {
        b && z(b, function(d, e) {
            d = d.toLowerCase();
            c.hasOwnProperty(d) || a.setAttribute(d, e)
        })
    }
    var Lc = function(a, b, c, d, e) {
        var f = H.createElement("script");
        Kc(f, d, Ic);
        f.type = "text/javascript";
        f.async = d && d.async === !1 ? !1 : !0;
        var g;
        g = fc(Bc(a));
        f.src = dc(g);
        var k, m, n, p = (n = (m = (f.ownerDocument && f.ownerDocument.defaultView || window).document).querySelector) == null ? void 0 : n.call(m, "script[nonce]");
        (k = p ? p.nonce || p.getAttribute("nonce") || "" : "") && f.setAttribute("nonce", k);
        b && (f.onload = b);
        c && (f.onerror = c);
        if (e)
            e.appendChild(f);
        else {
            var q = H.getElementsByTagName("script")[0] || H.body || H.head;
            q.parentNode.insertBefore(f, q)
        }
        return f
    }
      , Mc = function() {
        if (Fc) {
            var a = Fc.toLowerCase();
            if (a.indexOf("https://") === 0)
                return 2;
            if (a.indexOf("http://") === 0)
                return 3
        }
        return 1
    }
      , Nc = function(a, b, c, d, e) {
        var f;
        f = f === void 0 ? !0 : f;
        var g = e
          , k = !1;
        g || (g = H.createElement("iframe"),
        k = !0);
        Kc(g, c, Jc);
        d && z(d, function(n, p) {
            g.dataset[n] = p
        });
        f && (g.height = "0",
        g.width = "0",
        g.style.display = "none",
        g.style.visibility = "hidden");
        a !== void 0 && (g.src = a);
        if (k) {
            var m = H.body && H.body.lastChild || H.body || H.head;
            m.parentNode.insertBefore(g, m)
        }
        b && (g.onload = b);
        return g
    }
      , Oc = function(a, b, c, d) {
        var e = new Image(1,1);
        Kc(e, d, {});
        e.onload = function() {
            e.onload = null;
            b && b()
        }
        ;
        e.onerror = function() {
            e.onerror = null;
            c && c()
        }
        ;
        e.src = a;
        return e
    }
      , Pc = function(a, b, c, d) {
        a.addEventListener ? a.addEventListener(b, c, !!d) : a.attachEvent && a.attachEvent("on" + b, c)
    }
      , Qc = function(a, b, c) {
        a.removeEventListener ? a.removeEventListener(b, c, !1) : a.detachEvent && a.detachEvent("on" + b, c)
    }
      , I = function(a) {
        G.setTimeout(a, 0)
    }
      , Rc = function(a, b) {
        return a && b && a.attributes && a.attributes[b] ? a.attributes[b].value : null
    }
      , Sc = function(a) {
        function b(e) {
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && (e = e.replace(/(\xa0+|\s{2,}|\n|\r\t)/g, " "));
            return e
        }
        var c = b(a.innerText || a.textContent || "");
        if (zb(10)) {
            var d = b(a.textContent || "");
            ub("TAGGING", 26);
            d !== c && ub("TAGGING", 25)
        }
        return c
    }
      , Tc = function(a) {
        var b = H.createElement("div"), c = b, d, e = Bc("A<div>" + a + "</div>"), f = bc(), g = f ? f.createHTML(e) : e;
        d = new yc(g,xc);
        if (c.nodeType === 1) {
            var k = c.tagName;
            if (k === "SCRIPT" || k === "STYLE")
                throw Error("");
        }
        c.innerHTML = d instanceof yc && d.constructor === yc ? d.j : "type_error:SafeHtml";
        b = b.lastChild;
        for (var m = []; b.firstChild; )
            m.push(b.removeChild(b.firstChild));
        return m
    }
      , Uc = function(a, b, c) {
        c = c || 100;
        for (var d = {}, e = 0; e < b.length; e++)
            d[b[e]] = !0;
        for (var f = a, g = 0; f && g <= c; g++) {
            if (d[String(f.tagName).toLowerCase()])
                return f;
            f = f.parentElement
        }
        return null
    }
      , Vc = function(a) {
        var b;
        try {
            b = Cc.sendBeacon && Cc.sendBeacon(a)
        } catch (c) {
            ub("TAGGING", 15)
        }
        b || Oc(a)
    }
      , Wc = function(a, b) {
        try {
            return Cc.sendBeacon(a, b)
        } catch (c) {
            ub("TAGGING", 15)
        }
        return !1
    }
      , Xc = {
        cache: "no-store",
        credentials: "include",
        keepalive: !0,
        method: "POST",
        mode: "no-cors",
        redirect: "follow"
    }
      , Zc = function(a, b, c) {
        if (Yc()) {
            var d = Object.assign({}, Xc);
            b && (d.body = b);
            c && (c.attributionReporting && (d.attributionReporting = c.attributionReporting),
            c.browsingTopics && (d.browsingTopics = c.browsingTopics));
            try {
                var e = G.fetch(a, d);
                e && e.catch(Ab);
                return !0
            } catch (f) {}
        }
        if (c && c.noFallback)
            return !1;
        if (b)
            return Wc(a, b);
        Vc(a);
        return !0
    }
      , Yc = function() {
        return typeof G.fetch === "function"
    }
      , $c = function(a, b) {
        var c = a[b];
        c && typeof c.animVal === "string" && (c = c.animVal);
        return c
    }
      , ad = function() {
        var a = G.performance;
        if (a && Bb(a.now))
            return a.now()
    }
      , bd = function() {
        return G.performance || void 0
    };
    function cd(a, b) {
        return this.evaluate(a) && this.evaluate(b)
    }
    function dd(a, b) {
        return this.evaluate(a) === this.evaluate(b)
    }
    function ed(a, b) {
        return this.evaluate(a) || this.evaluate(b)
    }
    function fd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        return String(a).indexOf(String(b)) > -1
    }
    function gd(a, b) {
        var c = String(this.evaluate(a))
          , d = String(this.evaluate(b));
        return c.substring(0, d.length) === d
    }
    function hd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        switch (a) {
        case "pageLocation":
            var c = G.location.href;
            b instanceof lb && b.get("stripProtocol") && (c = c.replace(/^https?:\/\//, ""));
            return c
        }
    }
    ;var id = function(a, b) {
        $a.call(this);
        this.bk = a;
        this.uh = b
    };
    za(id, $a);
    ba = id.prototype;
    ba.toString = function() {
        return this.bk
    }
    ;
    ba.getName = function() {
        return this.bk
    }
    ;
    ba.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    ba.invoke = function(a) {
        return this.uh.apply(new jd(this,a), Array.prototype.slice.call(arguments, 1))
    }
    ;
    ba.ib = function(a) {
        try {
            return this.invoke.apply(this, Array.prototype.slice.call(arguments, 0))
        } catch (b) {}
    }
    ;
    var jd = function(a, b) {
        this.uh = a;
        this.F = b
    };
    jd.prototype.evaluate = function(a) {
        var b = this.F;
        return Array.isArray(a) ? Ya(b, a) : a
    }
    ;
    jd.prototype.getName = function() {
        return this.uh.getName()
    }
    ;
    jd.prototype.sd = function() {
        return this.F.sd()
    }
    ;
    var kd = function() {
        this.map = new Map
    };
    kd.prototype.set = function(a, b) {
        this.map.set(a, b)
    }
    ;
    kd.prototype.get = function(a) {
        return this.map.get(a)
    }
    ;
    var ld = function() {
        this.keys = [];
        this.values = []
    };
    ld.prototype.set = function(a, b) {
        this.keys.push(a);
        this.values.push(b)
    }
    ;
    ld.prototype.get = function(a) {
        var b = this.keys.indexOf(a);
        if (b > -1)
            return this.values[b]
    }
    ;
    function md() {
        try {
            return Map ? new kd : new ld
        } catch (a) {
            return new ld
        }
    }
    ;var nd = function(a) {
        if (a instanceof nd)
            return a;
        if (gb(a))
            throw Error("Type of given value has an equivalent Pixie type.");
        this.value = a
    };
    nd.prototype.getValue = function() {
        return this.value
    }
    ;
    nd.prototype.toString = function() {
        return String(this.value)
    }
    ;
    var pd = function(a) {
        $a.call(this);
        this.promise = a;
        this.set("then", od(this));
        this.set("catch", od(this, !0));
        this.set("finally", od(this, !1, !0))
    };
    za(pd, lb);
    var od = function(a, b, c) {
        b = b === void 0 ? !1 : b;
        c = c === void 0 ? !1 : c;
        return new id("",function(d, e) {
            b && (e = d,
            d = void 0);
            c && (e = d);
            d instanceof id || (d = void 0);
            e instanceof id || (e = void 0);
            var f = Wa(this.F)
              , g = function(m) {
                return function(n) {
                    return c ? (m.invoke(f),
                    a.promise) : m.invoke(f, n)
                }
            }
              , k = a.promise.then(d && g(d), e && g(e));
            return new pd(k)
        }
        )
    };
    function J(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m = ab(g, 1), n = 0; n < m.length; n++)
                k[m[n]] = f(g.get(m[n]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (g instanceof ib) {
                var m = [];
                d.set(g, m);
                for (var n = g.Qb(), p = 0; p < n.length(); p++)
                    m[n.get(p)] = f(g.get(n.get(p)));
                return m
            }
            if (g instanceof pd)
                return g.promise;
            if (g instanceof lb) {
                var q = {};
                d.set(g, q);
                e(g, q);
                return q
            }
            if (g instanceof id) {
                var r = function() {
                    for (var u = Array.prototype.slice.call(arguments, 0), v = 0; v < u.length; v++)
                        u[v] = qd(u[v], b, c);
                    var w = new Ua(b ? b.sd() : new Ta);
                    b && (w.j = b.j);
                    return f(g.invoke.apply(g, [w].concat(u)))
                };
                d.set(g, r);
                e(g, r);
                return r
            }
            var t = !1;
            switch (c) {
            case 1:
                t = !0;
                break;
            case 2:
                t = !1;
                break;
            case 3:
                t = !1;
                break;
            default:
            }
            if (g instanceof nd && t)
                return g.getValue();
            switch (typeof g) {
            case "boolean":
            case "number":
            case "string":
            case "undefined":
                return g;
            case "object":
                if (g === null)
                    return null
            }
        };
        return f(a)
    }
    function qd(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m in g)
                g.hasOwnProperty(m) && k.set(m, f(g[m]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (Array.isArray(g) || Ib(g)) {
                var m = new ib([]);
                d.set(g, m);
                for (var n in g)
                    g.hasOwnProperty(n) && m.set(n, f(g[n]));
                return m
            }
            if (fb(g)) {
                var p = new lb;
                d.set(g, p);
                e(g, p);
                return p
            }
            if (typeof g === "function") {
                var q = new id("",function() {
                    for (var x = Array.prototype.slice.call(arguments, 0), y = 0; y < x.length; y++)
                        x[y] = J(this.evaluate(x[y]), b, c);
                    return f((0,
                    this.F.H)(g, g, x))
                }
                );
                d.set(g, q);
                e(g, q);
                return q
            }
            var v = typeof g;
            if (g === null || v === "string" || v === "number" || v === "boolean")
                return g;
            var w = !1;
            switch (c) {
            case 1:
                w = !0;
                break;
            case 2:
                w = !1;
                break;
            default:
            }
            if (g !== void 0 && w)
                return new nd(g)
        };
        return f(a)
    }
    ;function rd() {
        var a = !1;
        return a
    }
    ;var sd = {
        supportedMethods: "concat every filter forEach hasOwnProperty indexOf join lastIndexOf map pop push reduce reduceRight reverse shift slice some sort splice unshift toString".split(" "),
        concat: function(a) {
            for (var b = [], c = 0; c < this.length(); c++)
                b.push(this.get(c));
            for (var d = 1; d < arguments.length; d++)
                if (arguments[d]instanceof ib)
                    for (var e = arguments[d], f = 0; f < e.length(); f++)
                        b.push(e.get(f));
                else
                    b.push(arguments[d]);
            return new ib(b)
        },
        every: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                if (this.has(d) && !b.invoke(a, this.get(d), d, this))
                    return !1;
            return !0
        },
        filter: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && b.invoke(a, this.get(e), e, this) && d.push(this.get(e));
            return new ib(d)
        },
        forEach: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                this.has(d) && b.invoke(a, this.get(d), d, this)
        },
        hasOwnProperty: function(a, b) {
            return this.has(b)
        },
        indexOf: function(a, b, c) {
            var d = this.length()
              , e = c === void 0 ? 0 : Number(c);
            e < 0 && (e = Math.max(d + e, 0));
            for (var f = e; f < d; f++)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        join: function(a, b) {
            for (var c = [], d = 0; d < this.length(); d++)
                c.push(this.get(d));
            return c.join(b)
        },
        lastIndexOf: function(a, b, c) {
            var d = this.length()
              , e = d - 1;
            c !== void 0 && (e = c < 0 ? d + c : Math.min(c, e));
            for (var f = e; f >= 0; f--)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        map: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && (d[e] = b.invoke(a, this.get(e), e, this));
            return new ib(d)
        },
        pop: function() {
            return this.pop()
        },
        push: function(a) {
            return this.push.apply(this, Array.prototype.slice.call(arguments, 1))
        },
        reduce: function(a, b, c) {
            var d = this.length(), e, f = 0;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: Reduce on List with no elements.");
                for (var g = 0; g < d; g++)
                    if (this.has(g)) {
                        e = this.get(g);
                        f = g + 1;
                        break
                    }
                if (g === d)
                    throw Error("TypeError: Reduce on List with no elements.");
            }
            for (var k = f; k < d; k++)
                this.has(k) && (e = b.invoke(a, e, this.get(k), k, this));
            return e
        },
        reduceRight: function(a, b, c) {
            var d = this.length(), e, f = d - 1;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: ReduceRight on List with no elements.");
                for (var g = 1; g <= d; g++)
                    if (this.has(d - g)) {
                        e = this.get(d - g);
                        f = d - (g + 1);
                        break
                    }
                if (g > d)
               Ua.prototype.Ma = function() {
        this.K = !0
    }
    ;
    function Xa(a, b) {
        for (var c, d = 0; d < b.length && !(c = Ya(a, b[d]),
        c instanceof Qa); d++)
            ;
        return c
    }
    function Ya(a, b) {
        try {
            var c = a.get(String(b[0]));
            if (!c || typeof c.invoke !== "function")
                throw Error("Attempting to execute non-function " + b[0] + ".");
            return c.invoke.apply(c, [a].concat(b.slice(1)))
        } catch (e) {
            var d = a.D;
            d && d(e, b.context ? {
                id: b[0],
                line: b.context.line
            } : null);
            throw e;
        }
    }
    ;var Za = function() {
        this.D = new Ta;
        this.j = new Ua(this.D)
    };
    ba = Za.prototype;
    ba.sd = function() {
        return this.D
    }
    ;
    ba.execute = function(a) {
        var b = Array.prototype.slice.call(arguments, 0);
        return this.Xh(b)
    }
    ;
    ba.Xh = function() {
        for (var a, b = 0; b < arguments.length; b++)
            a = Ya(this.j, arguments[b]);
        return a
    }
    ;
    ba.Xk = function(a) {
        var b = Wa(this.j);
        b.j = a;
        for (var c, d = 1; d < arguments.length; d++)
            c = Ya(b, arguments[d]);
        return c
    }
    ;
    ba.Ma = function() {
        this.j.Ma()
    }
    ;
    var $a = function() {
        Ra.call(this);
        this.D = !1
    };
    za($a, Ra);
    var ab = function(a, b) {
        var c = [], d;
        for (d in a.j)
            if (a.j.hasOwnProperty(d))
                switch (d = d.substr(5),
                b) {
                case 1:
                    c.push(d);
                    break;
                case 2:
                    c.push(a.get(d));
                    break;
                case 3:
                    c.push([d, a.get(d)])
                }
        return c
    };
    $a.prototype.set = function(a, b) {
        this.D || Ra.prototype.set.call(this, a, b)
    }
    ;
    $a.prototype.Zh = function(a, b) {
        this.D || Ra.prototype.Zh.call(this, a, b)
    }
    ;
    $a.prototype.Hf = function(a) {
        this.D || Ra.prototype.Hf.call(this, a)
    }
    ;
    $a.prototype.Ma = function() {
        this.D = !0
    }
    ;
    /*
 jQuery (c) 2005, 2012 jQuery Foundation, Inc. jquery.org/license.
*/
    var cb = /\[object (Boolean|Number|String|Function|Array|Date|RegExp)\]/
      , db = function(a) {
        if (a == null)
            return String(a);
        var b = cb.exec(Object.prototype.toString.call(Object(a)));
        return b ? b[1].toLowerCase() : "object"
    }
      , eb = function(a, b) {
        return Object.prototype.hasOwnProperty.call(Object(a), b)
    }
      , fb = function(a) {
        if (!a || db(a) != "object" || a.nodeType || a == a.window)
            return !1;
        try {
            if (a.constructor && !eb(a, "constructor") && !eb(a.constructor.prototype, "isPrototypeOf"))
                return !1
        } catch (c) {
            return !1
        }
        for (var b in a)
            ;
        return b === void 0 || eb(a, b)
    }
      , h = function(a, b) {
        var c = b || (db(a) == "array" ? [] : {}), d;
        for (d in a)
            if (eb(a, d)) {
                var e = a[d];
                db(e) == "array" ? (db(c[d]) != "array" && (c[d] = []),
                c[d] = h(e, c[d])) : fb(e) ? (fb(c[d]) || (c[d] = {}),
                c[d] = h(e, c[d])) : c[d] = e
            }
        return c
    };
    function gb(a) {
        if (a == void 0 || Array.isArray(a) || fb(a))
            return !0;
        switch (typeof a) {
        case "boolean":
        case "number":
        case "string":
        case "function":
            return !0
        }
        return !1
    }
    function hb(a) {
        return typeof a === "number" && a >= 0 && isFinite(a) && a % 1 === 0 || typeof a === "string" && a[0] !== "-" && a === "" + parseInt(a)
    }
    ;var ib = function(a) {
        this.j = [];
        this.H = !1;
        this.D = new $a;
        a = a || [];
        for (var b in a)
            a.hasOwnProperty(b) && (hb(b) ? this.j[Number(b)] = a[Number(b)] : this.D.set(b, a[b]))
    };
    ba = ib.prototype;
    ba.toString = function(a) {
        if (a && a.indexOf(this) >= 0)
            return "";
        for (var b = [], c = 0; c < this.j.length; c++) {
            var d = this.j[c];
            d === null || d === void 0 ? b.push("") : d instanceof ib ? (a = a || [],
            a.push(this),
            b.push(d.toString(a)),
            a.pop()) : b.push(String(d))
        }
        return b.join(",")
    }
    ;
    ba.set = function(a, b) {
        if (!this.H)
            if (a === "length") {
                if (!hb(b))
                    throw Error("RangeError: Length property must be a valid integer.");
                this.j.length = Number(b)
            } else
                hb(a) ? this.j[Number(a)] = b : this.D.set(a, b)
    }
    ;
    ba.get = function(a) {
        return a === "length" ? this.length() : hb(a) ? this.j[Number(a)] : this.D.get(a)
    }
    ;
    ba.length = function() {
        return this.j.length
    }
    ;
    ba.Qb = function() {
        for (var a = ab(this.D, 1), b = 0; b < this.j.length; b++)
            a.push(b + "");
        return new ib(a)
    }
    ;
    var jb = function(a, b) {
        hb(b) ? delete a.j[Number(b)] : a.D.Hf(b)
    };
    ba = ib.prototype;
    ba.pop = function() {
        return this.j.pop()
    }
    ;
    ba.push = function() {
        return this.j.push.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.shift = function() {
        return this.j.shift()
    }
    ;
    ba.splice = function(a, b) {
        return new ib(this.j.splice.apply(this.j, arguments))
    }
    ;
    ba.unshift = function() {
        return this.j.unshift.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.has = function(a) {
        return hb(a) && this.j.hasOwnProperty(a) || this.D.has(a)
    }
    ;
    ba.Ma = function() {
        this.H = !0;
        Object.freeze(this.j);
        this.D.Ma()
    }
    ;
    function kb(a) {
        for (var b = [], c = 0; c < a.length(); c++)
            a.has(c) && (b[c] = a.get(c));
        return b
    }
    ;var lb = function() {
        $a.call(this)
    };
    za(lb, $a);
    lb.prototype.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    var mb = function(a) {
        for (var b = ab(a, 3), c = new ib, d = 0; d < b.length; d++) {
            var e = new ib(b[d]);
            c.push(e)
        }
        return c
    };
    function nb() {
        for (var a = ob, b = {}, c = 0; c < a.length; ++c)
            b[a[c]] = c;
        return b
    }
    function pb() {
        var a = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
        a += a.toLowerCase() + "0123456789-_";
        return a + "."
    }
    var ob, qb;
    function rb(a) {
        ob = ob || pb();
        qb = qb || nb();
        for (var b = [], c = 0; c < a.length; c += 3) {
            var d = c + 1 < a.length
              , e = c + 2 < a.length
              , f = a.charCodeAt(c)
              , g = d ? a.charCodeAt(c + 1) : 0
              , k = e ? a.charCodeAt(c + 2) : 0
              , m = f >> 2
              , n = (f & 3) << 4 | g >> 4
              , p = (g & 15) << 2 | k >> 6
              , q = k & 63;
            e || (q = 64,
            d || (p = 64));
            b.push(ob[m], ob[n], ob[p], ob[q])
        }
        return b.join("")
    }
    function sb(a) {
        function b(m) {
            for (; d < a.length; ) {
                var n = a.charAt(d++)
                  , p = qb[n];
                if (p != null)
                    return p;
                if (!/^[\s\xa0]*$/.test(n))
                    throw Error("Unknown base64 encoding at char: " + n);
            }
            return m
        }
        ob = ob || pb();
        qb = qb || nb();
        for (var c = "", d = 0; ; ) {
            var e = b(-1)
              , f = b(0)
              , g = b(64)
              , k = b(64);
            if (k === 64 && e === -1)
                return c;
            c += String.fromCharCode(e << 2 | f >> 4);
            g !== 64 && (c += String.fromCharCode(f << 4 & 240 | g >> 2),
            k !== 64 && (c += String.fromCharCode(g << 6 & 192 | k)))
        }
    }
    ;var tb = {};
    function ub(a, b) {
        tb[a] = tb[a] || [];
        tb[a][b] = !0
    }
    function vb(a) {
        var b = tb[a];
        if (!b || b.length === 0)
            return "";
        for (var c = [], d = 0, e = 0; e < b.length; e++)
            e % 8 === 0 && e > 0 && (c.push(String.fromCharCode(d)),
            d = 0),
            b[e] && (d |= 1 << e % 8);
        d > 0 && c.push(String.fromCharCode(d));
        return rb(c.join("")).replace(/\.+$/, "")
    }
    function wb() {
        for (var a = [], b = tb.fdr || [], c = 0; c < b.length; c++)
            b[c] && a.push(c);
        return a.length > 0 ? a : void 0
    }
    ;var xb = []
      , yb = {};
    function zb(a) {
        return xb[a] === void 0 ? !1 : xb[a]
    }
    ;function Ab() {}
    function Bb(a) {
        return typeof a === "function"
    }
    function l(a) {
        return typeof a === "string"
    }
    function Cb(a) {
        return typeof a === "number" && !isNaN(a)
    }
    function Db(a) {
        return Array.isArray(a) ? a : [a]
    }
    function Eb(a, b) {
        if (a && Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                if (a[c] && b(a[c]))
                    return a[c]
    }
    function Fb(a, b) {
        if (!Cb(a) || !Cb(b) || a > b)
            a = 0,
            b = 2147483647;
        return Math.floor(Math.random() * (b - a + 1) + a)
    }
    function Gb(a, b) {
        for (var c = new Hb, d = 0; d < a.length; d++)
            c.set(a[d], !0);
        for (var e = 0; e < b.length; e++)
            if (c.get(b[e]))
                return !0;
        return !1
    }
    function z(a, b) {
        for (var c in a)
            Object.prototype.hasOwnProperty.call(a, c) && b(c, a[c])
    }
    function Ib(a) {
        return !!a && (Object.prototype.toString.call(a) === "[object Arguments]" || Object.prototype.hasOwnProperty.call(a, "callee"))
    }
    function Jb(a) {
        return Math.round(Number(a)) || 0
    }
    function Kb(a) {
        return "false" === String(a).toLowerCase() ? !1 : !!a
    }
    function Lb(a) {
        var b = [];
        if (Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                b.push(String(a[c]));
        return b
    }
    function Mb(a) {
        return a ? a.replace(/^\s+|\s+$/g, "") : ""
    }
    function Nb() {
        return new Date(Date.now())
    }
    function Ob() {
        return Nb().getTime()
    }
    var Hb = function() {
        this.prefix = "gtm.";
        this.values = {}
    };
    Hb.prototype.set = function(a, b) {
        this.values[this.prefix + a] = b
    }
    ;
    Hb.prototype.get = function(a) {
        return this.values[this.prefix + a]
    }
    ;
    function Pb(a, b, c) {
        return a && a.hasOwnProperty(b) ? a[b] : c
    }
    function Qb(a) {
        var b = a;
        return function() {
            if (b) {
                var c = b;
                b = void 0;
                try {
                    c()
                } catch (d) {}
            }
        }
    }
    function Rb(a, b) {
        for (var c in b)
            b.hasOwnProperty(c) && (a[c] = b[c])
    }
    function Sb(a, b) {
        for (var c = [], d = 0; d < a.length; d++)
            c.push(a[d]),
            c.push.apply(c, b[a[d]] || []);
        return c
    }
    function Tb(a, b) {
        return a.length >= b.length && a.substring(0, b.length) === b
    }
    function Ub(a, b) {
        return a.length >= b.length && a.substring(a.length - b.length, a.length) === b
    }
    function Vb(a, b) {
        var c = G;
        b = b || [];
        for (var d = c, e = 0; e < a.length - 1; e++) {
            if (!d.hasOwnProperty(a[e]))
                return;
            d = d[a[e]];
            if (b.indexOf(d) >= 0)
                return
        }
        return d
    }
    function Wb(a, b) {
        for (var c = {}, d = c, e = a.split("."), f = 0; f < e.length - 1; f++)
            d = d[e[f]] = {};
        d[e[e.length - 1]] = b;
        return c
    }
    var Xb = /^\w{1,9}$/;
    function Yb(a, b) {
        a = a || {};
        b = b || ",";
        var c = [];
        z(a, function(d, e) {
            Xb.test(d) && e && c.push(d)
        });
        return c.join(b)
    }
    function Zb(a, b) {
        function c() {
            e && ++d === b && (e(),
            e = null,
            c.done = !0)
        }
        var d = 0
          , e = a;
        c.done = !1;
        return c
    }
    function $b(a) {
        if (!a)
            return a;
        var b = a;
        if (zb(3))
            try {
                b = decodeURIComponent(a)
            } catch (d) {}
        var c = b.split(",");
        return c.length === 2 && c[0] === c[1] ? c[0] : a
    }
    ;var ac, bc = function() {
        if (ac === void 0) {
            var a = null
              , b = Oa.trustedTypes;
            if (b && b.createPolicy) {
                try {
                    a = b.createPolicy("goog#html", {
                        createHTML: Pa,
                        createScript: Pa,
                        createScriptURL: Pa
                    })
                } catch (c) {
                    Oa.console && Oa.console.error(c.message)
                }
                ac = a
            } else
                ac = a
        }
        return ac
    };
    var cc = function(a) {
        this.j = a
    };
    cc.prototype.toString = function() {
        return this.j + ""
    }
    ;
    var dc = function(a) {
        return a instanceof cc && a.constructor === cc ? a.j : "type_error:TrustedResourceUrl"
    }
      , ec = {}
      , fc = function(a) {
        var b = a
          , c = bc()
          , d = c ? c.createScriptURL(b) : b;
        return new cc(d,ec)
    };
    /*

 SPDX-License-Identifier: Apache-2.0
*/
    var gc = ka([""])
      , hc = na(["\x00"], ["\\0"])
      , ic = na(["\n"], ["\\n"])
      , jc = na(["\x00"], ["\\u0000"]);
    function kc(a) {
        return a.toString().indexOf("`") === -1
    }
    kc(function(a) {
        return a(gc)
    }) || kc(function(a) {
        return a(hc)
    }) || kc(function(a) {
        return a(ic)
    }) || kc(function(a) {
        return a(jc)
    });
    var lc = function(a) {
        this.j = a
    };
    lc.prototype.toString = function() {
        return this.j
    }
    ;
    var mc = new lc("about:invalid#zClosurez");
    var nc = function(a) {
        this.wm = a
    };
    function oc(a) {
        return new nc(function(b) {
            return b.substr(0, a.length + 1).toLowerCase() === a + ":"
        }
        )
    }
    var pc = [oc("data"), oc("http"), oc("https"), oc("mailto"), oc("ftp"), new nc(function(a) {
        return /^[^:]*([/?#]|$)/.test(a)
    }
    )];
    function qc(a, b) {
        b = b === void 0 ? pc : b;
        if (a instanceof lc)
            return a;
        for (var c = 0; c < b.length; ++c) {
            var d = b[c];
            if (d instanceof nc && d.wm(a))
                return new lc(a)
        }
    }
    function rc(a) {
        var b;
        b = b === void 0 ? pc : b;
        return qc(a, b) || mc
    }
    var sc = /^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
    function tc(a) {
        var b;
        if (a instanceof lc)
            if (a instanceof lc)
                b = a.j;
            else
                throw Error("");
        else
            b = sc.test(a) ? a : void 0;
        return b
    }
    ;var vc = function() {
        this.j = uc[0].toLowerCase()
    };
    vc.prototype.toString = function() {
        return this.j
    }
    ;
    var wc = Array.prototype.indexOf ? function(a, b) {
        return Array.prototype.indexOf.call(a, b, void 0)
    }
    : function(a, b) {
        if (typeof a === "string")
            return typeof b !== "string" || b.length != 1 ? -1 : a.indexOf(b, 0);
        for (var c = 0; c < a.length; c++)
            if (c in a && a[c] === b)
                return c;
        return -1
    }
    ;
    var xc = {}
      , yc = function(a) {
        this.j = a
    };
    yc.prototype.toString = function() {
        return this.j.toString()
    }
    ;
    function zc(a, b) {
        var c = [new vc];
        if (c.length === 0)
            throw Error("");
        var d = c.map(function(f) {
            var g;
            if (f instanceof vc)
                g = f.j;
            else
                throw Error("");
            return g
        })
          , e = b.toLowerCase();
        if (d.every(function(f) {
            return e.indexOf(f) !== 0
        }))
            throw Error('Attribute "' + b + '" does not match any of the allowed prefixes.');
        a.setAttribute(b, "true")
    }
    ;function Ac(a, b) {
        var c = tc(b);
        c !== void 0 && (a.action = c)
    }
    ;"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON", "INPUT"]);
    function Bc(a) {
        return a === null ? "null" : a === void 0 ? "undefined" : a
    }
    ;var G = window
      , H = document
      , Cc = navigator
      , Dc = function() {
        var a;
        try {
            a = Cc.serviceWorker
        } catch (b) {
            return
        }
        return a
    }
      , Ec = H.currentScript
      , Fc = Ec && Ec.src
      , Gc = function(a, b) {
        var c = G[a];
        G[a] = c === void 0 ? b : c;
        return G[a]
    };
    function Hc(a) {
        return (Cc.userAgent || "").indexOf(a) !== -1
    }
    var Ic = {
        async: 1,
        nonce: 1,
        onerror: 1,
        onload: 1,
        src: 1,
        type: 1
    }
      , Jc = {
        onload: 1,
        src: 1,
        width: 1,
        height: 1,
        style: 1
    };
    function Kc(a, b, c) {
        b && z(b, function(d, e) {
            d = d.toLowerCase();
            c.hasOwnProperty(d) || a.setAttribute(d, e)
        })
    }
    var Lc = function(a, b, c, d, e) {
        var f = H.createElement("script");
        Kc(f, d, Ic);
        f.type = "text/javascript";
        f.async = d && d.async === !1 ? !1 : !0;
        var g;
        g = fc(Bc(a));
        f.src = dc(g);
        var k, m, n, p = (n = (m = (f.ownerDocument && f.ownerDocument.defaultView || window).document).querySelector) == null ? void 0 : n.call(m, "script[nonce]");
        (k = p ? p.nonce || p.getAttribute("nonce") || "" : "") && f.setAttribute("nonce", k);
        b && (f.onload = b);
        c && (f.onerror = c);
        if (e)
            e.appendChild(f);
        else {
            var q = H.getElementsByTagName("script")[0] || H.body || H.head;
            q.parentNode.insertBefore(f, q)
        }
        return f
    }
      , Mc = function() {
        if (Fc) {
            var a = Fc.toLowerCase();
            if (a.indexOf("https://") === 0)
                return 2;
            if (a.indexOf("http://") === 0)
                return 3
        }
        return 1
    }
      , Nc = function(a, b, c, d, e) {
        var f;
        f = f === void 0 ? !0 : f;
        var g = e
          , k = !1;
        g || (g = H.createElement("iframe"),
        k = !0);
        Kc(g, c, Jc);
        d && z(d, function(n, p) {
            g.dataset[n] = p
        });
        f && (g.height = "0",
        g.width = "0",
        g.style.display = "none",
        g.style.visibility = "hidden");
        a !== void 0 && (g.src = a);
        if (k) {
            var m = H.body && H.body.lastChild || H.body || H.head;
            m.parentNode.insertBefore(g, m)
        }
        b && (g.onload = b);
        return g
    }
      , Oc = function(a, b, c, d) {
        var e = new Image(1,1);
        Kc(e, d, {});
        e.onload = function() {
            e.onload = null;
            b && b()
        }
        ;
        e.onerror = function() {
            e.onerror = null;
            c && c()
        }
        ;
        e.src = a;
        return e
    }
      , Pc = function(a, b, c, d) {
        a.addEventListener ? a.addEventListener(b, c, !!d) : a.attachEvent && a.attachEvent("on" + b, c)
    }
      , Qc = function(a, b, c) {
        a.removeEventListener ? a.removeEventListener(b, c, !1) : a.detachEvent && a.detachEvent("on" + b, c)
    }
      , I = function(a) {
        G.setTimeout(a, 0)
    }
      , Rc = function(a, b) {
        return a && b && a.attributes && a.attributes[b] ? a.attributes[b].value : null
    }
      , Sc = function(a) {
        function b(e) {
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && (e = e.replace(/(\xa0+|\s{2,}|\n|\r\t)/g, " "));
            return e
        }
        var c = b(a.innerText || a.textContent || "");
        if (zb(10)) {
            var d = b(a.textContent || "");
            ub("TAGGING", 26);
            d !== c && ub("TAGGING", 25)
        }
        return c
    }
      , Tc = function(a) {
        var b = H.createElement("div"), c = b, d, e = Bc("A<div>" + a + "</div>"), f = bc(), g = f ? f.createHTML(e) : e;
        d = new yc(g,xc);
        if (c.nodeType === 1) {
            var k = c.tagName;
            if (k === "SCRIPT" || k === "STYLE")
                throw Error("");
        }
        c.innerHTML = d instanceof yc && d.constructor === yc ? d.j : "type_error:SafeHtml";
        b = b.lastChild;
        for (var m = []; b.firstChild; )
            m.push(b.removeChild(b.firstChild));
        return m
    }
      , Uc = function(a, b, c) {
        c = c || 100;
        for (var d = {}, e = 0; e < b.length; e++)
            d[b[e]] = !0;
        for (var f = a, g = 0; f && g <= c; g++) {
            if (d[String(f.tagName).toLowerCase()])
                return f;
            f = f.parentElement
        }
        return null
    }
      , Vc = function(a) {
        var b;
        try {
            b = Cc.sendBeacon && Cc.sendBeacon(a)
        } catch (c) {
            ub("TAGGING", 15)
        }
        b || Oc(a)
    }
      , Wc = function(a, b) {
        try {
            return Cc.sendBeacon(a, b)
        } catch (c) {
            ub("TAGGING", 15)
        }
        return !1
    }
      , Xc = {
        cache: "no-store",
        credentials: "include",
        keepalive: !0,
        method: "POST",
        mode: "no-cors",
        redirect: "follow"
    }
      , Zc = function(a, b, c) {
        if (Yc()) {
            var d = Object.assign({}, Xc);
            b && (d.body = b);
            c && (c.attributionReporting && (d.attributionReporting = c.attributionReporting),
            c.browsingTopics && (d.browsingTopics = c.browsingTopics));
            try {
                var e = G.fetch(a, d);
                e && e.catch(Ab);
                return !0
            } catch (f) {}
        }
        if (c && c.noFallback)
            return !1;
        if (b)
            return Wc(a, b);
        Vc(a);
        return !0
    }
      , Yc = function() {
        return typeof G.fetch === "function"
    }
      , $c = function(a, b) {
        var c = a[b];
        c && typeof c.animVal === "string" && (c = c.animVal);
        return c
    }
      , ad = function() {
        var a = G.performance;
        if (a && Bb(a.now))
            return a.now()
    }
      , bd = function() {
        return G.performance || void 0
    };
    function cd(a, b) {
        return this.evaluate(a) && this.evaluate(b)
    }
    function dd(a, b) {
        return this.evaluate(a) === this.evaluate(b)
    }
    function ed(a, b) {
        return this.evaluate(a) || this.evaluate(b)
    }
    function fd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        return String(a).indexOf(String(b)) > -1
    }
    function gd(a, b) {
        var c = String(this.evaluate(a))
          , d = String(this.evaluate(b));
        return c.substring(0, d.length) === d
    }
    function hd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        switch (a) {
        case "pageLocation":
            var c = G.location.href;
            b instanceof lb && b.get("stripProtocol") && (c = c.replace(/^https?:\/\//, ""));
            return c
        }
    }
    ;var id = function(a, b) {
        $a.call(this);
        this.bk = a;
        this.uh = b
    };
    za(id, $a);
    ba = id.prototype;
    ba.toString = function() {
        return this.bk
    }
    ;
    ba.getName = function() {
        return this.bk
    }
    ;
    ba.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    ba.invoke = function(a) {
        return this.uh.apply(new jd(this,a), Array.prototype.slice.call(arguments, 1))
    }
    ;
    ba.ib = function(a) {
        try {
            return this.invoke.apply(this, Array.prototype.slice.call(arguments, 0))
        } catch (b) {}
    }
    ;
    var jd = function(a, b) {
        this.uh = a;
        this.F = b
    };
    jd.prototype.evaluate = function(a) {
        var b = this.F;
        return Array.isArray(a) ? Ya(b, a) : a
    }
    ;
    jd.prototype.getName = function() {
        return this.uh.getName()
    }
    ;
    jd.prototype.sd = function() {
        return this.F.sd()
    }
    ;
    var kd = function() {
        this.map = new Map
    };
    kd.prototype.set = function(a, b) {
        this.map.set(a, b)
    }
    ;
    kd.prototype.get = function(a) {
        return this.map.get(a)
    }
    ;
    var ld = function() {
        this.keys = [];
        this.values = []
    };
    ld.prototype.set = function(a, b) {
        this.keys.push(a);
        this.values.push(b)
    }
    ;
    ld.prototype.get = function(a) {
        var b = this.keys.indexOf(a);
        if (b > -1)
            return this.values[b]
    }
    ;
    function md() {
        try {
            return Map ? new kd : new ld
        } catch (a) {
            return new ld
        }
    }
    ;var nd = function(a) {
        if (a instanceof nd)
            return a;
        if (gb(a))
            throw Error("Type of given value has an equivalent Pixie type.");
        this.value = a
    };
    nd.prototype.getValue = function() {
        return this.value
    }
    ;
    nd.prototype.toString = function() {
        return String(this.value)
    }
    ;
    var pd = function(a) {
        $a.call(this);
        this.promise = a;
        this.set("then", od(this));
        this.set("catch", od(this, !0));
        this.set("finally", od(this, !1, !0))
    };
    za(pd, lb);
    var od = function(a, b, c) {
        b = b === void 0 ? !1 : b;
        c = c === void 0 ? !1 : c;
        return new id("",function(d, e) {
            b && (e = d,
            d = void 0);
            c && (e = d);
            d instanceof id || (d = void 0);
            e instanceof id || (e = void 0);
            var f = Wa(this.F)
              , g = function(m) {
                return function(n) {
                    return c ? (m.invoke(f),
                    a.promise) : m.invoke(f, n)
                }
            }
              , k = a.promise.then(d && g(d), e && g(e));
            return new pd(k)
        }
        )
    };
    function J(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m = ab(g, 1), n = 0; n < m.length; n++)
                k[m[n]] = f(g.get(m[n]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (g instanceof ib) {
                var m = [];
                d.set(g, m);
                for (var n = g.Qb(), p = 0; p < n.length(); p++)
                    m[n.get(p)] = f(g.get(n.get(p)));
                return m
            }
            if (g instanceof pd)
                return g.promise;
            if (g instanceof lb) {
                var q = {};
                d.set(g, q);
                e(g, q);
                return q
            }
            if (g instanceof id) {
                var r = function() {
                    for (var u = Array.prototype.slice.call(arguments, 0), v = 0; v < u.length; v++)
                        u[v] = qd(u[v], b, c);
                    var w = new Ua(b ? b.sd() : new Ta);
                    b && (w.j = b.j);
                    return f(g.invoke.apply(g, [w].concat(u)))
                };
                d.set(g, r);
                e(g, r);
                return r
            }
            var t = !1;
            switch (c) {
            case 1:
                t = !0;
                break;
            case 2:
                t = !1;
                break;
            case 3:
                t = !1;
                break;
            default:
            }
            if (g instanceof nd && t)
                return g.getValue();
            switch (typeof g) {
            case "boolean":
            case "number":
            case "string":
            case "undefined":
                return g;
            case "object":
                if (g === null)
                    return null
            }
        };
        return f(a)
    }
    function qd(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m in g)
                g.hasOwnProperty(m) && k.set(m, f(g[m]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (Array.isArray(g) || Ib(g)) {
                var m = new ib([]);
                d.set(g, m);
                for (var n in g)
                    g.hasOwnProperty(n) && m.set(n, f(g[n]));
                return m
            }
            if (fb(g)) {
                var p = new lb;
                d.set(g, p);
                e(g, p);
                return p
            }
            if (typeof g === "function") {
                var q = new id("",function() {
                    for (var x = Array.prototype.slice.call(arguments, 0), y = 0; y < x.length; y++)
                        x[y] = J(this.evaluate(x[y]), b, c);
                    return f((0,
                    this.F.H)(g, g, x))
                }
                );
                d.set(g, q);
                e(g, q);
                return q
            }
            var v = typeof g;
            if (g === null || v === "string" || v === "number" || v === "boolean")
                return g;
            var w = !1;
            switch (c) {
            case 1:
                w = !0;
                break;
            case 2:
                w = !1;
                break;
            default:
            }
            if (g !== void 0 && w)
                return new nd(g)
        };
        return f(a)
    }
    ;function rd() {
        var a = !1;
        return a
    }
    ;var sd = {
        supportedMethods: "concat every filter forEach hasOwnProperty indexOf join lastIndexOf map pop push reduce reduceRight reverse shift slice some sort splice unshift toString".split(" "),
        concat: function(a) {
            for (var b = [], c = 0; c < this.length(); c++)
                b.push(this.get(c));
            for (var d = 1; d < arguments.length; d++)
                if (arguments[d]instanceof ib)
                    for (var e = arguments[d], f = 0; f < e.length(); f++)
                        b.push(e.get(f));
                else
                    b.push(arguments[d]);
            return new ib(b)
        },
        every: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                if (this.has(d) && !b.invoke(a, this.get(d), d, this))
                    return !1;
            return !0
        },
        filter: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && b.invoke(a, this.get(e), e, this) && d.push(this.get(e));
            return new ib(d)
        },
        forEach: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                this.has(d) && b.invoke(a, this.get(d), d, this)
        },
        hasOwnProperty: function(a, b) {
            return this.has(b)
        },
        indexOf: function(a, b, c) {
            var d = this.length()
              , e = c === void 0 ? 0 : Number(c);
            e < 0 && (e = Math.max(d + e, 0));
            for (var f = e; f < d; f++)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        join: function(a, b) {
            for (var c = [], d = 0; d < this.length(); d++)
                c.push(this.get(d));
            return c.join(b)
        },
        lastIndexOf: function(a, b, c) {
            var d = this.length()
              , e = d - 1;
            c !== void 0 && (e = c < 0 ? d + c : Math.min(c, e));
            for (var f = e; f >= 0; f--)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        map: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && (d[e] = b.invoke(a, this.get(e), e, this));
            return new ib(d)
        },
        pop: function() {
            return this.pop()
        },
        push: function(a) {
            return this.push.apply(this, Array.prototype.slice.call(arguments, 1))
        },
        reduce: function(a, b, c) {
            var d = this.length(), e, f = 0;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: Reduce on List with no elements.");
                for (var g = 0; g < d; g++)
                    if (this.has(g)) {
                        e = this.get(g);
                        f = g + 1;
                        break
                    }
                if (g === d)
                    throw Error("TypeError: Reduce on List with no elements.");
            }
            for (var k = f; k < d; k++)
                this.has(k) && (e = b.invoke(a, e, this.get(k), k, this));
            return e
        },
        reduceRight: function(a, b, c) {
            var d = this.length(), e, f = d - 1;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: ReduceRight on List with no elements.");
                for (var g = 1; g <= d; g++)
                    if (this.has(d - g)) {
                        e = this.get(d - g);
                        f = d - (g + 1);
                        break
                    }
                if (g > d)
               Ua.prototype.Ma = function() {
        this.K = !0
    }
    ;
    function Xa(a, b) {
        for (var c, d = 0; d < b.length && !(c = Ya(a, b[d]),
        c instanceof Qa); d++)
            ;
        return c
    }
    function Ya(a, b) {
        try {
            var c = a.get(String(b[0]));
            if (!c || typeof c.invoke !== "function")
                throw Error("Attempting to execute non-function " + b[0] + ".");
            return c.invoke.apply(c, [a].concat(b.slice(1)))
        } catch (e) {
            var d = a.D;
            d && d(e, b.context ? {
                id: b[0],
                line: b.context.line
            } : null);
            throw e;
        }
    }
    ;var Za = function() {
        this.D = new Ta;
        this.j = new Ua(this.D)
    };
    ba = Za.prototype;
    ba.sd = function() {
        return this.D
    }
    ;
    ba.execute = function(a) {
        var b = Array.prototype.slice.call(arguments, 0);
        return this.Xh(b)
    }
    ;
    ba.Xh = function() {
        for (var a, b = 0; b < arguments.length; b++)
            a = Ya(this.j, arguments[b]);
        return a
    }
    ;
    ba.Xk = function(a) {
        var b = Wa(this.j);
        b.j = a;
        for (var c, d = 1; d < arguments.length; d++)
            c = Ya(b, arguments[d]);
        return c
    }
    ;
    ba.Ma = function() {
        this.j.Ma()
    }
    ;
    var $a = function() {
        Ra.call(this);
        this.D = !1
    };
    za($a, Ra);
    var ab = function(a, b) {
        var c = [], d;
        for (d in a.j)
            if (a.j.hasOwnProperty(d))
                switch (d = d.substr(5),
                b) {
                case 1:
                    c.push(d);
                    break;
                case 2:
                    c.push(a.get(d));
                    break;
                case 3:
                    c.push([d, a.get(d)])
                }
        return c
    };
    $a.prototype.set = function(a, b) {
        this.D || Ra.prototype.set.call(this, a, b)
    }
    ;
    $a.prototype.Zh = function(a, b) {
        this.D || Ra.prototype.Zh.call(this, a, b)
    }
    ;
    $a.prototype.Hf = function(a) {
        this.D || Ra.prototype.Hf.call(this, a)
    }
    ;
    $a.prototype.Ma = function() {
        this.D = !0
    }
    ;
    /*
 jQuery (c) 2005, 2012 jQuery Foundation, Inc. jquery.org/license.
*/
    var cb = /\[object (Boolean|Number|String|Function|Array|Date|RegExp)\]/
      , db = function(a) {
        if (a == null)
            return String(a);
        var b = cb.exec(Object.prototype.toString.call(Object(a)));
        return b ? b[1].toLowerCase() : "object"
    }
      , eb = function(a, b) {
        return Object.prototype.hasOwnProperty.call(Object(a), b)
    }
      , fb = function(a) {
        if (!a || db(a) != "object" || a.nodeType || a == a.window)
            return !1;
        try {
            if (a.constructor && !eb(a, "constructor") && !eb(a.constructor.prototype, "isPrototypeOf"))
                return !1
        } catch (c) {
            return !1
        }
        for (var b in a)
            ;
        return b === void 0 || eb(a, b)
    }
      , h = function(a, b) {
        var c = b || (db(a) == "array" ? [] : {}), d;
        for (d in a)
            if (eb(a, d)) {
                var e = a[d];
                db(e) == "array" ? (db(c[d]) != "array" && (c[d] = []),
                c[d] = h(e, c[d])) : fb(e) ? (fb(c[d]) || (c[d] = {}),
                c[d] = h(e, c[d])) : c[d] = e
            }
        return c
    };
    function gb(a) {
        if (a == void 0 || Array.isArray(a) || fb(a))
            return !0;
        switch (typeof a) {
        case "boolean":
        case "number":
        case "string":
        case "function":
            return !0
        }
        return !1
    }
    function hb(a) {
        return typeof a === "number" && a >= 0 && isFinite(a) && a % 1 === 0 || typeof a === "string" && a[0] !== "-" && a === "" + parseInt(a)
    }
    ;var ib = function(a) {
        this.j = [];
        this.H = !1;
        this.D = new $a;
        a = a || [];
        for (var b in a)
            a.hasOwnProperty(b) && (hb(b) ? this.j[Number(b)] = a[Number(b)] : this.D.set(b, a[b]))
    };
    ba = ib.prototype;
    ba.toString = function(a) {
        if (a && a.indexOf(this) >= 0)
            return "";
        for (var b = [], c = 0; c < this.j.length; c++) {
            var d = this.j[c];
            d === null || d === void 0 ? b.push("") : d instanceof ib ? (a = a || [],
            a.push(this),
            b.push(d.toString(a)),
            a.pop()) : b.push(String(d))
        }
        return b.join(",")
    }
    ;
    ba.set = function(a, b) {
        if (!this.H)
            if (a === "length") {
                if (!hb(b))
                    throw Error("RangeError: Length property must be a valid integer.");
                this.j.length = Number(b)
            } else
                hb(a) ? this.j[Number(a)] = b : this.D.set(a, b)
    }
    ;
    ba.get = function(a) {
        return a === "length" ? this.length() : hb(a) ? this.j[Number(a)] : this.D.get(a)
    }
    ;
    ba.length = function() {
        return this.j.length
    }
    ;
    ba.Qb = function() {
        for (var a = ab(this.D, 1), b = 0; b < this.j.length; b++)
            a.push(b + "");
        return new ib(a)
    }
    ;
    var jb = function(a, b) {
        hb(b) ? delete a.j[Number(b)] : a.D.Hf(b)
    };
    ba = ib.prototype;
    ba.pop = function() {
        return this.j.pop()
    }
    ;
    ba.push = function() {
        return this.j.push.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.shift = function() {
        return this.j.shift()
    }
    ;
    ba.splice = function(a, b) {
        return new ib(this.j.splice.apply(this.j, arguments))
    }
    ;
    ba.unshift = function() {
        return this.j.unshift.apply(this.j, Array.prototype.slice.call(arguments))
    }
    ;
    ba.has = function(a) {
        return hb(a) && this.j.hasOwnProperty(a) || this.D.has(a)
    }
    ;
    ba.Ma = function() {
        this.H = !0;
        Object.freeze(this.j);
        this.D.Ma()
    }
    ;
    function kb(a) {
        for (var b = [], c = 0; c < a.length(); c++)
            a.has(c) && (b[c] = a.get(c));
        return b
    }
    ;var lb = function() {
        $a.call(this)
    };
    za(lb, $a);
    lb.prototype.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    var mb = function(a) {
        for (var b = ab(a, 3), c = new ib, d = 0; d < b.length; d++) {
            var e = new ib(b[d]);
            c.push(e)
        }
        return c
    };
    function nb() {
        for (var a = ob, b = {}, c = 0; c < a.length; ++c)
            b[a[c]] = c;
        return b
    }
    function pb() {
        var a = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
        a += a.toLowerCase() + "0123456789-_";
        return a + "."
    }
    var ob, qb;
    function rb(a) {
        ob = ob || pb();
        qb = qb || nb();
        for (var b = [], c = 0; c < a.length; c += 3) {
            var d = c + 1 < a.length
              , e = c + 2 < a.length
              , f = a.charCodeAt(c)
              , g = d ? a.charCodeAt(c + 1) : 0
              , k = e ? a.charCodeAt(c + 2) : 0
              , m = f >> 2
              , n = (f & 3) << 4 | g >> 4
              , p = (g & 15) << 2 | k >> 6
              , q = k & 63;
            e || (q = 64,
            d || (p = 64));
            b.push(ob[m], ob[n], ob[p], ob[q])
        }
        return b.join("")
    }
    function sb(a) {
        function b(m) {
            for (; d < a.length; ) {
                var n = a.charAt(d++)
                  , p = qb[n];
                if (p != null)
                    return p;
                if (!/^[\s\xa0]*$/.test(n))
                    throw Error("Unknown base64 encoding at char: " + n);
            }
            return m
        }
        ob = ob || pb();
        qb = qb || nb();
        for (var c = "", d = 0; ; ) {
            var e = b(-1)
              , f = b(0)
              , g = b(64)
              , k = b(64);
            if (k === 64 && e === -1)
                return c;
            c += String.fromCharCode(e << 2 | f >> 4);
            g !== 64 && (c += String.fromCharCode(f << 4 & 240 | g >> 2),
            k !== 64 && (c += String.fromCharCode(g << 6 & 192 | k)))
        }
    }
    ;var tb = {};
    function ub(a, b) {
        tb[a] = tb[a] || [];
        tb[a][b] = !0
    }
    function vb(a) {
        var b = tb[a];
        if (!b || b.length === 0)
            return "";
        for (var c = [], d = 0, e = 0; e < b.length; e++)
            e % 8 === 0 && e > 0 && (c.push(String.fromCharCode(d)),
            d = 0),
            b[e] && (d |= 1 << e % 8);
        d > 0 && c.push(String.fromCharCode(d));
        return rb(c.join("")).replace(/\.+$/, "")
    }
    function wb() {
        for (var a = [], b = tb.fdr || [], c = 0; c < b.length; c++)
            b[c] && a.push(c);
        return a.length > 0 ? a : void 0
    }
    ;var xb = []
      , yb = {};
    function zb(a) {
        return xb[a] === void 0 ? !1 : xb[a]
    }
    ;function Ab() {}
    function Bb(a) {
        return typeof a === "function"
    }
    function l(a) {
        return typeof a === "string"
    }
    function Cb(a) {
        return typeof a === "number" && !isNaN(a)
    }
    function Db(a) {
        return Array.isArray(a) ? a : [a]
    }
    function Eb(a, b) {
        if (a && Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                if (a[c] && b(a[c]))
                    return a[c]
    }
    function Fb(a, b) {
        if (!Cb(a) || !Cb(b) || a > b)
            a = 0,
            b = 2147483647;
        return Math.floor(Math.random() * (b - a + 1) + a)
    }
    function Gb(a, b) {
        for (var c = new Hb, d = 0; d < a.length; d++)
            c.set(a[d], !0);
        for (var e = 0; e < b.length; e++)
            if (c.get(b[e]))
                return !0;
        return !1
    }
    function z(a, b) {
        for (var c in a)
            Object.prototype.hasOwnProperty.call(a, c) && b(c, a[c])
    }
    function Ib(a) {
        return !!a && (Object.prototype.toString.call(a) === "[object Arguments]" || Object.prototype.hasOwnProperty.call(a, "callee"))
    }
    function Jb(a) {
        return Math.round(Number(a)) || 0
    }
    function Kb(a) {
        return "false" === String(a).toLowerCase() ? !1 : !!a
    }
    function Lb(a) {
        var b = [];
        if (Array.isArray(a))
            for (var c = 0; c < a.length; c++)
                b.push(String(a[c]));
        return b
    }
    function Mb(a) {
        return a ? a.replace(/^\s+|\s+$/g, "") : ""
    }
    function Nb() {
        return new Date(Date.now())
    }
    function Ob() {
        return Nb().getTime()
    }
    var Hb = function() {
        this.prefix = "gtm.";
        this.values = {}
    };
    Hb.prototype.set = function(a, b) {
        this.values[this.prefix + a] = b
    }
    ;
    Hb.prototype.get = function(a) {
        return this.values[this.prefix + a]
    }
    ;
    function Pb(a, b, c) {
        return a && a.hasOwnProperty(b) ? a[b] : c
    }
    function Qb(a) {
        var b = a;
        return function() {
            if (b) {
                var c = b;
                b = void 0;
                try {
                    c()
                } catch (d) {}
            }
        }
    }
    function Rb(a, b) {
        for (var c in b)
            b.hasOwnProperty(c) && (a[c] = b[c])
    }
    function Sb(a, b) {
        for (var c = [], d = 0; d < a.length; d++)
            c.push(a[d]),
            c.push.apply(c, b[a[d]] || []);
        return c
    }
    function Tb(a, b) {
        return a.length >= b.length && a.substring(0, b.length) === b
    }
    function Ub(a, b) {
        return a.length >= b.length && a.substring(a.length - b.length, a.length) === b
    }
    function Vb(a, b) {
        var c = G;
        b = b || [];
        for (var d = c, e = 0; e < a.length - 1; e++) {
            if (!d.hasOwnProperty(a[e]))
                return;
            d = d[a[e]];
            if (b.indexOf(d) >= 0)
                return
        }
        return d
    }
    function Wb(a, b) {
        for (var c = {}, d = c, e = a.split("."), f = 0; f < e.length - 1; f++)
            d = d[e[f]] = {};
        d[e[e.length - 1]] = b;
        return c
    }
    var Xb = /^\w{1,9}$/;
    function Yb(a, b) {
        a = a || {};
        b = b || ",";
        var c = [];
        z(a, function(d, e) {
            Xb.test(d) && e && c.push(d)
        });
        return c.join(b)
    }
    function Zb(a, b) {
        function c() {
            e && ++d === b && (e(),
            e = null,
            c.done = !0)
        }
        var d = 0
          , e = a;
        c.done = !1;
        return c
    }
    function $b(a) {
        if (!a)
            return a;
        var b = a;
        if (zb(3))
            try {
                b = decodeURIComponent(a)
            } catch (d) {}
        var c = b.split(",");
        return c.length === 2 && c[0] === c[1] ? c[0] : a
    }
    ;var ac, bc = function() {
        if (ac === void 0) {
            var a = null
              , b = Oa.trustedTypes;
            if (b && b.createPolicy) {
                try {
                    a = b.createPolicy("goog#html", {
                        createHTML: Pa,
                        createScript: Pa,
                        createScriptURL: Pa
                    })
                } catch (c) {
                    Oa.console && Oa.console.error(c.message)
                }
                ac = a
            } else
                ac = a
        }
        return ac
    };
    var cc = function(a) {
        this.j = a
    };
    cc.prototype.toString = function() {
        return this.j + ""
    }
    ;
    var dc = function(a) {
        return a instanceof cc && a.constructor === cc ? a.j : "type_error:TrustedResourceUrl"
    }
      , ec = {}
      , fc = function(a) {
        var b = a
          , c = bc()
          , d = c ? c.createScriptURL(b) : b;
        return new cc(d,ec)
    };
    /*

 SPDX-License-Identifier: Apache-2.0
*/
    var gc = ka([""])
      , hc = na(["\x00"], ["\\0"])
      , ic = na(["\n"], ["\\n"])
      , jc = na(["\x00"], ["\\u0000"]);
    function kc(a) {
        return a.toString().indexOf("`") === -1
    }
    kc(function(a) {
        return a(gc)
    }) || kc(function(a) {
        return a(hc)
    }) || kc(function(a) {
        return a(ic)
    }) || kc(function(a) {
        return a(jc)
    });
    var lc = function(a) {
        this.j = a
    };
    lc.prototype.toString = function() {
        return this.j
    }
    ;
    var mc = new lc("about:invalid#zClosurez");
    var nc = function(a) {
        this.wm = a
    };
    function oc(a) {
        return new nc(function(b) {
            return b.substr(0, a.length + 1).toLowerCase() === a + ":"
        }
        )
    }
    var pc = [oc("data"), oc("http"), oc("https"), oc("mailto"), oc("ftp"), new nc(function(a) {
        return /^[^:]*([/?#]|$)/.test(a)
    }
    )];
    function qc(a, b) {
        b = b === void 0 ? pc : b;
        if (a instanceof lc)
            return a;
        for (var c = 0; c < b.length; ++c) {
            var d = b[c];
            if (d instanceof nc && d.wm(a))
                return new lc(a)
        }
    }
    function rc(a) {
        var b;
        b = b === void 0 ? pc : b;
        return qc(a, b) || mc
    }
    var sc = /^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
    function tc(a) {
        var b;
        if (a instanceof lc)
            if (a instanceof lc)
                b = a.j;
            else
                throw Error("");
        else
            b = sc.test(a) ? a : void 0;
        return b
    }
    ;var vc = function() {
        this.j = uc[0].toLowerCase()
    };
    vc.prototype.toString = function() {
        return this.j
    }
    ;
    var wc = Array.prototype.indexOf ? function(a, b) {
        return Array.prototype.indexOf.call(a, b, void 0)
    }
    : function(a, b) {
        if (typeof a === "string")
            return typeof b !== "string" || b.length != 1 ? -1 : a.indexOf(b, 0);
        for (var c = 0; c < a.length; c++)
            if (c in a && a[c] === b)
                return c;
        return -1
    }
    ;
    var xc = {}
      , yc = function(a) {
        this.j = a
    };
    yc.prototype.toString = function() {
        return this.j.toString()
    }
    ;
    function zc(a, b) {
        var c = [new vc];
        if (c.length === 0)
            throw Error("");
        var d = c.map(function(f) {
            var g;
            if (f instanceof vc)
                g = f.j;
            else
                throw Error("");
            return g
        })
          , e = b.toLowerCase();
        if (d.every(function(f) {
            return e.indexOf(f) !== 0
        }))
            throw Error('Attribute "' + b + '" does not match any of the allowed prefixes.');
        a.setAttribute(b, "true")
    }
    ;function Ac(a, b) {
        var c = tc(b);
        c !== void 0 && (a.action = c)
    }
    ;"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON", "INPUT"]);
    function Bc(a) {
        return a === null ? "null" : a === void 0 ? "undefined" : a
    }
    ;var G = window
      , H = document
      , Cc = navigator
      , Dc = function() {
        var a;
        try {
            a = Cc.serviceWorker
        } catch (b) {
            return
        }
        return a
    }
      , Ec = H.currentScript
      , Fc = Ec && Ec.src
      , Gc = function(a, b) {
        var c = G[a];
        G[a] = c === void 0 ? b : c;
        return G[a]
    };
    function Hc(a) {
        return (Cc.userAgent || "").indexOf(a) !== -1
    }
    var Ic = {
        async: 1,
        nonce: 1,
        onerror: 1,
        onload: 1,
        src: 1,
        type: 1
    }
      , Jc = {
        onload: 1,
        src: 1,
        width: 1,
        height: 1,
        style: 1
    };
    function Kc(a, b, c) {
        b && z(b, function(d, e) {
            d = d.toLowerCase();
            c.hasOwnProperty(d) || a.setAttribute(d, e)
        })
    }
    var Lc = function(a, b, c, d, e) {
        var f = H.createElement("script");
        Kc(f, d, Ic);
        f.type = "text/javascript";
        f.async = d && d.async === !1 ? !1 : !0;
        var g;
        g = fc(Bc(a));
        f.src = dc(g);
        var k, m, n, p = (n = (m = (f.ownerDocument && f.ownerDocument.defaultView || window).document).querySelector) == null ? void 0 : n.call(m, "script[nonce]");
        (k = p ? p.nonce || p.getAttribute("nonce") || "" : "") && f.setAttribute("nonce", k);
        b && (f.onload = b);
        c && (f.onerror = c);
        if (e)
            e.appendChild(f);
        else {
            var q = H.getElementsByTagName("script")[0] || H.body || H.head;
            q.parentNode.insertBefore(f, q)
        }
        return f
    }
      , Mc = function() {
        if (Fc) {
            var a = Fc.toLowerCase();
            if (a.indexOf("https://") === 0)
                return 2;
            if (a.indexOf("http://") === 0)
                return 3
        }
        return 1
    }
      , Nc = function(a, b, c, d, e) {
        var f;
        f = f === void 0 ? !0 : f;
        var g = e
          , k = !1;
        g || (g = H.createElement("iframe"),
        k = !0);
        Kc(g, c, Jc);
        d && z(d, function(n, p) {
            g.dataset[n] = p
        });
        f && (g.height = "0",
        g.width = "0",
        g.style.display = "none",
        g.style.visibility = "hidden");
        a !== void 0 && (g.src = a);
        if (k) {
            var m = H.body && H.body.lastChild || H.body || H.head;
            m.parentNode.insertBefore(g, m)
        }
        b && (g.onload = b);
        return g
    }
      , Oc = function(a, b, c, d) {
        var e = new Image(1,1);
        Kc(e, d, {});
        e.onload = function() {
            e.onload = null;
            b && b()
        }
        ;
        e.onerror = function() {
            e.onerror = null;
            c && c()
        }
        ;
        e.src = a;
        return e
    }
      , Pc = function(a, b, c, d) {
        a.addEventListener ? a.addEventListener(b, c, !!d) : a.attachEvent && a.attachEvent("on" + b, c)
    }
      , Qc = function(a, b, c) {
        a.removeEventListener ? a.removeEventListener(b, c, !1) : a.detachEvent && a.detachEvent("on" + b, c)
    }
      , I = function(a) {
        G.setTimeout(a, 0)
    }
      , Rc = function(a, b) {
        return a && b && a.attributes && a.attributes[b] ? a.attributes[b].value : null
    }
      , Sc = function(a) {
        function b(e) {
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && e != " " && (e = e.replace(/^[\s\xa0]+|[\s\xa0]+$/g, ""));
            e && (e = e.replace(/(\xa0+|\s{2,}|\n|\r\t)/g, " "));
            return e
        }
        var c = b(a.innerText || a.textContent || "");
        if (zb(10)) {
            var d = b(a.textContent || "");
            ub("TAGGING", 26);
            d !== c && ub("TAGGING", 25)
        }
        return c
    }
      , Tc = function(a) {
        var b = H.createElement("div"), c = b, d, e = Bc("A<div>" + a + "</div>"), f = bc(), g = f ? f.createHTML(e) : e;
        d = new yc(g,xc);
        if (c.nodeType === 1) {
            var k = c.tagName;
            if (k === "SCRIPT" || k === "STYLE")
                throw Error("");
        }
        c.innerHTML = d instanceof yc && d.constructor === yc ? d.j : "type_error:SafeHtml";
        b = b.lastChild;
        for (var m = []; b.firstChild; )
            m.push(b.removeChild(b.firstChild));
        return m
    }
      , Uc = function(a, b, c) {
        c = c || 100;
        for (var d = {}, e = 0; e < b.length; e++)
            d[b[e]] = !0;
        for (var f = a, g = 0; f && g <= c; g++) {
            if (d[String(f.tagName).toLowerCase()])
                return f;
            f = f.parentElement
        }
        return null
    }
      , Vc = function(a) {
        var b;
        try {
            b = Cc.sendBeacon && Cc.sendBeacon(a)
        } catch (c) {
            ub("TAGGING", 15)
        }
        b || Oc(a)
    }
      , Wc = function(a, b) {
        try {
            return Cc.sendBeacon(a, b)
        } catch (c) {
            ub("TAGGING", 15)
        }
        return !1
    }
      , Xc = {
        cache: "no-store",
        credentials: "include",
        keepalive: !0,
        method: "POST",
        mode: "no-cors",
        redirect: "follow"
    }
      , Zc = function(a, b, c) {
        if (Yc()) {
            var d = Object.assign({}, Xc);
            b && (d.body = b);
            c && (c.attributionReporting && (d.attributionReporting = c.attributionReporting),
            c.browsingTopics && (d.browsingTopics = c.browsingTopics));
            try {
                var e = G.fetch(a, d);
                e && e.catch(Ab);
                return !0
            } catch (f) {}
        }
        if (c && c.noFallback)
            return !1;
        if (b)
            return Wc(a, b);
        Vc(a);
        return !0
    }
      , Yc = function() {
        return typeof G.fetch === "function"
    }
      , $c = function(a, b) {
        var c = a[b];
        c && typeof c.animVal === "string" && (c = c.animVal);
        return c
    }
      , ad = function() {
        var a = G.performance;
        if (a && Bb(a.now))
            return a.now()
    }
      , bd = function() {
        return G.performance || void 0
    };
    function cd(a, b) {
        return this.evaluate(a) && this.evaluate(b)
    }
    function dd(a, b) {
        return this.evaluate(a) === this.evaluate(b)
    }
    function ed(a, b) {
        return this.evaluate(a) || this.evaluate(b)
    }
    function fd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        return String(a).indexOf(String(b)) > -1
    }
    function gd(a, b) {
        var c = String(this.evaluate(a))
          , d = String(this.evaluate(b));
        return c.substring(0, d.length) === d
    }
    function hd(a, b) {
        a = this.evaluate(a);
        b = this.evaluate(b);
        switch (a) {
        case "pageLocation":
            var c = G.location.href;
            b instanceof lb && b.get("stripProtocol") && (c = c.replace(/^https?:\/\//, ""));
            return c
        }
    }
    ;var id = function(a, b) {
        $a.call(this);
        this.bk = a;
        this.uh = b
    };
    za(id, $a);
    ba = id.prototype;
    ba.toString = function() {
        return this.bk
    }
    ;
    ba.getName = function() {
        return this.bk
    }
    ;
    ba.Qb = function() {
        return new ib(ab(this, 1))
    }
    ;
    ba.invoke = function(a) {
        return this.uh.apply(new jd(this,a), Array.prototype.slice.call(arguments, 1))
    }
    ;
    ba.ib = function(a) {
        try {
            return this.invoke.apply(this, Array.prototype.slice.call(arguments, 0))
        } catch (b) {}
    }
    ;
    var jd = function(a, b) {
        this.uh = a;
        this.F = b
    };
    jd.prototype.evaluate = function(a) {
        var b = this.F;
        return Array.isArray(a) ? Ya(b, a) : a
    }
    ;
    jd.prototype.getName = function() {
        return this.uh.getName()
    }
    ;
    jd.prototype.sd = function() {
        return this.F.sd()
    }
    ;
    var kd = function() {
        this.map = new Map
    };
    kd.prototype.set = function(a, b) {
        this.map.set(a, b)
    }
    ;
    kd.prototype.get = function(a) {
        return this.map.get(a)
    }
    ;
    var ld = function() {
        this.keys = [];
        this.values = []
    };
    ld.prototype.set = function(a, b) {
        this.keys.push(a);
        this.values.push(b)
    }
    ;
    ld.prototype.get = function(a) {
        var b = this.keys.indexOf(a);
        if (b > -1)
            return this.values[b]
    }
    ;
    function md() {
        try {
            return Map ? new kd : new ld
        } catch (a) {
            return new ld
        }
    }
    ;var nd = function(a) {
        if (a instanceof nd)
            return a;
        if (gb(a))
            throw Error("Type of given value has an equivalent Pixie type.");
        this.value = a
    };
    nd.prototype.getValue = function() {
        return this.value
    }
    ;
    nd.prototype.toString = function() {
        return String(this.value)
    }
    ;
    var pd = function(a) {
        $a.call(this);
        this.promise = a;
        this.set("then", od(this));
        this.set("catch", od(this, !0));
        this.set("finally", od(this, !1, !0))
    };
    za(pd, lb);
    var od = function(a, b, c) {
        b = b === void 0 ? !1 : b;
        c = c === void 0 ? !1 : c;
        return new id("",function(d, e) {
            b && (e = d,
            d = void 0);
            c && (e = d);
            d instanceof id || (d = void 0);
            e instanceof id || (e = void 0);
            var f = Wa(this.F)
              , g = function(m) {
                return function(n) {
                    return c ? (m.invoke(f),
                    a.promise) : m.invoke(f, n)
                }
            }
              , k = a.promise.then(d && g(d), e && g(e));
            return new pd(k)
        }
        )
    };
    function J(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m = ab(g, 1), n = 0; n < m.length; n++)
                k[m[n]] = f(g.get(m[n]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (g instanceof ib) {
                var m = [];
                d.set(g, m);
                for (var n = g.Qb(), p = 0; p < n.length(); p++)
                    m[n.get(p)] = f(g.get(n.get(p)));
                return m
            }
            if (g instanceof pd)
                return g.promise;
            if (g instanceof lb) {
                var q = {};
                d.set(g, q);
                e(g, q);
                return q
            }
            if (g instanceof id) {
                var r = function() {
                    for (var u = Array.prototype.slice.call(arguments, 0), v = 0; v < u.length; v++)
                        u[v] = qd(u[v], b, c);
                    var w = new Ua(b ? b.sd() : new Ta);
                    b && (w.j = b.j);
                    return f(g.invoke.apply(g, [w].concat(u)))
                };
                d.set(g, r);
                e(g, r);
                return r
            }
            var t = !1;
            switch (c) {
            case 1:
                t = !0;
                break;
            case 2:
                t = !1;
                break;
            case 3:
                t = !1;
                break;
            default:
            }
            if (g instanceof nd && t)
                return g.getValue();
            switch (typeof g) {
            case "boolean":
            case "number":
            case "string":
            case "undefined":
                return g;
            case "object":
                if (g === null)
                    return null
            }
        };
        return f(a)
    }
    function qd(a, b, c) {
        var d = md()
          , e = function(g, k) {
            for (var m in g)
                g.hasOwnProperty(m) && k.set(m, f(g[m]))
        }
          , f = function(g) {
            var k = d.get(g);
            if (k)
                return k;
            if (Array.isArray(g) || Ib(g)) {
                var m = new ib([]);
                d.set(g, m);
                for (var n in g)
                    g.hasOwnProperty(n) && m.set(n, f(g[n]));
                return m
            }
            if (fb(g)) {
                var p = new lb;
                d.set(g, p);
                e(g, p);
                return p
            }
            if (typeof g === "function") {
                var q = new id("",function() {
                    for (var x = Array.prototype.slice.call(arguments, 0), y = 0; y < x.length; y++)
                        x[y] = J(this.evaluate(x[y]), b, c);
                    return f((0,
                    this.F.H)(g, g, x))
                }
                );
                d.set(g, q);
                e(g, q);
                return q
            }
            var v = typeof g;
            if (g === null || v === "string" || v === "number" || v === "boolean")
                return g;
            var w = !1;
            switch (c) {
            case 1:
                w = !0;
                break;
            case 2:
                w = !1;
                break;
            default:
            }
            if (g !== void 0 && w)
                return new nd(g)
        };
        return f(a)
    }
    ;function rd() {
        var a = !1;
        return a
    }
    ;var sd = {
        supportedMethods: "concat every filter forEach hasOwnProperty indexOf join lastIndexOf map pop push reduce reduceRight reverse shift slice some sort splice unshift toString".split(" "),
        concat: function(a) {
            for (var b = [], c = 0; c < this.length(); c++)
                b.push(this.get(c));
            for (var d = 1; d < arguments.length; d++)
                if (arguments[d]instanceof ib)
                    for (var e = arguments[d], f = 0; f < e.length(); f++)
                        b.push(e.get(f));
                else
                    b.push(arguments[d]);
            return new ib(b)
        },
        every: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                if (this.has(d) && !b.invoke(a, this.get(d), d, this))
                    return !1;
            return !0
        },
        filter: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && b.invoke(a, this.get(e), e, this) && d.push(this.get(e));
            return new ib(d)
        },
        forEach: function(a, b) {
            for (var c = this.length(), d = 0; d < this.length() && d < c; d++)
                this.has(d) && b.invoke(a, this.get(d), d, this)
        },
        hasOwnProperty: function(a, b) {
            return this.has(b)
        },
        indexOf: function(a, b, c) {
            var d = this.length()
              , e = c === void 0 ? 0 : Number(c);
            e < 0 && (e = Math.max(d + e, 0));
            for (var f = e; f < d; f++)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        join: function(a, b) {
            for (var c = [], d = 0; d < this.length(); d++)
                c.push(this.get(d));
            return c.join(b)
        },
        lastIndexOf: function(a, b, c) {
            var d = this.length()
              , e = d - 1;
            c !== void 0 && (e = c < 0 ? d + c : Math.min(c, e));
            for (var f = e; f >= 0; f--)
                if (this.has(f) && this.get(f) === b)
                    return f;
            return -1
        },
        map: function(a, b) {
            for (var c = this.length(), d = [], e = 0; e < this.length() && e < c; e++)
                this.has(e) && (d[e] = b.invoke(a, this.get(e), e, this));
            return new ib(d)
        },
        pop: function() {
            return this.pop()
        },
        push: function(a) {
            return this.push.apply(this, Array.prototype.slice.call(arguments, 1))
        },
        reduce: function(a, b, c) {
            var d = this.length(), e, f = 0;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: Reduce on List with no elements.");
                for (var g = 0; g < d; g++)
                    if (this.has(g)) {
                        e = this.get(g);
                        f = g + 1;
                        break
                    }
                if (g === d)
                    throw Error("TypeError: Reduce on List with no elements.");
            }
            for (var k = f; k < d; k++)
                this.has(k) && (e = b.invoke(a, e, this.get(k), k, this));
            return e
        },
        reduceRight: function(a, b, c) {
            var d = this.length(), e, f = d - 1;
            if (c !== void 0)
                e = c;
            else {
                if (d === 0)
                    throw Error("TypeError: ReduceRight on List with no elements.");
                for (var g = 1; g <= d; g++)
                    if (this.has(d - g)) {
                        e = this.get(d - g);
                        f = d - (g + 1);
                        break
                    }
                if (g > d)
               
// Copyright 2012 Google Inc. All rights reserved.
 
(function(){

var data = {
"resource": {
  "version":"1",
  
  "macros":[{"function":"__e"},{"vtp_signal":1,"function":"__c","vtp_value":1},{"function":"__c","vtp_value":""},{"function":"__c","vtp_value":0},{"vtp_signal":1,"function":"__c","vtp_value":1},{"function":"__c","vtp_value":""},{"function":"__c","vtp_value":0}],
  "tags":[{"function":"__ogt_1p_data_v2","priority":15,"vtp_isAutoEnabled":true,"vtp_autoCollectExclusionSelectors":["list",["map","exclusionSelector",""]],"vtp_isEnabled":true,"vtp_cityType":"CSS_SELECTOR","vtp_manualEmailEnabled":false,"vtp_firstNameType":"CSS_SELECTOR","vtp_countryType":"CSS_SELECTOR","vtp_cityValue":"","vtp_emailType":"CSS_SELECTOR","vtp_regionType":"CSS_SELECTOR","vtp_autoEmailEnabled":true,"vtp_postalCodeValue":"","vtp_lastNameValue":"","vtp_phoneType":"CSS_SELECTOR","vtp_phoneValue":"","vtp_streetType":"CSS_SELECTOR","vtp_autoPhoneEnabled":false,"vtp_postalCodeType":"CSS_SELECTOR","vtp_emailValue":"","vtp_firstNameValue":"","vtp_streetValue":"","vtp_lastNameType":"CSS_SELECTOR","vtp_autoAddressEnabled":false,"vtp_regionValue":"","vtp_countryValue":"","vtp_isAutoCollectPiiEnabledFlag":false,"tag_id":10},{"function":"__ccd_ga_first","priority":14,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":26},{"function":"__set_product_settings","priority":13,"vtp_instanceDestinationId":"G-DBEM2FVVRF","vtp_foreignTldMacroResult":["macro",5],"vtp_isChinaVipRegionMacroResult":["macro",6],"tag_id":25},{"function":"__ccd_ga_ads_link","priority":12,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":24},{"function":"__ogt_google_signals","priority":11,"vtp_googleSignals":"ENABLED","vtp_instanceDestinationId":"G-DBEM2FVVRF","vtp_serverMacroResult":["macro",4],"tag_id":23},{"function":"__ccd_ga_regscope","priority":10,"vtp_settingsTable":["list",["map","redactFieldGroup","DEVICE_AND_GEO","disallowAllRegions",false,"disallowedRegions",""],["map","redactFieldGroup","GOOGLE_SIGNALS","disallowAllRegions",false,"disallowedRegions",""]],"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":22},{"function":"__ccd_em_download","priority":9,"vtp_includeParams":true,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":21},{"function":"__ccd_em_outbound_click","priority":8,"vtp_includeParams":true,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":20},{"function":"__ccd_em_page_view","priority":7,"vtp_historyEvents":true,"vtp_includeParams":true,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":19},{"function":"__ccd_em_scroll","priority":6,"vtp_includeParams":true,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":18},{"function":"__ccd_em_site_search","priority":5,"vtp_searchQueryParams":"SearchableText","vtp_includeParams":true,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":17},{"function":"__ccd_em_video","priority":4,"vtp_includeParams":true,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":16},{"function":"__ccd_conversion_marking","priority":3,"vtp_conversionRules":["list",["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"purchase\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"bank_robbers_app_pageview\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"visit_duration\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"pages_screens_per_session\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"]],"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":15},{"function":"__ogt_event_create","priority":2,"vtp_eventName":"bank_robbers_app_pageview","vtp_isCopy":true,"vtp_instanceDestinationId":"G-DBEM2FVVRF","vtp_precompiledRule":["map","new_event_name","bank_robbers_app_pageview","merge_source_event_params",true,"event_name_predicate",["map","values",["list",["map","type","event_name"],["map","type","const","const_value","page_view"]],"type","eq"],"conditions",["list",["map","predicates",["list",["map","values",["list",["map","type","event_param","event_param",["map","param_name","page_path"]],["map","type","const","const_value","\/news\/apps\/bank-robbers-app"]],"type","swi"]]]],"event_param_ops",["list",["map","edit_param",["map","param_name","value","param_value",["map","type","const","const_value","0.0"]]],["map","edit_param",["map","param_name","currency","param_value",["map","type","const","const_value","USD"]]]]],"tag_id":14},{"function":"__ccd_auto_redact","priority":1,"vtp_redactEmail":false,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":13},{"function":"__gct","vtp_trackingId":"G-DBEM2FVVRF","vtp_sessionDuration":0,"vtp_googleSignals":["macro",1],"vtp_foreignTld":["macro",2],"vtp_restrictDomain":["macro",3],"tag_id":7},{"function":"__ccd_ga_last","priority":0,"vtp_instanceDestinationId":"G-DBEM2FVVRF","tag_id":12}],
  "predicates":[{"function":"_eq","arg0":["macro",0],"arg1":"gtm.js"},{"function":"_eq","arg0":["macro",0],"arg1":"gtm.init"}],
  "rules":[[["if",0],["add",15]],[["if",1],["add",0,16,14,13,12,11,10,9,8,7,6,5,4,3,2,1]]]
},
"runtime":[ [50,"__c",[46,"a"],[36,[17,[15,"a"],"value"]]]
 ,[50,"__ccd_auto_redact",[46,"a"],[50,"v",[46,"bk"],[36,[2,[15,"bk"],"replace",[7,[15,"u"],"\\$1"]]]],[50,"w",[46,"bk"],[52,"bl",["c",[15,"bk"]]],[52,"bm",[7]],[65,"bn",[2,[15,"bl"],"split",[7,""]],[46,[53,[52,"bo",[7,["v",[15,"bn"]]]],[52,"bp",["d",[15,"bn"]]],[22,[12,[15,"bp"],[45]],[46,[36,["d",["v",[15,"bk"]]]]]],[22,[21,[15,"bp"],[15,"bn"]],[46,[2,[15,"bo"],"push",[7,[15,"bp"]]],[22,[21,[15,"bn"],[2,[15,"bn"],"toLowerCase",[7]]],[46,[2,[15,"bo"],"push",[7,["d",[2,[15,"bn"],"toLowerCase",[7]]]]]],[46,[22,[21,[15,"bn"],[2,[15,"bn"],"toUpperCase",[7]]],[46,[2,[15,"bo"],"push",[7,["d",[2,[15,"bn"],"toUpperCase",[7]]]]]]]]]]],[22,[18,[17,[15,"bo"],"length"],1],[46,[2,[15,"bm"],"push",[7,[0,[0,"(?:",[2,[15,"bo"],"join",[7,"|"]]],")"]]]],[46,[2,[15,"bm"],"push",[7,[16,[15,"bo"],0]]]]]]]],[36,[2,[15,"bm"],"join",[7,""]]]],[50,"x",[46,"bk","bl","bm"],[52,"bn",["z",[15,"bk"],[15,"bm"]]],[22,[28,[15,"bn"]],[46,[36,[15,"bk"]]]],[22,[28,[17,[15,"bn"],"search"]],[46,[36,[15,"bk"]]]],[41,"bo"],[3,"bo",[17,[15,"bn"],"search"]],[65,"bp",[15,"bl"],[46,[53,[52,"bq",[7,["v",[15,"bp"]],["w",[15,"bp"]]]],[65,"br",[15,"bq"],[46,[53,[52,"bs",[30,[16,[15,"t"],[15,"br"]],[43,[15,"t"],[15,"br"],["b",[0,[0,"([?&]",[15,"br"]],"=)([^&]*)"],"gi"]]]],[3,"bo",[2,[15,"bo"],"replace",[7,[15,"bs"],[0,"$1",[15,"r"]]]]]]]]]]],[22,[20,[15,"bo"],[17,[15,"bn"],"search"]],[46,[36,[15,"bk"]]]],[22,[20,[16,[15,"bo"],0],"&"],[46,[3,"bo",[2,[15,"bo"],"substring",[7,1]]]]],[22,[21,[16,[15,"bo"],0],"?"],[46,[3,"bo",[0,"?",[15,"bo"]]]]],[22,[20,[15,"bo"],"?"],[46,[3,"bo",""]]],[43,[15,"bn"],"search",[15,"bo"]],[36,["ba",[15,"bn"],[15,"bm"]]]],[50,"z",[46,"bk","bl"],[22,[20,[15,"bl"],[17,[15,"s"],"PATH"]],[46,[3,"bk",[0,[15,"y"],[15,"bk"]]]]],[36,["g",[15,"bk"]]]],[50,"ba",[46,"bk","bl"],[41,"bm"],[3,"bm",""],[22,[20,[15,"bl"],[17,[15,"s"],"URL"]],[46,[53,[41,"bn"],[3,"bn",""],[22,[30,[17,[15,"bk"],"username"],[17,[15,"bk"],"password"]],[46,[3,"bn",[0,[15,"bn"],[0,[0,[0,[17,[15,"bk"],"username"],[39,[17,[15,"bk"],"password"],":",""]],[17,[15,"bk"],"password"]],"@"]]]]],[3,"bm",[0,[0,[0,[17,[15,"bk"],"protocol"],"//"],[15,"bn"]],[17,[15,"bk"],"host"]]]]]],[36,[0,[0,[0,[15,"bm"],[17,[15,"bk"],"pathname"]],[17,[15,"bk"],"search"]],[17,[15,"bk"],"hash"]]]],[50,"bb",[46,"bk","bl"],[41,"bm"],[3,"bm",[2,[15,"bk"],"replace",[7,[15,"n"],[15,"r"]]]],[22,[30,[20,[15,"bl"],[17,[15,"s"],"URL"]],[20,[15,"bl"],[17,[15,"s"],"PATH"]]],[46,[53,[52,"bn",["z",[15,"bm"],[15,"bl"]]],[22,[20,[15,"bn"],[44]],[46,[36,[15,"bm"]]]],[52,"bo",[17,[15,"bn"],"search"]],[52,"bp",[2,[15,"bo"],"replace",[7,[15,"o"],[15,"r"]]]],[22,[20,[15,"bo"],[15,"bp"]],[46,[36,[15,"bm"]]]],[43,[15,"bn"],"search",[15,"bp"]],[3,"bm",["ba",[15,"bn"],[15,"bl"]]]]]],[36,[15,"bm"]]],[50,"bc",[46,"bk"],[22,[20,[15,"bk"],[15,"q"]],[46,[36,[17,[15,"s"],"PATH"]]],[46,[22,[21,[2,[15,"p"],"indexOf",[7,[15,"bk"]]],[27,1]],[46,[36,[17,[15,"s"],"URL"]]],[46,[36,[17,[15,"s"],"TEXT"]]]]]]],[50,"bd",[46,"bk","bl"],[41,"bm"],[3,"bm",false],[52,"bn",["f",[15,"bk"]]],[38,[15,"bn"],[46,"string","array","object"],[46,[5,[46,[52,"bo",["bb",[15,"bk"],[15,"bl"]]],[22,[21,[15,"bk"],[15,"bo"]],[46,[36,[15,"bo"]]]],[4]]],[5,[46,[53,[41,"bp"],[3,"bp",0],[63,[7,"bp"],[23,[15,"bp"],[17,[15,"bk"],"length"]],[33,[15,"bp"],[3,"bp",[0,[15,"bp"],1]]],[46,[53,[52,"bq",["bd",[16,[15,"bk"],[15,"bp"]],[17,[15,"s"],"TEXT"]]],[22,[21,[15,"bq"],[44]],[46,[43,[15,"bk"],[15,"bp"],[15,"bq"]],[3,"bm",true]]]]]]],[4]]],[5,[46,[54,"bp",[15,"bk"],[46,[53,[52,"bq",["bd",[16,[15,"bk"],[15,"bp"]],[17,[15,"s"],"TEXT"]]],[22,[21,[15,"bq"],[44]],[46,[43,[15,"bk"],[15,"bp"],[15,"bq"]],[3,"bm",true]]]]]],[4]]]]],[36,[39,[15,"bm"],[15,"bk"],[44]]]],[50,"bj",[46,"bk","bl"],[52,"bm",[30,[2,[15,"bk"],"getMetadata",[7,[15,"bi"]]],[7]]],[22,[20,[2,[15,"bm"],"indexOf",[7,[15,"bl"]]],[27,1]],[46,[2,[15,"bm"],"push",[7,[15,"bl"]]]]],[2,[15,"bk"],"setMetadata",[7,[15,"bi"],[15,"bm"]]]],[52,"b",["require","internal.createRegex"]],[52,"c",["require","decodeUriComponent"]],[52,"d",["require","encodeUriComponent"]],[52,"e",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"f",["require","getType"]],[52,"g",["require","parseUrl"]],[52,"h",["require","internal.registerCcdCallback"]],[52,"i",[17,[15,"a"],"instanceDestinationId"]],[52,"j",[17,[15,"a"],"redactEmail"]],[52,"k",[17,[15,"a"],"redactQueryParams"]],[52,"l",[39,[15,"k"],[2,[15,"k"],"split",[7,","]],[7]]],[52,"m","is_sgtm_prehit"],[22,[1,[28,[17,[15,"l"],"length"]],[28,[15,"j"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"n",["b","[A-Z0-9._%+-]+@[A-Z0-9.-]+\\.[A-Z]{2,}","gi"]],[52,"o",["b",[0,"([A-Z0-9._-]|%25|%2B)+%40[A-Z0-9.-]","+\\.[A-Z]{2,}"],"gi"]],[52,"p",[7,"page_location","page_referrer","page_path","link_url","video_url","form_destination"]],[52,"q","page_path"],[52,"r","(redacted)"],[52,"s",[8,"TEXT",0,"URL",1,"PATH",2]],[52,"t",[8]],[52,"u",["b","([\\\\^$.|?*+(){}]|\\[|\\[)","g"]],[52,"y","http://."],[52,"be",15],[52,"bf",16],[52,"bg",23],[52,"bh",24],[52,"bi","event_usage"],["h",[15,"i"],[51,"",[7,"bk"],[22,[15,"j"],[46,[53,[52,"bl",[2,[15,"bk"],"getHitKeys",[7]]],[65,"bm",[15,"bl"],[46,[53,[22,[20,[15,"bm"],"_sst_parameters"],[46,[6]]],[52,"bn",[2,[15,"bk"],"getHitData",[7,[15,"bm"]]]],[22,[28,[15,"bn"]],[46,[6]]],[52,"bo",["bc",[15,"bm"]]],[52,"bp",["bd",[15,"bn"],[15,"bo"]]],[22,[21,[15,"bp"],[44]],[46,[2,[15,"bk"],"setHitData",[7,[15,"bm"],[15,"bp"]]],["bj",[15,"bk"],[39,[2,[15,"bk"],"getMetadata",[7,[15,"m"]]],[15,"bg"],[15,"be"]]]]]]]]]]],[22,[17,[15,"l"],"length"],[46,[65,"bl",[15,"p"],[46,[53,[52,"bm",[2,[15,"bk"],"getHitData",[7,[15,"bl"]]]],[22,[28,[15,"bm"]],[46,[6]]],[52,"bn",[39,[20,[15,"bl"],[15,"q"]],[17,[15,"s"],"PATH"],[17,[15,"s"],"URL"]]],[52,"bo",["x",[15,"bm"],[15,"l"],[15,"bn"]]],[22,[21,[15,"bo"],[15,"bm"]],[46,[2,[15,"bk"],"setHitData",[7,[15,"bl"],[15,"bo"]]],["bj",[15,"bk"],[39,[2,[15,"bk"],"getMetadata",[7,[15,"m"]]],[15,"bh"],[15,"bf"]]]]]]]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_conversion_marking",[46,"a"],[22,[30,[28,[17,[15,"a"],"conversionRules"]],[20,[17,[17,[15,"a"],"conversionRules"],"length"],0]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"b",["require","internal.copyPreHit"]],[52,"c",["require","internal.evaluateBooleanExpression"]],[52,"d",["require","internal.registerCcdCallback"]],[52,"e","is_conversion"],[52,"f","is_first_visit"],[52,"g","is_first_visit_conversion"],[52,"h","is_session_start"],[52,"i","is_session_start_conversion"],[52,"j","first_visit"],[52,"k","session_start"],[41,"l"],[41,"m"],["d",[17,[15,"a"],"instanceDestinationId"],[51,"",[7,"n"],[52,"o",[8,"preHit",[15,"n"]]],[65,"p",[17,[15,"a"],"conversionRules"],[46,[22,["c",[17,[15,"p"],"matchingRules"],[15,"o"]],[46,[2,[15,"n"],"setMetadata",[7,[15,"e"],true]],[4]]]]],[22,[2,[15,"n"],"getMetadata",[7,[15,"f"]]],[46,[22,[28,[15,"l"]],[46,[53,[52,"p",["b",[15,"n"],[8,"omitHitData",true,"omitMetadata",true]]],[2,[15,"p"],"setEventName",[7,[15,"j"]]],[3,"l",[8,"preHit",[15,"p"]]]]]],[65,"p",[17,[15,"a"],"conversionRules"],[46,[22,["c",[17,[15,"p"],"matchingRules"],[15,"l"]],[46,[2,[15,"n"],"setMetadata",[7,[15,"g"],true]],[4]]]]]]],[22,[2,[15,"n"],"getMetadata",[7,[15,"h"]]],[46,[22,[28,[15,"m"]],[46,[53,[52,"p",["b",[15,"n"],[8,"omitHitData",true,"omitMetadata",true]]],[2,[15,"p"],"setEventName",[7,[15,"k"]]],[3,"m",[8,"preHit",[15,"p"]]]]]],[65,"p",[17,[15,"a"],"conversionRules"],[46,[22,["c",[17,[15,"p"],"matchingRules"],[15,"m"]],[46,[2,[15,"n"],"setMetadata",[7,[15,"i"],true]],[4]]]]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]],[36]]
 ,[50,"__ccd_em_download",[46,"a"],[50,"r",[46,"x"],[36,[1,[15,"x"],[21,[2,[2,[15,"x"],"toLowerCase",[7]],"match",[7,[15,"q"]]],[45]]]]],[50,"s",[46,"x"],[52,"y",[2,[17,[15,"x"],"pathname"],"split",[7,"."]]],[52,"z",[39,[18,[17,[15,"y"],"length"],1],[16,[15,"y"],[37,[17,[15,"y"],"length"],1]],""]],[36,[16,[2,[15,"z"],"split",[7,"/"]],0]]],[50,"t",[46,"x"],[36,[39,[12,[2,[17,[15,"x"],"pathname"],"substring",[7,0,1]],"/"],[17,[15,"x"],"pathname"],[0,"/",[17,[15,"x"],"pathname"]]]]],[50,"u",[46,"x"],[41,"y"],[3,"y",""],[22,[1,[15,"x"],[17,[15,"x"],"href"]],[46,[53,[41,"z"],[3,"z",[2,[17,[15,"x"],"href"],"indexOf",[7,"#"]]],[3,"y",[39,[23,[15,"z"],0],[17,[15,"x"],"href"],[2,[17,[15,"x"],"href"],"substring",[7,0,[15,"z"]]]]]]]],[36,[15,"y"]]],[50,"w",[46,"x"],[52,"y",[8]],[43,[15,"y"],[15,"j"],true],[43,[15,"y"],[15,"f"],true],[43,[15,"x"],"eventMetadata",[15,"y"]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getProductSettingsParameter"]],[52,"d",["require","templateStorage"]],[52,"e",[15,"__module_ccdEmDownloadActivity"]],[52,"f","speculative"],[52,"g","ae_block_downloads"],[52,"h","file_download"],[52,"i","isRegistered"],[52,"j","em_event"],[52,"k",[17,[15,"a"],"instanceDestinationId"]],[22,["c",[15,"k"],[15,"g"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"e"],"registerDownloadActivityCallback",[7,[15,"k"],[17,[15,"a"],"includeParams"]]],[22,[2,[15,"d"],"getItem",[7,[15,"i"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"l",["require","internal.addDataLayerEventListener"]],[52,"m",["require","internal.enableAutoEventOnLinkClick"]],[52,"n",["require","internal.getDestinationIds"]],[52,"o",["require","parseUrl"]],[52,"p",["require","internal.sendGtagEvent"]],[52,"q",[0,"^(pdf|xlsx?|docx?|txt|rtf|csv|exe|key|pp(s|t|tx)|7z|pkg|rar|gz|zip|avi|","mov|mp4|mpe?g|wmv|midi?|mp3|wav|wma)$"]],[52,"v",["m",[8,"checkValidation",true]]],[22,[28,[15,"v"]],[46,[2,[15,"a"],"gtmOnFailure",[7]],[36]]],[2,[15,"d"],"setItem",[7,[15,"i"],true]],["l","gtm.linkClick",[51,"",[7,"x","y"],["y"],[52,"z",[8,"eventId",[16,[15,"x"],"gtm.uniqueEventId"]]],[22,[16,[15,"b"],"enableDeferAllEnhancedMeasurement"],[46,[43,[15,"z"],"deferrable",true]]],[52,"ba",[16,[15,"x"],"gtm.elementUrl"]],[52,"bb",["o",[15,"ba"]]],[22,[28,[15,"bb"]],[46,[36]]],[52,"bc",["s",[15,"bb"]]],[22,[28,["r",[15,"bc"]]],[46,[36]]],[52,"bd",[8,"link_id",[16,[15,"x"],"gtm.elementId"],"link_url",["u",[15,"bb"]],"link_text",[16,[15,"x"],"gtm.elementText"],"file_name",["t",[15,"bb"]],"file_extension",[15,"bc"]]],["w",[15,"z"]],["p",["n"],[15,"h"],[15,"bd"],[15,"z"]]],[15,"v"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_em_outbound_click",[46,"a"],[50,"s",[46,"y"],[22,[28,[15,"y"]],[46,[36,[44]]]],[41,"z"],[3,"z",""],[22,[1,[15,"y"],[17,[15,"y"],"href"]],[46,[53,[41,"ba"],[3,"ba",[2,[17,[15,"y"],"href"],"indexOf",[7,"#"]]],[3,"z",[39,[23,[15,"ba"],0],[17,[15,"y"],"href"],[2,[17,[15,"y"],"href"],"substring",[7,0,[15,"ba"]]]]]]]],[36,[15,"z"]]],[50,"t",[46,"y"],[22,[28,[15,"y"]],[46,[36,[44]]]],[41,"z"],[3,"z",[17,[15,"y"],"hostname"]],[52,"ba",[2,[15,"z"],"match",[7,"^www\\d*\\."]]],[22,[1,[15,"ba"],[16,[15,"ba"],0]],[46,[3,"z",[2,[15,"z"],"substring",[7,[17,[16,[15,"ba"],0],"length"]]]]]],[36,[15,"z"]]],[50,"u",[46,"y"],[22,[28,[15,"y"]],[46,[36,false]]],[52,"z",[2,[17,[15,"y"],"hostname"],"toLowerCase",[7]]],[41,"ba"],[3,"ba",[2,["t",["q",["p"]]],"toLowerCase",[7]]],[41,"bb"],[3,"bb",[37,[17,[15,"z"],"length"],[17,[15,"ba"],"length"]]],[22,[1,[18,[15,"bb"],0],[29,[2,[15,"ba"],"charAt",[7,0]],"."]],[46,[32,[15,"bb"],[3,"bb",[37,[15,"bb"],1]]],[3,"ba",[0,".",[15,"ba"]]]]],[22,[1,[19,[15,"bb"],0],[12,[2,[15,"z"],"indexOf",[7,[15,"ba"],[15,"bb"]]],[15,"bb"]]],[46,[36,false]]],[36,true]],[50,"x",[46,"y"],[52,"z",[8]],[43,[15,"z"],[15,"j"],true],[43,[15,"z"],[15,"f"],true],[43,[15,"y"],"eventMetadata",[15,"z"]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getProductSettingsParameter"]],[52,"d",["require","templateStorage"]],[52,"e",[15,"__module_ccdEmOutboundClickActivity"]],[52,"f","speculative"],[52,"g","ae_block_outbound_click"],[52,"h","click"],[52,"i","isRegistered"],[52,"j","em_event"],[52,"k",[17,[15,"a"],"instanceDestinationId"]],[22,["c",[15,"k"],[15,"g"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"e"],"registerOutbackClickActivityCallback",[7,[15,"k"],[17,[15,"a"],"includeParams"]]],[22,[2,[15,"d"],"getItem",[7,[15,"i"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"l",["require","internal.addDataLayerEventListener"]],[52,"m",["require","internal.enableAutoEventOnLinkClick"]],[52,"n",["require","internal.getDestinationIds"]],[52,"o",["require","internal.getRemoteConfigParameter"]],[52,"p",["require","getUrl"]],[52,"q",["require","parseUrl"]],[52,"r",["require","internal.sendGtagEvent"]],[52,"v",["o",[15,"k"],"cross_domain_conditions"]],[52,"w",["m",[8,"affiliateDomains",[15,"v"],"checkValidation",true,"waitForTags",false]]],[22,[28,[15,"w"]],[46,[2,[15,"a"],"gtmOnFailure",[7]],[36]]],[2,[15,"d"],"setItem",[7,[15,"i"],true]],["l","gtm.linkClick",[51,"",[7,"y","z"],[52,"ba",["q",[16,[15,"y"],"gtm.elementUrl"]]],[22,[28,["u",[15,"ba"]]],[46,["z"],[36]]],[52,"bb",[8,"link_id",[16,[15,"y"],"gtm.elementId"],"link_classes",[16,[15,"y"],"gtm.elementClasses"],"link_url",["s",[15,"ba"]],"link_domain",["t",[15,"ba"]],"outbound",true]],[43,[15,"bb"],"event_callback",[15,"z"]],[52,"bc",[8,"eventId",[16,[15,"y"],"gtm.uniqueEventId"]]],[22,[16,[15,"b"],"enableDeferAllEnhancedMeasurement"],[46,[43,[15,"bc"],"deferrable",true]]],["x",[15,"bc"]],["r",["n"],[15,"h"],[15,"bb"],[15,"bc"]]],[15,"w"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_em_page_view",[46,"a"],[50,"s",[46,"t"],[52,"u",[8]],[43,[15,"u"],[15,"k"],true],[43,[15,"u"],[15,"g"],true],[43,[15,"t"],"eventMetadata",[15,"u"]]],[22,[28,[17,[15,"a"],"historyEvents"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getProductSettingsParameter"]],[52,"d",["require","internal.setRemoteConfigParameter"]],[52,"e",["require","templateStorage"]],[52,"f",[15,"__module_ccdEmPageViewActivity"]],[52,"g","speculative"],[52,"h","ae_block_history"],[52,"i","page_view"],[52,"j","isRegistered"],[52,"k","em_event"],[52,"l",[17,[15,"a"],"instanceDestinationId"]],[22,["c",[15,"l"],[15,"h"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"f"],"registerPageViewActivityCallback",[7,[15,"l"]]],[22,[2,[15,"e"],"getItem",[7,[15,"j"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"m",["require","internal.addDataLayerEventListener"]],[52,"n",["require","internal.enableAutoEventOnHistoryChange"]],[52,"o",["require","internal.getDestinationIds"]],[52,"p",["require","internal.sendGtagEvent"]],[52,"q",[8,"interval",1000,"useV2EventName",true]],[52,"r",["n",[15,"q"]]],[22,[28,[15,"r"]],[46,[2,[15,"a"],"gtmOnFailure",[7]],[36]]],[2,[15,"e"],"setItem",[7,[15,"j"],true]],["m","gtm.historyChange-v2",[51,"",[7,"t","u"],["u"],[52,"v",[16,[15,"t"],"gtm.oldUrl"]],[22,[20,[16,[15,"t"],"gtm.newUrl"],[15,"v"]],[46,[36]]],[52,"w",[16,[15,"t"],"gtm.historyChangeSource"]],[22,[1,[1,[21,[15,"w"],"pushState"],[21,[15,"w"],"popstate"]],[21,[15,"w"],"replaceState"]],[46,[36]]],[52,"x",[8]],[22,[17,[15,"a"],"includeParams"],[46,[43,[15,"x"],"page_location",[16,[15,"t"],"gtm.newUrl"]],[43,[15,"x"],"page_referrer",[15,"v"]]]],[52,"y",[8,"eventId",[16,[15,"t"],"gtm.uniqueEventId"]]],[22,[16,[15,"b"],"enableDeferAllEnhancedMeasurement"],[46,[43,[15,"y"],"deferrable",true]]],["s",[15,"y"]],["p",["o"],[15,"i"],[15,"x"],[15,"y"]]],[15,"r"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_em_scroll",[46,"a"],[50,"q",[46,"r"],[52,"s",[8]],[43,[15,"s"],[15,"j"],true],[43,[15,"s"],[15,"f"],true],[43,[15,"r"],"eventMetadata",[15,"s"]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getProductSettingsParameter"]],[52,"d",["require","templateStorage"]],[52,"e",[15,"__module_ccdEmScrollActivity"]],[52,"f","speculative"],[52,"g","ae_block_scroll"],[52,"h","scroll"],[52,"i","isRegistered"],[52,"j","em_event"],[52,"k",[17,[15,"a"],"instanceDestinationId"]],[22,["c",[15,"k"],[15,"g"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"e"],"registerScrollActivityCallback",[7,[15,"k"],[17,[15,"a"],"includeParams"]]],[22,[2,[15,"d"],"getItem",[7,[15,"i"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"l",["require","internal.addDataLayerEventListener"]],[52,"m",["require","internal.enableAutoEventOnScroll"]],[52,"n",["require","internal.getDestinationIds"]],[52,"o",["require","internal.sendGtagEvent"]],[52,"p",["m",[8,"verticalThresholdUnits","PERCENT","verticalThresholds",90]]],[22,[28,[15,"p"]],[46,[2,[15,"a"],"gtmOnFailure",[7]],[36]]],[2,[15,"d"],"setItem",[7,[15,"i"],true]],["l","gtm.scrollDepth",[51,"",[7,"r","s"],["s"],[52,"t",[8,"eventId",[16,[15,"r"],"gtm.uniqueEventId"]]],[22,[16,[15,"b"],"enableDeferAllEnhancedMeasurement"],[46,[43,[15,"t"],"deferrable",true]]],[52,"u",[8,"percent_scrolled",[16,[15,"r"],"gtm.scrollThreshold"]]],["q",[15,"t"]],["o",["n"],[15,"h"],[15,"u"],[15,"t"]]],[15,"p"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_em_site_search",[46,"a"],[52,"b",["require","getQueryParameters"]],[52,"c",["require","internal.sendGtagEvent"]],[52,"d",["require","getContainerVersion"]],[52,"e",[15,"__module_ccdEmSiteSearchActivity"]],[52,"f",[2,[15,"e"],"getSearchTerm",[7,[17,[15,"a"],"searchQueryParams"],[15,"b"]]]],[52,"g",[30,[17,[15,"a"],"instanceDestinationId"],[17,["d"],"containerId"]]],[52,"h",[8,"deferrable",true,"eventId",[17,[15,"a"],"gtmEventId"],"eventMetadata",[8,"em_event",true]]],[22,[15,"f"],[46,[53,[52,"i",[39,[28,[28,[17,[15,"a"],"includeParams"]]],[2,[15,"e"],"buildEventParams",[7,[15,"f"],[17,[15,"a"],"additionalQueryParams"],[15,"b"]]],[8]]],["c",[15,"g"],"view_search_results",[15,"i"],[15,"h"]]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_em_video",[46,"a"],[50,"s",[46,"t"],[52,"u",[8]],[43,[15,"u"],[15,"l"],true],[43,[15,"u"],[15,"f"],true],[43,[15,"t"],"eventMetadata",[15,"u"]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getProductSettingsParameter"]],[52,"d",["require","templateStorage"]],[52,"e",[15,"__module_ccdEmVideoActivity"]],[52,"f","speculative"],[52,"g","ae_block_video"],[52,"h","video_start"],[52,"i","video_progress"],[52,"j","video_complete"],[52,"k","isRegistered"],[52,"l","em_event"],[52,"m",[17,[15,"a"],"instanceDestinationId"]],[22,["c",[15,"m"],[15,"g"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"e"],"registerVideoActivityCallback",[7,[15,"m"],[17,[15,"a"],"includeParams"]]],[22,[2,[15,"d"],"getItem",[7,[15,"k"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"n",["require","internal.addDataLayerEventListener"]],[52,"o",["require","internal.enableAutoEventOnYouTubeActivity"]],[52,"p",["require","internal.getDestinationIds"]],[52,"q",["require","internal.sendGtagEvent"]],[52,"r",["o",[8,"captureComplete",true,"captureStart",true,"progressThresholdsPercent",[7,10,25,50,75]]]],[22,[28,[15,"r"]],[46,[2,[15,"a"],"gtmOnFailure",[7]],[36]]],[2,[15,"d"],"setItem",[7,[15,"k"],true]],["n","gtm.video",[51,"",[7,"t","u"],["u"],[52,"v",[16,[15,"t"],"gtm.videoStatus"]],[41,"w"],[22,[20,[15,"v"],"start"],[46,[3,"w",[15,"h"]]],[46,[22,[20,[15,"v"],"progress"],[46,[3,"w",[15,"i"]]],[46,[22,[20,[15,"v"],"complete"],[46,[3,"w",[15,"j"]]],[46,[36]]]]]]],[52,"x",[8,"video_current_time",[16,[15,"t"],"gtm.videoCurrentTime"],"video_duration",[16,[15,"t"],"gtm.videoDuration"],"video_percent",[16,[15,"t"],"gtm.videoPercent"],"video_provider",[16,[15,"t"],"gtm.videoProvider"],"video_title",[16,[15,"t"],"gtm.videoTitle"],"video_url",[16,[15,"t"],"gtm.videoUrl"],"visible",[16,[15,"t"],"gtm.videoVisible"]]],[52,"y",[8,"eventId",[16,[15,"t"],"gtm.uniqueEventId"]]],[22,[16,[15,"b"],"enableDeferAllEnhancedMeasurement"],[46,[43,[15,"y"],"deferrable",true]]],["s",[15,"y"]],["q",["p"],[15,"w"],[15,"x"],[15,"y"]]],[15,"r"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_ga_ads_link",[46,"a"],[52,"b",["require","internal.CrossContainerSchema"]],[52,"c",["require","internal.GtagSchema"]],[52,"d",["require","internal.copyFromCrossContainerData"]],[52,"e",["require","internal.registerCcdCallback"]],[52,"f",["require","internal.setInCrossContainerData"]],[52,"g",["require","internal.setProductSettingsParameter"]],[52,"h","event_usage"],[52,"i",27],["g",[17,[15,"a"],"instanceDestinationId"],"ga4_ads_linked",true],["e",[17,[15,"a"],"instanceDestinationId"],[51,"",[7,"j"],[41,"k"],[3,"k",[2,[15,"j"],"getHitData",[7,[17,[17,[15,"c"],"EventParameters"],"USER_ID"]]]],[22,[28,[15,"k"]],[46,[53,[52,"n",[30,[2,[15,"j"],"getHitData",[7,[17,[17,[15,"c"],"EventParameters"],"USER_PROPERTIES"]]],[8]]],[3,"k",[16,[15,"n"],[17,[17,[15,"c"],"EventParameters"],"USER_ID"]]]]]],[22,[28,[15,"k"]],[46,[36]]],[52,"l",["d",[17,[15,"b"],"SHARED_USER_ID"]]],[22,[15,"l"],[46,[36]]],["f",[17,[15,"b"],"SHARED_USER_ID"],[15,"k"]],["f",[17,[15,"b"],"SHARED_USER_ID_SOURCE"],[17,[15,"a"],"instanceDestinationId"]],[52,"m",["d",[17,[15,"b"],"SHARED_USER_ID_REQUESTED"]]],[22,[15,"m"],[46,[53,[52,"n",[30,[2,[15,"j"],"getMetadata",[7,[15,"h"]]],[7]]],[22,[23,[2,[15,"n"],"indexOf",[7,[15,"i"]]],0],[46,[2,[15,"n"],"push",[7,[15,"i"]]],[2,[15,"j"],"setMetadata",[7,[15,"h"],[15,"n"]]]]]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_ga_first",[46,"a"],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_ga_last",[46,"a"],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_ga_regscope",[46,"a"],[52,"b",[15,"__module_ccdGaRegionScopedSettings"]],[52,"c",[2,[15,"b"],"extractRedactedLocations",[7,[15,"a"]]]],[2,[15,"b"],"applyRegionScopedSettings",[7,[15,"a"],[15,"c"]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__e",[46,"a"],[36,[13,[41,"$0"],[3,"$0",["require","internal.getEventData"]],["$0","event"]]]]
 ,[50,"__ogt_1p_data_v2",[46,"a"],[50,"j",[46,"m","n","o"],[22,[20,[16,[15,"n"],"type"],[15,"o"]],[46,[22,[28,[15,"m"]],[46,[3,"m",[8]]]],[22,[28,[16,[15,"m"],[15,"o"]]],[46,[43,[15,"m"],[15,"o"],[16,[15,"n"],"userData"]]]]]],[36,[15,"m"]]],[50,"k",[46,"m","n"],[52,"o",[16,[15,"a"],[15,"m"]]],[41,"p"],[22,[20,[15,"o"],"CSS_SELECTOR"],[46,[3,"p","css_selector"]],[46,[22,[20,[15,"o"],"JS_VAR"],[46,[3,"p","js_variable"]]]]],[36,[8,"selector_type",[15,"p"],"value",[16,[15,"a"],[15,"n"]]]]],[50,"l",[46,"m","n","o","p"],[22,[28,[16,[15,"a"],[15,"p"]]],[46,[36]]],[43,[15,"m"],[15,"n"],["k",[15,"o"],[15,"p"]]]],[22,[28,[17,[15,"a"],"isEnabled"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getDestinationIds"]],[52,"d",["require","internal.getProductSettingsParameter"]],[52,"e",["require","internal.detectUserProvidedData"]],[52,"f",["require","internal.setRemoteConfigParameter"]],[52,"g",["require","internal.registerCcdCallback"]],[52,"h",[30,["c"],[7]]],[52,"i",[8,"enable_code",true]],[22,[17,[15,"a"],"isAutoEnabled"],[46,[53,[52,"m",[7]],[22,[1,[17,[15,"a"],"autoCollectExclusionSelectors"],[17,[17,[15,"a"],"autoCollectExclusionSelectors"],"length"]],[46,[53,[41,"o"],[3,"o",0],[63,[7,"o"],[23,[15,"o"],[17,[17,[15,"a"],"autoCollectExclusionSelectors"],"length"]],[33,[15,"o"],[3,"o",[0,[15,"o"],1]]],[46,[53,[52,"p",[17,[16,[17,[15,"a"],"autoCollectExclusionSelectors"],[15,"o"]],"exclusionSelector"]],[22,[15,"p"],[46,[2,[15,"m"],"push",[7,[15,"p"]]]]]]]]]]],[52,"n",[39,[17,[15,"a"],"isAutoCollectPiiEnabledFlag"],[17,[15,"a"],"autoEmailEnabled"],true]],[43,[15,"i"],"auto_detect",[8,"email",[15,"n"],"phone",[17,[15,"a"],"autoPhoneEnabled"],"address",[17,[15,"a"],"autoAddressEnabled"],"exclude_element_selectors",[15,"m"]]]]]],[22,[17,[15,"a"],"isManualEnabled"],[46,[53,[52,"m",[8]],[22,[17,[15,"a"],"manualEmailEnabled"],[46,["l",[15,"m"],"email","emailType","emailValue"]]],[22,[17,[15,"a"],"manualPhoneEnabled"],[46,["l",[15,"m"],"phone","phoneType","phoneValue"]]],[22,[17,[15,"a"],"manualAddressEnabled"],[46,[53,[52,"n",[8]],["l",[15,"n"],"first_name","firstNameType","firstNameValue"],["l",[15,"n"],"last_name","lastNameType","lastNameValue"],["l",[15,"n"],"street","streetType","streetValue"],["l",[15,"n"],"city","cityType","cityValue"],["l",[15,"n"],"region","regionType","regionValue"],["l",[15,"n"],"country","countryType","countryValue"],["l",[15,"n"],"postal_code","postalCodeType","postalCodeValue"],[43,[15,"m"],"name_and_address",[7,[15,"n"]]]]]],[43,[15,"i"],"selectors",[15,"m"]]]]],[65,"m",[15,"h"],[46,[53,[41,"n"],[3,"n",[15,"i"]],[22,[1,[20,[2,[15,"m"],"indexOf",[7,"G-"]],0],[28,[16,[15,"b"],"enableEuidAutoMode"]]],[46,[53,[52,"q",[8,"enable_code",true,"selectors",[16,[15,"i"],"selectors"]]],[3,"n",[15,"q"]]]]],["f",[15,"m"],"user_data_settings",[15,"n"]],[52,"o",[16,[15,"n"],"auto_detect"]],[22,[28,[15,"o"]],[46,[6]]],[52,"p",[51,"",[7,"q"],[52,"r",[2,[15,"q"],"getMetadata",[7,"user_data_from_automatic"]]],[22,[15,"r"],[46,[36,[15,"r"]]]],[52,"s",["e",[8,"excludeElementSelectors",[16,[15,"o"],"exclude_element_selectors"],"fieldFilters",[8,"email",[16,[15,"o"],"email"],"phone",[16,[15,"o"],"phone"],"address",[16,[15,"o"],"address"]]]]],[52,"t",[1,[15,"s"],[16,[15,"s"],"elements"]]],[52,"u",[8]],[22,[1,[15,"t"],[18,[17,[15,"t"],"length"],0]],[46,[53,[41,"v"],[53,[41,"w"],[3,"w",0],[63,[7,"w"],[23,[15,"w"],[17,[15,"t"],"length"]],[33,[15,"w"],[3,"w",[0,[15,"w"],1]]],[46,[53,[52,"x",[16,[15,"t"],[15,"w"]]],["j",[15,"u"],[15,"x"],"email"],[22,[16,[15,"b"],"enableAutoPiiOnPhoneAndAddress"],[46,["j",[15,"u"],[15,"x"],"phone_number"],[3,"v",["j",[15,"v"],[15,"x"],"first_name"]],[3,"v",["j",[15,"v"],[15,"x"],"last_name"]],[3,"v",["j",[15,"v"],[15,"x"],"country"]],[3,"v",["j",[15,"v"],[15,"x"],"postal_code"]]]]]]]],[22,[1,[15,"v"],[28,[16,[15,"u"],"address"]]],[46,[43,[15,"u"],"address",[15,"v"]]]]]]],[2,[15,"q"],"setMetadata",[7,"user_data_from_automatic",[15,"u"]]],[36,[15,"u"]]]],["g",[15,"m"],[51,"",[7,"q"],[2,[15,"q"],"setMetadata",[7,"user_data_from_automatic_getter",[15,"p"]]]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ogt_event_create",[46,"a"],[50,"r",[46,"s","t"],[22,[28,[2,[15,"c"],"preHitMatchesRule",[7,[15,"s"],[16,[15,"t"],[15,"n"]],[30,[16,[15,"t"],[15,"o"]],[7]]]]],[46,[36,false]]],[52,"u",[16,[15,"t"],[15,"p"]]],[22,[2,[15,"c"],"isEventNameFalsyOrReserved",[7,[15,"u"]]],[46,[36]]],[52,"v",[28,[16,[15,"t"],[15,"q"]]]],[52,"w",[30,[2,[15,"s"],"getMetadata",[7,[15,"j"]]],[7]]],[22,[20,[2,[15,"w"],"indexOf",[7,[15,"k"]]],[27,1]],[46,[2,[15,"w"],"push",[7,[15,"k"]]]]],[2,[15,"s"],"setMetadata",[7,[15,"j"],[15,"w"]]],[52,"x",["b",[15,"s"],[8,"omitHitData",[15,"v"],"omitEventContext",[15,"v"],"omitMetadata",true]]],[2,[15,"c"],"applyParamOperations",[7,[15,"x"],[15,"t"]]],[2,[15,"x"],"setEventName",[7,[15,"u"]]],[2,[15,"x"],"setMetadata",[7,[15,"m"],true]],[2,[15,"x"],"setMetadata",[7,[15,"j"],[7,[15,"l"]]]],["d",[15,"x"]]],[52,"b",["require","internal.copyPreHit"]],[52,"c",[15,"__module_eventEditingAndSynthesis"]],[52,"d",["require","internal.processAsNewEvent"]],[52,"e",["require","internal.registerCcdCallback"]],[52,"f",["require","templateStorage"]],[52,"g",[17,[15,"a"],"instanceDestinationId"]],[41,"h"],[3,"h",[2,[15,"f"],"getItem",[7,[15,"g"]]]],[41,"i"],[3,"i",[28,[28,[15,"h"]]]],[22,[15,"i"],[46,[2,[15,"h"],"push",[7,[17,[15,"a"],"precompiledRule"]]],[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"f"],"setItem",[7,[15,"g"],[7,[17,[15,"a"],"precompiledRule"]]]],[52,"j","event_usage"],[52,"k",1],[52,"l",11],[52,"m","is_syn"],[52,"n","event_name_predicate"],[52,"o","conditions"],[52,"p","new_event_name"],[52,"q","merge_source_event_params"],["e",[15,"g"],[51,"",[7,"s"],[22,[2,[15,"s"],"getMetadata",[7,[15,"m"]]],[46,[36]]],[52,"t",[2,[15,"f"],"getItem",[7,[15,"g"]]]],[66,"u",[15,"t"],[46,["r",[15,"s"],[15,"u"]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ogt_google_signals",[46,"a"],[52,"b",["require","internal.setProductSettingsParameter"]],[52,"c",["require","getContainerVersion"]],[52,"d",[30,[17,[15,"a"],"instanceDestinationId"],[17,["c"],"containerId"]]],["b",[15,"d"],"google_signals",[20,[17,[15,"a"],"googleSignals"],"ENABLED"]],["b",[15,"d"],"google_ng",[20,[17,[15,"a"],"googleSignals"],"NON_GAIA_REMARKETING"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__set_product_settings",[46,"a"],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[52,"__module_eventEditingAndSynthesis",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"bc",[46,"bp","bq"],[52,"br",[30,[16,[15,"bq"],[15,"i"]],[7]]],[66,"bs",[15,"br"],[46,[22,[16,[15,"bs"],[15,"j"]],[46,[53,[52,"bt",[16,[16,[15,"bs"],[15,"j"]],[15,"l"]]],[52,"bu",["bh",[15,"bp"],[16,[16,[15,"bs"],[15,"j"]],[15,"m"]]]],[2,[15,"bp"],"setHitData",[7,[15,"bt"],["bd",[15,"bu"]]]]]],[46,[22,[16,[15,"bs"],[15,"k"]],[46,[53,[52,"bt",[16,[16,[15,"bs"],[15,"k"]],[15,"l"]]],[2,[15,"bp"],"setHitData",[7,[15,"bt"],[44]]]]]]]]]]],[50,"bd",[46,"bp"],[22,[28,[15,"bp"]],[46,[36,[15,"bp"]]]],[52,"bq",["c",[15,"bp"]]],[52,"br",[21,[15,"bq"],[15,"bq"]]],[22,[15,"br"],[46,[36,[15,"bp"]]]],[36,[15,"bq"]]],[50,"be",[46,"bp","bq","br"],[22,[1,[15,"bq"],[28,["bg",[15,"bp"],[15,"bq"]]]],[46,[36,false]]],[22,[30,[28,[15,"br"]],[20,[17,[15,"br"],"length"],0]],[46,[36,true]]],[53,[41,"bs"],[3,"bs",0],[63,[7,"bs"],[23,[15,"bs"],[17,[15,"br"],"length"]],[33,[15,"bs"],[3,"bs",[0,[15,"bs"],1]]],[46,[53,[52,"bt",[30,[16,[16,[15,"br"],[15,"bs"]],[15,"q"]],[7]]],[22,["bf",[15,"bp"],[15,"bt"]],[46,[36,true]]]]]]],[36,false]],[50,"bf",[46,"bp","bq"],[53,[41,"br"],[3,"br",0],[63,[7,"br"],[23,[15,"br"],[17,[15,"bq"],"length"]],[33,[15,"br"],[3,"br",[0,[15,"br"],1]]],[46,[53,[52,"bs",[16,[15,"bq"],[15,"br"]]],[52,"bt",["bg",[15,"bp"],[15,"bs"],false]],[22,[16,[15,"b"],"enableUrlDecodeEventUsage"],[46,[53,[52,"bu",[16,[30,[16,[15,"bs"],[15,"t"]],[7]],0]],[22,[1,[1,[15,"bu"],[20,[16,[15,"bu"],[15,"u"]],[15,"p"]]],[21,[2,[15,"bb"],"indexOf",[7,[16,[16,[15,"bu"],[15,"p"]],[15,"o"]]]],[27,1]]],[46,[53,[52,"bv",["bg",[15,"bp"],[15,"bs"],true]],[22,[21,[15,"bt"],[15,"bv"]],[46,[53,[52,"bw",[30,[2,[15,"bp"],"getMetadata",[7,[15,"y"]]],[7]]],[2,[15,"bw"],"push",[7,[39,[15,"bt"],[15,"ba"],[15,"z"]]]],[2,[15,"bp"],"setMetadata",[7,[15,"y"],[15,"bw"]]]]]]]]]]]],[22,[28,[15,"bt"]],[46,[36,false]]]]]]],[36,true]],[50,"bg",[46,"bp","bq","br"],[52,"bs",[30,[16,[15,"bq"],[15,"t"]],[7]]],[41,"bt"],[3,"bt",["bh",[15,"bp"],[16,[15,"bs"],0]]],[41,"bu"],[3,"bu",["bh",[15,"bp"],[16,[15,"bs"],1]]],[22,[1,[15,"br"],[15,"bt"]],[46,[3,"bt",[30,["h",[15,"bt"]],[15,"bt"]]]]],[22,[1,[16,[15,"b"],"enableDecodeUri"],[15,"bu"]],[46,[53,[52,"ca",[16,[30,[16,[15,"bq"],[15,"t"]],[7]],0]],[22,[1,[1,[15,"ca"],[20,[16,[15,"ca"],[15,"u"]],[15,"p"]]],[21,[2,[15,"bb"],"indexOf",[7,[16,[16,[15,"ca"],[15,"p"]],[15,"o"]]]],[27,1]]],[46,[53,[52,"cb",[2,[15,"bu"],"indexOf",[7,"?"]]],[22,[20,[15,"cb"],[27,1]],[46,[3,"bu",[30,["h",[15,"bu"]],[15,"bu"]]]],[46,[53,[52,"cc",[2,[15,"bu"],"substring",[7,0,[15,"cb"]]]],[3,"bu",[0,[30,["h",[15,"cc"]],[15,"cc"]],[2,[15,"bu"],"substring",[7,[15,"cb"]]]]]]]]]]]]]],[52,"bv",[16,[15,"bq"],[15,"s"]]],[22,[30,[30,[30,[20,[15,"bv"],"eqi"],[20,[15,"bv"],"swi"]],[20,[15,"bv"],"ewi"]],[20,[15,"bv"],"cni"]],[46,[22,[15,"bt"],[46,[3,"bt",[2,["e",[15,"bt"]],"toLowerCase",[7]]]]],[22,[15,"bu"],[46,[3,"bu",[2,["e",[15,"bu"]],"toLowerCase",[7]]]]]]],[41,"bw"],[3,"bw",false],[38,[15,"bv"],[46,"eq","eqi","sw","swi","ew","ewi","cn","cni","lt","le","gt","ge","re","rei"],[46,[5,[46]],[5,[46,[3,"bw",[20,["e",[15,"bt"]],["e",[15,"bu"]]]],[4]]],[5,[46]],[5,[46,[3,"bw",[20,[2,["e",[15,"bt"]],"indexOf",[7,["e",[15,"bu"]]]],0]],[4]]],[5,[46]],[5,[46,[41,"bx"],[3,"bx",["e",[15,"bt"]]],[41,"by"],[3,"by",["e",[15,"bu"]]],[52,"bz",[37,[17,[15,"bx"],"length"],[17,[15,"by"],"length"]]],[3,"bw",[1,[19,[15,"bz"],0],[20,[2,[15,"bx"],"indexOf",[7,[15,"by"],[15,"bz"]]],[15,"bz"]]]],[4]]],[5,[46]],[5,[46,[3,"bw",[19,[2,["e",[15,"bt"]],"indexOf",[7,["e",[15,"bu"]]]],0]],[4]]],[5,[46,[3,"bw",[23,["c",[15,"bt"]],["c",[15,"bu"]]]],[4]]],[5,[46,[3,"bw",[24,["c",[15,"bt"]],["c",[15,"bu"]]]],[4]]],[5,[46,[3,"bw",[18,["c",[15,"bt"]],["c",[15,"bu"]]]],[4]]],[5,[46,[3,"bw",[19,["c",[15,"bt"]],["c",[15,"bu"]]]],[4]]],[5,[46,[22,[21,[15,"bt"],[44]],[46,[53,[52,"ca",["f",[15,"bu"]]],[22,[15,"ca"],[46,[3,"bw",["g",[15,"ca"],[15,"bt"]]]]]]]],[4]]],[5,[46,[22,[21,[15,"bt"],[44]],[46,[53,[52,"ca",["f",[15,"bu"],"i"]],[22,[15,"ca"],[46,[3,"bw",["g",[15,"ca"],[15,"bt"]]]]]]]],[4]]],[9,[46]]]],[22,[28,[28,[16,[15,"bq"],[15,"r"]]]],[46,[36,[28,[15,"bw"]]]]],[36,[15,"bw"]]],[50,"bh",[46,"bp","bq"],[22,[28,[15,"bq"]],[46,[36,[44]]]],[38,[16,[15,"bq"],[15,"u"]],[46,"event_name","const","event_param"],[46,[5,[46,[36,[2,[15,"bp"],"getEventName",[7]]]]],[5,[46,[36,[16,[15,"bq"],[15,"n"]]]]],[5,[46,[52,"br",[16,[16,[15,"bq"],[15,"p"]],[15,"o"]]],[22,[20,[15,"br"],[15,"w"]],[46,[36,["bk",[15,"bp"]]]]],[22,[20,[15,"br"],[15,"v"]],[46,[36,["bl",[15,"bp"]]]]],[36,[2,[15,"bp"],"getHitData",[7,[15,"br"]]]]]],[9,[46,[36,[44]]]]]]],[50,"bj",[46,"bp"],[22,[28,[15,"bp"]],[46,[36,[15,"bp"]]]],[52,"bq",[2,[15,"bp"],"split",[7,"&"]]],[52,"br",[7]],[43,[15,"bq"],0,[2,[16,[15,"bq"],0],"substring",[7,1]]],[53,[41,"bs"],[3,"bs",0],[63,[7,"bs"],[23,[15,"bs"],[17,[15,"bq"],"length"]],[33,[15,"bs"],[3,"bs",[0,[15,"bs"],1]]],[46,[53,[52,"bt",[16,[15,"bq"],[15,"bs"]]],[52,"bu",[2,[15,"bt"],"indexOf",[7,"="]]],[52,"bv",[39,[19,[15,"bu"],0],[2,[15,"bt"],"substring",[7,0,[15,"bu"]]],[15,"bt"]]],[22,[28,[16,[15,"bi"],[15,"bv"]]],[46,[2,[15,"br"],"push",[7,[16,[15,"bq"],[15,"bs"]]]]]]]]]],[22,[17,[15,"br"],"length"],[46,[36,[0,"?",[2,[15,"br"],"join",[7,"&"]]]]]],[36,""]],[50,"bk",[46,"bp"],[52,"bq",[2,[15,"bp"],"getHitData",[7,[15,"w"]]]],[22,[15,"bq"],[46,[36,[15,"bq"]]]],[52,"br",[2,[15,"bp"],"getHitData",[7,[15,"x"]]]],[22,[21,[40,[15,"br"]],"string"],[46,[36,[44]]]],[52,"bs",["d",[15,"br"]]],[22,[28,[15,"bs"]],[46,[36,[44]]]],[41,"bt"],[3,"bt",[17,[15,"bs"],"pathname"]],[22,[16,[15,"b"],"enableDecodeUri"],[46,[3,"bt",[30,["h",[15,"bt"]],[15,"bt"]]]]],[36,[0,[15,"bt"],["bj",[17,[15,"bs"],"search"]]]]],[50,"bl",[46,"bp"],[52,"bq",[2,[15,"bp"],"getHitData",[7,[15,"v"]]]],[22,[15,"bq"],[46,[36,[15,"bq"]]]],[52,"br",[2,[15,"bp"],"getHitData",[7,[15,"x"]]]],[22,[21,[40,[15,"br"]],"string"],[46,[36,[44]]]],[52,"bs",["d",[15,"br"]]],[22,[28,[15,"bs"]],[46,[36,[44]]]],[36,[17,[15,"bs"],"hostname"]]],[50,"bo",[46,"bp"],[22,[28,[15,"bp"]],[46,[36,true]]],[3,"bp",["e",[15,"bp"]]],[66,"bq",[15,"bn"],[46,[22,[20,[2,[15,"bp"],"indexOf",[7,[15,"bq"]]],0],[46,[36,true]]]]],[22,[18,[2,[15,"bm"],"indexOf",[7,[15,"bp"]]],[27,1]],[46,[36,true]]],[36,false]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","makeNumber"]],[52,"d",["require","parseUrl"]],[52,"e",["require","makeString"]],[52,"f",["require","internal.createRegex"]],[52,"g",["require","internal.testRegex"]],[52,"h",["require","decodeUriComponent"]],[52,"i","event_param_ops"],[52,"j","edit_param"],[52,"k","delete_param"],[52,"l","param_name"],[52,"m","param_value"],[52,"n","const_value"],[52,"o","param_name"],[52,"p","event_param"],[52,"q","predicates"],[52,"r","negate"],[52,"s","type"],[52,"t","values"],[52,"u","type"],[52,"v","page_hostname"],[52,"w","page_path"],[52,"x","page_location"],[52,"y","event_usage"],[52,"z",20],[52,"ba",21],[52,"bb",[7,[15,"w"],[15,"x"],"page_referrer"]],[52,"bi",[8,"__utma",1,"__utmb",1,"__utmc",1,"__utmk",1,"__utmv",1,"__utmx",1,"__utmz",1,"__ga",1,"_gac",1,"_gl",1,"dclid",1,"gbraid",1,"gclid",1,"gclsrc",1,"utm_campaign",1,"utm_content",1,"utm_expid",1,"utm_id",1,"utm_medium",1,"utm_nooverride",1,"utm_referrer",1,"utm_source",1,"utm_term",1,"wbraid",1]],[52,"bm",[7,"app_remove","app_store_refund","app_store_subscription_cancel","app_store_subscription_convert","app_store_subscription_renew","first_open","first_visit","in_app_purchase","session_start","user_engagement"]],[52,"bn",[7,"_","ga_","google_","gtag.","firebase_"]],[36,[8,"applyParamOperations",[15,"bc"],"preHitMatchesRule",[15,"be"],"resolveValue",[15,"bh"],"isEventNameFalsyOrReserved",[15,"bo"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_activities",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"b",[46,"c","d"],[36,[39,[15,"d"],["d",[15,"c"]],[15,"c"]]]],[36,[8,"withRequestContext",[15,"b"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmDownloadActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"h",[46,"i","j"],["c",[15,"i"],[51,"",[7,"k"],[22,[30,[21,[2,[15,"k"],"getEventName",[7]],[15,"f"]],[28,[2,[15,"k"],"getMetadata",[7,[15,"g"]]]]],[46,[36]]],[22,["b",[15,"i"],[15,"e"]],[46,[2,[15,"k"],"abort",[7]],[36]]],[2,[15,"k"],"setMetadata",[7,[15,"d"],false]],[22,[28,[15,"j"]],[46,[2,[15,"k"],"setHitData",[7,"link_id",[44]]],[2,[15,"k"],"setHitData",[7,"link_url",[44]]],[2,[15,"k"],"setHitData",[7,"link_text",[44]]],[2,[15,"k"],"setHitData",[7,"file_name",[44]]],[2,[15,"k"],"setHitData",[7,"file_extension",[44]]]]]]]],[52,"b",["require","internal.getProductSettingsParameter"]],[52,"c",["require","internal.registerCcdCallback"]],[52,"d","speculative"],[52,"e","ae_block_downloads"],[52,"f","file_download"],[52,"g","em_event"],[36,[8,"registerDownloadActivityCallback",[15,"h"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmOutboundClickActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"h",[46,"i","j"],["c",[15,"i"],[51,"",[7,"k"],[22,[30,[21,[2,[15,"k"],"getEventName",[7]],[15,"f"]],[28,[2,[15,"k"],"getMetadata",[7,[15,"g"]]]]],[46,[36]]],[22,["b",[15,"i"],[15,"e"]],[46,[2,[15,"k"],"abort",[7]],[36]]],[2,[15,"k"],"setMetadata",[7,[15,"d"],false]],[22,[28,[15,"j"]],[46,[2,[15,"k"],"setHitData",[7,"link_id",[44]]],[2,[15,"k"],"setHitData",[7,"link_classes",[44]]],[2,[15,"k"],"setHitData",[7,"link_url",[44]]],[2,[15,"k"],"setHitData",[7,"link_domain",[44]]],[2,[15,"k"],"setHitData",[7,"outbound",[44]]]]]]]],[52,"b",["require","internal.getProductSettingsParameter"]],[52,"c",["require","internal.registerCcdCallback"]],[52,"d","speculative"],[52,"e","ae_block_outbound_click"],[52,"f","click"],[52,"g","em_event"],[36,[8,"registerOutbackClickActivityCallback",[15,"h"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmPageViewActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"j",[46,"k"],["c",[15,"k"],[51,"",[7,"l"],[22,[30,[21,[2,[15,"l"],"getEventName",[7]],[15,"h"]],[28,[2,[15,"l"],"getMetadata",[7,[15,"i"]]]]],[46,[36]]],[22,["b",[15,"k"],[15,"g"]],[46,[2,[15,"l"],"abort",[7]],[36]]],[22,[28,[2,[15,"l"],"getMetadata",[7,[15,"f"]]]],[46,["d",[15,"k"],"page_referrer",[2,[15,"l"],"getHitData",[7,"page_referrer"]]]]],[2,[15,"l"],"setMetadata",[7,[15,"e"],false]]]]],[52,"b",["require","internal.getProductSettingsParameter"]],[52,"c",["require","internal.registerCcdCallback"]],[52,"d",["require","internal.setRemoteConfigParameter"]],[52,"e","speculative"],[52,"f","is_sgtm_prehit"],[52,"g","ae_block_history"],[52,"h","page_view"],[52,"i","em_event"],[36,[8,"registerPageViewActivityCallback",[15,"j"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmSiteSearchActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"b",[46,"d","e"],[52,"f",[2,[30,[15,"d"],""],"split",[7,","]]],[53,[41,"g"],[3,"g",0],[63,[7,"g"],[23,[15,"g"],[17,[15,"f"],"length"]],[33,[15,"g"],[3,"g",[0,[15,"g"],1]]],[46,[53,[52,"h",["e",[2,[16,[15,"f"],[15,"g"]],"trim",[7]]]],[22,[21,[15,"h"],[44]],[46,[36,[15,"h"]]]]]]]]],[50,"c",[46,"d","e","f"],[52,"g",[8,"search_term",[15,"d"]]],[52,"h",[2,[30,[15,"e"],""],"split",[7,","]]],[53,[41,"i"],[3,"i",0],[63,[7,"i"],[23,[15,"i"],[17,[15,"h"],"length"]],[33,[15,"i"],[3,"i",[0,[15,"i"],1]]],[46,[53,[52,"j",[2,[16,[15,"h"],[15,"i"]],"trim",[7]]],[52,"k",["f",[15,"j"]]],[22,[21,[15,"k"],[44]],[46,[43,[15,"g"],[0,"q_",[15,"j"]],[15,"k"]]]]]]]],[36,[15,"g"]]],[36,[8,"getSearchTerm",[15,"b"],"buildEventParams",[15,"c"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmScrollActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"h",[46,"i","j"],["c",[15,"i"],[51,"",[7,"k"],[22,[30,[21,[2,[15,"k"],"getEventName",[7]],[15,"f"]],[28,[2,[15,"k"],"getMetadata",[7,[15,"g"]]]]],[46,[36]]],[22,["b",[15,"i"],[15,"e"]],[46,[2,[15,"k"],"abort",[7]],[36]]],[2,[15,"k"],"setMetadata",[7,[15,"d"],false]],[22,[28,[15,"j"]],[46,[2,[15,"k"],"setHitData",[7,"percent_scrolled",[44]]]]]]]],[52,"b",["require","internal.getProductSettingsParameter"]],[52,"c",["require","internal.registerCcdCallback"]],[52,"d","speculative"],[52,"e","ae_block_scroll"],[52,"f","scroll"],[52,"g","em_event"],[36,[8,"registerScrollActivityCallback",[15,"h"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmVideoActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"j",[46,"k","l"],["c",[15,"k"],[51,"",[7,"m"],[52,"n",[2,[15,"m"],"getEventName",[7]]],[52,"o",[30,[30,[20,[15,"n"],[15,"f"]],[20,[15,"n"],[15,"g"]]],[20,[15,"n"],[15,"h"]]]],[22,[30,[28,[15,"o"]],[28,[2,[15,"m"],"getMetadata",[7,[15,"i"]]]]],[46,[36]]],[22,["b",[15,"k"],[15,"e"]],[46,[2,[15,"m"],"abort",[7]],[36]]],[2,[15,"m"],"setMetadata",[7,[15,"d"],false]],[22,[28,[15,"l"]],[46,[2,[15,"m"],"setHitData",[7,"video_current_time",[44]]],[2,[15,"m"],"setHitData",[7,"video_duration",[44]]],[2,[15,"m"],"setHitData",[7,"video_percent",[44]]],[2,[15,"m"],"setHitData",[7,"video_provider",[44]]],[2,[15,"m"],"setHitData",[7,"video_title",[44]]],[2,[15,"m"],"setHitData",[7,"video_url",[44]]],[2,[15,"m"],"setHitData",[7,"visible",[44]]]]]]]],[52,"b",["require","internal.getProductSettingsParameter"]],[52,"c",["require","internal.registerCcdCallback"]],[52,"d","speculative"],[52,"e","ae_block_video"],[52,"f","video_start"],[52,"g","video_progress"],[52,"h","video_complete"],[52,"i","em_event"],[36,[8,"registerVideoActivityCallback",[15,"j"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdGaRegionScopedSettings",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"n",[46,"q","r","s"],[50,"x",[46,"z"],[52,"ba",[16,[15,"m"],[15,"z"]]],[22,[28,[15,"ba"]],[46,[36]]],[53,[41,"bb"],[3,"bb",0],[63,[7,"bb"],[23,[15,"bb"],[17,[15,"ba"],"length"]],[33,[15,"bb"],[3,"bb",[0,[15,"bb"],1]]],[46,[53,[52,"bc",[16,[15,"ba"],[15,"bb"]]],["u",[15,"t"],[17,[15,"bc"],"name"],[17,[15,"bc"],"value"]]]]]]],[50,"y",[46,"z"],[22,[30,[28,[15,"v"]],[21,[17,[15,"v"],"length"],2]],[46,[36,false]]],[41,"ba"],[3,"ba",[16,[15,"z"],[15,"w"]]],[22,[20,[15,"ba"],[44]],[46,[3,"ba",[16,[15,"z"],[15,"v"]]]]],[36,[28,[28,[15,"ba"]]]]],[22,[28,[15,"r"]],[46,[36]]],[52,"t",[30,[17,[15,"q"],"instanceDestinationId"],[17,["d"],"containerId"]]],[52,"u",["i",[15,"g"],[15,"s"]]],[52,"v",[13,[41,"$0"],[3,"$0",["i",[15,"e"],[15,"s"]]],["$0"]]],[52,"w",[13,[41,"$0"],[3,"$0",["i",[15,"f"],[15,"s"]]],["$0"]]],[53,[41,"z"],[3,"z",0],[63,[7,"z"],[23,[15,"z"],[17,[15,"r"],"length"]],[33,[15,"z"],[3,"z",[0,[15,"z"],1]]],[46,[53,[52,"ba",[16,[15,"r"],[15,"z"]]],[22,[30,[17,[15,"ba"],"disallowAllRegions"],["y",[17,[15,"ba"],"disallowedRegions"]]],[46,["x",[17,[15,"ba"],"redactFieldGroup"]]]]]]]]],[50,"o",[46,"q"],[52,"r",[8]],[22,[28,[15,"q"]],[46,[36,[15,"r"]]]],[52,"s",[2,[15,"q"],"split",[7,","]]],[53,[41,"t"],[3,"t",0],[63,[7,"t"],[23,[15,"t"],[17,[15,"s"],"length"]],[33,[15,"t"],[3,"t",[0,[15,"t"],1]]],[46,[53,[52,"u",[2,[16,[15,"s"],[15,"t"]],"trim",[7]]],[22,[28,[15,"u"]],[46,[6]]],[52,"v",[2,[15,"u"],"split",[7,"-"]]],[52,"w",[16,[15,"v"],0]],[52,"x",[39,[20,[17,[15,"v"],"length"],2],[15,"u"],[44]]],[22,[30,[28,[15,"w"]],[21,[17,[15,"w"],"length"],2]],[46,[6]]],[22,[1,[21,[15,"x"],[44]],[30,[23,[17,[15,"x"],"length"],4],[18,[17,[15,"x"],"length"],6]]],[46,[6]]],[43,[15,"r"],[15,"u"],true]]]]],[36,[15,"r"]]],[50,"p",[46,"q"],[22,[28,[17,[15,"q"],"settingsTable"]],[46,[36,[7]]]],[52,"r",[8]],[53,[41,"s"],[3,"s",0],[63,[7,"s"],[23,[15,"s"],[17,[17,[15,"q"],"settingsTable"],"length"]],[33,[15,"s"],[3,"s",[0,[15,"s"],1]]],[46,[53,[52,"t",[16,[17,[15,"q"],"settingsTable"],[15,"s"]]],[52,"u",[17,[15,"t"],"redactFieldGroup"]],[22,[28,[16,[15,"m"],[15,"u"]]],[46,[6]]],[43,[15,"r"],[15,"u"],[8,"redactFieldGroup",[15,"u"],"disallowAllRegions",false,"disallowedRegions",[8]]],[52,"v",[16,[15,"r"],[15,"u"]]],[22,[17,[15,"t"],"disallowAllRegions"],[46,[43,[15,"v"],"disallowAllRegions",true],[6]]],[43,[15,"v"],"disallowedRegions",["o",[17,[15,"t"],"disallowedRegions"]]]]]]],[36,[2,[15,"b"],"values",[7,[15,"r"]]]]],[52,"b",["require","Object"]],[52,"c",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"d",["require","getContainerVersion"]],[52,"e",["require","internal.getCountryCode"]],[52,"f",["require","internal.getRegionCode"]],[52,"g",["require","internal.setRemoteConfigParameter"]],[52,"h",[15,"__module_activities"]],[52,"i",[17,[15,"h"],"withRequestContext"]],[41,"j"],[41,"k"],[41,"l"],[52,"m",[8,"GOOGLE_SIGNALS",[7,[8,"name","allow_google_signals","value",false]],"DEVICE_AND_GEO",[7,[8,"name","geo_granularity","value",true],[8,"name","redact_device_info","value",true]]]],[36,[8,"applyRegionScopedSettings",[15,"n"],"extractRedactedLocations",[15,"p"]]]],[36,["a"]]]],["$0"]]]
 
]
,"entities":{
"__c":{"2":true,"4":true}
,
"__ccd_auto_redact":{"2":true,"4":true}
,
"__ccd_conversion_marking":{"2":true,"4":true}
,
"__ccd_em_download":{"2":true,"4":true}
,
"__ccd_em_outbound_click":{"2":true,"4":true}
,
"__ccd_em_page_view":{"2":true,"4":true}
,
"__ccd_em_scroll":{"2":true,"4":true}
,
"__ccd_em_site_search":{"2":true,"4":true}
,
"__ccd_em_video":{"2":true,"4":true}
,
"__ccd_ga_ads_link":{"2":true,"4":true}
,
"__ccd_ga_first":{"2":true,"4":true}
,
"__ccd_ga_last":{"2":true,"4":true}
,
"__ccd_ga_regscope":{"2":true,"4":true}
,
"__e":{"2":true,"4":true}
,
"__ogt_1p_data_v2":{"2":true}
,
"__ogt_event_create":{"2":true,"4":true}
,
"__ogt_google_signals":{"2":true,"4":true}
,
"__set_product_settings":{"2":true,"4":true}


}
,"blob":{"1":"1"}
,"permissions":{
"__c":{}
,
"__ccd_auto_redact":{}
,
"__ccd_conversion_marking":{}
,
"__ccd_em_download":{"listen_data_layer":{"accessType":"specific","allowedEvents":["gtm.linkClick"]},"access_template_storage":{},"detect_link_click_events":{"allowWaitForTags":""}}
,
"__ccd_em_outbound_click":{"get_url":{"urlParts":"any","queriesAllowed":"any"},"listen_data_layer":{"accessType":"specific","allowedEvents":["gtm.linkClick"]},"access_template_storage":{},"detect_link_click_events":{"allowWaitForTags":""}}
,
"__ccd_em_page_view":{"listen_data_layer":{"accessType":"specific","allowedEvents":["gtm.historyChange-v2"]},"access_template_storage":{},"detect_history_change_events":{}}
,
"__ccd_em_scroll":{"listen_data_layer":{"accessType":"specific","allowedEvents":["gtm.scrollDepth"]},"process_dom_events":{"targets":[{"targetType":"window","eventName":"resize"},{"targetType":"window","eventName":"scroll"},{"targetType":"window","eventName":"scrollend"}]},"access_template_storage":{},"detect_scroll_events":{}}
,
"__ccd_em_site_search":{"get_url":{"urlParts":"any","queriesAllowed":"any"},"read_container_data":{}}
,
"__ccd_em_video":{"listen_data_layer":{"accessType":"specific","allowedEvents":["gtm.video"]},"access_template_storage":{},"detect_youtube_activity_events":{"allowFixMissingJavaScriptApi":false}}
,
"__ccd_ga_ads_link":{}
,
"__ccd_ga_first":{}
,
"__ccd_ga_last":{}
,
"__ccd_ga_regscope":{"read_container_data":{}}
,
"__e":{"read_event_data":{"eventDataAccess":"specific","keyPatterns":["event"]}}
,
"__ogt_1p_data_v2":{"detect_user_provided_data":{"limitDataSources":true,"allowAutoDataSources":true,"allowManualDataSources":false,"allowCodeDataSources":false}}
,
"__ogt_event_create":{"access_template_storage":{}}
,
"__ogt_google_signals":{"read_container_data":{}}
,
"__set_product_settings":{}


}



,"security_groups":{
"google":[
"__c"
,
"__ccd_auto_redact"
,
"__ccd_conversion_marking"
,
"__ccd_em_download"
,
"__ccd_em_outbound_click"
,
"__ccd_em_page_view"
,
"__ccd_em_scroll"
,
"__ccd_em_site_search"
,
"__ccd_em_video"
,
"__ccd_ga_ads_link"
,
"__ccd_ga_first"
,
"__ccd_ga_last"
,
"__ccd_ga_regscope"
,
"__e"
,
"__ogt_1p_data_v2"
,
"__ogt_event_create"
,
"__ogt_google_signals"
,
"__set_product_settings"

]


}



};




var ba,ca=function(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}},da=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a},ea=function(a){for(var b=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global],c=0;c<b.length;++c){var d=b[c];if(d&&d.Math==Math)return d}throw Error("Cannot find global object");
},fa=ea(this),ia=function(a,b){if(b)a:{for(var c=fa,d=a.split("."),e=0;e<d.length-1;e++){var f=d[e];if(!(f in c))break a;c=c[f]}var g=d[d.length-1],k=c[g],m=b(k);m!=k&&m!=null&&da(c,g,{configurable:!0,writable:!0,value:m})}};
ia("Symbol",function(a){if(a)return a;var b=function(f,g){this.j=f;da(this,"description",{configurable:!0,writable:!0,value:g})};b.prototype.toString=function(){return this.j};var c="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",d=0,e=function(f){if(this instanceof e)throw new TypeError("Symbol is not a constructor");return new b(c+(f||"")+"_"+d++,f)};return e});
ia("Symbol.iterator",function(a){if(a)return a;for(var b=Symbol("Symbol.iterator"),c="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),d=0;d<c.length;d++){var e=fa[c[d]];typeof e==="function"&&typeof e.prototype[b]!="function"&&da(e.prototype,b,{configurable:!0,writable:!0,value:function(){return ja(ca(this))}})}return b});
var ja=function(a){var b={next:a};b[Symbol.iterator]=function(){return this};return b},ka=function(a){return a.raw=a},na=function(a,b){a.raw=b;return a},oa=function(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:ca(a)};throw Error(String(a)+" is not an iterable or ArrayLike");},pa=function(a){for(var b,c=[];!(b=a.next()).done;)c.push(b.value);return c},qa=function(a){return a instanceof Array?a:pa(oa(a))},ra=
typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Object.prototype.hasOwnProperty.call(d,e)&&(a[e]=d[e])}return a};ia("Object.assign",function(a){return a||ra});var sa=typeof Object.create=="function"?Object.create:function(a){var b=function(){};b.prototype=a;return new b},ta;
if(typeof Object.setPrototypeOf=="function")ta=Object.setPrototypeOf;else{var ua;a:{var va={a:!0},wa={};try{wa.__proto__=va;ua=wa.a;break a}catch(a){}ua=!1}ta=ua?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}
var xa=ta,za=function(a,b){a.prototype=sa(b.prototype);a.prototype.constructor=a;if(xa)xa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.bo=b.prototype},Aa=function(){this.K=!1;this.D=null;this.xb=void 0;this.j=1;this.Ca=this.O=0;this.H=null},Ba=function(a){if(a.K)throw new TypeError("Generator is already running");a.K=!0};Aa.prototype.W=function(a){this.xb=a};
var Ca=function(a,b){a.H={Sj:b,mm:!0};a.j=a.O||a.Ca};Aa.prototype.return=function(a){this.H={return:a};this.j=this.Ca};
var Da=function(a,b){a.j=4;return{value:b}},Ea=function(a){a.O=0;var b=a.H.Sj;a.H=null;return b},Ga=function(a){this.j=new Aa;this.D=a},Ja=function(a,b){Ba(a.j);var c=a.j.D;if(c)return Ha(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.j.return);a.j.return(b);return Ia(a)},Ha=function(a,b,c,d){try{var e=b.call(a.j.D,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.j.K=!1,e;var f=e.value}catch(g){return a.j.D=null,Ca(a.j,
g),Ia(a)}a.j.D=null;d.call(a.j,f);return Ia(a)},Ia=function(a){for(;a.j.j;)try{var b=a.D(a.j);if(b)return a.j.K=!1,{value:b.value,done:!1}}catch(d){a.j.xb=void 0,Ca(a.j,d)}a.j.K=!1;if(a.j.H){var c=a.j.H;a.j.H=null;if(c.mm)throw c.Sj;return{value:c.return,done:!0}}return{value:void 0,done:!0}},Ka=function(a){this.next=function(b){var c;Ba(a.j);a.j.D?c=Ha(a,a.j.D.next,b,a.j.W):(a.j.W(b),c=Ia(a));return c};this.throw=function(b){var c;Ba(a.j);a.j.D?c=Ha(a,a.j.D["throw"],b,a.j.W):(Ca(a.j,b),c=Ia(a));
return c};this.return=function(b){return Ja(a,b)};this[Symbol.iterator]=function(){return this}},La=function(a){function b(d){return a.next(d)}function c(d){return a.throw(d)}new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}f(a.next())})},Ma=function(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b};/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Oa=this||self,Pa=function(a){return a};var Qa=function(a,b){this.type=a;this.data=b};var Ra=function(){this.j={};this.H={}};ba=Ra.prototype;ba.get=function(a){return this.j["dust."+a]};ba.set=function(a,b){a="dust."+a;this.H.hasOwnProperty(a)||(this.j[a]=b)};ba.Zh=function(a,b){this.set(a,b);this.H["dust."+a]=!0};ba.has=function(a){return this.j.hasOwnProperty("dust."+a)};ba.Hf=function(a){a="dust."+a;this.H.hasOwnProperty(a)||delete this.j[a]};var Ta=function(){};Ta.prototype.reset=function(){};var Ua=function(a,b){this.O=a;this.parent=b;this.j=this.D=void 0;this.K=!1;this.H=function(c,d,e){return c.apply(d,e)};this.values=new Ra};Ua.prototype.add=function(a,b){Va(this,a,b,!1)};var Va=function(a,b,c,d){a.K||(d?a.values.Zh(b,c):a.values.set(b,c))};Ua.prototype.set=function(a,b){this.K||(!this.values.has(a)&&this.parent&&this.parent.has(a)?this.parent.set(a,b):this.values.set(a,b))};Ua.prototype.get=function(a){return this.values.has(a)?this.values.get(a):this.parent?this.parent.get(a):void 0};
Ua.prototype.has=function(a){return!!this.values.has(a)||!(!this.parent||!this.parent.has(a))};var Wa=function(a){var b=new Ua(a.O,a);a.D&&(b.D=a.D);b.H=a.H;b.j=a.j;return b};Ua.prototype.sd=function(){return this.O};Ua.prototype.Ma=function(){this.K=!0};function Xa(a,b){for(var c,d=0;d<b.length&&!(c=Ya(a,b[d]),c instanceof Qa);d++);return c}function Ya(a,b){try{var c=a.get(String(b[0]));if(!c||typeof c.invoke!=="function")throw Error("Attempting to execute non-function "+b[0]+".");return c.invoke.apply(c,[a].concat(b.slice(1)))}catch(e){var d=a.D;d&&d(e,b.context?{id:b[0],line:b.context.line}:null);throw e;}};var Za=function(){this.D=new Ta;this.j=new Ua(this.D)};ba=Za.prototype;ba.sd=function(){return this.D};ba.execute=function(a){var b=Array.prototype.slice.call(arguments,0);return this.Xh(b)};ba.Xh=function(){for(var a,b=0;b<arguments.length;b++)a=Ya(this.j,arguments[b]);return a};ba.Xk=function(a){var b=Wa(this.j);b.j=a;for(var c,d=1;d<arguments.length;d++)c=Ya(b,arguments[d]);return c};ba.Ma=function(){this.j.Ma()};var $a=function(){Ra.call(this);this.D=!1};za($a,Ra);var ab=function(a,b){var c=[],d;for(d in a.j)if(a.j.hasOwnProperty(d))switch(d=d.substr(5),b){case 1:c.push(d);break;case 2:c.push(a.get(d));break;case 3:c.push([d,a.get(d)])}return c};$a.prototype.set=function(a,b){this.D||Ra.prototype.set.call(this,a,b)};$a.prototype.Zh=function(a,b){this.D||Ra.prototype.Zh.call(this,a,b)};$a.prototype.Hf=function(a){this.D||Ra.prototype.Hf.call(this,a)};$a.prototype.Ma=function(){this.D=!0};/*
 jQuery (c) 2005, 2012 jQuery Foundation, Inc. jquery.org/license.
*/
var cb=/\[object (Boolean|Number|String|Function|Array|Date|RegExp)\]/,db=function(a){if(a==null)return String(a);var b=cb.exec(Object.prototype.toString.call(Object(a)));return b?b[1].toLowerCase():"object"},eb=function(a,b){return Object.prototype.hasOwnProperty.call(Object(a),b)},fb=function(a){if(!a||db(a)!="object"||a.nodeType||a==a.window)return!1;try{if(a.constructor&&!eb(a,"constructor")&&!eb(a.constructor.prototype,"isPrototypeOf"))return!1}catch(c){return!1}for(var b in a);return b===void 0||
eb(a,b)},h=function(a,b){var c=b||(db(a)=="array"?[]:{}),d;for(d in a)if(eb(a,d)){var e=a[d];db(e)=="array"?(db(c[d])!="array"&&(c[d]=[]),c[d]=h(e,c[d])):fb(e)?(fb(c[d])||(c[d]={}),c[d]=h(e,c[d])):c[d]=e}return c};function gb(a){if(a==void 0||Array.isArray(a)||fb(a))return!0;switch(typeof a){case "boolean":case "number":case "string":case "function":return!0}return!1}function hb(a){return typeof a==="number"&&a>=0&&isFinite(a)&&a%1===0||typeof a==="string"&&a[0]!=="-"&&a===""+parseInt(a)};var ib=function(a){this.j=[];this.H=!1;this.D=new $a;a=a||[];for(var b in a)a.hasOwnProperty(b)&&(hb(b)?this.j[Number(b)]=a[Number(b)]:this.D.set(b,a[b]))};ba=ib.prototype;ba.toString=function(a){if(a&&a.indexOf(this)>=0)return"";for(var b=[],c=0;c<this.j.length;c++){var d=this.j[c];d===null||d===void 0?b.push(""):d instanceof ib?(a=a||[],a.push(this),b.push(d.toString(a)),a.pop()):b.push(String(d))}return b.join(",")};
ba.set=function(a,b){if(!this.H)if(a==="length"){if(!hb(b))throw Error("RangeError: Length property must be a valid integer.");this.j.length=Number(b)}else hb(a)?this.j[Number(a)]=b:this.D.set(a,b)};ba.get=function(a){return a==="length"?this.length():hb(a)?this.j[Number(a)]:this.D.get(a)};ba.length=function(){return this.j.length};ba.Qb=function(){for(var a=ab(this.D,1),b=0;b<this.j.length;b++)a.push(b+"");return new ib(a)};var jb=function(a,b){hb(b)?delete a.j[Number(b)]:a.D.Hf(b)};ba=ib.prototype;
ba.pop=function(){return this.j.pop()};ba.push=function(){return this.j.push.apply(this.j,Array.prototype.slice.call(arguments))};ba.shift=function(){return this.j.shift()};ba.splice=function(a,b){return new ib(this.j.splice.apply(this.j,arguments))};ba.unshift=function(){return this.j.unshift.apply(this.j,Array.prototype.slice.call(arguments))};ba.has=function(a){return hb(a)&&this.j.hasOwnProperty(a)||this.D.has(a)};ba.Ma=function(){this.H=!0;Object.freeze(this.j);this.D.Ma()};
function kb(a){for(var b=[],c=0;c<a.length();c++)a.has(c)&&(b[c]=a.get(c));return b};var lb=function(){$a.call(this)};za(lb,$a);lb.prototype.Qb=function(){return new ib(ab(this,1))};var mb=function(a){for(var b=ab(a,3),c=new ib,d=0;d<b.length;d++){var e=new ib(b[d]);c.push(e)}return c};function nb(){for(var a=ob,b={},c=0;c<a.length;++c)b[a[c]]=c;return b}function pb(){var a="ABCDEFGHIJKLMNOPQRSTUVWXYZ";a+=a.toLowerCase()+"0123456789-_";return a+"."}var ob,qb;function rb(a){ob=ob||pb();qb=qb||nb();for(var b=[],c=0;c<a.length;c+=3){var d=c+1<a.length,e=c+2<a.length,f=a.charCodeAt(c),g=d?a.charCodeAt(c+1):0,k=e?a.charCodeAt(c+2):0,m=f>>2,n=(f&3)<<4|g>>4,p=(g&15)<<2|k>>6,q=k&63;e||(q=64,d||(p=64));b.push(ob[m],ob[n],ob[p],ob[q])}return b.join("")}
function sb(a){function b(m){for(;d<a.length;){var n=a.charAt(d++),p=qb[n];if(p!=null)return p;if(!/^[\s\xa0]*$/.test(n))throw Error("Unknown base64 encoding at char: "+n);}return m}ob=ob||pb();qb=qb||nb();for(var c="",d=0;;){var e=b(-1),f=b(0),g=b(64),k=b(64);if(k===64&&e===-1)return c;c+=String.fromCharCode(e<<2|f>>4);g!==64&&(c+=String.fromCharCode(f<<4&240|g>>2),k!==64&&(c+=String.fromCharCode(g<<6&192|k)))}};var tb={};function ub(a,b){tb[a]=tb[a]||[];tb[a][b]=!0}function vb(a){var b=tb[a];if(!b||b.length===0)return"";for(var c=[],d=0,e=0;e<b.length;e++)e%8===0&&e>0&&(c.push(String.fromCharCode(d)),d=0),b[e]&&(d|=1<<e%8);d>0&&c.push(String.fromCharCode(d));return rb(c.join("")).replace(/\.+$/,"")}function wb(){for(var a=[],b=tb.fdr||[],c=0;c<b.length;c++)b[c]&&a.push(c);return a.length>0?a:void 0};var xb=[],yb={};function zb(a){return xb[a]===void 0?!1:xb[a]};function Ab(){}function Bb(a){return typeof a==="function"}function l(a){return typeof a==="string"}function Cb(a){return typeof a==="number"&&!isNaN(a)}function Db(a){return Array.isArray(a)?a:[a]}function Eb(a,b){if(a&&Array.isArray(a))for(var c=0;c<a.length;c++)if(a[c]&&b(a[c]))return a[c]}function Fb(a,b){if(!Cb(a)||!Cb(b)||a>b)a=0,b=2147483647;return Math.floor(Math.random()*(b-a+1)+a)}
function Gb(a,b){for(var c=new Hb,d=0;d<a.length;d++)c.set(a[d],!0);for(var e=0;e<b.length;e++)if(c.get(b[e]))return!0;return!1}function z(a,b){for(var c in a)Object.prototype.hasOwnProperty.call(a,c)&&b(c,a[c])}function Ib(a){return!!a&&(Object.prototype.toString.call(a)==="[object Arguments]"||Object.prototype.hasOwnProperty.call(a,"callee"))}function Jb(a){return Math.round(Number(a))||0}function Kb(a){return"false"===String(a).toLowerCase()?!1:!!a}
function Lb(a){var b=[];if(Array.isArray(a))for(var c=0;c<a.length;c++)b.push(String(a[c]));return b}function Mb(a){return a?a.replace(/^\s+|\s+$/g,""):""}function Nb(){return new Date(Date.now())}function Ob(){return Nb().getTime()}var Hb=function(){this.prefix="gtm.";this.values={}};Hb.prototype.set=function(a,b){this.values[this.prefix+a]=b};Hb.prototype.get=function(a){return this.values[this.prefix+a]};function Pb(a,b,c){return a&&a.hasOwnProperty(b)?a[b]:c}
function Qb(a){var b=a;return function(){if(b){var c=b;b=void 0;try{c()}catch(d){}}}}function Rb(a,b){for(var c in b)b.hasOwnProperty(c)&&(a[c]=b[c])}function Sb(a,b){for(var c=[],d=0;d<a.length;d++)c.push(a[d]),c.push.apply(c,b[a[d]]||[]);return c}function Tb(a,b){return a.length>=b.length&&a.substring(0,b.length)===b}function Ub(a,b){return a.length>=b.length&&a.substring(a.length-b.length,a.length)===b}
function Vb(a,b){var c=G;b=b||[];for(var d=c,e=0;e<a.length-1;e++){if(!d.hasOwnProperty(a[e]))return;d=d[a[e]];if(b.indexOf(d)>=0)return}return d}function Wb(a,b){for(var c={},d=c,e=a.split("."),f=0;f<e.length-1;f++)d=d[e[f]]={};d[e[e.length-1]]=b;return c}var Xb=/^\w{1,9}$/;function Yb(a,b){a=a||{};b=b||",";var c=[];z(a,function(d,e){Xb.test(d)&&e&&c.push(d)});return c.join(b)}function Zb(a,b){function c(){e&&++d===b&&(e(),e=null,c.done=!0)}var d=0,e=a;c.done=!1;return c}
function $b(a){if(!a)return a;var b=a;if(zb(3))try{b=decodeURIComponent(a)}catch(d){}var c=b.split(",");return c.length===2&&c[0]===c[1]?c[0]:a};var ac,bc=function(){if(ac===void 0){var a=null,b=Oa.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Pa,createScript:Pa,createScriptURL:Pa})}catch(c){Oa.console&&Oa.console.error(c.message)}ac=a}else ac=a}return ac};var cc=function(a){this.j=a};cc.prototype.toString=function(){return this.j+""};var dc=function(a){return a instanceof cc&&a.constructor===cc?a.j:"type_error:TrustedResourceUrl"},ec={},fc=function(a){var b=a,c=bc(),d=c?c.createScriptURL(b):b;return new cc(d,ec)};/*

 SPDX-License-Identifier: Apache-2.0
*/
var gc=ka([""]),hc=na(["\x00"],["\\0"]),ic=na(["\n"],["\\n"]),jc=na(["\x00"],["\\u0000"]);function kc(a){return a.toString().indexOf("`")===-1}kc(function(a){return a(gc)})||kc(function(a){return a(hc)})||kc(function(a){return a(ic)})||kc(function(a){return a(jc)});var lc=function(a){this.j=a};lc.prototype.toString=function(){return this.j};var mc=new lc("about:invalid#zClosurez");var nc=function(a){this.wm=a};function oc(a){return new nc(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}var pc=[oc("data"),oc("http"),oc("https"),oc("mailto"),oc("ftp"),new nc(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function qc(a,b){b=b===void 0?pc:b;if(a instanceof lc)return a;for(var c=0;c<b.length;++c){var d=b[c];if(d instanceof nc&&d.wm(a))return new lc(a)}}function rc(a){var b;b=b===void 0?pc:b;return qc(a,b)||mc}var sc=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function tc(a){var b;if(a instanceof lc)if(a instanceof lc)b=a.j;else throw Error("");else b=sc.test(a)?a:void 0;return b};var vc=function(){this.j=uc[0].toLowerCase()};vc.prototype.toString=function(){return this.j};var wc=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1};var xc={},yc=function(a){this.j=a};yc.prototype.toString=function(){return this.j.toString()};function zc(a,b){var c=[new vc];if(c.length===0)throw Error("");var d=c.map(function(f){var g;if(f instanceof vc)g=f.j;else throw Error("");return g}),e=b.toLowerCase();if(d.every(function(f){return e.indexOf(f)!==0}))throw Error('Attribute "'+b+'" does not match any of the allowed prefixes.');a.setAttribute(b,"true")};function Ac(a,b){var c=tc(b);c!==void 0&&(a.action=c)};"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function Bc(a){return a===null?"null":a===void 0?"undefined":a};var G=window,H=document,Cc=navigator,Dc=function(){var a;try{a=Cc.serviceWorker}catch(b){return}return a},Ec=H.currentScript,Fc=Ec&&Ec.src,Gc=function(a,b){var c=G[a];G[a]=c===void 0?b:c;return G[a]};function Hc(a){return(Cc.userAgent||"").indexOf(a)!==-1}var Ic={async:1,nonce:1,onerror:1,onload:1,src:1,type:1},Jc={onload:1,src:1,width:1,height:1,style:1};function Kc(a,b,c){b&&z(b,function(d,e){d=d.toLowerCase();c.hasOwnProperty(d)||a.setAttribute(d,e)})}
var Lc=function(a,b,c,d,e){var f=H.createElement("script");Kc(f,d,Ic);f.type="text/javascript";f.async=d&&d.async===!1?!1:!0;var g;g=fc(Bc(a));f.src=dc(g);var k,m,n,p=(n=(m=(f.ownerDocument&&f.ownerDocument.defaultView||window).document).querySelector)==null?void 0:n.call(m,"script[nonce]");(k=p?p.nonce||p.getAttribute("nonce")||"":"")&&f.setAttribute("nonce",k);b&&(f.onload=b);c&&(f.onerror=c);if(e)e.appendChild(f);else{var q=H.getElementsByTagName("script")[0]||H.body||H.head;q.parentNode.insertBefore(f,
q)}return f},Mc=function(){if(Fc){var a=Fc.toLowerCase();if(a.indexOf("https://")===0)return 2;if(a.indexOf("http://")===0)return 3}return 1},Nc=function(a,b,c,d,e){var f;f=f===void 0?!0:f;var g=e,k=!1;g||(g=H.createElement("iframe"),k=!0);Kc(g,c,Jc);d&&z(d,function(n,p){g.dataset[n]=p});f&&(g.height="0",g.width="0",g.style.display="none",g.style.visibility="hidden");a!==void 0&&(g.src=a);if(k){var m=H.body&&H.body.lastChild||H.body||H.head;m.parentNode.insertBefore(g,m)}b&&(g.onload=b);return g},
Oc=function(a,b,c,d){var e=new Image(1,1);Kc(e,d,{});e.onload=function(){e.onload=null;b&&b()};e.onerror=function(){e.onerror=null;c&&c()};e.src=a;return e},Pc=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,!!d):a.attachEvent&&a.attachEvent("on"+b,c)},Qc=function(a,b,c){a.removeEventListener?a.removeEventListener(b,c,!1):a.detachEvent&&a.detachEvent("on"+b,c)},I=function(a){G.setTimeout(a,0)},Rc=function(a,b){return a&&b&&a.attributes&&a.attributes[b]?a.attributes[b].value:null},Sc=function(a){function b(e){e&&
e!=" "&&(e=e.replace(/^[\s\xa0]+|[\s\xa0]+$/g,""));e&&e!=" "&&(e=e.replace(/^[\s\xa0]+|[\s\xa0]+$/g,""));e&&(e=e.replace(/(\xa0+|\s{2,}|\n|\r\t)/g," "));return e}var c=b(a.innerText||a.textContent||"");if(zb(10)){var d=b(a.textContent||"");ub("TAGGING",26);d!==c&&ub("TAGGING",25)}return c},Tc=function(a){var b=H.createElement("div"),c=b,d,e=Bc("A<div>"+a+"</div>"),f=bc(),g=f?f.createHTML(e):e;d=new yc(g,xc);if(c.nodeType===1){var k=c.tagName;if(k==="SCRIPT"||k==="STYLE")throw Error("");}c.innerHTML=
d instanceof yc&&d.constructor===yc?d.j:"type_error:SafeHtml";b=b.lastChild;for(var m=[];b.firstChild;)m.push(b.removeChild(b.firstChild));return m},Uc=function(a,b,c){c=c||100;for(var d={},e=0;e<b.length;e++)d[b[e]]=!0;for(var f=a,g=0;f&&g<=c;g++){if(d[String(f.tagName).toLowerCase()])return f;f=f.parentElement}return null},Vc=function(a){var b;try{b=Cc.sendBeacon&&Cc.sendBeacon(a)}catch(c){ub("TAGGING",15)}b||Oc(a)},Wc=function(a,b){try{return Cc.sendBeacon(a,b)}catch(c){ub("TAGGING",15)}return!1},
Xc={cache:"no-store",credentials:"include",keepalive:!0,method:"POST",mode:"no-cors",redirect:"follow"},Zc=function(a,b,c){if(Yc()){var d=Object.assign({},Xc);b&&(d.body=b);c&&(c.attributionReporting&&(d.attributionReporting=c.attributionReporting),c.browsingTopics&&(d.browsingTopics=c.browsingTopics));try{var e=G.fetch(a,d);e&&e.catch(Ab);return!0}catch(f){}}if(c&&c.noFallback)return!1;if(b)return Wc(a,b);Vc(a);return!0},Yc=function(){return typeof G.fetch==="function"},$c=function(a,b){var c=a[b];
c&&typeof c.animVal==="string"&&(c=c.animVal);return c},ad=function(){var a=G.performance;if(a&&Bb(a.now))return a.now()},bd=function(){return G.performance||void 0};function cd(a,b){return this.evaluate(a)&&this.evaluate(b)}function dd(a,b){return this.evaluate(a)===this.evaluate(b)}function ed(a,b){return this.evaluate(a)||this.evaluate(b)}function fd(a,b){a=this.evaluate(a);b=this.evaluate(b);return String(a).indexOf(String(b))>-1}function gd(a,b){var c=String(this.evaluate(a)),d=String(this.evaluate(b));return c.substring(0,d.length)===d}
function hd(a,b){a=this.evaluate(a);b=this.evaluate(b);switch(a){case "pageLocation":var c=G.location.href;b instanceof lb&&b.get("stripProtocol")&&(c=c.replace(/^https?:\/\//,""));return c}};var id=function(a,b){$a.call(this);this.bk=a;this.uh=b};za(id,$a);ba=id.prototype;ba.toString=function(){return this.bk};ba.getName=function(){return this.bk};ba.Qb=function(){return new ib(ab(this,1))};ba.invoke=function(a){return this.uh.apply(new jd(this,a),Array.prototype.slice.call(arguments,1))};ba.ib=function(a){try{return this.invoke.apply(this,Array.prototype.slice.call(arguments,0))}catch(b){}};var jd=function(a,b){this.uh=a;this.F=b};
jd.prototype.evaluate=function(a){var b=this.F;return Array.isArray(a)?Ya(b,a):a};jd.prototype.getName=function(){return this.uh.getName()};jd.prototype.sd=function(){return this.F.sd()};var kd=function(){this.map=new Map};kd.prototype.set=function(a,b){this.map.set(a,b)};kd.prototype.get=function(a){return this.map.get(a)};var ld=function(){this.keys=[];this.values=[]};ld.prototype.set=function(a,b){this.keys.push(a);this.values.push(b)};ld.prototype.get=function(a){var b=this.keys.indexOf(a);if(b>-1)return this.values[b]};function md(){try{return Map?new kd:new ld}catch(a){return new ld}};var nd=function(a){if(a instanceof nd)return a;if(gb(a))throw Error("Type of given value has an equivalent Pixie type.");this.value=a};nd.prototype.getValue=function(){return this.value};nd.prototype.toString=function(){return String(this.value)};var pd=function(a){$a.call(this);this.promise=a;this.set("then",od(this));this.set("catch",od(this,!0));this.set("finally",od(this,!1,!0))};za(pd,lb);var od=function(a,b,c){b=b===void 0?!1:b;c=c===void 0?!1:c;return new id("",function(d,e){b&&(e=d,d=void 0);c&&(e=d);d instanceof id||(d=void 0);e instanceof id||(e=void 0);var f=Wa(this.F),g=function(m){return function(n){return c?(m.invoke(f),a.promise):m.invoke(f,n)}},k=a.promise.then(d&&g(d),e&&g(e));return new pd(k)})};function J(a,b,c){var d=md(),e=function(g,k){for(var m=ab(g,1),n=0;n<m.length;n++)k[m[n]]=f(g.get(m[n]))},f=function(g){var k=d.get(g);if(k)return k;if(g instanceof ib){var m=[];d.set(g,m);for(var n=g.Qb(),p=0;p<n.length();p++)m[n.get(p)]=f(g.get(n.get(p)));return m}if(g instanceof pd)return g.promise;if(g instanceof lb){var q={};d.set(g,q);e(g,q);return q}if(g instanceof id){var r=function(){for(var u=Array.prototype.slice.call(arguments,0),v=0;v<u.length;v++)u[v]=qd(u[v],b,c);var w=new Ua(b?b.sd():
new Ta);b&&(w.j=b.j);return f(g.invoke.apply(g,[w].concat(u)))};d.set(g,r);e(g,r);return r}var t=!1;switch(c){case 1:t=!0;break;case 2:t=!1;break;case 3:t=!1;break;default:}if(g instanceof nd&&t)return g.getValue();switch(typeof g){case "boolean":case "number":case "string":case "undefined":return g;case "object":if(g===null)return null}};return f(a)}
function qd(a,b,c){var d=md(),e=function(g,k){for(var m in g)g.hasOwnProperty(m)&&k.set(m,f(g[m]))},f=function(g){var k=d.get(g);if(k)return k;if(Array.isArray(g)||Ib(g)){var m=new ib([]);d.set(g,m);for(var n in g)g.hasOwnProperty(n)&&m.set(n,f(g[n]));return m}if(fb(g)){var p=new lb;d.set(g,p);e(g,p);return p}if(typeof g==="function"){var q=new id("",function(){for(var x=Array.prototype.slice.call(arguments,0),y=0;y<x.length;y++)x[y]=J(this.evaluate(x[y]),b,c);return f((0,this.F.H)(g,g,x))});d.set(g,
q);e(g,q);return q}var v=typeof g;if(g===null||v==="string"||v==="number"||v==="boolean")return g;var w=!1;switch(c){case 1:w=
!0;break;case 2:w=!1;break;default:}if(g!==void 0&&w)return new nd(g)};return f(a)};function rd(){var a=!1;return a};var sd={supportedMethods:"concat every filter forEach hasOwnProperty indexOf join lastIndexOf map pop push reduce reduceRight reverse shift slice some sort splice unshift toString".split(" "),concat:function(a){for(var b=[],c=0;c<this.length();c++)b.push(this.get(c));for(var d=1;d<arguments.length;d++)if(arguments[d]instanceof ib)for(var e=arguments[d],f=0;f<e.length();f++)b.push(e.get(f));else b.push(arguments[d]);return new ib(b)},every:function(a,b){for(var c=this.length(),d=0;d<this.length()&&
d<c;d++)if(this.has(d)&&!b.invoke(a,this.get(d),d,this))return!1;return!0},filter:function(a,b){for(var c=this.length(),d=[],e=0;e<this.length()&&e<c;e++)this.has(e)&&b.invoke(a,this.get(e),e,this)&&d.push(this.get(e));return new ib(d)},forEach:function(a,b){for(var c=this.length(),d=0;d<this.length()&&d<c;d++)this.has(d)&&b.invoke(a,this.get(d),d,this)},hasOwnProperty:function(a,b){return this.has(b)},indexOf:function(a,b,c){var d=this.length(),e=c===void 0?0:Number(c);e<0&&(e=Math.max(d+e,0));for(var f=
e;f<d;f++)if(this.has(f)&&this.get(f)===b)return f;return-1},join:function(a,b){for(var c=[],d=0;d<this.length();d++)c.push(this.get(d));return c.join(b)},lastIndexOf:function(a,b,c){var d=this.length(),e=d-1;c!==void 0&&(e=c<0?d+c:Math.min(c,e));for(var f=e;f>=0;f--)if(this.has(f)&&this.get(f)===b)return f;return-1},map:function(a,b){for(var c=this.length(),d=[],e=0;e<this.length()&&e<c;e++)this.has(e)&&(d[e]=b.invoke(a,this.get(e),e,this));return new ib(d)},pop:function(){return this.pop()},push:function(a){return this.push.apply(this,
Array.prototype.slice.call(arguments,1))},reduce:function(a,b,c){var d=this.length(),e,f=0;if(c!==void 0)e=c;else{if(d===0)throw Error("TypeError: Reduce on List with no elements.");for(var g=0;g<d;g++)if(this.has(g)){e=this.get(g);f=g+1;break}if(g===d)throw Error("TypeError: Reduce on List with no elements.");}for(var k=f;k<d;k++)this.has(k)&&(e=b.invoke(a,e,this.get(k),k,this));return e},reduceRight:function(a,b,c){var d=this.length(),e,f=d-1;if(c!==void 0)e=c;else{if(d===0)throw Error("TypeError: ReduceRight on List with no elements.");
for(var g=1;g<=d;g++)if(this.has(d-g)){e=this.get(d-g);f=d-(g+1);break}if(g>d)throw Error("TypeError: ReduceRight on List with no elements.");}for(var k=f;k>=0;k--)this.has(k)&&(e=b.invoke(a,e,this.get(k),k,this));return e},reverse:function(){for(var a=kb(this),b=a.length-1,c=0;b>=0;b--,c++)a.hasOwnProperty(b)?this.set(c,a[b]):jb(this,c);return this},shift:function(){return this.shift()},slice:function(a,b,c){var d=this.length();b===void 0&&(b=0);b=b<0?Math.max(d+b,0):Math.min(b,d);c=c===void 0?d:
c<0?Math.max(d+c,0):Math.min(c,d);c=Math.max(b,c);for(var e=[],f=b;f<c;f++)e.push(this.get(f));return new ib(e)},some:function(a,b){for(var c=this.length(),d=0;d<this.length()&&d<c;d++)if(this.has(d)&&b.invoke(a,this.get(d),d,this))return!0;return!1},sort:function(a,b){var c=kb(this);b===void 0?c.sort():c.sort(function(e,f){return Number(b.invoke(a,e,f))});for(var d=0;d<c.length;d++)c.hasOwnProperty(d)?this.set(d,c[d]):jb(this,d);return this},splice:function(a,b,c){return this.splice.apply(this,Array.prototype.splice.call(arguments,
1,arguments.length-1))},toString:function(){return this.toString()},unshift:function(a){return this.unshift.apply(this,Array.prototype.slice.call(arguments,1))}};var td=function(a){var b;b=Error.call(this,a);this.message=b.message;"stack"in b&&(this.stack=b.stack)};za(td,Error);var wd={charAt:1,concat:1,indexOf:1,lastIndexOf:1,match:1,replace:1,search:1,slice:1,split:1,substring:1,toLowerCase:1,toLocaleLowerCase:1,toString:1,toUpperCase:1,toLocaleUpperCase:1,trim:1},xd=new Qa("break"),yd=new Qa("continue");function zd(a,b){return this.evaluate(a)+this.evaluate(b)}function Ad(a,b){return this.evaluate(a)&&this.evaluate(b)}
function Bd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);if(!(c instanceof ib))throw Error("Error: Non-List argument given to Apply instruction.");if(a===null||a===void 0){var d="TypeError: Can't read property "+b+" of "+a+".";if(rd())throw new td(d);throw Error(d);}var e=typeof a==="number";if(typeof a==="boolean"||e){if(b==="toString"){if(e&&c.length()){var f=J(c.get(0));try{return a.toString(f)}catch(y){}}return a.toString()}var g="TypeError: "+a+"."+b+" is not a function.";
if(rd())throw new td(g);throw Error(g);}if(typeof a==="string"){if(wd.hasOwnProperty(b)){var k=2;k=1;var m=J(c,void 0,k);return qd(a[b].apply(a,m),this.F)}var n="TypeError: "+b+" is not a function";if(rd())throw new td(n);throw Error(n);}if(a instanceof ib){if(a.has(b)){var p=a.get(b);if(p instanceof id){var q=kb(c);q.unshift(this.F);return p.invoke.apply(p,q)}var r=
"TypeError: "+b+" is not a function";if(rd())throw new td(r);throw Error(r);}if(sd.supportedMethods.indexOf(b)>=0){var t=kb(c);t.unshift(this.F);return sd[b].apply(a,t)}}if(a instanceof id||a instanceof lb){if(a.has(b)){var u=a.get(b);if(u instanceof id){var v=kb(c);v.unshift(this.F);return u.invoke.apply(u,v)}var w="TypeError: "+b+" is not a function";if(rd())throw new td(w);throw Error(w);}if(b==="toString")return a instanceof id?a.getName():a.toString();if(b==="hasOwnProperty")return a.has.apply(a,
kb(c))}if(a instanceof nd&&b==="toString")return a.toString();var x="TypeError: Object has no '"+b+"' property.";if(rd())throw new td(x);throw Error(x);}function Cd(a,b){a=this.evaluate(a);if(typeof a!=="string")throw Error("Invalid key name given for assignment.");var c=this.F;if(!c.has(a))throw Error("Attempting to assign to undefined value "+b);var d=this.evaluate(b);c.set(a,d);return d}function Dd(){var a=Wa(this.F),b=Xa(a,Array.prototype.slice.apply(arguments));if(b instanceof Qa)return b}
function Ed(){return xd}function Fd(a){for(var b=this.evaluate(a),c=0;c<b.length;c++){var d=this.evaluate(b[c]);if(d instanceof Qa)return d}}function Gd(){for(var a=this.F,b=0;b<arguments.length-1;b+=2){var c=arguments[b];if(typeof c==="string"){var d=this.evaluate(arguments[b+1]);Va(a,c,d,!0)}}}function Hd(){return yd}function Id(a,b){return new Qa(a,this.evaluate(b))}
function Jd(a,b){var c=new ib;b=this.evaluate(b);for(var d=0;d<b.length;d++)c.push(b[d]);var e=[51,a,c].concat(Array.prototype.splice.call(arguments,2,arguments.length-2));this.F.add(a,this.evaluate(e))}function Kd(a,b){return this.evaluate(a)/this.evaluate(b)}function Ld(a,b){a=this.evaluate(a);b=this.evaluate(b);var c=a instanceof nd,d=b instanceof nd;return c||d?c&&d?a.getValue()===b.getValue():!1:a==b}function Md(){for(var a,b=0;b<arguments.length;b++)a=this.evaluate(arguments[b]);return a}
function Nd(a,b,c,d){for(var e=0;e<b();e++){var f=a(c(e)),g=Xa(f,d);if(g instanceof Qa){if(g.type==="break")break;if(g.type==="return")return g}}}function Od(a,b,c){if(typeof b==="string")return Nd(a,function(){return b.length},function(f){return f},c);if(b instanceof lb||b instanceof ib||b instanceof id){var d=b.Qb(),e=d.length();return Nd(a,function(){return e},function(f){return d.get(f)},c)}}
function Pd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Od(function(e){d.set(a,e);return d},b,c)}function Qd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Od(function(e){var f=Wa(d);Va(f,a,e,!0);return f},b,c)}function Rd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Od(function(e){var f=Wa(d);f.add(a,e);return f},b,c)}
function Sd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Td(function(e){d.set(a,e);return d},b,c)}function Ud(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Td(function(e){var f=Wa(d);Va(f,a,e,!0);return f},b,c)}function Vd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Td(function(e){var f=Wa(d);f.add(a,e);return f},b,c)}
function Td(a,b,c){if(typeof b==="string")return Nd(a,function(){return b.length},function(d){return b[d]},c);if(b instanceof ib)return Nd(a,function(){return b.length()},function(d){return b.get(d)},c);if(rd())throw new td("The value is not iterable.");throw new TypeError("The value is not iterable.");}
function Wd(a,b,c,d){function e(p,q){for(var r=0;r<f.length();r++){var t=f.get(r);q.add(t,p.get(t))}}var f=this.evaluate(a);if(!(f instanceof ib))throw Error("TypeError: Non-List argument given to ForLet instruction.");var g=this.F;d=this.evaluate(d);var k=Wa(g);for(e(g,k);Ya(k,b);){var m=Xa(k,d);if(m instanceof Qa){if(m.type==="break")break;if(m.type==="return")return m}var n=Wa(g);e(k,n);Ya(n,c);k=n}}
function Xd(a,b){var c=this.F,d=this.evaluate(b);if(!(d instanceof ib))throw Error("Error: non-List value given for Fn argument names.");var e=Array.prototype.slice.call(arguments,2);return new id(a,function(){return function(f){var g=Wa(c);g.j===void 0&&(g.j=this.F.j);for(var k=Array.prototype.slice.call(arguments,0),m=0;m<k.length;m++)if(k[m]=this.evaluate(k[m]),k[m]instanceof Qa)return k[m];for(var n=d.get("length"),p=0;p<n;p++)p<k.length?g.add(d.get(p),k[p]):g.add(d.get(p),void 0);g.add("arguments",
new ib(k));var q=Xa(g,e);if(q instanceof Qa)return q.type==="return"?q.data:q}}())}function Yd(a){a=this.evaluate(a);var b=this.F;if(Zd&&!b.has(a))throw new ReferenceError(a+" is not defined.");return b.get(a)}
function $d(a,b){var c;a=this.evaluate(a);b=this.evaluate(b);if(a===void 0||a===null){var d="TypeError: Cannot read properties of "+a+" (reading '"+b+"')";if(rd())throw new td(d);throw Error(d);}if(a instanceof lb||a instanceof ib||a instanceof id)c=a.get(b);else if(typeof a==="string")b==="length"?c=a.length:hb(b)&&(c=a[b]);else if(a instanceof nd)return;return c}function ae(a,b){return this.evaluate(a)>this.evaluate(b)}function be(a,b){return this.evaluate(a)>=this.evaluate(b)}
function ce(a,b){a=this.evaluate(a);b=this.evaluate(b);a instanceof nd&&(a=a.getValue());b instanceof nd&&(b=b.getValue());return a===b}function de(a,b){return!ce.call(this,a,b)}function ee(a,b,c){var d=[];this.evaluate(a)?d=this.evaluate(b):c&&(d=this.evaluate(c));var e=Xa(this.F,d);if(e instanceof Qa)return e}var Zd=!1;
function fe(a,b){return this.evaluate(a)<this.evaluate(b)}function ge(a,b){return this.evaluate(a)<=this.evaluate(b)}function he(){for(var a=new ib,b=0;b<arguments.length;b++){var c=this.evaluate(arguments[b]);a.push(c)}return a}function ie(){for(var a=new lb,b=0;b<arguments.length-1;b+=2){var c=this.evaluate(arguments[b])+"",d=this.evaluate(arguments[b+1]);a.set(c,d)}return a}function je(a,b){return this.evaluate(a)%this.evaluate(b)}function ke(a,b){return this.evaluate(a)*this.evaluate(b)}
function le(a){return-this.evaluate(a)}function me(a){return!this.evaluate(a)}function ne(a,b){return!Ld.call(this,a,b)}function oe(){return null}function pe(a,b){return this.evaluate(a)||this.evaluate(b)}function qe(a,b){var c=this.evaluate(a);this.evaluate(b);return c}function re(a){return this.evaluate(a)}function se(){return Array.prototype.slice.apply(arguments)}function te(a){return new Qa("return",this.evaluate(a))}
function ue(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);if(a===null||a===void 0){var d="TypeError: Can't set property "+b+" of "+a+".";if(rd())throw new td(d);throw Error(d);}(a instanceof id||a instanceof ib||a instanceof lb)&&a.set(b,c);return c}function ve(a,b){return this.evaluate(a)-this.evaluate(b)}
function we(a,b,c){a=this.evaluate(a);var d=this.evaluate(b),e=this.evaluate(c);if(!Array.isArray(d)||!Array.isArray(e))throw Error("Error: Malformed switch instruction.");for(var f,g=!1,k=0;k<d.length;k++)if(g||a===this.evaluate(d[k]))if(f=this.evaluate(e[k]),f instanceof Qa){var m=f.type;if(m==="break")return;if(m==="return"||m==="continue")return f}else g=!0;if(e.length===d.length+1&&(f=this.evaluate(e[e.length-1]),f instanceof Qa&&(f.type==="return"||f.type==="continue")))return f}
function xe(a,b,c){return this.evaluate(a)?this.evaluate(b):this.evaluate(c)}function ye(a){a=this.evaluate(a);return a instanceof id?"function":typeof a}function ze(){for(var a=this.F,b=0;b<arguments.length;b++){var c=arguments[b];typeof c!=="string"||a.add(c,void 0)}}
function Ae(a,b,c,d){var e=this.evaluate(d);if(this.evaluate(c)){var f=Xa(this.F,e);if(f instanceof Qa){if(f.type==="break")return;if(f.type==="return")return f}}for(;this.evaluate(a);){var g=Xa(this.F,e);if(g instanceof Qa){if(g.type==="break")break;if(g.type==="return")return g}this.evaluate(b)}}function Be(a){return~Number(this.evaluate(a))}function Ce(a,b){return Number(this.evaluate(a))<<Number(this.evaluate(b))}function De(a,b){return Number(this.evaluate(a))>>Number(this.evaluate(b))}
function Ee(a,b){return Number(this.evaluate(a))>>>Number(this.evaluate(b))}function Fe(a,b){return Number(this.evaluate(a))&Number(this.evaluate(b))}function Ge(a,b){return Number(this.evaluate(a))^Number(this.evaluate(b))}function He(a,b){return Number(this.evaluate(a))|Number(this.evaluate(b))}function Ie(){}
function Je(a,b,c,d,e){var f=!0;try{var g=this.evaluate(c);if(g instanceof Qa)return g}catch(r){if(!(r instanceof td&&a))throw f=r instanceof td,r;var k=Wa(this.F),m=new nd(r);k.add(b,m);var n=this.evaluate(d),p=Xa(k,n);if(p instanceof Qa)return p}finally{if(f&&e!==void 0){var q=this.evaluate(e);if(q instanceof Qa)return q}}};var Le=function(){this.j=new Za;Ke(this)};Le.prototype.execute=function(a){return this.j.Xh(a)};var Ke=function(a){var b=function(c,d){var e=new id(String(c),d);e.Ma();a.j.j.set(String(c),e)};b("map",ie);b("and",cd);b("contains",fd);b("equals",dd);b("or",ed);b("startsWith",gd);b("variable",hd)};var Pe=function(){this.D=!1;this.j=new Za;Me(this);this.D=!0};Pe.prototype.execute=function(a){return Qe(this.j.Xh(a))};var Re=function(a,b,c){return Qe(a.j.Xk(b,c))};Pe.prototype.Ma=function(){this.j.Ma()};
var Me=function(a){var b=function(c,d){var e=String(c),f=new id(e,d);f.Ma();a.j.j.set(e,f)};b(0,zd);b(1,Ad);b(2,Bd);b(3,Cd);b(56,Fe);b(57,Ce);b(58,Be);b(59,He);b(60,De);b(61,Ee);b(62,Ge);b(53,Dd);b(4,Ed);b(5,Fd);b(52,Gd);b(6,Hd);b(49,Id);b(7,he);b(8,ie);b(9,Fd);b(50,Jd);b(10,Kd);b(12,Ld);b(13,Md);b(51,Xd);b(47,Pd);b(54,Qd);b(55,Rd);b(63,Wd);b(64,Sd);b(65,Ud);b(66,Vd);b(15,Yd);b(16,$d);b(17,$d);b(18,ae);b(19,be);b(20,ce);b(21,de);b(22,ee);b(23,fe);b(24,ge);b(25,je);b(26,ke);b(27,le);b(28,me);b(29,
ne);b(45,oe);b(30,pe);b(32,qe);b(33,qe);b(34,re);b(35,re);b(46,se);b(36,te);b(43,ue);b(37,ve);b(38,we);b(39,xe);b(67,Je);b(40,ye);b(44,Ie);b(41,ze);b(42,Ae)};Pe.prototype.sd=function(){return this.j.sd()};function Qe(a){if(a instanceof Qa||a instanceof id||a instanceof ib||a instanceof lb||a instanceof nd||a===null||a===void 0||typeof a==="string"||typeof a==="number"||typeof a==="boolean")return a};var Se=function(a){this.message=a};function Te(a){var b="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[a];return b===void 0?new Se("Value "+a+" can not be encoded in web-safe base64 dictionary."):b};function Ue(a){switch(a){case 1:return"1";case 2:case 4:return"0";default:return"-"}};var Ve=/^[1-9a-zA-Z_-][1-9a-c][1-9a-v]\d$/;function We(a,b){for(var c="",d=!0;a>7;){var e=a&31;a>>=5;d?d=!1:e|=32;c=""+Te(e)+c}a<<=2;d||(a|=32);return c=""+Te(a|b)+c};var Xe=function(){function a(b){return{toString:function(){return b}}}return{Bk:a("consent"),ki:a("convert_case_to"),li:a("convert_false_to"),mi:a("convert_null_to"),ni:a("convert_true_to"),oi:a("convert_undefined_to"),wn:a("debug_mode_metadata"),oa:a("function"),Wg:a("instance_name"),al:a("live_only"),bl:a("malware_disabled"),fl:a("metadata"),kl:a("original_activity_id"),Gn:a("original_vendor_template_id"),En:a("once_on_load"),jl:a("once_per_event"),xj:a("once_per_load"),In:a("priority_override"),
Jn:a("respected_consent_types"),Fj:a("setup_tags"),ve:a("tag_id"),Lj:a("teardown_tags")}}();var tf;var uf=[],vf=[],wf=[],xf=[],yf=[],zf={},Af,Bf;function Cf(a){Bf=Bf||a}
function Df(a){}var Ef,Ff=[],Gf=[];function Hf(a,b){var c={};c[Xe.oa]="__"+a;for(var d in b)b.hasOwnProperty(d)&&(c["vtp_"+d]=b[d]);return c}
function If(a,b,c){try{return Af(Jf(a,b,c))}catch(d){JSON.stringify(a)}return 2}function Kf(a){var b=a[Xe.oa];if(!b)throw Error("Error: No function name given for function call.");return!!zf[b]}
var Jf=function(a,b,c){c=c||[];var d={},e;for(e in a)a.hasOwnProperty(e)&&(d[e]=Lf(a[e],b,c));return d},Lf=function(a,b,c){if(Array.isArray(a)){var d;switch(a[0]){case "function_id":return a[1];case "list":d=[];for(var e=1;e<a.length;e++)d.push(Lf(a[e],b,c));return d;case "macro":var f=a[1];if(c[f])return;var g=uf[f];if(!g||b.isBlocked(g))return;c[f]=!0;var k=String(g[Xe.Wg]);try{var m=Jf(g,b,c);m.vtp_gtmEventId=b.id;b.priorityId&&(m.vtp_gtmPriorityId=b.priorityId);d=Mf(m,{event:b,index:f,type:2,
name:k});Ef&&(d=Ef.Bl(d,m))}catch(y){b.logMacroError&&b.logMacroError(y,Number(f),k),d=!1}c[f]=!1;return d;case "map":d={};for(var n=1;n<a.length;n+=2)d[Lf(a[n],b,c)]=Lf(a[n+1],b,c);return d;case "template":d=[];for(var p=!1,q=1;q<a.length;q++){var r=Lf(a[q],b,c);Bf&&(p=p||Bf.qm(r));d.push(r)}return Bf&&p?Bf.El(d):d.join("");case "escape":d=Lf(a[1],b,c);if(Bf&&Array.isArray(a[1])&&a[1][0]==="macro"&&Bf.sm(a))return Bf.Nm(d);d=String(d);for(var t=2;t<a.length;t++)Ye[a[t]]&&(d=Ye[a[t]](d));return d;
case "tag":var u=a[1];if(!xf[u])throw Error("Unable to resolve tag reference "+u+".");return{Tj:a[2],index:u};case "zb":var v={arg0:a[2],arg1:a[3],ignore_case:a[5]};v[Xe.oa]=a[1];var w=If(v,b,c),x=!!a[4];return x||w!==2?x!==(w===1):null;default:throw Error("Attempting to expand unknown Value type: "+a[0]+".");}}return a},Mf=function(a,b){var c=a[Xe.oa],d=b&&b.event;if(!c)throw Error("Error: No function name given for function call.");var e=zf[c],f=b&&b.type===2&&(d==null?void 0:d.reportMacroDiscrepancy)&&
e&&Ff.indexOf(c)!==-1,g={},k={},m;for(m in a)a.hasOwnProperty(m)&&Tb(m,"vtp_")&&(e&&(g[m]=a[m]),!e||f)&&(k[m.substring(4)]=a[m]);e&&d&&d.cachedModelValues&&(g.vtp_gtmCachedValues=d.cachedModelValues);if(b){if(b.name==null){var n;a:{var p=b.type,q=b.index;if(q==null)n="";else{var r;switch(p){case 2:r=uf[q];break;case 1:r=xf[q];break;default:n="";break a}var t=r&&r[Xe.Wg];n=t?String(t):""}}b.name=n}e&&(g.vtp_gtmEntityIndex=b.index,g.vtp_gtmEntityName=b.name)}var u,v,w;if(f&&Gf.indexOf(c)===-1){Gf.push(c);
var x=Ob();u=e(g);var y=Ob()-x,B=Ob();v=tf(c,k,b);w=y-(Ob()-B)}else if(e&&(u=e(g)),!e||f)v=tf(c,k,b);f&&d&&(d.reportMacroDiscrepancy(d.id,c,void 0,!0),gb(u)?(Array.isArray(u)?Array.isArray(v):fb(u)?fb(v):typeof u==="function"?typeof v==="function":u===v)||d.reportMacroDiscrepancy(d.id,c):u!==v&&d.reportMacroDiscrepancy(d.id,c),w!==void 0&&d.reportMacroDiscrepancy(d.id,c,w));return e?u:v};var Nf=function(a,b,c){var d;d=Error.call(this,c);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.permissionId=a;this.parameters=b;this.name="PermissionError"};za(Nf,Error);function Of(a,b){if(Array.isArray(a)){Object.defineProperty(a,"context",{value:{line:b[0]}});for(var c=1;c<a.length;c++)Of(a[c],b[c])}};var Pf=function(a,b){var c;c=Error.call(this,"Wrapped error for Dust debugging. Original error message: "+a.message);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.Hm=a;this.j=[];this.D=b};za(Pf,Error);function Qf(){return function(a,b){a instanceof Pf||(a=new Pf(a,Rf));b&&a instanceof Pf&&a.j.push(b);throw a;}}function Rf(a){if(!a.length)return a;a.push({id:"main",line:0});for(var b=a.length-1;b>0;b--)Cb(a[b].id)&&a.splice(b++,1);for(var c=a.length-1;c>0;c--)a[c].line=a[c-1].line;a.splice(0,1);return a};function Sf(a){function b(r){for(var t=0;t<r.length;t++)d[r[t]]=!0}for(var c=[],d=[],e=Tf(a),f=0;f<vf.length;f++){var g=vf[f],k=Uf(g,e);if(k){for(var m=g.add||[],n=0;n<m.length;n++)c[m[n]]=!0;b(g.block||[])}else k===null&&b(g.block||[]);}for(var p=[],q=0;q<xf.length;q++)c[q]&&!d[q]&&(p[q]=!0);return p}
function Uf(a,b){for(var c=a["if"]||[],d=0;d<c.length;d++){var e=b(c[d]);if(e===0)return!1;if(e===2)return null}for(var f=a.unless||[],g=0;g<f.length;g++){var k=b(f[g]);if(k===2)return null;if(k===1)return!1}return!0}function Tf(a){var b=[];return function(c){b[c]===void 0&&(b[c]=If(wf[c],a));return b[c]}};var Vf={Bl:function(a,b){b[Xe.ki]&&typeof a==="string"&&(a=b[Xe.ki]===1?a.toLowerCase():a.toUpperCase());b.hasOwnProperty(Xe.mi)&&a===null&&(a=b[Xe.mi]);b.hasOwnProperty(Xe.oi)&&a===void 0&&(a=b[Xe.oi]);b.hasOwnProperty(Xe.ni)&&a===!0&&(a=b[Xe.ni]);b.hasOwnProperty(Xe.li)&&a===!1&&(a=b[Xe.li]);return a}};var Wf=function(){this.j={}},Yf=function(a,b){var c=Xf.D,d;(d=c.j)[a]!=null||(d[a]=[]);c.j[a].push(function(){return b.apply(null,qa(Ma.apply(0,arguments)))})};function Zf(a,b,c,d){if(a)for(var e=0;e<a.length;e++){var f=void 0,g="A policy function denied the permission request";try{f=a[e](b,c,d),g+="."}catch(k){g=typeof k==="string"?g+(": "+k):k instanceof Error?g+(": "+k.message):g+"."}if(!f)throw new Nf(c,d,g);}}
function $f(a,b,c){return function(){var d=arguments[0];if(d){var e=a.j[d],f=a.j.all;if(e||f){var g=c.apply(void 0,Array.prototype.slice.call(arguments,0));Zf(e,b,d,g);Zf(f,b,d,g)}}}};var dg=function(){var a=data.permissions||{},b=ag.ctid,c=this;this.j={};this.D=new Wf;var d={},e={},f=$f(this.D,b,function(){var g=arguments[0];return g&&d[g]?d[g].apply(void 0,Array.prototype.slice.call(arguments,0)):{}});z(a,function(g,k){function m(p){var q=Ma.apply(1,arguments);if(!n[p])throw bg(p,{},"The requested additional permission "+p+" is not configured.");f.apply(null,[p].concat(qa(q)))}var n={};z(k,function(p,q){var r=cg(p,q);n[p]=r.assert;d[p]||(d[p]=r.N);r.Oj&&!e[p]&&(e[p]=r.Oj)});
c.j[g]=function(p,q){var r=n[p];if(!r)throw bg(p,{},"The requested permission "+p+" is not configured.");var t=Array.prototype.slice.call(arguments,0);r.apply(void 0,t);f.apply(void 0,t);var u=e[p];u&&u.apply(null,[m].concat(qa(t.slice(1))))}})},eg=function(a){return Xf.j[a]||function(){}};
function cg(a,b){var c=Hf(a,b);c.vtp_permissionName=a;c.vtp_createPermissionError=bg;try{return Mf(c)}catch(d){return{assert:function(e){throw new Nf(e,{},"Permission "+e+" is unknown.");},N:function(){throw new Nf(a,{},"Permission "+a+" is unknown.");}}}}function bg(a,b,c){return new Nf(a,b,c)};var fg=!1;var gg={};gg.tk=Kb('');gg.Hl=Kb('');
var kg=function(a){var b={},c=0;z(a,function(e,f){if(f!=null){var g=(""+f).replace(/~/g,"~~");if(hg.hasOwnProperty(e))b[hg[e]]=g;else if(ig.hasOwnProperty(e)){var k=ig[e];b.hasOwnProperty(k)||(b[k]=g)}else if(e==="category")for(var m=g.split("/",5),n=0;n<m.length;n++){var p=b,q=jg[n],r=m[n];p.hasOwnProperty(q)||(p[q]=r)}else if(c<27){var t=String.fromCharCode(c<10?48+c:65+c-10);b["k"+t]=(""+String(e)).replace(/~/g,"~~");b["v"+t]=g;c++}}});var d=[];z(b,function(e,f){d.push(""+e+f)});return d.join("~")},
hg={item_id:"id",item_name:"nm",item_brand:"br",item_category:"ca",item_category2:"c2",item_category3:"c3",item_category4:"c4",item_category5:"c5",item_variant:"va",price:"pr",quantity:"qt",coupon:"cp",item_list_name:"ln",index:"lp",item_list_id:"li",discount:"ds",affiliation:"af",promotion_id:"pi",promotion_name:"pn",creative_name:"cn",creative_slot:"cs",location_id:"lo"},ig={id:"id",name:"nm",brand:"br",variant:"va",list_name:"ln",list_position:"lp",list:"ln",position:"lp",creative:"cn"},jg=["ca",
"c2","c3","c4","c5"];
var lg=function(){this.events=[];this.j="";this.ja={};this.baseUrl="";this.H=0;this.K=this.D=!1;};lg.prototype.add=function(a){return this.O(a)?(this.events.push(a),this.j=a.D,this.ja=a.ja,this.baseUrl=a.baseUrl,this.H+=a.K,this.D=a.H,!0):!1};lg.prototype.O=function(a){return this.events.length?this.events.length>=20||a.K+this.H>=16384?!1:this.baseUrl===
a.baseUrl&&this.D===a.H&&this.W(a):!0};lg.prototype.W=function(a){var b=this;if(!this.K)return this.j===a.D;var c=Object.keys(this.ja);return c.length===Object.keys(a.ja).length&&c.every(function(d){return a.ja.hasOwnProperty(d)&&String(b.ja[d])===String(a.ja[d])})};var mg={},ng=(mg.uaa=!0,mg.uab=!0,mg.uafvl=!0,mg.uamb=!0,mg.uam=!0,mg.uap=!0,mg.uapv=!0,mg.uaw=!0,mg);
var qg=function(a,b){var c=a.events;if(c.length===1)return og(c[0],b);var d=[];a.j&&d.push(a.j);for(var e={},f=0;f<c.length;f++)z(c[f].Mc,function(t,u){u!=null&&(e[t]=e[t]||{},e[t][String(u)]=e[t][String(u)]+1||1)});var g={};z(e,function(t,u){var v,w=-1,x=0;z(u,function(y,B){x+=B;var A=(y.length+t.length+2)*(B-1);A>w&&(v=y,w=A)});x===c.length&&(g[t]=v)});pg(g,d);b&&d.push("_s="+b);for(var k=d.join("&"),m=[],n={},p=0;p<c.length;n={Kh:void 0},p++){var q=[];n.Kh={};z(c[p].Mc,function(t){return function(u,
v){g[u]!==""+v&&(t.Kh[u]=v)}}(n));c[p].j&&q.push(c[p].j);pg(n.Kh,q);m.push(q.join("&"))}var r=m.join("\r\n");return{params:k,body:r}},og=function(a,b){var c=[];a.D&&c.push(a.D);b&&c.push("_s="+b);pg(a.Mc,c);var d=!1;a.j&&(c.push(a.j),d=!0);var e=c.join("&"),f="",g=e.length+a.baseUrl.length+1;d&&g>2048&&(f=c.pop(),e=c.join("&"));return{params:e,body:f}},pg=function(a,b){z(a,function(c,d){d!=null&&b.push(encodeURIComponent(c)+"="+encodeURIComponent(d))})};var rg=function(a){var b=[];z(a,function(c,d){d!=null&&b.push(encodeURIComponent(c)+"="+encodeURIComponent(String(d)))});return b.join("&")},sg=function(a,b,c,d,e){this.baseUrl=b;this.endpoint=c;this.ja=a.ja;this.Mc=a.Mc;this.sh=a.sh;this.H=d;this.D=rg(a.ja);this.j=rg(a.sh);this.K=this.j.length;if(e&&this.K>16384)throw Error("EVENT_TOO_LARGE");};
var vg=function(a,b){for(var c=0;c<b.length;c++){var d=a,e=b[c];if(!tg.exec(e))throw Error("Invalid key wildcard");var f=e.indexOf(".*"),g=f!==-1&&f===e.length-2,k=g?e.slice(0,e.length-2):e,m;a:if(d.length===0)m=!1;else{for(var n=d.split("."),p=0;p<n.length;p++)if(!ug.exec(n[p])){m=!1;break a}m=!0}if(!m||k.length>d.length||!g&&d.length!==e.length?0:g?Tb(d,k)&&(d===k||d.charAt(k.length)==="."):d===k)return!0}return!1},ug=/^[a-z$_][\w$]*$/i,tg=/^(?:[a-z_$][a-z_$0-9]*\.)*[a-z_$][a-z_$0-9]*(?:\.\*)?$/i;
var wg=["matches","webkitMatchesSelector","mozMatchesSelector","msMatchesSelector","oMatchesSelector"];function xg(a,b){var c=String(a),d=String(b),e=c.length-d.length;return e>=0&&c.indexOf(d,e)===e}var yg=new Hb;function zg(a,b,c){var d=c?"i":void 0;try{var e=String(b)+String(d),f=yg.get(e);f||(f=new RegExp(b,d),yg.set(e,f));return f.test(a)}catch(g){return!1}}function Ag(a,b){return String(a).indexOf(String(b))>=0}function Bg(a,b){return String(a)===String(b)}
function Cg(a,b){return Number(a)>=Number(b)}function Dg(a,b){return Number(a)<=Number(b)}function Eg(a,b){return Number(a)>Number(b)}function Fg(a,b){return Number(a)<Number(b)}function Gg(a,b){return Tb(String(a),String(b))};var Ng=/^([a-z][a-z0-9]*):(!|\?)(\*|string|boolean|number|Fn|PixieMap|List|OpaqueValue)$/i,Og={Fn:"function",PixieMap:"Object",List:"Array"};
function K(a,b,c){for(var d=0;d<b.length;d++){var e=Ng.exec(b[d]);if(!e)throw Error("Internal Error in "+a);var f=e[1],g=e[2]==="!",k=e[3],m=c[d];if(m==null){if(g)throw Error("Error in "+a+". Required argument "+f+" not supplied.");}else if(k!=="*"){var n=typeof m;m instanceof id?n="Fn":m instanceof ib?n="List":m instanceof lb?n="PixieMap":m instanceof nd&&(n="OpaqueValue");if(n!==k)throw Error("Error in "+a+". Argument "+f+" has type "+((Og[n]||n)+", which does not match required type ")+((Og[k]||
k)+"."));}}};function Pg(a){return""+a}
function Qg(a,b){var c=[];return c};function Rg(a,b){var c=new id(a,function(){for(var d=Array.prototype.slice.call(arguments,0),e=0;e<d.length;e++)d[e]=this.evaluate(d[e]);try{return b.apply(this,d)}catch(g){if(rd())throw new td(g.message);throw g;}});c.Ma();return c}
function Sg(a,b){var c=new lb,d;for(d in b)if(b.hasOwnProperty(d)){var e=b[d];Bb(e)?c.set(d,Rg(a+"_"+d,e)):fb(e)?c.set(d,Sg(a+"_"+d,e)):(Cb(e)||l(e)||typeof e==="boolean")&&c.set(d,e)}c.Ma();return c};function Tg(a,b){K(this.getName(),["apiName:!string","message:?string"],arguments);var c={},d=new lb;return d=Sg("AssertApiSubject",c)};function Ug(a,b){K(this.getName(),["actual:?*","message:?string"],arguments);if(a instanceof pd)throw Error("Argument actual cannot have type Promise. Assertions on asynchronous code aren't supported.");var c={},d=new lb;return d=Sg("AssertThatSubject",c)};function Vg(a){return function(){for(var b=[],c=this.F,d=0;d<arguments.length;++d)b.push(J(arguments[d],c));return qd(a.apply(null,b))}}function Wg(){for(var a=Math,b=Xg,c={},d=0;d<b.length;d++){var e=b[d];a.hasOwnProperty(e)&&(c[e]=Vg(a[e].bind(a)))}return c};function Yg(a){var b;return b};function Zg(a){var b;K(this.getName(),["uri:!string"],arguments);try{b=decodeURIComponent(a)}catch(c){}return b};function $g(a){try{return encodeURI(a)}catch(b){}};function ah(a){try{return encodeURIComponent(a)}catch(b){}};
var bh=function(a,b){for(var c=0;c<b.length;c++){if(a===void 0)return;a=a[b[c]]}return a},ch=function(a,b){var c=b.preHit;if(c){var d=a[0];switch(d){case "hitData":return a.length<2?void 0:bh(c.getHitData(a[1]),a.slice(2));case "metadata":return a.length<2?void 0:bh(c.getMetadata(a[1]),a.slice(2));case "eventName":return c.getEventName();case "destinationId":return c.getDestinationId();default:throw Error(d+" is not a valid field that can be accessed\n                      from PreHit data.");}}},
eh=function(a,b){if(a){if(a.contextValue!==void 0){var c;a:{var d=a.contextValue,e=d.keyParts;if(e&&e.length!==0){var f=d.namespaceType;switch(f){case 1:c=ch(e,b);break a;case 2:var g=b.macro;c=g?g[e[0]]:void 0;break a;default:throw Error("Unknown Namespace Type used: "+f);}}c=void 0}return c}if(a.booleanExpressionValue!==void 0)return dh(a.booleanExpressionValue,b);if(a.booleanValue!==void 0)return!!a.booleanValue;if(a.stringValue!==void 0)return String(a.stringValue);if(a.integerValue!==void 0)return Number(a.integerValue);
if(a.doubleValue!==void 0)return Number(a.doubleValue);throw Error("Unknown field used for variable of type ExpressionValue:"+a);}},dh=function(a,b){var c=a.args;if(!Array.isArray(c)||c.length===0)throw Error('Invalid boolean expression format. Expected "args":'+c+" property to\n         be non-empty array.");var d=function(g){return eh(g,b)};switch(a.type){case 1:for(var e=0;e<c.length;e++)if(d(c[e]))return!0;return!1;case 2:for(var f=0;f<c.length;f++)if(!d(c[f]))return!1;return c.length>0;case 3:return!d(c[0]);
case 4:return zg(d(c[0]),d(c[1]),!1);case 5:return Bg(d(c[0]),d(c[1]));case 6:return Gg(d(c[0]),d(c[1]));case 7:return xg(d(c[0]),d(c[1]));case 8:return Ag(d(c[0]),d(c[1]));case 9:return Fg(d(c[0]),d(c[1]));case 10:return Dg(d(c[0]),d(c[1]));case 11:return Eg(d(c[0]),d(c[1]));case 12:return Cg(d(c[0]),d(c[1]));default:throw Error('Invalid boolean expression format. Expected "type" property tobe a positive integer which is less than 13.');}};function fh(a){K(this.getName(),["message:?string"],arguments);};function gh(a,b){K(this.getName(),["min:!number","max:!number"],arguments);return Fb(a,b)};function hh(){return(new Date).getTime()};function ih(a){if(a===null)return"null";if(a instanceof ib)return"array";if(a instanceof id)return"function";if(a instanceof nd){var b;a=(b=a)==null?void 0:b.getValue();var c;if(((c=a)==null?void 0:c.constructor)===void 0||a.constructor.name===void 0){var d=String(a);return d.substring(8,d.length-1)}return String(a.constructor.name)}return typeof a};function jh(a){function b(c){return function(d){try{return c(d)}catch(e){(fg||gg.tk)&&a.call(this,e.message)}}}return{parse:b(function(c){return qd(JSON.parse(c))}),stringify:b(function(c){return JSON.stringify(J(c))})}};function kh(a){return Jb(J(a,this.F))};function lh(a){return Number(J(a,this.F))};function mh(a){return a===null?"null":a===void 0?"undefined":a.toString()};function nh(a,b,c){var d=null,e=!1;return e?d:null};var Xg="floor ceil round max min abs pow sqrt".split(" ");function oh(){var a={};return{Rl:function(b){return a.hasOwnProperty(b)?a[b]:void 0},qk:function(b,c){a[b]=c},reset:function(){a={}}}}function ph(a,b){return function(){var c=Array.prototype.slice.call(Ma.apply(0,arguments),0);c.unshift(b);return id.prototype.invoke.apply(a,c)}}
function qh(a,b){K(this.getName(),["apiName:!string","mock:?*"],arguments);}
function rh(a,b){K(this.getName(),["apiName:!string","mock:!PixieMap"],arguments);};var sh={};var th=function(a){var b=new lb;if(a instanceof ib)for(var c=a.Qb(),d=0;d<c.length();d++){var e=c.get(d);a.has(e)&&b.set(e,a.get(e))}else if(a instanceof id)for(var f=ab(a,1),g=0;g<f.length;g++){var k=f[g];b.set(k,a.get(k))}else for(var m=0;m<a.length;m++)b.set(m,a[m]);return b};
sh.keys=function(a){K(this.getName(),["input:!*"],arguments);if(a instanceof ib||a instanceof id||typeof a==="string")a=th(a);if(a instanceof lb)return a.Qb();return new ib};
sh.values=function(a){K(this.getName(),["input:!*"],arguments);if(a instanceof ib||a instanceof id||typeof a==="string")a=th(a);if(a instanceof lb)return new ib(ab(a,2));return new ib};
sh.entries=function(a){K(this.getName(),["input:!*"],arguments);if(a instanceof ib||a instanceof id||typeof a==="string")a=th(a);if(a instanceof lb)return mb(a);return new ib};sh.freeze=function(a){(a instanceof lb||a instanceof ib||a instanceof id)&&a.Ma();return a};
sh.delete=function(a,b){if(a instanceof lb&&!a.D)return a.Hf(b),!0;return!1};function N(a,b){var c=Ma.apply(2,arguments),d=a.F.j;if(!d)throw Error("Missing program state.");if(d.Tm){try{d.Pj.apply(null,[b].concat(qa(c)))}catch(e){throw ub("TAGGING",21),e;}return}d.Pj.apply(null,[b].concat(qa(c)))};var uh=function(){this.j={};this.D={};this.H=!0;};uh.prototype.get=function(a,b){var c=this.j.hasOwnProperty(a)?this.j[a]:void 0;return c};
uh.prototype.add=function(a,b,c){if(this.j.hasOwnProperty(a))throw Error("Attempting to add a function which already exists: "+a+".");if(this.D.hasOwnProperty(a))throw Error("Attempting to add an API with an existing private API name: "+a+".");this.j[a]=c?void 0:Bb(b)?Rg(a,b):Sg(a,b)};function vh(a,b){var c=void 0;return c};function wh(){var a={};
return a};function xh(a){return yh?H.querySelectorAll(a):null}
function zh(a,b){if(!yh)return null;if(Element.prototype.closest)try{return a.closest(b)}catch(e){return null}var c=Element.prototype.matches||Element.prototype.webkitMatchesSelector||Element.prototype.mozMatchesSelector||Element.prototype.msMatchesSelector||Element.prototype.oMatchesSelector,d=a;if(!H.documentElement.contains(d))return null;do{try{if(c.call(d,b))return d}catch(e){break}d=d.parentElement||d.parentNode}while(d!==null&&d.nodeType===1);return null}var Ah=!1;
if(H.querySelectorAll)try{var Bh=H.querySelectorAll(":root");Bh&&Bh.length==1&&Bh[0]==H.documentElement&&(Ah=!0)}catch(a){}var yh=Ah;var Ch=/^[0-9A-Fa-f]{64}$/;function Dh(a){try{return(new TextEncoder).encode(a)}catch(e){for(var b=[],c=0;c<a.length;c++){var d=a.charCodeAt(c);d<128?b.push(d):d<2048?b.push(192|d>>6,128|d&63):d<55296||d>=57344?b.push(224|d>>12,128|d>>6&63,128|d&63):(d=65536+((d&1023)<<10|a.charCodeAt(++c)&1023),b.push(240|d>>18,128|d>>12&63,128|d>>6&63,128|d&63))}return new Uint8Array(b)}}
function Eh(a){if(a===""||a==="e0")return Promise.resolve(a);var b;if((b=G.crypto)==null?0:b.subtle){if(Ch.test(a))return Promise.resolve(a);try{var c=Dh(a);return G.crypto.subtle.digest("SHA-256",c).then(function(d){var e=Array.from(new Uint8Array(d)).map(function(f){return String.fromCharCode(f)}).join("");return G.btoa(e).replace(/\+/g,"-").replace(/\//g,"_").replace(/=+$/,"")}).catch(function(){return"e2"})}catch(d){return Promise.resolve("e2")}}else return Promise.resolve("e1")};function O(a){ub("GTM",a)};
var Ih=function(a){var b={},c=["tv.1"],d=0;var u=c.join("~");return{ai:{userData:b},
kn:u,sn:d}},Kh=function(a){if(G.Promise)try{return new Promise(function(b){Jh(a,function(c,d){b({dk:c,We:d})})})}catch(b){}},Lh=function(a){for(var b=["tv.1"],c=0,d=0;d<a.length;++d){var e=a[d].name,f=a[d].value,g=a[d].index,k=Fh[e];k&&f&&(Gh.indexOf(e)===-1||/^e\d+$/.test(f)||Hh.test(f)||Ch.test(f))&&(g!==void 0&&(k+=g),b.push(k+"."+f),c++)}a.length===1&&a[0].name==="error_code"&&(c=0);return{ek:encodeURIComponent(b.join("~")),We:c}},Jh=function(a,b){Mh(a,function(c){var d=Lh(c);b(d.ek,d.We)})},
Uh=function(a){function b(r,t,u,v){var w=Nh(r);w!==""&&(Ch.test(w)?k.push({name:t,value:w,index:v}):k.push({name:t,value:u(w),index:v}))}function c(r,t){var u=r;if(l(u)||Array.isArray(u)){u=Db(r);for(var v=0;v<u.length;++v){var w=Nh(u[v]),x=Ch.test(w);t&&!x&&O(89);!t&&x&&O(88)}}}function d(r,t){var u=r[t];c(u,!1);var v=Oh[t];r[v]&&(r[t]&&O(90),u=r[v],c(u,!0));return u}function e(r,t,u){for(var v=Db(d(r,t)),w=0;w<v.length;++w)b(v[w],t,u)}function f(r,t,u,v){var w=d(r,t);b(w,t,u,v)}function g(r){return function(t){O(64);
return r(t)}}var k=[];if(G.location.protocol!=="https:")return k.push({name:"error_code",value:"e3",index:void 0}),k;e(a,"email",Ph);e(a,"phone_number",Qh);e(a,"first_name",g(Rh));e(a,"last_name",g(Rh));var m=a.home_address||{};e(m,"street",g(Sh));e(m,"city",g(Sh));e(m,"postal_code",g(Th));e(m,"region",g(Sh));e(m,"country",g(Th));for(var n=Db(a.address||{}),p=0;p<n.length;p++){var q=n[p];f(q,"first_name",Rh,p);f(q,"last_name",Rh,p);f(q,"street",Sh,p);f(q,"city",Sh,p);f(q,"postal_code",Th,p);f(q,"region",
Sh,p);f(q,"country",Th,p)}return k},Mh=function(a,b){var c=Uh(a);Vh(c,b)},Nh=function(a){return a==null?"":l(a)?Mb(String(a)):"e0"},Th=function(a){return a.replace(Wh,"")},Rh=function(a){return Sh(a.replace(/\s/g,""))},Sh=function(a){return Mb(a.replace(Xh,"").toLowerCase())},Qh=function(a){a=a.replace(/[\s-()/.]/g,"");a.charAt(0)!=="+"&&(a="+"+a);return Yh.test(a)?a:"e0"},Ph=function(a){var b=a.toLowerCase().split("@");if(b.length===2){var c=b[0];/^(gmail|googlemail)\./.test(b[1])&&(c=c.replace(/\./g,
""));c=c+"@"+b[1];if(Zh.test(c))return c}return"e0"},Vh=function(a,b){a.some(function(c){c.value&&Gh.indexOf(c.name)})?b(a):G.Promise?Promise.all(a.map(function(c){return c.value&&Gh.indexOf(c.name)!==-1?Eh(c.value).then(function(d){c.value=d}):Promise.resolve()})).then(function(){b(a)}).catch(function(){b([])}):b([])},Xh=/[0-9`~!@#$%^&*()_\-+=:;<>,.?|/\\[\]]/g,Zh=/^\S+@\S+\.\S+$/,Yh=/^\+\d{10,15}$/,Wh=/[.~]/g,Hh=/^[0-9A-Za-z_-]{43}$/,$h={},Fh=($h.email="em",$h.phone_number="pn",$h.first_name="fn",
$h.last_name="ln",$h.street="sa",$h.city="ct",$h.region="rg",$h.country="co",$h.postal_code="pc",$h.error_code="ec",$h),ai={},Oh=(ai.email="sha256_email_address",ai.phone_number="sha256_phone_number",ai.first_name="sha256_first_name",ai.last_name="sha256_last_name",ai.street="sha256_street",ai),Gh=Object.freeze(["email","phone_number","first_name","last_name","street"]);var P={g:{ya:"ad_personalization",R:"ad_storage",P:"ad_user_data",U:"analytics_storage",Fb:"region",Tb:"consent_updated",cf:"wait_for_update",si:"app_remove",ui:"app_store_refund",vi:"app_store_subscription_cancel",wi:"app_store_subscription_convert",xi:"app_store_subscription_renew",Ek:"consent_update",hg:"add_payment_info",ig:"add_shipping_info",oc:"add_to_cart",qc:"remove_from_cart",jg:"view_cart",Ub:"begin_checkout",rc:"select_item",kb:"view_item_list",Gb:"select_promotion",lb:"view_promotion",
Ja:"purchase",sc:"refund",Oa:"view_item",kg:"add_to_wishlist",Fk:"exception",yi:"first_open",zi:"first_visit",ba:"gtag.config",Ua:"gtag.get",Ai:"in_app_purchase",Vb:"page_view",Gk:"screen_view",Bi:"session_start",Hk:"timing_complete",Ik:"track_social",Nc:"user_engagement",Jk:"user_id_update",nb:"gclgb",Va:"gclid",Ci:"gclgs",Di:"gclst",fa:"ads_data_redaction",Ei:"gad_source",Fi:"gad_source_src",Gd:"gclid_url",Gi:"gclsrc",lg:"gbraid",df:"wbraid",ka:"allow_ad_personalization_signals",ef:"allow_custom_scripts",
Hd:"allow_direct_google_requests",ff:"allow_display_features",Id:"allow_enhanced_conversions",ob:"allow_google_signals",Ea:"allow_interest_groups",Kk:"app_id",Lk:"app_installer_id",Mk:"app_name",Nk:"app_version",Hb:"auid",Hi:"auto_detection_enabled",Wb:"aw_remarketing",hf:"aw_remarketing_only",Jd:"discount",Kd:"aw_feed_country",Ld:"aw_feed_language",da:"items",Md:"aw_merchant_id",mg:"aw_basket_type",Oc:"campaign_content",Pc:"campaign_id",Qc:"campaign_medium",Rc:"campaign_name",Sc:"campaign",Tc:"campaign_source",
Uc:"campaign_term",pb:"client_id",Ii:"rnd",ng:"consent_update_type",Ji:"content_group",Ki:"content_type",Za:"conversion_cookie_prefix",Vc:"conversion_id",ra:"conversion_linker",Li:"conversion_linker_disabled",Xb:"conversion_api",jf:"cookie_deprecation",Wa:"cookie_domain",Pa:"cookie_expires",ab:"cookie_flags",uc:"cookie_name",Ib:"cookie_path",Qa:"cookie_prefix",vc:"cookie_update",wc:"country",za:"currency",Nd:"customer_lifetime_value",Wc:"custom_map",og:"gcldc",Od:"dclid",Mi:"debug_mode",la:"developer_id",
Ni:"disable_merchant_reported_purchases",Xc:"dc_custom_params",Oi:"dc_natural_search",pg:"dynamic_event_settings",qg:"affiliation",Pd:"checkout_option",kf:"checkout_step",rg:"coupon",Yc:"item_list_name",lf:"list_name",Pi:"promotions",Zc:"shipping",nf:"tax",Qd:"engagement_time_msec",Rd:"enhanced_client_id",Sd:"enhanced_conversions",sg:"enhanced_conversions_automatic_settings",Td:"estimated_delivery_date",pf:"euid_logged_in_state",bd:"event_callback",Ok:"event_category",rb:"event_developer_id_string",
Pk:"event_label",xc:"event",Ud:"event_settings",Vd:"event_timeout",Qk:"description",Rk:"fatal",Qi:"experiments",qf:"firebase_id",yc:"first_party_collection",Wd:"_x_20",sb:"_x_19",Ri:"fledge_drop_reason",ug:"fledge",vg:"flight_error_code",wg:"flight_error_message",Si:"fl_activity_category",Ti:"fl_activity_group",xg:"fl_advertiser_id",Ui:"fl_ar_dedupe",yg:"match_id",Vi:"fl_random_number",Wi:"tran",Xi:"u",Xd:"gac_gclid",zc:"gac_wbraid",zg:"gac_wbraid_multiple_conversions",Ag:"ga_restrict_domain",Bg:"ga_temp_client_id",
Ac:"gdpr_applies",Cg:"geo_granularity",Jb:"value_callback",tb:"value_key",Bc:"_google_ng",Yb:"google_signals",Dg:"google_tld",Yd:"groups",Eg:"gsa_experiment_id",Yi:"gtm_up",Kb:"iframe_state",dd:"ignore_referrer",rf:"internal_traffic_results",Zb:"is_legacy_converted",Lb:"is_legacy_loaded",Zd:"is_passthrough",ed:"_lps",Ra:"language",ae:"legacy_developer_id_string",sa:"linker",Cc:"accept_incoming",vb:"decorate_forms",X:"domains",Mb:"url_position",Fg:"method",Sk:"name",fd:"new_customer",Gg:"non_interaction",
Zi:"optimize_id",aj:"page_hostname",gd:"page_path",Fa:"page_referrer",cb:"page_title",Hg:"passengers",Ig:"phone_conversion_callback",bj:"phone_conversion_country_code",Jg:"phone_conversion_css_class",cj:"phone_conversion_ids",Kg:"phone_conversion_number",Lg:"phone_conversion_options",Mg:"_protected_audience_enabled",hd:"quantity",be:"redact_device_info",tf:"referral_exclusion_definition",ac:"restricted_data_processing",dj:"retoken",Tk:"sample_rate",uf:"screen_name",Nb:"screen_resolution",ej:"search_term",
Ka:"send_page_view",bc:"send_to",jd:"server_container_url",kd:"session_duration",de:"session_engaged",vf:"session_engaged_time",wb:"session_id",ee:"session_number",wf:"_shared_user_id",ld:"delivery_postal_code",Uk:"temporary_client_id",xf:"topmost_url",fj:"tracking_id",yf:"traffic_type",Aa:"transaction_id",Ob:"transport_url",Ng:"trip_type",fc:"update",Xa:"url_passthrough",zf:"_user_agent_architecture",Af:"_user_agent_bitness",Bf:"_user_agent_full_version_list",Cf:"_user_agent_mobile",Df:"_user_agent_model",
Ef:"_user_agent_platform",Ff:"_user_agent_platform_version",Gf:"_user_agent_wow64",Ga:"user_data",Og:"user_data_auto_latency",Pg:"user_data_auto_meta",Qg:"user_data_auto_multi",Rg:"user_data_auto_selectors",Sg:"user_data_auto_status",md:"user_data_mode",fe:"user_data_settings",Ba:"user_id",eb:"user_properties",gj:"_user_region",he:"us_privacy_string",na:"value",Tg:"wbraid_multiple_conversions",ke:"_fpm_parameters",pj:"_host_name",qj:"_in_page_command",rj:"_is_passthrough_cid",Pb:"non_personalized_ads",
te:"_sst_parameters",qb:"conversion_label",wa:"page_location",ub:"global_developer_id_string",Dc:"tc_privacy_string"}},bi={},ci=Object.freeze((bi[P.g.ka]=1,bi[P.g.ff]=1,bi[P.g.Id]=1,bi[P.g.ob]=1,bi[P.g.da]=1,bi[P.g.Wa]=1,bi[P.g.Pa]=1,bi[P.g.ab]=1,bi[P.g.uc]=1,bi[P.g.Ib]=1,bi[P.g.Qa]=1,bi[P.g.vc]=1,bi[P.g.Wc]=1,bi[P.g.la]=1,bi[P.g.pg]=1,bi[P.g.bd]=1,bi[P.g.Ud]=1,bi[P.g.Vd]=1,bi[P.g.yc]=1,bi[P.g.Ag]=1,bi[P.g.Yb]=1,bi[P.g.Dg]=1,bi[P.g.Yd]=1,bi[P.g.rf]=1,bi[P.g.Zb]=1,bi[P.g.Lb]=1,bi[P.g.sa]=1,bi[P.g.tf]=
1,bi[P.g.ac]=1,bi[P.g.Ka]=1,bi[P.g.bc]=1,bi[P.g.jd]=1,bi[P.g.kd]=1,bi[P.g.vf]=1,bi[P.g.ld]=1,bi[P.g.Ob]=1,bi[P.g.fc]=1,bi[P.g.fe]=1,bi[P.g.eb]=1,bi[P.g.te]=1,bi));Object.freeze([P.g.wa,P.g.Fa,P.g.cb,P.g.Ra,P.g.uf,P.g.Ba,P.g.qf,P.g.Ji]);
var di={},ei=Object.freeze((di[P.g.si]=1,di[P.g.ui]=1,di[P.g.vi]=1,di[P.g.wi]=1,di[P.g.xi]=1,di[P.g.yi]=1,di[P.g.zi]=1,di[P.g.Ai]=1,di[P.g.Bi]=1,di[P.g.Nc]=1,di)),fi={},gi=Object.freeze((fi[P.g.hg]=1,fi[P.g.ig]=1,fi[P.g.oc]=1,fi[P.g.qc]=1,fi[P.g.jg]=1,fi[P.g.Ub]=1,fi[P.g.rc]=1,fi[P.g.kb]=1,fi[P.g.Gb]=1,fi[P.g.lb]=1,fi[P.g.Ja]=1,fi[P.g.sc]=1,fi[P.g.Oa]=1,fi[P.g.kg]=1,fi)),hi=Object.freeze([P.g.ka,P.g.Hd,P.g.ob,P.g.vc,P.g.yc,P.g.dd,P.g.Ka,P.g.fc]),ii=Object.freeze([].concat(qa(hi))),ji=Object.freeze([P.g.Pa,
P.g.Vd,P.g.kd,P.g.vf,P.g.Qd]),ki=Object.freeze([].concat(qa(ji))),li={},mi=(li[P.g.R]="1",li[P.g.U]="2",li[P.g.P]="3",li[P.g.ya]="4",li),ni={},oi=Object.freeze((ni[P.g.ka]=1,ni[P.g.Hd]=1,ni[P.g.Id]=1,ni[P.g.Ea]=1,ni[P.g.Wb]=1,ni[P.g.hf]=1,ni[P.g.Jd]=1,ni[P.g.Kd]=1,ni[P.g.Ld]=1,ni[P.g.da]=1,ni[P.g.Md]=1,ni[P.g.Za]=1,ni[P.g.ra]=1,ni[P.g.Wa]=1,ni[P.g.Pa]=1,ni[P.g.ab]=1,ni[P.g.Qa]=1,ni[P.g.za]=1,ni[P.g.Nd]=1,ni[P.g.la]=1,ni[P.g.Ni]=1,ni[P.g.Sd]=1,ni[P.g.Td]=1,ni[P.g.qf]=1,ni[P.g.yc]=1,ni[P.g.Zb]=1,ni[P.g.Lb]=
1,ni[P.g.Ra]=1,ni[P.g.fd]=1,ni[P.g.wa]=1,ni[P.g.Fa]=1,ni[P.g.Ig]=1,ni[P.g.Jg]=1,ni[P.g.Kg]=1,ni[P.g.Lg]=1,ni[P.g.ac]=1,ni[P.g.Ka]=1,ni[P.g.bc]=1,ni[P.g.jd]=1,ni[P.g.ld]=1,ni[P.g.Aa]=1,ni[P.g.Ob]=1,ni[P.g.fc]=1,ni[P.g.Xa]=1,ni[P.g.Ga]=1,ni[P.g.Ba]=1,ni[P.g.na]=1,ni)),pi={},qi=Object.freeze((pi.search="s",pi.youtube="y",pi.playstore="p",pi.shopping="h",pi.ads="a",pi.maps="m",pi));Object.freeze(P.g);function ri(a,b){if(a==="")return b;var c=Number(a);return isNaN(c)?b:c};var si=[];function ti(a){switch(a){case 0:return 0;case 42:return 1;case 43:return 2;case 44:return 11;case 50:return 3;case 58:return 4;case 66:return 7;case 75:return 5;case 86:return 6;case 87:return 10;case 89:return 8;case 90:return 9}}function Q(a){si[a]=!0;var b=ti(a);b!==void 0&&(xb[b]=!0)}
Q(30);
Q(26);Q(27);Q(28);Q(29);Q(45);Q(70);Q(54);Q(67);
Q(33);Q(15);Q(95);Q(14);
Q(100);Q(94);
Q(59);Q(76);Q(6);
Q(46);Q(4);Q(73);Q(91);Q(65);Q(63);Q(64);Q(74);
Q(104);Q(101);Q(75);Q(5);Q(86);
yb[1]=ri('1',6E4);yb[3]=ri('10',1);yb[2]=ri('',50);Q(23);Q(11);Q(62);
Q(92);

Q(51);Q(22);
Q(41);Q(77);Q(89);
Q(87);Q(79);Q(48);
Q(60);function T(a){return!!si[a]}var ui={},vi=G.google_tag_manager=G.google_tag_manager||{};ui.Yg="48e0";ui.se=Number("0")||0;ui.jb="dataLayer";ui.vn="ChAI8M72tQYQxcf4oZGJlqVqEiUAQXVlUHeqiMRy5/3gnNf/GDVKCkYhKe4k0O54zvG18h8T9aZBGgI4yw\x3d\x3d";var wi={__cl:1,__ecl:1,__ehl:1,__evl:1,__fal:1,__fil:1,__fsl:1,__hl:1,__jel:1,__lcl:1,__sdl:1,__tl:1,__ytl:1},xi={__paused:1,__tg:1},yi;for(yi in wi)wi.hasOwnProperty(yi)&&(xi[yi]=1);var zi=Kb(""),Ai=!1,Bi,Ci=!1;Ci=!0;
Bi=Ci;var Di,Ei=!1;Di=Ei;var Fi,Gi=!1;Fi=Gi;ui.Fd="www.googletagmanager.com";var Hi=""+ui.Fd+(Bi?"/gtag/js":"/gtm.js"),Ii=null,Ji=null,Ki={},Li={};function Mi(){var a=vi.sequence||1;vi.sequence=a+1;return a}ui.Ck="true";var Ni="";ui.Zg=Ni;var Oi=new function(){this.j="";this.H=!1;this.D=0;this.Ca=this.O=this.W=this.K=""};function Pi(){var a=Oi.K.length;return Oi.K[a-1]==="/"?Oi.K.substring(0,a-1):Oi.K}function Qi(){return Oi.H&&Oi.D!==1}function Ri(a){for(var b={},c=oa(a.split("|")),d=c.next();!d.done;d=c.next())b[d.value]=!0;return b}var Si=new Hb,Ti={},Ui={},Xi={name:ui.jb,set:function(a,b){h(Wb(a,b),Ti);Vi()},get:function(a){return Wi(a,2)},reset:function(){Si=new Hb;Ti={};Vi()}};function Wi(a,b){return b!=2?Si.get(a):Yi(a)}function Yi(a,b){var c=a.split(".");b=b||[];for(var d=Ti,e=0;e<c.length;e++){if(d===null)return!1;if(d===void 0)break;d=d[c[e]];if(b.indexOf(d)!==-1)return}return d}function Zi(a,b){Ui.hasOwnProperty(a)||(Si.set(a,b),h(Wb(a,b),Ti),Vi())}
function $i(){for(var a=["gtm.allowlist","gtm.blocklist","gtm.whitelist","gtm.blacklist","tagTypeBlacklist"],b=0;b<a.length;b++){var c=a[b],d=Wi(c,1);if(Array.isArray(d)||fb(d))d=h(d);Ui[c]=d}}function Vi(a){z(Ui,function(b,c){Si.set(b,c);h(Wb(b),Ti);h(Wb(b,c),Ti);a&&delete Ui[b]})}function aj(a,b){var c,d=(b===void 0?2:b)!==1?Yi(a):Si.get(a);db(d)==="array"||db(d)==="object"?c=h(d):c=d;return c};
var bj=function(a,b,c){if(!c)return!1;var d=c.selector_type,e=String(c.value),f;if(d==="js_variable"){e=e.replace(/\["?'?/g,".").replace(/"?'?\]/g,"");for(var g=e.split(","),k=0;k<g.length;k++){var m=g[k].trim();if(m){if(Tb(m,"dataLayer."))f=Wi(m.substring(10));else{var n=m.split(".");f=G[n.shift()];for(var p=0;p<n.length;p++)f=f&&f[n[p]]}if(f!==void 0)break}}}else if(d==="css_selector"&&yh)try{var q=xh(e);if(q&&q.length>0){f=[];for(var r=0;r<q.length&&r<(b==="email"||b==="phone_number"?5:1);r++)f.push(Sc(q[r])||
Mb(q[r].value));f=f.length===1?f[0]:f}}catch(t){O(149)}return f?(a[b]=f,!0):!1},cj=function(a){if(a){var b={},c=!1;c=bj(b,"email",a.email)||c;c=bj(b,"phone_number",a.phone)||c;b.address=[];for(var d=a.name_and_address||[],e=0;e<d.length;e++){var f={};c=bj(f,"first_name",d[e].first_name)||c;c=bj(f,"last_name",d[e].last_name)||c;c=bj(f,"street",d[e].street)||c;c=bj(f,"city",d[e].city)||c;c=bj(f,"region",d[e].region)||c;c=bj(f,"country",d[e].country)||c;c=bj(f,"postal_code",d[e].postal_code)||c;b.address.push(f)}return c?
b:void 0}},dj=function(a){return fb(a)?!!a.enable_code:!1};var ej=/:[0-9]+$/,fj=/^\d+\.fls\.doubleclick\.net$/;function gj(a,b,c,d){for(var e=[],f=oa(a.split("&")),g=f.next();!g.done;g=f.next()){var k=oa(g.value.split("=")),m=k.next().value,n=pa(k);if(decodeURIComponent(m.replace(/\+/g," "))===b){var p=n.join("=");if(!c)return d?p:decodeURIComponent(p.replace(/\+/g," "));e.push(d?p:decodeURIComponent(p.replace(/\+/g," ")))}}return c?e:void 0}
function hj(a,b,c,d,e){b&&(b=String(b).toLowerCase());if(b==="protocol"||b==="port")a.protocol=ij(a.protocol)||ij(G.location.protocol);b==="port"?a.port=String(Number(a.hostname?a.port:G.location.port)||(a.protocol==="http"?80:a.protocol==="https"?443:"")):b==="host"&&(a.hostname=(a.hostname||G.location.hostname).replace(ej,"").toLowerCase());return jj(a,b,c,d,e)}
function jj(a,b,c,d,e){var f,g=ij(a.protocol);b&&(b=String(b).toLowerCase());switch(b){case "url_no_fragment":f=kj(a);break;case "protocol":f=g;break;case "host":f=a.hostname.replace(ej,"").toLowerCase();if(c){var k=/^www\d*\./.exec(f);k&&k[0]&&(f=f.substring(k[0].length))}break;case "port":f=String(Number(a.port)||(g==="http"?80:g==="https"?443:""));break;case "path":a.pathname||a.hostname||ub("TAGGING",1);f=a.pathname.substring(0,1)==="/"?a.pathname:"/"+a.pathname;var m=f.split("/");(d||[]).indexOf(m[m.length-
1])>=0&&(m[m.length-1]="");f=m.join("/");break;case "query":f=a.search.replace("?","");e&&(f=gj(f,e,!1));break;case "extension":var n=a.pathname.split(".");f=n.length>1?n[n.length-1]:"";f=f.split("/")[0];break;case "fragment":f=a.hash.replace("#","");break;default:f=a&&a.href}return f}function ij(a){return a?a.replace(":","").toLowerCase():""}function kj(a){var b="";if(a&&a.href){var c=a.href.indexOf("#");b=c<0?a.href:a.href.substring(0,c)}return b}var lj={},mj=0;
function nj(a){var b=lj[a];if(!b){var c=H.createElement("a");a&&(c.href=a);var d=c.pathname;d[0]!=="/"&&(a||ub("TAGGING",1),d="/"+d);var e=c.hostname.replace(ej,"");b={href:c.href,protocol:c.protocol,host:c.host,hostname:e,pathname:d,search:c.search,hash:c.hash,port:c.port};mj<5&&(lj[a]=b,mj++)}return b}
function oj(a){function b(n){var p=n.split("=")[0];return d.indexOf(p)<0?n:p+"=0"}function c(n){return n.split("&").map(b).filter(function(p){return p!==void 0}).join("&")}var d="gclid dclid gbraid wbraid gclaw gcldc gclha gclgf gclgb _gl".split(" "),e=nj(a),f=a.split(/[?#]/)[0],g=e.search,k=e.hash;g[0]==="?"&&(g=g.substring(1));k[0]==="#"&&(k=k.substring(1));g=c(g);k=c(k);g!==""&&(g="?"+g);k!==""&&(k="#"+k);var m=""+f+g+k;m[m.length-1]==="/"&&(m=m.substring(0,m.length-1));return m}
function pj(a){var b=nj(G.location.href),c=hj(b,"host",!1);if(c&&c.match(fj)){var d=hj(b,"path");if(d){var e=d.split(a+"=");if(e.length>1)return e[1].split(";")[0].split("?")[0]}}};var qj={"https://www.google.com":"/g","https://www.googleadservices.com":"/as","https://pagead2.googlesyndication.com":"/gs"};function rj(a,b){if(a){var c=""+a;c.indexOf("http://")!==0&&c.indexOf("https://")!==0&&(c="https://"+c);c[c.length-1]==="/"&&(c=c.substring(0,c.length-1));return nj(""+c+b).href}}function sj(a,b){if(Qi()||Di)return rj(a,b)}function tj(){return!!ui.Zg&&ui.Zg.split("@@").join("")!=="SGTM_TOKEN"}
function uj(a){for(var b=oa([P.g.jd,P.g.Ob]),c=b.next();!c.done;c=b.next()){var d=U(a,c.value);if(d)return d}}function vj(a,b){return Qi()?""+Pi()+(b?qj[a]||"":""):a};function wj(a){var b=String(a[Xe.oa]||"").replace(/_/g,"");return Tb(b,"cvt")?"cvt":b}var xj=G.location.search.indexOf("?gtm_latency=")>=0||G.location.search.indexOf("&gtm_latency=")>=0;var yj={sampleRate:"0.005000",yk:"",tn:"0.007"},zj=Math.random(),Aj;if(!(Aj=xj)){var Bj=yj.sampleRate;Aj=zj<Number(Bj)}var Cj=Aj,Dj=(Fc==null?void 0:Fc.includes("gtm_debug=d"))||xj||zj>=1-Number(yj.tn);var Ej=/gtag[.\/]js/,Fj=/gtm[.\/]js/,Gj=!1;function Hj(a){if(Gj)return"1";var b=a.scriptSource;if(b){if(Ej.test(b))return"3";if(Fj.test(b))return"2"}return"0"}function Ij(a,b){var c=Jj();c.pending||(c.pending=[]);Eb(c.pending,function(d){return d.target.ctid===a.ctid&&d.target.isDestination===a.isDestination})||c.pending.push({target:a,onLoad:b})}
var Kj=function(){this.container={};this.destination={};this.canonical={};this.pending=[];this.siloed=[];this.injectedFirstPartyContainers={};var a;var b=G.google_tags_first_party||[];if(Array.isArray(b)){for(var c={},d=oa(b),e=d.next();!e.done;e=d.next())c[e.value]=!0;a=Object.freeze(c)}else a={};this.injectedFirstPartyContainers=a};function Jj(){var a=Gc("google_tag_data",{}),b=a.tidr;b||(b=new Kj,a.tidr=b);return b};var Lj={},Pj=!1,ag={ctid:"G-DBEM2FVVRF",canonicalContainerId:"75478076",fk:"G-DBEM2FVVRF",gk:"G-DBEM2FVVRF"};Lj.oe=Kb("");function Qj(){var a=Rj();return Pj?a.map(Sj):a}function Tj(){var a=Uj();return Pj?a.map(Sj):a}function Vj(){return Wj(ag.ctid)}function Xj(){return Wj(ag.canonicalContainerId||"_"+ag.ctid)}function Rj(){return ag.fk?ag.fk.split("|"):[ag.ctid]}function Uj(){return ag.gk?ag.gk.split("|"):[]}
function Yj(){var a=Zj(ak()),b=a&&a.parent;if(b)return Zj(b)}function Zj(a){var b=Jj();return a.isDestination?b.destination[a.ctid]:b.container[a.ctid]}function Wj(a){return Pj?Sj(a):a}function Sj(a){return"siloed_"+a}function bk(a){return Pj?ck(a):a}function ck(a){a=String(a);return Tb(a,"siloed_")?a.substring(7):a}
function dk(){var a=!1;if(a){var b=Jj();if(b.siloed){for(var c=[],d=Rj().map(Sj),e=Uj().map(Sj),f={},g=0;g<b.siloed.length;f={Pf:void 0},g++)f.Pf=b.siloed[g],!Pj&&Eb(f.Pf.isDestination?e:d,function(k){return function(m){return m===k.Pf.ctid}}(f))?Pj=!0:c.push(f.Pf);b.siloed=c}}}
function ek(){var a=Jj();if(a.pending){for(var b,c=[],d=!1,e=Qj(),f=Tj(),g={},k=0;k<a.pending.length;g={Ue:void 0},k++)g.Ue=a.pending[k],Eb(g.Ue.target.isDestination?f:e,function(m){return function(n){return n===m.Ue.target.ctid}}(g))?d||(b=g.Ue.onLoad,d=!0):c.push(g.Ue);a.pending=c;if(b)try{b(Xj())}catch(m){}}}
function fk(){for(var a=ag.ctid,b=Qj(),c=Tj(),d=function(n,p){var q={canonicalContainerId:ag.canonicalContainerId,scriptContainerId:a,state:2,containers:b.slice(),destinations:c.slice()};Ec&&(q.scriptElement=Ec);Fc&&(q.scriptSource=Fc);if(Yj()===void 0){var r;a:{if((q.scriptContainerId||"").indexOf("GTM-")>=0){var t;b:{if(q.scriptSource){for(var u=Oi.H,v=nj(q.scriptSource),w=u?v.pathname:""+v.hostname+v.pathname,x=H.scripts,y="",B=0;B<x.length;++B){var A=x[B];if(!(A.innerHTML.length===0||!u&&A.innerHTML.indexOf(q.scriptContainerId||
"SHOULD_NOT_BE_SET")<0||A.innerHTML.indexOf(w)<0)){if(A.innerHTML.indexOf("(function(w,d,s,l,i)")>=0){t=String(B);break b}y=String(B)}}if(y){t=y;break b}}t=void 0}var C=t;if(C){Gj=!0;r=C;break a}}var E=[].slice.call(document.scripts);r=q.scriptElement?String(E.indexOf(q.scriptElement)):"-1"}q.htmlLoadOrder=r;q.loadScriptType=Hj(q)}var D=p?e.destination:e.container,F=D[n];F?(p&&F.state===0&&O(93),Object.assign(F,q)):D[n]=q},e=Jj(),f=oa(b),g=f.next();!g.done;g=f.next())d(g.value,!1);for(var k=oa(c),
m=k.next();!m.done;m=k.next())d(m.value,!0);e.canonical[Xj()]={};ek()}function gk(a){return!!Jj().container[a]}function hk(a){var b=Jj().destination[a];return!!b&&!!b.state}function ak(){return{ctid:Vj(),isDestination:Lj.oe}}function ik(a){var b=Jj();(b.siloed=b.siloed||[]).push(a)}function jk(){var a=Jj().container,b;for(b in a)if(a.hasOwnProperty(b)&&a[b].state===1)return!0;return!1}function kk(){var a={};z(Jj().destination,function(b,c){c.state===0&&(a[ck(b)]=c)});return a}
function lk(a){return!!(a&&a.parent&&a.context&&a.context.source===1&&a.parent.ctid.indexOf("GTM-")!==0)}var mk="/td?id="+ag.ctid,nk=["v","t","pid","dl","tdp"],ok=["mcc"],pk={},qk={};function rk(a,b,c){qk[a]=b;(c===void 0||c)&&sk(a)}function sk(a,b){if(pk[a]===void 0||(b===void 0?0:b))pk[a]=!0}function tk(a){a=a===void 0?!1:a;var b=Object.keys(pk).filter(function(c){return pk[c]===!0&&qk[c]!==void 0&&(a||!ok.includes(c))}).map(function(c){var d=qk[c];typeof d==="function"&&(d=d());return d?"&"+c+"="+d:""}).join("");return""+vj("https://www.googletagmanager.com")+mk+(""+b+"&z=0")}
function uk(){Object.keys(pk).forEach(function(a){nk.indexOf(a)<0&&(pk[a]=!1)})}function vk(a){a=a===void 0?!1:a;if(Dj&&ag.ctid){var b=tk(a);a?Zc(b):Oc(b);uk()}}function wk(){Object.keys(pk).filter(function(a){return pk[a]&&!nk.includes(a)}).length>0&&vk(!0)}var xk=Fb();function yk(){xk=Fb()}function zk(){rk("v","3");rk("t","t");rk("pid",function(){return String(xk)});Pc(G,"pagehide",wk);G.setInterval(yk,864E5)}var Ak=new function(a,b){this.j=a;this.defaultValue=b===void 0?!1:b}(1933);function Bk(){var a=Gc("google_tag_data",{});return a.ics=a.ics||new Ck}var Ck=function(){this.entries={};this.waitPeriodTimedOut=this.wasSetLate=this.accessedAny=this.accessedDefault=this.usedImplicit=this.usedUpdate=this.usedDefault=this.usedDeclare=this.active=!1;this.j=[]};
Ck.prototype.default=function(a,b,c,d,e,f,g){this.usedDefault||this.usedDeclare||!this.accessedDefault&&!this.accessedAny||(this.wasSetLate=!0);this.usedDefault=this.active=!0;ub("TAGGING",19);b==null?ub("TAGGING",18):Dk(this,a,b==="granted",c,d,e,f,g)};Ck.prototype.waitForUpdate=function(a,b,c){for(var d=0;d<a.length;d++)Dk(this,a[d],void 0,void 0,"","",b,c)};
var Dk=function(a,b,c,d,e,f,g,k){var m=a.entries,n=m[b]||{},p=n.region,q=d&&l(d)?d.toUpperCase():void 0;e=e.toUpperCase();f=f.toUpperCase();if(e===""||q===f||(q===e?p!==f:!q&&!p)){var r=!!(g&&g>0&&n.update===void 0),t={region:q,declare_region:n.declare_region,implicit:n.implicit,default:c!==void 0?c:n.default,declare:n.declare,update:n.update,quiet:r};if(e!==""||n.default!==!1)m[b]=t;r&&G.setTimeout(function(){m[b]===t&&t.quiet&&(ub("TAGGING",2),a.waitPeriodTimedOut=!0,a.clearTimeout(b,void 0,k),
a.notifyListeners())},g)}};ba=Ck.prototype;ba.clearTimeout=function(a,b,c){var d=[a],e=c.delegatedConsentTypes,f;for(f in e)e.hasOwnProperty(f)&&e[f]===a&&d.push(f);var g=this.entries[a]||{},k=this.getConsentState(a,c);if(g.quiet){g.quiet=!1;for(var m=oa(d),n=m.next();!n.done;n=m.next())Ek(this,n.value)}else if(b!==void 0&&k!==b)for(var p=oa(d),q=p.next();!q.done;q=p.next())Ek(this,q.value)};
ba.update=function(a,b,c){this.usedDefault||this.usedDeclare||this.usedUpdate||!this.accessedAny||(this.wasSetLate=!0);this.usedUpdate=this.active=!0;if(b!=null){var d=this.getConsentState(a,c),e=this.entries;(e[a]=e[a]||{}).update=b==="granted";this.clearTimeout(a,d,c)}};
ba.declare=function(a,b,c,d,e){this.usedDeclare=this.active=!0;var f=this.entries,g=f[a]||{},k=g.declare_region,m=c&&l(c)?c.toUpperCase():void 0;d=d.toUpperCase();e=e.toUpperCase();if(d===""||m===e||(m===d?k!==e:!m&&!k)){var n={region:g.region,declare_region:m,declare:b==="granted",implicit:g.implicit,default:g.default,update:g.update,quiet:g.quiet};if(d!==""||g.declare!==!1)f[a]=n}};
ba.implicit=function(a,b){this.usedImplicit=!0;var c=this.entries,d=c[a]=c[a]||{};d.implicit!==!1&&(d.implicit=b==="granted")};
ba.getConsentState=function(a,b){var c=this.entries,d=c[a]||{},e=d.update;if(e!==void 0)return e?1:2;if(zb(8)&&b.usedContainerScopedDefaults){var f=b.containerScopedDefaults[a];if(f===3)return 1;if(f===2)return 2}else if(e=d.default,e!==void 0)return e?1:2;if(b==null?0:b.delegatedConsentTypes.hasOwnProperty(a)){var g=b.delegatedConsentTypes[a],k=c[g]||{};e=k.update;if(e!==void 0)return e?1:2;if(zb(8)&&b.usedContainerScopedDefaults){var m=b.containerScopedDefaults[g];if(m===3)return 1;if(m===2)return 2}else if(e=
k.default,e!==void 0)return e?1:2}e=d.declare;if(e!==void 0)return e?1:2;e=d.implicit;return e!==void 0?e?3:4:0};ba.addListener=function(a,b){this.j.push({consentTypes:a,Ml:b})};var Ek=function(a,b){for(var c=0;c<a.j.length;++c){var d=a.j[c];Array.isArray(d.consentTypes)&&d.consentTypes.indexOf(b)!==-1&&(d.hk=!0)}};Ck.prototype.notifyListeners=function(a,b){for(var c=0;c<this.j.length;++c){var d=this.j[c];if(d.hk){d.hk=!1;try{d.Ml({consentEventId:a,consentPriorityId:b})}catch(e){}}}};var Fk=function(a){Fk[" "](a);return a};Fk[" "]=function(){};var Hk=function(){var a=Gk,b="Bh";if(a.Bh&&a.hasOwnProperty(b))return a.Bh;var c=new a;return a.Bh=c};var Gk=function(){var a={};this.j=function(){var b=Ak.j,c=Ak.defaultValue;return a[b]!=null?a[b]:c};this.D=function(){a[Ak.j]=!0}};var Ik=!1,Jk=!1,Kk={},Lk={delegatedConsentTypes:{},corePlatformServices:{},usedCorePlatformServices:!1,selectedAllCorePlatformServices:!1,containerScopedDefaults:(Kk.ad_storage=1,Kk.analytics_storage=1,Kk.ad_user_data=1,Kk.ad_personalization=1,Kk),usedContainerScopedDefaults:!1};function Mk(a){var b=Bk();b.accessedAny=!0;return(l(a)?[a]:a).every(function(c){switch(b.getConsentState(c,Lk)){case 1:case 3:return!0;case 2:case 4:return!1;default:return!0}})}
function Nk(a){var b=Bk();b.accessedAny=!0;return b.getConsentState(a,Lk)}function Ok(a){for(var b={},c=oa(a),d=c.next();!d.done;d=c.next()){var e=d.value;b[e]=Lk.corePlatformServices[e]!==!1}return b}function Pk(a){var b=Bk();b.accessedAny=!0;return!(b.entries[a]||{}).quiet}
function Qk(){if(!Hk().j())return!1;var a=Bk();a.accessedAny=!0;if(a.active)return!0;if(!zb(8)||!Lk.usedContainerScopedDefaults)return!1;for(var b=oa(Object.keys(Lk.containerScopedDefaults)),c=b.next();!c.done;c=b.next())if(Lk.containerScopedDefaults[c.value]!==1)return!0;return!1}function Rk(a,b){Bk().addListener(a,b)}function Sk(a,b){Bk().notifyListeners(a,b)}
function Tk(a,b){function c(){for(var e=0;e<b.length;e++)if(!Pk(b[e]))return!0;return!1}if(c()){var d=!1;Rk(b,function(e){d||c()||(d=!0,a(e))})}else a({})}
function Uk(a,b){function c(){for(var k=[],m=0;m<e.length;m++){var n=e[m];Mk(n)&&!f[n]&&k.push(n)}return k}function d(k){for(var m=0;m<k.length;m++)f[k[m]]=!0}var e=l(b)?[b]:b,f={},g=c();g.length!==e.length&&(d(g),Rk(e,function(k){function m(q){q.length!==0&&(d(q),k.consentTypes=q,a(k))}var n=c();if(n.length!==0){var p=Object.keys(f).length;n.length+p>=e.length?m(n):G.setTimeout(function(){m(c())},500)}}))};var Vk=["ad_storage","analytics_storage","ad_user_data","ad_personalization"],Wk=!1,Xk=!1;function Yk(){T(48)&&!Xk&&Wk&&(Vk.some(function(a){return Lk.containerScopedDefaults[a]!==1})||Zk("mbc"));Xk=!0}function Zk(a){Dj&&(rk(a,"1"),vk())}function $k(a){ub("HEALTH",a)};var al;try{al=JSON.parse(sb("eyIwIjoiVVMiLCIxIjoiVVMtTU4iLCIyIjpmYWxzZSwiMyI6IiIsIjQiOiIiLCI1Ijp0cnVlLCI2IjpmYWxzZSwiNyI6ImFkX3N0b3JhZ2V8YW5hbHl0aWNzX3N0b3JhZ2V8YWRfdXNlcl9kYXRhfGFkX3BlcnNvbmFsaXphdGlvbiJ9"))}catch(a){O(123),$k(2),al={}}function bl(){return al["0"]||""}function cl(){return al["1"]||""}function dl(){var a=!1;a=!!al["2"];return a}function el(){return al["6"]!==!1}function fl(){var a="";a=al["4"]||"";return a}
function gl(){var a=!1;a=!!al["5"];return a}function hl(){var a="";a=al["3"]||"";return a}var il=[P.g.R,P.g.U,P.g.P,P.g.ya],jl,kl;function ll(a){for(var b=a[P.g.Fb],c=Array.isArray(b)?b:[b],d={Ke:0};d.Ke<c.length;d={Ke:d.Ke},++d.Ke)z(a,function(e){return function(f,g){if(f!==P.g.Fb){var k=c[e.Ke],m=bl(),n=cl();Jk=!0;Ik&&ub("TAGGING",20);Bk().declare(f,g,k,m,n)}}}(d))}
function ml(a){Yk();!kl&&jl&&Zk("crc");kl=!0;var b=a[P.g.Fb];b&&O(40);var c=a[P.g.cf];c&&O(41);for(var d=Array.isArray(b)?b:[b],e={Le:0};e.Le<d.length;e={Le:e.Le},++e.Le)z(a,function(f){return function(g,k){if(g!==P.g.Fb&&g!==P.g.cf){var m=d[f.Le],n=Number(c),p=bl(),q=cl();n=n===void 0?0:n;Ik=!0;Jk&&ub("TAGGING",20);Bk().default(g,k,m,p,q,n,Lk)}}}(e))}
function nl(a){if(T(90)){zb(9)&&(Lk.usedContainerScopedDefaults=!0);var b=a[P.g.Fb];if(b){var c=Array.isArray(b)?b:[b];if(!c.includes(cl())&&!c.includes(bl()))return}z(a,function(d,e){switch(d){case "ad_storage":case "analytics_storage":case "ad_user_data":case "ad_personalization":break;default:return}zb(9)&&(Lk.usedContainerScopedDefaults=!0);Lk.containerScopedDefaults[d]=e==="granted"?3:2})}}
function ol(a,b){Yk();jl=!0;z(a,function(c,d){Ik=!0;Jk&&ub("TAGGING",20);Bk().update(c,d,Lk)});Sk(b.eventId,b.priorityId)}function pl(a){a.hasOwnProperty("all")&&(Lk.selectedAllCorePlatformServices=!0,z(qi,function(b){Lk.corePlatformServices[b]=a.all==="granted";Lk.usedCorePlatformServices=!0}));z(a,function(b,c){b!=="all"&&(Lk.corePlatformServices[b]=c==="granted",Lk.usedCorePlatformServices=!0)})}function W(a){Array.isArray(a)||(a=[a]);return a.every(function(b){return Mk(b)})}
function ql(a,b){Rk(a,b)}function rl(a,b){Uk(a,b)}function sl(a,b){Tk(a,b)}function tl(){var a=[P.g.R,P.g.ya,P.g.P];Bk().waitForUpdate(a,500,Lk)}function ul(a){for(var b=oa(a),c=b.next();!c.done;c=b.next()){var d=c.value;Bk().clearTimeout(d,void 0,Lk)}Sk()}var vl=function(){var a,b,c,d;La(new Ka(new Ga(function(e){if(e.j==1){if(vi.pscdl!==void 0)return e.return();a=function(f){vi.pscdl=f};b=function(){a("error")};e.O=2;c=Cc;if(!("cookieDeprecationLabel"in c)){a("noapi");e.j=4;return}a("pending");return Da(e,c.cookieDeprecationLabel.getValue().then(a).catch(b))}e.j!=2?(e.j=0,e.O=0):(d=Ea(e),b(d),e.j=0)})))};function wl(a,b){T(12)&&b&&z(b,function(c,d){typeof d!=="object"&&d!==void 0&&(a["1p."+c]=String(d))})};var xl=/[A-Z]+/,yl=/\s/;function zl(a,b){if(l(a)){a=Mb(a);var c=a.indexOf("-");if(!(c<0)){var d=a.substring(0,c);if(xl.test(d)){var e=a.substring(c+1),f;if(b){var g=function(n){var p=n.indexOf("/");return p<0?[n]:[n.substring(0,p),n.substring(p+1)]};f=g(e);if(d==="DC"&&f.length===2){var k=g(f[1]);k.length===2&&(f[1]=k[0],f.push(k[1]))}}else{f=e.split("/");for(var m=0;m<f.length;m++)if(!f[m]||yl.test(f[m])&&(d!=="AW"||m!==1))return}return{id:a,prefix:d,ia:d+"-"+f[0],ma:f}}}}}
function Al(a,b){for(var c={},d=0;d<a.length;++d){var e=zl(a[d],b);e&&(c[e.id]=e)}Bl(c);var f=[];z(c,function(g,k){f.push(k)});return f}function Bl(a){var b=[],c;for(c in a)if(a.hasOwnProperty(c)){var d=a[c];d.prefix==="AW"&&d.ma[Cl[2]]&&b.push(d.ia)}for(var e=0;e<b.length;++e)delete a[b[e]]}var Dl={},Cl=(Dl[0]=0,Dl[1]=0,Dl[2]=1,Dl[3]=0,Dl[4]=1,Dl[5]=2,Dl[6]=0,Dl[7]=0,Dl[8]=0,Dl);var El=Number('')||500,Fl={},Gl={},Hl={initialized:11,complete:12,interactive:13},Il={},Jl=Object.freeze((Il[P.g.Ka]=!0,Il)),Kl=H.location.search.indexOf("?gtm_diagnostics=")>=0||H.location.search.indexOf("&gtm_diagnostics=")>=0,Ll=void 0;
function Ml(a,b){if(b.length&&Dj){var c;(c=Fl)[a]!=null||(c[a]=[]);Gl[a]!=null||(Gl[a]=[]);var d=b.filter(function(e){return!Gl[a].includes(e)});Fl[a].push.apply(Fl[a],qa(d));Gl[a].push.apply(Gl[a],qa(d));!Ll&&d.length>0&&(sk("tdc",!0),Ll=G.setTimeout(function(){vk();Fl={};Ll=void 0},El))}}
function Nl(a,b,c){if(Dj&&a==="config"){var d,e=(d=zl(b))==null?void 0:d.ma;if(!(e&&e.length>1)){var f,g=Gc("google_tag_data",{});g.td||(g.td={});f=g.td;var k=h(c.K);h(c.j,k);var m=[],n;for(n in f)if(f.hasOwnProperty(n)){var p=Ol(f[n],k);p.length&&(Kl&&console.log(p),m.push(n))}m.length&&(Ml(b,m),ub("TAGGING",Hl[H.readyState]||14));f[b]=k}}}function Pl(a,b){var c={},d;for(d in b)b.hasOwnProperty(d)&&(c[d]=!0);for(var e in a)a.hasOwnProperty(e)&&(c[e]=!0);return c}
function Ol(a,b,c,d){c=c===void 0?{}:c;d=d===void 0?"":d;if(a===b)return[];var e=function(r,t){var u;db(t)==="object"?u=t[r]:db(t)==="array"&&(u=t[r]);return u===void 0?Jl[r]:u},f=Pl(a,b),g;for(g in f)if(f.hasOwnProperty(g)){var k=(d?d+".":"")+g,m=e(g,a),n=e(g,b),p=db(m)==="object"||db(m)==="array",q=db(n)==="object"||db(n)==="array";if(p&&q)Ol(m,n,c,k);else if(p||q||m!==n)c[k]=!0}return Object.keys(c)}
function Ql(){rk("tdc",function(){Ll&&(G.clearTimeout(Ll),Ll=void 0);var a=[],b;for(b in Fl)Fl.hasOwnProperty(b)&&a.push(b+"*"+Fl[b].join("."));return a.length?a.join("!"):void 0},!1)};var Rl=function(a,b,c,d,e,f,g,k,m,n,p){this.eventId=a;this.priorityId=b;this.j=c;this.O=d;this.H=e;this.K=f;this.D=g;this.eventMetadata=k;this.onSuccess=m;this.onFailure=n;this.isGtmEvent=p},Sl=function(a,b){var c=[];switch(b){case 3:c.push(a.j);c.push(a.O);c.push(a.H);c.push(a.K);c.push(a.D);break;case 2:c.push(a.j);break;case 1:c.push(a.O);c.push(a.H);c.push(a.K);c.push(a.D);break;case 4:c.push(a.j),c.push(a.O),c.push(a.H),c.push(a.K)}return c},U=function(a,b,c,d){for(var e=oa(Sl(a,d===void 0?3:
d)),f=e.next();!f.done;f=e.next()){var g=f.value;if(g[b]!==void 0)return g[b]}return c},Tl=function(a){for(var b={},c=Sl(a,4),d=oa(c),e=d.next();!e.done;e=d.next())for(var f=Object.keys(e.value),g=oa(f),k=g.next();!k.done;k=g.next())b[k.value]=1;return Object.keys(b)},Ul=function(a,b,c){function d(n){fb(n)&&z(n,function(p,q){f=!0;e[p]=q})}var e={},f=!1,g=Sl(a,c===void 0?3:c);g.reverse();for(var k=oa(g),m=k.next();!m.done;m=k.next())d(m.value[b]);return f?e:void 0},Vl=function(a){for(var b=[P.g.Sc,
P.g.Oc,P.g.Pc,P.g.Qc,P.g.Rc,P.g.Tc,P.g.Uc],c=Sl(a,3),d=oa(c),e=d.next();!e.done;e=d.next()){for(var f=e.value,g={},k=!1,m=oa(b),n=m.next();!n.done;n=m.next()){var p=n.value;f[p]!==void 0&&(g[p]=f[p],k=!0)}var q=k?g:void 0;if(q)return q}return{}},Wl=function(a,b){this.eventId=a;this.priorityId=b;this.D={};this.O={};this.j={};this.H={};this.W={};this.K={};this.eventMetadata={};this.isGtmEvent=!1;this.onSuccess=function(){};this.onFailure=function(){}},Xl=function(a,b){a.D=b;return a},Yl=function(a,
b){a.O=b;return a},Zl=function(a,b){a.j=b;return a},$l=function(a,b){a.H=b;return a},am=function(a,b){a.W=b;return a},bm=function(a,b){a.K=b;return a},cm=function(a,b){a.eventMetadata=b||{};return a},dm=function(a,b){a.onSuccess=b;return a},em=function(a,b){a.onFailure=b;return a},fm=function(a,b){a.isGtmEvent=b;return a},gm=function(a){return new Rl(a.eventId,a.priorityId,a.D,a.O,a.j,a.H,a.K,a.eventMetadata,a.onSuccess,a.onFailure,a.isGtmEvent)};var hm={xk:Number("5"),co:Number("")},im=[];function jm(a){im.push(a)}var km="?id="+ag.ctid,lm=void 0,mm={},nm=void 0,om=new function(){var a=5;hm.xk>0&&(a=hm.xk);this.D=a;this.j=0;this.H=[]},pm=1E3;
function qm(a,b){var c=lm;if(c===void 0)if(b)c=Mi();else return"";for(var d=[vj("https://www.googletagmanager.com"),"/a",km],e=oa(im),f=e.next();!f.done;f=e.next())for(var g=f.value,k=g({eventId:c,mc:!!a}),m=oa(k),n=m.next();!n.done;n=m.next()){var p=oa(n.value),q=p.next().value,r=p.next().value;d.push("&"+q+"="+r)}d.push("&z=0");return d.join("")}
function rm(){nm&&(G.clearTimeout(nm),nm=void 0);if(lm!==void 0&&sm){var a;(a=mm[lm])||(a=om.j<om.D?!1:Ob()-om.H[om.j%om.D]<1E3);if(a||pm--<=0)O(1),mm[lm]=!0;else{var b=om.j++%om.D;om.H[b]=Ob();var c=qm(!0);Oc(c);sm=!1}}}var sm=!1;function tm(a){mm[a]||(a!==lm&&(rm(),lm=a),sm=!0,nm||(nm=G.setTimeout(rm,500)),qm().length>=2022&&rm())}var um=Fb();function vm(){um=Fb()}function wm(){return[["v","3"],["t","t"],["pid",String(um)]]}var xm={};function ym(a,b,c){Cj&&a!==void 0&&(xm[a]=xm[a]||[],xm[a].push(c+b),tm(a))}function zm(a){var b=a.eventId,c=a.mc,d=[],e=xm[b]||[];e.length&&d.push(["epr",e.join(".")]);c&&delete xm[b];return d};function Am(a,b){var c=zl(Wj(a),!0);c&&Bm.register(c,b)}function Cm(a,b,c,d){var e=zl(c,d.isGtmEvent);e&&(T(47)&&T(47)&&Ai&&(d.deferrable=!0),Bm.push("event",[b,a],e,d))}function Dm(a,b,c,d){var e=zl(c,d.isGtmEvent);e&&Bm.push("get",[a,b],e,d)}function Em(a){var b=zl(Wj(a),!0),c;b?c=Fm(Bm,b).j:c={};return c}function Gm(a,b){var c=zl(Wj(a),!0);if(c){var d=Bm,e=h(b,null);h(Fm(d,c).j,e);Fm(d,c).j=e}}
var Hm=function(){this.O={};this.j={};this.D={};this.W=null;this.K={};this.H=!1;this.status=1},Im=function(a,b,c,d){this.D=Ob();this.j=b;this.args=c;this.messageContext=d;this.type=a},Jm=function(){this.destinations={};this.D={};this.j=[]},Fm=function(a,b){var c=b.ia;return a.destinations[c]=a.destinations[c]||new Hm},Km=function(a,b,c,d){if(d.j){var e=Fm(a,d.j),f=e.W;if(f){var g=h(c,null),k=h(e.O[d.j.id],null),m=h(e.K,null),n=h(e.j,null),p=h(a.D,null),q={};if(Cj)try{q=h(Ti)}catch(v){O(72)}var r=
d.j.prefix,t=function(v){ym(d.messageContext.eventId,r,v)},u=gm(fm(em(dm(cm(am($l(bm(Zl(Yl(Xl(new Wl(d.messageContext.eventId,d.messageContext.priorityId),g),k),m),n),p),q),d.messageContext.eventMetadata),function(){if(t){var v=t;t=void 0;v("2");if(d.messageContext.onSuccess)d.messageContext.onSuccess()}}),function(){if(t){var v=t;t=void 0;v("3");if(d.messageContext.onFailure)d.messageContext.onFailure()}}),!!d.messageContext.isGtmEvent));try{ym(d.messageContext.eventId,r,"1"),Nl(d.type,d.j.id,u),
f(d.j.id,b,d.D,u)}catch(v){ym(d.messageContext.eventId,r,"4")}}}};Jm.prototype.register=function(a,b,c){var d=Fm(this,a);d.status!==3&&(d.W=b,d.status=3,c&&(h(d.j,c),d.j=c),this.flush())};Jm.prototype.push=function(a,b,c,d){c!==void 0&&(Fm(this,c).status===1&&(Fm(this,c).status=2,this.push("require",[{}],c,{})),Fm(this,c).H&&(d.deferrable=!1));this.j.push(new Im(a,c,b,d));d.deferrable||this.flush()};
Jm.prototype.flush=function(a){for(var b=this,c=[],d=!1,e={};this.j.length;e={Ec:void 0,th:void 0}){var f=this.j[0],g=f.j;if(f.messageContext.deferrable)!g||Fm(this,g).H?(f.messageContext.deferrable=!1,this.j.push(f)):c.push(f),this.j.shift();else{switch(f.type){case "require":if(Fm(this,g).status!==3&&!a){this.j.push.apply(this.j,c);return}break;case "set":z(f.args[0],function(r,t){h(Wb(r,t),b.D)});break;case "config":var k=Fm(this,g);e.Ec={};z(f.args[0],function(r){return function(t,u){h(Wb(t,u),
r.Ec)}}(e));var m=!!e.Ec[P.g.fc];delete e.Ec[P.g.fc];var n=g.ia===g.id;m||(n?k.K={}:k.O[g.id]={});k.H&&m||Km(this,P.g.ba,e.Ec,f);k.H=!0;n?h(e.Ec,k.K):(h(e.Ec,k.O[g.id]),O(70));d=!0;break;case "event":e.th={};z(f.args[0],function(r){return function(t,u){h(Wb(t,u),r.th)}}(e));Km(this,f.args[1],e.th,f);break;case "get":var p={},q=(p[P.g.tb]=f.args[0],p[P.g.Jb]=f.args[1],p);Km(this,P.g.Ua,q,f)}this.j.shift();Lm(this,f)}}this.j.push.apply(this.j,c);d&&this.flush()};
var Lm=function(a,b){if(b.type!=="require")if(b.j)for(var c=Fm(a,b.j).D[b.type]||[],d=0;d<c.length;d++)c[d]();else for(var e in a.destinations)if(a.destinations.hasOwnProperty(e)){var f=a.destinations[e];if(f&&f.D)for(var g=f.D[b.type]||[],k=0;k<g.length;k++)g[k]()}},Bm=new Jm;var Mm=function(a,b){var c=function(){};c.prototype=a.prototype;var d=new c;a.apply(d,Array.prototype.slice.call(arguments,1));return d},Nm=function(a){var b=a;return function(){if(b){var c=b;b=null;c()}}};var Om=function(a,b,c){a.addEventListener&&a.addEventListener(b,c,!1)},Pm=function(a,b,c){a.removeEventListener&&a.removeEventListener(b,c,!1)};var Qm,Rm;a:{for(var Sm=["CLOSURE_FLAGS"],Tm=Oa,Um=0;Um<Sm.length;Um++)if(Tm=Tm[Sm[Um]],Tm==null){Rm=null;break a}Rm=Tm}var Vm=Rm&&Rm[610401301];Qm=Vm!=null?Vm:!1;function Wm(){var a=Oa.navigator;if(a){var b=a.userAgent;if(b)return b}return""}var Xm,Ym=Oa.navigator;Xm=Ym?Ym.userAgentData||null:null;function Zm(a){return Qm?Xm?Xm.brands.some(function(b){var c;return(c=b.brand)&&c.indexOf(a)!=-1}):!1:!1}function $m(a){return Wm().indexOf(a)!=-1};function an(){return Qm?!!Xm&&Xm.brands.length>0:!1}function bn(){return an()?!1:$m("Opera")}function cn(){return $m("Firefox")||$m("FxiOS")}function dn(){return an()?Zm("Chromium"):($m("Chrome")||$m("CriOS"))&&!(an()?0:$m("Edge"))||$m("Silk")};function en(){return Qm?!!Xm&&!!Xm.platform:!1}function fn(){return $m("iPhone")&&!$m("iPod")&&!$m("iPad")}function gn(){fn()||$m("iPad")||$m("iPod")};bn();an()||$m("Trident")||$m("MSIE");$m("Edge");!$m("Gecko")||Wm().toLowerCase().indexOf("webkit")!=-1&&!$m("Edge")||$m("Trident")||$m("MSIE")||$m("Edge");Wm().toLowerCase().indexOf("webkit")!=-1&&!$m("Edge")&&$m("Mobile");en()||$m("Macintosh");en()||$m("Windows");(en()?Xm.platform==="Linux":$m("Linux"))||en()||$m("CrOS");en()||$m("Android");fn();$m("iPad");$m("iPod");gn();Wm().toLowerCase().indexOf("kaios");var hn=function(a,b,c,d){for(var e=b,f=c.length;(e=a.indexOf(c,e))>=0&&e<d;){var g=a.charCodeAt(e-1);if(g==38||g==63){var k=a.charCodeAt(e+f);if(!k||k==61||k==38||k==35)return e}e+=f+1}return-1},jn=/#|$/,kn=function(a,b){var c=a.search(jn),d=hn(a,0,b,c);if(d<0)return null;var e=a.indexOf("&",d);if(e<0||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.slice(d,e!==-1?e:0).replace(/\+/g," "))},ln=/[?&]($|#)/,mn=function(a,b,c){for(var d,e=a.search(jn),f=0,g,k=[];(g=hn(a,f,b,e))>=0;)k.push(a.substring(f,
g)),f=Math.min(a.indexOf("&",g)+1||e,e);k.push(a.slice(f));d=k.join("").replace(ln,"$1");var m,n=c!=null?"="+encodeURIComponent(String(c)):"";var p=b+n;if(p){var q,r=d.indexOf("#");r<0&&(r=d.length);var t=d.indexOf("?"),u;t<0||t>r?(t=r,u=""):u=d.substring(t+1,r);q=[d.slice(0,t),u,d.slice(r)];var v=q[1];q[1]=p?v?v+"&"+p:p:v;m=q[0]+(q[1]?"?"+q[1]:"")+q[2]}else m=d;return m};var nn=function(a){try{var b;if(b=!!a&&a.location.href!=null)a:{try{Fk(a.foo);b=!0;break a}catch(c){}b=!1}return b}catch(c){return!1}},on=function(a,b){if(a)for(var c in a)Object.prototype.hasOwnProperty.call(a,c)&&b(a[c],c,a)},pn=function(a){if(G.top==G)return 0;if(a===void 0?0:a){var b=G.location.ancestorOrigins;if(b)return b[b.length-1]==G.location.origin?1:2}return nn(G.top)?1:2},qn=function(a){a=a===void 0?document:a;return a.createElement("img")};function rn(a,b,c,d){d=d===void 0?!1:d;a.google_image_requests||(a.google_image_requests=[]);var e=qn(a.document);if(c){var f=function(){if(c){var g=a.google_image_requests,k=wc(g,e);k>=0&&Array.prototype.splice.call(g,k,1)}Pm(e,"load",f);Pm(e,"error",f)};Om(e,"load",f);Om(e,"error",f)}d&&(e.attributionSrc="");e.src=b;a.google_image_requests.push(e)}
var tn=function(a){var b;b=b===void 0?!1:b;var c="https://pagead2.googlesyndication.com/pagead/gen_204?id=tcfe";on(a,function(d,e){if(d||d===0)c+="&"+e+"="+encodeURIComponent(""+d)});sn(c,b)},sn=function(a,b){var c=window,d;b=b===void 0?!1:b;d=d===void 0?!1:d;if(c.fetch){var e={keepalive:!0,credentials:"include",redirect:"follow",method:"get",mode:"no-cors"};d&&(e.mode="cors","setAttributionReporting"in XMLHttpRequest.prototype?e.attributionReporting={eventSourceEligible:"true",triggerEligible:"false"}:
e.headers={"Attribution-Reporting-Eligible":"event-source"});c.fetch(a,e)}else rn(c,a,b===void 0?!1:b,d===void 0?!1:d)};var un=function(){this.O=this.O;this.D=this.D};un.prototype.O=!1;un.prototype.dispose=function(){this.O||(this.O=!0,this.Ca())};un.prototype[Symbol.dispose]=function(){this.dispose()};un.prototype.addOnDisposeCallback=function(a,b){this.O?b!==void 0?a.call(b):a():(this.D||(this.D=[]),b&&(a=a.bind(b)),this.D.push(a))};un.prototype.Ca=function(){if(this.D)for(;this.D.length;)this.D.shift()()};var vn=function(a){a.addtlConsent!==void 0&&typeof a.addtlConsent!=="string"&&(a.addtlConsent=void 0);a.gdprApplies!==void 0&&typeof a.gdprApplies!=="boolean"&&(a.gdprApplies=void 0);return a.tcString!==void 0&&typeof a.tcString!=="string"||a.listenerId!==void 0&&typeof a.listenerId!=="number"?2:a.cmpStatus&&a.cmpStatus!=="error"?0:3},wn=function(a,b){b=b===void 0?{}:b;un.call(this);this.H=a;this.j=null;this.W={};this.If=0;var c;this.me=(c=b.nn)!=null?c:500;var d;this.xb=(d=b.Qn)!=null?d:!1;this.K=
null};za(wn,un);wn.prototype.Ca=function(){this.W={};this.K&&(Pm(this.H,"message",this.K),delete this.K);delete this.W;delete this.H;delete this.j;un.prototype.Ca.call(this)};var yn=function(a){return typeof a.H.__tcfapi==="function"||xn(a)!=null};
wn.prototype.addEventListener=function(a){var b=this,c={internalBlockOnErrors:this.xb},d=Nm(function(){return a(c)}),e=0;this.me!==-1&&(e=setTimeout(function(){c.tcString="tcunavailable";c.internalErrorState=1;d()},this.me));var f=function(g,k){clearTimeout(e);g?(c=g,c.internalErrorState=vn(c),c.internalBlockOnErrors=b.xb,k&&c.internalErrorState===0||(c.tcString="tcunavailable",k||(c.internalErrorState=3))):(c.tcString="tcunavailable",c.internalErrorState=3);a(c)};try{zn(this,"addEventListener",f)}catch(g){c.tcString=
"tcunavailable",c.internalErrorState=3,e&&(clearTimeout(e),e=0),d()}};wn.prototype.removeEventListener=function(a){a&&a.listenerId&&zn(this,"removeEventListener",null,a.listenerId)};
var Bn=function(a,b,c){var d;d=d===void 0?"755":d;var e;a:{if(a.publisher&&a.publisher.restrictions){var f=a.publisher.restrictions[b];if(f!==void 0){e=f[d===void 0?"755":d];break a}}e=void 0}var g=e;if(g===0)return!1;var k=c;c===2?(k=0,g===2&&(k=1)):c===3&&(k=1,g===1&&(k=0));var m;if(k===0)if(a.purpose&&a.vendor){var n=An(a.vendor.consents,d===void 0?"755":d);m=n&&b==="1"&&a.purposeOneTreatment&&a.publisherCC==="CH"?!0:n&&An(a.purpose.consents,b)}else m=!0;else m=k===1?a.purpose&&a.vendor?An(a.purpose.legitimateInterests,
b)&&An(a.vendor.legitimateInterests,d===void 0?"755":d):!0:!0;return m},An=function(a,b){return!(!a||!a[b])},zn=function(a,b,c,d){c||(c=function(){});if(typeof a.H.__tcfapi==="function"){var e=a.H.__tcfapi;e(b,2,c,d)}else if(xn(a)){Cn(a);var f=++a.If;a.W[f]=c;if(a.j){var g={};a.j.postMessage((g.__tcfapiCall={command:b,version:2,callId:f,parameter:d},g),"*")}}else c({},!1)},xn=function(a){if(a.j)return a.j;var b;a:{for(var c=a.H,d=0;d<50;++d){var e;try{e=!(!c.frames||!c.frames.__tcfapiLocator)}catch(k){e=
!1}if(e){b=c;break a}var f;b:{try{var g=c.parent;if(g&&g!=c){f=g;break b}}catch(k){}f=null}if(!(c=f))break}b=null}a.j=b;return a.j},Cn=function(a){a.K||(a.K=function(b){try{var c;c=(typeof b.data==="string"?JSON.parse(b.data):b.data).__tcfapiReturn;a.W[c.callId](c.returnValue,c.success)}catch(d){}},Om(a.H,"message",a.K))},Dn=function(a){if(a.gdprApplies===!1)return!0;a.internalErrorState===void 0&&(a.internalErrorState=vn(a));return a.cmpStatus==="error"||a.internalErrorState!==0?a.internalBlockOnErrors?
(tn({e:String(a.internalErrorState)}),!1):!0:a.cmpStatus!=="loaded"||a.eventStatus!=="tcloaded"&&a.eventStatus!=="useractioncomplete"?!1:!0};var En={1:0,3:0,4:0,7:3,9:3,10:3};function Fn(){var a=vi.tcf||{};return vi.tcf=a}var Gn=function(){return new wn(G,{nn:-1})};
function Hn(){var a=Fn(),b=Gn();yn(b)&&!In()&&!Jn()&&O(124);if(!a.active&&yn(b)){In()&&(a.active=!0,a.kc={},a.cmpId=0,a.tcfPolicyVersion=0,Bk().active=!0,a.tcString="tcunavailable");tl();try{b.addEventListener(function(c){if(c.internalErrorState!==0)Kn(a),ul([P.g.R,P.g.ya,P.g.P]),Bk().active=!0;else if(a.gdprApplies=c.gdprApplies,a.cmpId=c.cmpId,a.enableAdvertiserConsentMode=c.enableAdvertiserConsentMode,Jn()&&(a.active=!0),!Ln(c)||In()||Jn()){a.tcfPolicyVersion=c.tcfPolicyVersion;var d;if(c.gdprApplies===
!1){var e={},f;for(f in En)En.hasOwnProperty(f)&&(e[f]=!0);d=e;b.removeEventListener(c)}else if(Ln(c)){var g={},k;for(k in En)if(En.hasOwnProperty(k))if(k==="1"){var m,n=c,p={Ql:!0};p=p===void 0?{}:p;m=Dn(n)?n.gdprApplies===!1?!0:n.tcString==="tcunavailable"?!p.Xj:(p.Xj||n.gdprApplies!==void 0||p.Ql)&&(p.Xj||typeof n.tcString==="string"&&n.tcString.length)?Bn(n,"1",0):!0:!1;g["1"]=m}else g[k]=Bn(c,k,En[k]);d=g}if(d){a.tcString=c.tcString||"tcempty";a.kc=d;var q={},r=(q[P.g.R]=a.kc["1"]?"granted":
"denied",q);a.gdprApplies!==!0?(ul([P.g.R,P.g.ya,P.g.P]),Bk().active=!0):(r[P.g.ya]=a.kc["3"]&&a.kc["4"]?"granted":"denied",typeof a.tcfPolicyVersion==="number"&&a.tcfPolicyVersion>=4?r[P.g.P]=a.kc["1"]&&a.kc["7"]?"granted":"denied":ul([P.g.P]),ol(r,{eventId:0},{gdprApplies:a?a.gdprApplies:void 0,tcString:Mn()||""}))}}else ul([P.g.R,P.g.ya,P.g.P])})}catch(c){Kn(a),ul([P.g.R,P.g.ya,P.g.P]),Bk().active=!0}}}function Kn(a){a.type="e";a.tcString="tcunavailable"}
function Ln(a){return a.eventStatus==="tcloaded"||a.eventStatus==="useractioncomplete"||a.eventStatus==="cmpuishown"}function In(){return G.gtag_enable_tcf_support===!0}function Jn(){return Fn().enableAdvertiserConsentMode===!0}function Mn(){var a=Fn();if(a.active)return a.tcString}function Nn(){var a=Fn();if(a.active&&a.gdprApplies!==void 0)return a.gdprApplies?"1":"0"}function On(a){if(!En.hasOwnProperty(String(a)))return!0;var b=Fn();return b.active&&b.kc?!!b.kc[String(a)]:!0}var Pn=[P.g.R,P.g.U,P.g.P,P.g.ya],Qn={},Rn=(Qn[P.g.R]=1,Qn[P.g.U]=2,Qn);function Sn(a){if(a===void 0)return 0;switch(U(a,P.g.ka)){case void 0:return 1;case !1:return 3;default:return 2}}function Tn(a){if(cl()==="US-CO"&&Cc.globalPrivacyControl===!0)return!1;var b=Sn(a);if(b===3)return!1;switch(Nk(P.g.ya)){case 1:case 3:return!0;case 2:return!1;case 4:return b===2;case 0:return!0;default:return!1}}function Un(){return Qk()||!Mk(P.g.R)||!Mk(P.g.U)}
function Vn(){var a={},b;for(b in Rn)Rn.hasOwnProperty(b)&&(a[Rn[b]]=Nk(b));return"G1"+Ue(a[1]||0)+Ue(a[2]||0)}var Wn={},Xn=(Wn[P.g.R]=0,Wn[P.g.U]=1,Wn[P.g.P]=2,Wn[P.g.ya]=3,Wn);function eo(a){switch(a){case void 0:return 1;case !0:return 3;case !1:return 2;default:return 0}}
function fo(a){for(var b="1",c=0;c<Pn.length;c++){var d=b,e,f=Pn[c],g=Lk.delegatedConsentTypes[f];e=g===void 0?0:Xn.hasOwnProperty(g)?12|Xn[g]:8;var k=Bk();k.accessedAny=!0;var m=k.entries[f]||{};e=e<<2|eo(m.implicit);b=d+(""+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[e]+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[eo(m.declare)<<4|eo(m.default)<<2|eo(m.update)])}var n=b,p=(cl()==="US-CO"&&Cc.globalPrivacyControl===!0?1:0)<<3,q=(Qk()?1:0)<<2,r=Sn(a);b=
n+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[p|q|r];T(90)&&(b+=""+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[Lk.containerScopedDefaults.ad_storage<<4|Lk.containerScopedDefaults.analytics_storage<<2|Lk.containerScopedDefaults.ad_user_data]+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[(zb(8)&&Lk.usedContainerScopedDefaults?1:0)<<2|Lk.containerScopedDefaults.ad_personalization]);return b}
function go(){if(!Mk(P.g.P))return"-";for(var a=Object.keys(qi),b=Ok(a),c="",d=oa(a),e=d.next();!e.done;e=d.next()){var f=e.value;b[f]&&(c+=qi[f])}(Lk.usedCorePlatformServices?Lk.selectedAllCorePlatformServices:1)&&(c+="o");return c||"-"}function ho(){return el()||(In()||Jn())&&Nn()==="1"?"1":"0"}function io(){return(el()?!0:!(!In()&&!Jn())&&Nn()==="1")||!Mk(P.g.P)}
function jo(){var a="0",b="0",c;var d=Fn();c=d.active?d.cmpId:void 0;typeof c==="number"&&c>=0&&c<=4095&&(a="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[c>>6&63],b="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[c&63]);var e="0",f;var g=Fn();f=g.active?g.tcfPolicyVersion:void 0;typeof f==="number"&&f>=0&&f<=63&&(e="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[f]);var k=0;el()&&(k|=1);Nn()==="1"&&(k|=2);In()&&(k|=4);var m;var n=Fn();m=n.enableAdvertiserConsentMode!==
void 0?n.enableAdvertiserConsentMode?"1":"0":void 0;m==="1"&&(k|=8);Bk().waitPeriodTimedOut&&(k|=16);return"1"+a+b+e+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[k]}function ko(){return cl()==="US-CO"};function lo(){var a=!1;return a};var mo={UA:1,AW:2,DC:3,G:4,GF:5,GT:12,GTM:14,HA:6,MC:7};
function no(a){a=a===void 0?{}:a;var b=ag.ctid.split("-")[0].toUpperCase(),c={};c.ctid=ag.ctid;c.Sm=ui.se;c.Wm=ui.Yg;c.xm=Lj.oe?2:1;c.gn=a.pk;c.ze=ag.canonicalContainerId;c.ze!==a.xa&&(c.xa=a.xa);var d=Yj();c.Im=d?d.canonicalContainerId:void 0;Bi?(c.Yf=mo[b],c.Yf||(c.Yf=0)):c.Yf=Fi?13:10;Oi.H?(c.Wf=0,c.xl=2):Di?c.Wf=1:lo()?c.Wf=2:c.Wf=3;var e={};e[6]=Pj;Oi.D===2?e[7]=!0:Oi.D===1&&(e[2]=!0);c.Al=e;var f=a.Nf,g;var k=c.Yf,m=c.Wf;k===void 0?g="":(m||(m=0),g=""+We(1,1)+Te(k<<2|m));var n=c.xl,p="4"+g+
(n?""+We(2,1)+Te(n):""),q,r=c.Wm;q=r&&Ve.test(r)?""+We(3,2)+r:"";var t,u=c.Sm;t=u?""+We(4,1)+Te(u):"";var v;var w=c.ctid;if(w&&f){var x=w.split("-"),y=x[0].toUpperCase();if(y!=="GTM"&&y!=="OPT")v="";else{var B=x[1];v=""+We(5,3)+Te(1+B.length)+(c.xm||0)+B}}else v="";var A=c.gn,C=c.ze,E=c.xa,D=c.ao,F=p+q+t+v+(A?""+We(6,1)+Te(A):"")+(C?""+We(7,3)+Te(C.length)+C:"")+(E?""+We(8,3)+Te(E.length)+E:"")+(D?""+We(9,3)+Te(D.length)+D:""),L;var M=c.Al;M=M===void 0?{}:M;for(var S=[],V=oa(Object.keys(M)),aa=V.next();!aa.done;aa=
V.next()){var X=aa.value;S[Number(X)]=M[X]}if(S.length){var R=We(10,3),ma;if(S.length===0)ma=Te(0);else{for(var la=[],ha=0,ya=!1,Na=0;Na<S.length;Na++){ya=!0;var Fa=Na%6;S[Na]&&(ha|=1<<Fa);Fa===5&&(la.push(Te(ha)),ha=0,ya=!1)}ya&&la.push(Te(ha));ma=la.join("")}var Sa=ma;L=""+R+Te(Sa.length)+Sa}else L="";var bb=c.Im;return F+L+(bb?""+We(11,3)+Te(bb.length)+bb:"")};var oo={Ej:"service_worker_endpoint",ah:"shared_user_id",bh:"shared_user_id_requested",ue:"shared_user_id_source"},po;function qo(a){if(!po){po={};for(var b=oa(Object.keys(oo)),c=b.next();!c.done;c=b.next())po[oo[c.value]]=!0}return!!po[a]}
function ro(a,b){b=b===void 0?!1:b;if(qo(a)){var c,d,e=(d=(c=Gc("google_tag_data",{})).xcd)!=null?d:c.xcd={};if(e[a])return e[a];if(b){var f=void 0,g=1,k={},m={set:function(n){f=n;m.notify()},get:function(){return f},subscribe:function(n){k[String(g)]=n;return g++},unsubscribe:function(n){var p=String(n);return k.hasOwnProperty(p)?(delete k[p],!0):!1},notify:function(){for(var n=oa(Object.keys(k)),p=n.next();!p.done;p=n.next()){var q=p.value;try{k[q](a,f)}catch(r){}}}};return e[a]=m}}}
function so(a,b){var c=ro(a,!0);c&&c.set(b)}function to(a){var b;return(b=ro(a))==null?void 0:b.get()}function uo(a,b){if(typeof b==="function"){var c;return(c=ro(a,!0))==null?void 0:c.subscribe(b)}}function vo(a,b){var c=ro(a);return c?c.unsubscribe(b):!1};function wo(a){return a.origin!=="null"};function xo(a,b,c,d){var e;if(yo(d)){for(var f=[],g=String(b||zo()).split(";"),k=0;k<g.length;k++){var m=g[k].split("="),n=m[0].replace(/^\s*|\s*$/g,"");if(n&&n===a){var p=m.slice(1).join("=").replace(/^\s*|\s*$/g,"");p&&c&&(p=decodeURIComponent(p));f.push(p)}}e=f}else e=[];return e}
function Ao(a,b,c,d,e){if(yo(e)){var f=Bo(a,d,e);if(f.length===1)return f[0].id;if(f.length!==0){f=Co(f,function(g){return g.Gl},b);if(f.length===1)return f[0].id;f=Co(f,function(g){return g.Km},c);return f[0]?f[0].id:void 0}}}function Do(a,b,c,d){var e=zo(),f=window;wo(f)&&(f.document.cookie=a);var g=zo();return e!==g||c!==void 0&&xo(b,g,!1,d).indexOf(c)>=0}
function Eo(a,b,c,d){function e(w,x,y){if(y==null)return delete k[x],w;k[x]=y;return w+"; "+x+"="+y}function f(w,x){if(x==null)return w;k[x]=!0;return w+"; "+x}if(!yo(c.Db))return 2;var g;b==null?g=a+"=deleted; expires="+(new Date(0)).toUTCString():(c.encode&&(b=encodeURIComponent(b)),b=Fo(b),g=a+"="+b);var k={};g=e(g,"path",c.path);var m;c.expires instanceof Date?m=c.expires.toUTCString():c.expires!=null&&(m=""+c.expires);g=e(g,"expires",m);g=e(g,"max-age",c.Bm);g=e(g,"samesite",c.Xm);c.Ym&&(g=f(g,
"secure"));var n=c.domain;if(n&&n.toLowerCase()==="auto"){for(var p=Go(),q=void 0,r=!1,t=0;t<p.length;++t){var u=p[t]!=="none"?p[t]:void 0,v=e(g,"domain",u);v=f(v,c.flags);try{d&&d(a,k)}catch(w){q=w;continue}r=!0;if(!Ho(u,c.path)&&Do(v,a,b,c.Db))return 0}if(q&&!r)throw q;return 1}n&&n.toLowerCase()!=="none"&&(g=e(g,"domain",n));g=f(g,c.flags);d&&d(a,k);return Ho(n,c.path)?1:Do(g,a,b,c.Db)?0:1}function Io(a,b,c){c.path==null&&(c.path="/");c.domain||(c.domain="auto");return Eo(a,b,c)}
function Co(a,b,c){for(var d=[],e=[],f,g=0;g<a.length;g++){var k=a[g],m=b(k);m===c?d.push(k):f===void 0||m<f?(e=[k],f=m):m===f&&e.push(k)}return d.length>0?d:e}function Bo(a,b,c){for(var d=[],e=xo(a,void 0,void 0,c),f=0;f<e.length;f++){var g=e[f].split("."),k=g.shift();if(!b||!k||b.indexOf(k)!==-1){var m=g.shift();if(m){var n=m.split("-");d.push({id:g.join("."),Gl:Number(n[0])||1,Km:Number(n[1])||1})}}}return d}function Fo(a){a&&a.length>1200&&(a=a.substring(0,1200));return a}
var Jo=/^(www\.)?google(\.com?)?(\.[a-z]{2})?$/,Ko=/(^|\.)doubleclick\.net$/i;function Ho(a,b){return a!==void 0&&(Ko.test(window.document.location.hostname)||b==="/"&&Jo.test(a))}function Lo(a){if(!a)return 1;var b=a;zb(11)&&a==="none"&&(b=window.document.location.hostname);b=b.indexOf(".")===0?b.substring(1):b;return b.split(".").length}function Mo(a){if(!a||a==="/")return 1;a[0]!=="/"&&(a="/"+a);a[a.length-1]!=="/"&&(a+="/");return a.split("/").length-1}
function No(a,b){var c=""+Lo(a),d=Mo(b);d>1&&(c+="-"+d);return c}
var zo=function(){return wo(window)?window.document.cookie:""},yo=function(a){return a&&Hk().j()?(Array.isArray(a)?a:[a]).every(function(b){return Pk(b)&&Mk(b)}):!0},Go=function(){var a=[],b=window.document.location.hostname.split(".");if(b.length===4){var c=b[b.length-1];if(Number(c).toString()===c)return["none"]}for(var d=b.length-2;d>=0;d--)a.push(b.slice(d).join("."));var e=window.document.location.hostname;Ko.test(e)||Jo.test(e)||a.push("none");return a};function Oo(a){var b=Math.round(Math.random()*2147483647),c;if(a){var d=1,e,f,g;if(a)for(d=0,f=a.length-1;f>=0;f--)g=a.charCodeAt(f),d=(d<<6&268435455)+g+(g<<14),e=d&266338304,d=e!==0?d^e>>21:d;c=String(b^d&2147483647)}else c=String(b);return c}function Po(a){return[Oo(a),Math.round(Ob()/1E3)].join(".")}function Qo(a,b,c,d,e){var f=Lo(b);return Ao(a,f,Mo(c),d,e)}function Ro(a,b,c,d){return[b,No(c,d),a].join(".")};function So(a,b,c,d){var e,f=Number(a.Cb!=null?a.Cb:void 0);f!==0&&(e=new Date((b||Ob())+1E3*(f||7776E3)));return{path:a.path,domain:a.domain,flags:a.flags,encode:!!c,expires:e,Db:d}};var To;function Uo(){function a(g){c(g.target||g.srcElement||{})}function b(g){d(g.target||g.srcElement||{})}var c=Vo,d=Wo,e=Xo();if(!e.init){Pc(H,"mousedown",a);Pc(H,"keyup",a);Pc(H,"submit",b);var f=HTMLFormElement.prototype.submit;HTMLFormElement.prototype.submit=function(){d(this);f.call(this)};e.init=!0}}function Yo(a,b,c,d,e){var f={callback:a,domains:b,fragment:c===2,placement:c,forms:d,sameHost:e};Xo().decorators.push(f)}
function Zo(a,b,c){for(var d=Xo().decorators,e={},f=0;f<d.length;++f){var g=d[f],k;if(k=!c||g.forms)a:{var m=g.domains,n=a,p=!!g.sameHost;if(m&&(p||n!==H.location.hostname))for(var q=0;q<m.length;q++)if(m[q]instanceof RegExp){if(m[q].test(n)){k=!0;break a}}else if(n.indexOf(m[q])>=0||p&&m[q].indexOf(n)>=0){k=!0;break a}k=!1}if(k){var r=g.placement;r===void 0&&(r=g.fragment?2:1);r===b&&Rb(e,g.callback())}}return e}
function Xo(){var a=Gc("google_tag_data",{}),b=a.gl;b&&b.decorators||(b={decorators:[]},a.gl=b);return b};var $o=/(.*?)\*(.*?)\*(.*)/,ap=/^https?:\/\/([^\/]*?)\.?cdn\.ampproject\.org\/?(.*)/,bp=/^(?:www\.|m\.|amp\.)+/,cp=/([^?#]+)(\?[^#]*)?(#.*)?/;function dp(a){var b=cp.exec(a);if(b)return{Oh:b[1],query:b[2],fragment:b[3]}}
function ep(a,b){var c=[Cc.userAgent,(new Date).getTimezoneOffset(),Cc.userLanguage||Cc.language,Math.floor(Ob()/60/1E3)-(b===void 0?0:b),a].join("*"),d;if(!(d=To)){for(var e=Array(256),f=0;f<256;f++){for(var g=f,k=0;k<8;k++)g=g&1?g>>>1^3988292384:g>>>1;e[f]=g}d=e}To=d;for(var m=4294967295,n=0;n<c.length;n++)m=m>>>8^To[(m^c.charCodeAt(n))&255];return((m^-1)>>>0).toString(36)}
function fp(){return function(a){var b=nj(G.location.href),c=b.search.replace("?",""),d=gj(c,"_gl",!1,!0)||"";a.query=gp(d)||{};var e=hj(b,"fragment"),f;var g=-1;if(Tb(e,"_gl="))g=4;else{var k=e.indexOf("&_gl=");k>0&&(g=k+3+2)}if(g<0)f=void 0;else{var m=e.indexOf("&",g);f=m<0?e.substring(g):e.substring(g,m)}a.fragment=gp(f||"")||{}}}function hp(a){var b=fp(),c=Xo();c.data||(c.data={query:{},fragment:{}},b(c.data));var d={},e=c.data;e&&(Rb(d,e.query),a&&Rb(d,e.fragment));return d}
var gp=function(a){try{var b=ip(a,3);if(b!==void 0){for(var c={},d=b?b.split("*"):[],e=0;e+1<d.length;e+=2){var f=d[e],g=sb(d[e+1]);c[f]=g}ub("TAGGING",6);return c}}catch(k){ub("TAGGING",8)}};function ip(a,b){if(a){var c;a:{for(var d=a,e=0;e<3;++e){var f=$o.exec(d);if(f){c=f;break a}d=decodeURIComponent(d)}c=void 0}var g=c;if(g&&g[1]==="1"){var k=g[3],m;a:{for(var n=g[2],p=0;p<b;++p)if(n===ep(k,p)){m=!0;break a}m=!1}if(m)return k;ub("TAGGING",7)}}}
function jp(a,b,c,d,e){function f(p){var q=p,r=(new RegExp("(.*?)(^|&)"+a+"=([^&]*)&?(.*)")).exec(q),t=q;if(r){var u=r[2],v=r[4];t=r[1];v&&(t=t+u+v)}p=t;var w=p.charAt(p.length-1);p&&w!=="&"&&(p+="&");return p+n}d=d===void 0?!1:d;e=e===void 0?!1:e;var g=dp(c);if(!g)return"";var k=g.query||"",m=g.fragment||"",n=a+"="+b;d?m.substring(1).length!==0&&e||(m="#"+f(m.substring(1))):k="?"+f(k.substring(1));return""+g.Oh+k+m}
function kp(a,b){function c(n,p,q){var r;a:{for(var t in n)if(n.hasOwnProperty(t)){r=!0;break a}r=!1}if(r){var u,v=[],w;for(w in n)if(n.hasOwnProperty(w)){var x=n[w];x!==void 0&&x===x&&x!==null&&x.toString()!=="[object Object]"&&(v.push(w),v.push(rb(String(x))))}var y=v.join("*");u=["1",ep(y),y].join("*");d?(zb(4)||zb(1)||!p)&&lp("_gl",u,a,p,q):mp("_gl",u,a,p,q)}}var d=(a.tagName||"").toUpperCase()==="FORM",e=Zo(b,1,d),f=Zo(b,2,d),g=Zo(b,4,d),k=Zo(b,3,d);c(e,!1,!1);c(f,!0,!1);zb(1)&&c(g,!0,!0);for(var m in k)k.hasOwnProperty(m)&&
np(m,k[m],a)}function np(a,b,c){c.tagName.toLowerCase()==="a"?mp(a,b,c):c.tagName.toLowerCase()==="form"&&lp(a,b,c)}function mp(a,b,c,d,e){d=d===void 0?!1:d;e=e===void 0?!1:e;var f;if(f=c.href){var g;if(!(g=!zb(5)||d)){var k=G.location.href,m=dp(c.href),n=dp(k);g=!(m&&n&&m.Oh===n.Oh&&m.query===n.query&&m.fragment)}f=g}if(f){var p=jp(a,b,c.href,d,e);sc.test(p)&&(c.href=p)}}
function lp(a,b,c,d,e){d=d===void 0?!1:d;e=e===void 0?!1:e;if(c&&c.action){var f=(c.method||"").toLowerCase();if(f!=="get"||d){if(f==="get"||f==="post"){var g=jp(a,b,c.action,d,e);sc.test(g)&&(c.action=g)}}else{for(var k=c.childNodes||[],m=!1,n=0;n<k.length;n++){var p=k[n];if(p.name===a){p.setAttribute("value",b);m=!0;break}}if(!m){var q=H.createElement("input");q.setAttribute("type","hidden");q.setAttribute("name",a);q.setAttribute("value",b);c.appendChild(q)}}}}
function Vo(a){try{var b;a:{for(var c=a,d=100;c&&d>0;){if(c.href&&c.nodeName.match(/^a(?:rea)?$/i)){b=c;break a}c=c.parentNode;d--}b=null}var e=b;if(e){var f=e.protocol;f!=="http:"&&f!=="https:"||kp(e,e.hostname)}}catch(g){}}function Wo(a){try{if(a.action){var b=hj(nj(a.action),"host");kp(a,b)}}catch(c){}}function op(a,b,c,d){Uo();var e=c==="fragment"?2:1;d=!!d;Yo(a,b,e,d,!1);e===2&&ub("TAGGING",23);d&&ub("TAGGING",24)}function pp(a,b){Uo();Yo(a,[jj(G.location,"host",!0)],b,!0,!0)}
function qp(){var a=H.location.hostname,b=ap.exec(H.referrer);if(!b)return!1;var c=b[2],d=b[1],e="";if(c){var f=c.split("/"),g=f[1];e=g==="s"?decodeURIComponent(f[2]):decodeURIComponent(g)}else if(d){if(d.indexOf("xn--")===0)return!1;e=d.replace(/-/g,".").replace(/\.\./g,"-")}var k=a.replace(bp,""),m=e.replace(bp,"");return k===m||Ub(k,"."+m)}function rp(a,b){return a===!1?!1:a||b||qp()};var sp=["1"],tp={},up={};function vp(a,b){b=b===void 0?!0:b;var c=wp(a.prefix);if(!tp[c])if(xp(c,a.path,a.domain)){var d=up[wp(a.prefix)];yp(a,d?d.id:void 0,d?d.Ih:void 0)}else{var e=pj("auiddc");if(e)ub("TAGGING",17),tp[c]=e;else if(b){var f=wp(a.prefix),g=Po();zp(f,g,a);xp(c,a.path,a.domain)}}}function yp(a,b,c){var d=wp(a.prefix),e=tp[d];if(e){var f=e.split(".");if(f.length===2){var g=Number(f[1])||0;if(g){var k=e;b&&(k=e+"."+b+"."+(c?c:Math.floor(Ob()/1E3)));zp(d,k,a,g*1E3)}}}}
function zp(a,b,c,d){var e=Ro(b,"1",c.domain,c.path),f=So(c,d);f.Db=Ap();Io(a,e,f)}function xp(a,b,c){var d=Qo(a,b,c,sp,Ap());if(!d)return!1;Bp(a,d);return!0}function Bp(a,b){var c=b.split(".");c.length===5?(tp[a]=c.slice(0,2).join("."),up[a]={id:c.slice(2,4).join("."),Ih:Number(c[4])||0}):c.length===3?up[a]={id:c.slice(0,2).join("."),Ih:Number(c[2])||0}:tp[a]=b}function wp(a){return(a||"_gcl")+"_au"}function Cp(a){function b(){Mk(c)&&a()}var c=Ap();Tk(function(){b();Mk(c)||Uk(b,c)},c)}
function Dp(a){var b=hp(!0),c=wp(a.prefix);Cp(function(){var d=b[c];if(d){Bp(c,d);var e=Number(tp[c].split(".")[1])*1E3;if(e){ub("TAGGING",16);var f=So(a,e);f.Db=Ap();var g=Ro(d,"1",a.domain,a.path);Io(c,g,f)}}})}function Ep(a,b,c,d,e){e=e||{};var f=function(){var g={},k=Qo(a,e.path,e.domain,sp,Ap());k&&(g[a]=k);return g};Cp(function(){op(f,b,c,d)})}function Ap(){return["ad_storage","ad_user_data"]};function Fp(a){for(var b=[],c=H.cookie.split(";"),d=new RegExp("^\\s*"+(a||"_gac")+"_(UA-\\d+-\\d+)=\\s*(.+?)\\s*$"),e=0;e<c.length;e++){var f=c[e].match(d);f&&b.push({di:f[1],value:f[2],timestamp:Number(f[2].split(".")[1])||0})}b.sort(function(g,k){return k.timestamp-g.timestamp});return b}
function Gp(a,b){var c=Fp(a),d={};if(!c||!c.length)return d;for(var e=0;e<c.length;e++){var f=c[e].value.split(".");if(!(f[0]!=="1"||b&&f.length<3||!b&&f.length!==3)&&Number(f[1])){d[c[e].di]||(d[c[e].di]=[]);var g={version:f[0],timestamp:Number(f[1])*1E3,aa:f[2]};b&&f.length>3&&(g.labels=f.slice(3));d[c[e].di].push(g)}}return d};var Hp={},Ip=(Hp.k={Na:/^[\w-]+$/},Hp.b={Na:/^[\w-]+$/,Vh:!0},Hp.i={Na:/^[1-9]\d*$/},Hp);var Jp={},Mp=(Jp[5]={zk:{2:Kp},jh:["k","i","b"]},Jp[4]={zk:{2:Kp,GCL:Lp},jh:["k","i","b"]},Jp);function Np(a){var b=Mp[5];if(b){var c=a.split(".")[0];if(c){var d=b.zk[c];if(d)return d(a,5)}}}function Kp(a,b){var c=a.split(".");if(c.length===3){var d={},e=Mp[b];if(e){for(var f=e.jh,g=oa(c[2].split("$")),k=g.next();!k.done;k=g.next()){var m=k.value,n=m[0];if(f.indexOf(n)!==-1)try{var p=decodeURIComponent(m.substring(1)),q=Ip[n];q&&(q.Vh?(d[n]=d[n]||[],d[n].push(p)):d[n]=p)}catch(r){}}return d}}}
function Op(a,b){var c=Mp[5];if(c){for(var d=[],e=oa(c.jh),f=e.next();!f.done;f=e.next()){var g=f.value,k=Ip[g];if(k){var m=a[g];if(m!==void 0)if(k.Vh&&Array.isArray(m))for(var n=oa(m),p=n.next();!p.done;p=n.next())d.push(encodeURIComponent(""+g+p.value));else d.push(encodeURIComponent(""+g+m))}}return["2",b||"1",d.join("$")].join(".")}}function Lp(a){var b=a.split(".");b.shift();var c=b.shift(),d=b.shift(),e={};return e.k=d,e.i=c,e.b=b,e};var Pp=new Map([[5,"ad_storage"],[4,["ad_storage","ad_user_data"]]]);function Qp(a){if(Mp[5]){for(var b=[],c=xo(a,void 0,void 0,Pp.get(5)),d=oa(c),e=d.next();!e.done;e=d.next()){var f=Np(e.value);f&&(Rp(f),b.push(f))}return b}}function Sp(a,b,c,d){c=c||{};var e=No(c.domain,c.path),f=Op(b,e);if(f){var g=So(c,d,void 0,Pp.get(5));Io(a,f,g)}}function Tp(a,b){var c=b.Na;return typeof c==="function"?c(a):c.test(a)}
function Rp(a){for(var b=oa(Object.keys(a)),c=b.next(),d={};!c.done;d={Be:void 0},c=b.next()){var e=c.value,f=a[e];d.Be=Ip[e];d.Be?d.Be.Vh?a[e]=Array.isArray(f)?f.filter(function(g){return function(k){return Tp(k,g.Be)}}(d)):void 0:typeof f==="string"&&Tp(f,d.Be)||(a[e]=void 0):a[e]=void 0}};var Up=/^\w+$/,Vp=/^[\w-]+$/,Wp={},Xp=(Wp.aw="_aw",Wp.dc="_dc",Wp.gf="_gf",Wp.gp="_gp",Wp.gs="_gs",Wp.ha="_ha",Wp.ag="_ag",Wp.gb="_gb",Wp);function Yp(){return["ad_storage","ad_user_data"]}function Zp(a){return!Hk().j()||Mk(a)}function $p(a,b){function c(){var d=Zp(b);d&&a();return d}Tk(function(){c()||Uk(c,b)},b)}function aq(a){return bq(a).map(function(b){return b.aa})}function cq(a){return dq(a).filter(function(b){return b.aa}).map(function(b){return b.aa})}
function dq(a){var b=eq(a.prefix),c=fq("gb",b),d=fq("ag",b);if(!d||!c)return[];var e=function(k){return function(m){m.type=k;return m}},f=bq(c).map(e("gb")),g=(zb(7)?gq(d):[]).map(e("ag"));return f.concat(g).sort(function(k,m){return m.timestamp-k.timestamp})}function hq(a,b,c,d,e){var f=Eb(a,function(g){return g.aa===c});f?(f.timestamp=Math.max(f.timestamp,d),f.labels=iq(f.labels||[],e||[])):a.push({version:b,aa:c,timestamp:d,labels:e})}
function gq(a){for(var b=Qp(a)||[],c=[],d=oa(b),e=d.next();!e.done;e=d.next()){var f=e.value,g=f,k=jq(f);k&&hq(c,"2",g.k,k,g.b||[])}return c.sort(function(m,n){return n.timestamp-m.timestamp})}function bq(a){for(var b=[],c=xo(a,H.cookie,void 0,Yp()),d=oa(c),e=d.next();!e.done;e=d.next()){var f=kq(e.value);if(f!=null){var g=f;hq(b,g.version,g.aa,g.timestamp,g.labels)}}b.sort(function(k,m){return m.timestamp-k.timestamp});return lq(b)}
function iq(a,b){if(!a.length)return b;if(!b.length)return a;var c={};return a.concat(b).filter(function(d){return c.hasOwnProperty(d)?!1:c[d]=!0})}function eq(a){return a&&typeof a==="string"&&a.match(Up)?a:"_gcl"}
function mq(a,b){var c=zb(7),d=nj(a),e=hj(d,"query",!1,void 0,"gclid"),f=hj(d,"query",!1,void 0,"gclsrc"),g=hj(d,"query",!1,void 0,"wbraid");g=$b(g);var k;c&&(k=hj(d,"query",!1,void 0,"gbraid"));var m=hj(d,"query",!1,void 0,"gad_source"),n=hj(d,"query",!1,void 0,"dclid");if(b&&(!e||!f||!g||c&&!k)){var p=d.hash.replace("#","");e=e||gj(p,"gclid",!1);f=f||gj(p,"gclsrc",!1);g=g||gj(p,"wbraid",!1);c&&(k=k||gj(p,"gbraid",!1));m=m||gj(p,"gad_source",!1)}return nq(e,f,n,g,k,m)}
function oq(){return mq(G.location.href,!0)}
function nq(a,b,c,d,e,f){var g={},k=function(m,n){g[n]||(g[n]=[]);g[n].push(m)};g.gclid=a;g.gclsrc=b;g.dclid=c;if(a!==void 0&&a.match(Vp))switch(b){case void 0:k(a,"aw");break;case "aw.ds":k(a,"aw");k(a,"dc");break;case "ds":k(a,"dc");break;case "3p.ds":k(a,"dc");break;case "gf":k(a,"gf");break;case "ha":k(a,"ha")}c&&k(c,"dc");d!==void 0&&Vp.test(d)&&(g.wbraid=d,k(d,"gb"));zb(7)&&e!==void 0&&Vp.test(e)&&(g.gbraid=e,k(e,"ag"));f!==void 0&&Vp.test(f)&&(g.gad_source=f,k(f,"gs"));return g}
function pq(a){var b=oq();if(zb(6)){for(var c=!0,d=oa(Object.keys(b)),e=d.next();!e.done;e=d.next())if(b[e.value]!==void 0){c=!1;break}c&&(b=mq(G.document.referrer,!1))}qq(b,!1,a)}
function qq(a,b,c,d,e){c=c||{};e=e||[];var f=eq(c.prefix),g=d||Ob(),k=Math.round(g/1E3),m=Yp(),n=!1,p=!1,q=function(){if(Zp(m)){var r=So(c,g,!0);r.Db=m;for(var t=function(F,L){var M=fq(F,f);M&&(Io(M,L,r),F!=="gb"&&(n=!0))},u=function(F){var L=["GCL",k,F];e.length>0&&L.push(e.join("."));return L.join(".")},v=oa(["aw","dc","gf","ha","gp"]),w=v.next();!w.done;w=v.next()){var x=w.value;a[x]&&t(x,u(a[x][0]))}if(!n&&a.gb){var y=a.gb[0],B=fq("gb",f);!b&&bq(B).some(function(F){return F.aa===y&&F.labels&&
F.labels.length>0})||t("gb",u(y))}}if(!p&&zb(7)&&a.gbraid&&Zp("ad_storage")&&(p=!0,!n)){var A=a.gbraid,C=fq("ag",f);if(b||!(zb(7)?gq(C):[]).some(function(F){return F.aa===A&&F.labels&&F.labels.length>0})){var E={},D=(E.k=A,E.i=""+k,E.b=e,E);Sp(C,D,c,g)}}rq(a,f,g,c)};Tk(function(){q();Zp(m)||Uk(q,m)},m)}function rq(a,b,c,d){if(a.gad_source!==void 0&&Zp("ad_storage")){var e=fq("gs",b);if(e){var f=Math.round((Ob()-(ad()||0))/1E3),g={},k=(g.k=a.gad_source,g.i=""+f,g);Sp(e,k,d,c)}}}
function sq(a,b){var c=hp(!0);$p(function(){for(var d=eq(b.prefix),e=0;e<a.length;++e){var f=a[e];if(Xp[f]!==void 0){var g=fq(f,d),k=c[g];if(k){var m=Math.min(tq(k),Ob()),n;b:{for(var p=m,q=xo(g,H.cookie,void 0,Yp()),r=0;r<q.length;++r)if(tq(q[r])>p){n=!0;break b}n=!1}if(!n){var t=So(b,m,!0);t.Db=Yp();Io(g,k,t)}}}}qq(nq(c.gclid,c.gclsrc),!1,b)},Yp())}
function uq(a){var b=[];zb(7)&&b.push("ag");if(b.length!==0){var c=hp(!0),d=eq(a.prefix);$p(function(){for(var e=0;e<b.length;++e){var f=fq(b[e],d);if(f){var g=c[f];if(g){var k=Np(g);if(k){var m=jq(k);m||(m=Ob());var n;a:{for(var p=m,q=Qp(f),r=0;r<q.length;++r)if(jq(q[r])>p){n=!0;break a}n=!1}if(n)break;k.i=""+Math.round(m/1E3);Sp(f,k,a,m)}}}}},["ad_storage"])}}function fq(a,b){var c=Xp[a];if(c!==void 0)return b+c}
function tq(a){return vq(a.split(".")).length!==0?(Number(a.split(".")[1])||0)*1E3:0}function jq(a){return a?(Number(a.i)||0)*1E3:0}function kq(a){var b=vq(a.split("."));return b.length===0?null:{version:b[0],aa:b[2],timestamp:(Number(b[1])||0)*1E3,labels:b.slice(3)}}function vq(a){return a.length<3||a[0]!=="GCL"&&a[0]!=="1"||!/^\d+$/.test(a[1])||!Vp.test(a[2])?[]:a}
function wq(a,b,c,d,e){if(Array.isArray(b)&&wo(G)){var f=eq(e),g=function(){for(var k={},m=0;m<a.length;++m){var n=fq(a[m],f);if(n){var p=xo(n,H.cookie,void 0,Yp());p.length&&(k[n]=p.sort()[p.length-1])}}return k};$p(function(){op(g,b,c,d)},Yp())}}
function xq(a,b,c,d){if(Array.isArray(a)&&wo(G)){var e=[];zb(7)&&e.push("ag");if(e.length!==0){var f=eq(d),g=function(){for(var k={},m=0;m<e.length;++m){var n=fq(e[m],f);if(!n)return{};var p=Qp(n);if(p.length){var q=p.sort(function(r,t){return jq(t)-jq(r)})[0];k[n]=Op(q)}}return k};$p(function(){op(g,a,b,c)},["ad_storage"])}}}function lq(a){return a.filter(function(b){return Vp.test(b.aa)})}
function yq(a,b){if(wo(G)){for(var c=eq(b.prefix),d={},e=0;e<a.length;e++)Xp[a[e]]&&(d[a[e]]=Xp[a[e]]);$p(function(){z(d,function(f,g){var k=xo(c+g,H.cookie,void 0,Yp());k.sort(function(t,u){return tq(u)-tq(t)});if(k.length){var m=k[0],n=tq(m),p=vq(m.split(".")).length!==0?m.split(".").slice(3):[],q={},r;r=vq(m.split(".")).length!==0?m.split(".")[2]:void 0;q[f]=[r];qq(q,!0,b,n,p)}})},Yp())}}
function zq(a){var b=[],c=[];zb(7)&&(b.push("ag"),c.push("gbraid"));b.length!==0&&$p(function(){for(var d=eq(a.prefix),e=0;e<b.length;++e){var f=fq(b[e],d);if(!f)break;var g=Qp(f);if(g.length){var k=g.sort(function(q,r){return jq(r)-jq(q)})[0],m=jq(k),n=k.b,p={};p[c[e]]=k.k;qq(p,!0,a,m,n)}}},["ad_storage"])}function Aq(a,b){for(var c=0;c<b.length;++c)if(a[b[c]])return!0;return!1}
function Bq(a){function b(e,f,g){g&&(e[f]=g)}if(Qk()){var c=oq();if(Aq(c,a)){var d={};b(d,"gclid",c.gclid);b(d,"dclid",c.dclid);b(d,"gclsrc",c.gclsrc);b(d,"wbraid",c.wbraid);zb(7)&&b(d,"gbraid",c.gbraid);pp(function(){return d},3);pp(function(){var e={};return e._up="1",e},1)}}}
function Cq(a){if(!zb(1))return null;var b=hp(!0).gad_source;if(b!=null)return G.location.hash="",b;if(zb(2)){var c=nj(G.location.href);b=hj(c,"query",!1,void 0,"gad_source");if(b!=null)return b;var d=oq();if(Aq(d,a))return"0"}return null}function Dq(a){var b=Cq(a);b!=null&&pp(function(){var c={};return c.gad_source=b,c},4)}
function Eq(a,b,c){var d=[];if(b.length===0)return d;for(var e={},f=0;f<b.length;f++){var g=b[f],k=g.type?g.type:"gcl";(g.labels||[]).indexOf(c)===-1?(a.push(0),e[k]||d.push(g)):a.push(1);e[k]=!0}return d}function Fq(a,b,c,d){var e=[];c=c||{};if(!Zp(Yp()))return e;var f=bq(a),g=Eq(e,f,b);if(g.length&&!d)for(var k=oa(g),m=k.next();!m.done;m=k.next()){var n=m.value,p=n.timestamp,q=[n.version,Math.round(p/1E3),n.aa].concat(n.labels||[],[b]).join("."),r=So(c,p,!0);r.Db=Yp();Io(a,q,r)}return e}
function Gq(a,b){var c=[];b=b||{};var d=dq(b),e=Eq(c,d,a);if(e.length)for(var f=oa(e),g=f.next();!g.done;g=f.next()){var k=g.value,m=eq(b.prefix),n=fq(k.type,m);if(!n)break;var p=k,q=p.version,r=p.aa,t=p.labels,u=p.timestamp,v=Math.round(u/1E3);if(k.type==="ag"){var w={},x=(w.k=r,w.i=""+v,w.b=(t||[]).concat([a]),w);Sp(n,x,b,u)}else if(k.type==="gb"){var y=[q,v,r].concat(t||[],[a]).join("."),B=So(b,u,!0);B.Db=Yp();Io(n,y,B)}}return c}
function Hq(a,b){var c=eq(b),d=fq(a,c);if(!d)return 0;var e;e=a==="ag"?zb(7)?gq(d):[]:bq(d);for(var f=0,g=0;g<e.length;g++)f=Math.max(f,e[g].timestamp);return f}function Iq(a){for(var b=0,c=oa(Object.keys(a)),d=c.next();!d.done;d=c.next())for(var e=a[d.value],f=0;f<e.length;f++)b=Math.max(b,Number(e[f].timestamp));return b}function Jq(a,b){var c=Math.max(Hq("aw",a),Iq(Zp(Yp())?Gp():{})),d=Math.max(Hq("gb",a),Iq(Zp(Yp())?Gp("_gac_gb",!0):{}));zb(7)&&b&&(d=Math.max(d,Hq("ag",a)));return d>c};
var Kq=function(a,b,c){var d=vi.joined_auid=vi.joined_auid||{},e=(c?a||"_gcl":"")+"."+b;if(d[e])return!0;d[e]=!0;return!1},Lq=function(){var a=nj(G.location.href),b=void 0,c=void 0,d=hj(a,"query",!1,void 0,"gad_source"),e=a.hash.replace("#",""),f=gj(e,"gad_source",!1);d&&f?(b=d,c=1):d?(b=d,c=2):f&&(b=f,c=3);return{rd:b,Uj:c}},Mq=function(){var a=nj(G.location.href),b=hj(a,"query",!1,void 0,"gad_source");if(b===void 0){var c=a.hash.replace("#","");b=gj(c,"gad_source",!1)}return b},Nq=function(){var a=
nj(G.location.href).search.replace("?","");return gj(a,"gad",!1,!0)==="1"},Oq=function(){var a=pn(!1)===1?G.top.location.href:G.location.href;return a=a.replace(/[\?#].*$/,"")},Pq=function(a){var b=[];z(a,function(c,d){d=lq(d);for(var e=[],f=0;f<d.length;f++)e.push(d[f].aa);e.length&&b.push(c+":"+e.join(","))});return b.join(";")},Rq=function(a,b,c){if(a==="aw"||a==="dc"||a==="gb"){var d=pj("gcl"+a);if(d)return d.split(".")}var e=eq(b);if(e==="_gcl"){var f=!W(Qq())&&c,g;g=oq()[a]||[];if(g.length>
0)return f?["0"]:g}var k=fq(a,e);return k?aq(k):[]},Sq=function(a){var b=Qq();sl(function(){a();W(b)||Uk(a,b)},b)},Qq=function(){return[P.g.R,P.g.P]},Tq=/^(www\.)?google(\.com?)?(\.[a-z]{2}t?)?$/,Uq=/^www.googleadservices.com$/,Vq=function(a,b){return Rq("aw",a,b)},Wq=function(a,b){return Rq("dc",a,b)},Xq=function(a,b,c,d,e){var f=oq(),g=[],k=c&&Tn(c),m=f.gclid,n=f.dclid,p=f.gclsrc||"aw",q=Nq(),r,t;if(T(64)){var u=Lq();r=u.rd;t=u.Uj}else r=Mq();!m||p!=="aw.ds"&&p!=="aw"&&p!=="ds"&&p!=="3p.ds"||g.push({aa:m,
Ie:p});n&&g.push({aa:n,Ie:"ds"});g.length===2&&O(147);g.length===0&&f.wbraid&&g.push({aa:f.wbraid,Ie:"gb"});g.length===0&&p==="aw.ds"&&g.push({aa:"",Ie:"aw.ds"});Sq(function(){var v=W(Qq());if(v){vp(a);var w=[],x=v?tp[wp(a.prefix)]:void 0;x&&w.push("auid="+x);if(W(P.g.P)){e&&w.push("userId="+e);var y=to(oo.ah);if(y===void 0)so(oo.bh,!0);else{var B=to(oo.ue);w.push("ga_uid="+B+"."+y)}}var A=H.referrer?hj(nj(H.referrer),"host"):"",C=v||!d?g:[];C.length===0&&(Tq.test(A)||Uq.test(A))&&C.push({aa:"",Ie:""});
if(C.length!==0||q||r!==void 0){A&&w.push("ref="+encodeURIComponent(A));var E=Oq();w.push("url="+encodeURIComponent(E));w.push("tft="+Ob());var D=ad();D!==void 0&&w.push("tfd="+Math.round(D));var F=pn(!0);w.push("frm="+F);q&&w.push("gad=1");r!==void 0&&w.push("gad_source="+encodeURIComponent(r));t!==void 0&&w.push("gad_source_src="+encodeURIComponent(t.toString()));if(!c){var L={};c=gm(Xl(new Wl(0),(L[P.g.ka]=Bm.D[P.g.ka],L)))}else if(!T(77)){var M={};c=gm(Xl(new Wl(0),(M[P.g.ka]=k,M)))}w.push("gtm="+
no({xa:b}));Un()&&w.push("gcs="+Vn());w.push("gcd="+fo(c));io()&&w.push("dma_cps="+go());w.push("dma="+ho());Tn(c)?w.push("npa=0"):w.push("npa=1");ko()&&w.push("_ng=1");yn(Gn())&&w.push("tcfd="+jo());var S=Nn();S&&w.push("gdpr="+S);var V=Mn();V&&w.push("gdpr_consent="+V);T(17)&&w.push("apve="+(T(18)?1:0));Oi.j&&w.push("tag_exp="+Oi.j);if(C.length>0)for(var aa=0;aa<C.length;aa++){var X=C[aa],R=X.aa,ma=X.Ie;if(!Kq(a.prefix,ma+"."+R,x!==void 0)){var la='https://adservice.google.com/pagead/regclk?'+w.join("&");
R!==""?la=ma==="gb"?la+"&wbraid="+R:la+"&gclid="+R+"&gclsrc="+ma:ma==="aw.ds"&&(la+="&gclsrc=aw.ds");Vc(la)}}else if((q||r!==void 0)&&!Kq(a.prefix,"gad",x!==void 0)){var ha='https://adservice.google.com/pagead/regclk?'+w.join("&");Vc(ha)}}}})};function Yq(){vi.dedupe_gclid||(vi.dedupe_gclid=Po());return vi.dedupe_gclid};var Zq=/^(www\.)?google(\.com?)?(\.[a-z]{2}t?)?$/,$q=/^www.googleadservices.com$/;function ar(a){a||(a=br());return a.rn?!1:a.bm||a.dm||a.gm||a.fm||a.zh||a.rd||a.Pl||a.Tl?!0:!1}
function br(){var a={},b=hp(!0);a.rn=!!b._up;var c=oq();a.bm=c.aw!==void 0;a.dm=c.dc!==void 0;a.gm=c.wbraid!==void 0;a.fm=c.gbraid!==void 0;var d=nj(G.location.href),e=hj(d,"query",!1,void 0,"gad");a.zh=e!==void 0;if(!a.zh){var f=d.hash.replace("#",""),g=gj(f,"gad",!1);a.zh=g!==void 0}a.rd=hj(d,"query",!1,void 0,"gad_source");if(a.rd===void 0){var k=d.hash.replace("#",""),m=gj(k,"gad_source",!1);a.rd=m}var n=H.referrer?hj(nj(H.referrer),"host"):"";a.Tl=Zq.test(n);a.Pl=$q.test(n);return a};var cr=RegExp("^UA-\\d+-\\d+%3A[\\w-]+(?:%2C[\\w-]+)*(?:%3BUA-\\d+-\\d+%3A[\\w-]+(?:%2C[\\w-]+)*)*$"),dr=/^~?[\w-]+(?:\.~?[\w-]+)*$/,er=/^\d+\.fls\.doubleclick\.net$/,fr=/;gac=([^;?]+)/,gr=/;gacgb=([^;?]+)/;
function hr(a,b){if(er.test(H.location.host)){var c=H.location.href.match(b);return c&&c.length===2&&c[1].match(cr)?decodeURIComponent(c[1]):""}for(var d=[],e=oa(Object.keys(a)),f=e.next();!f.done;f=e.next()){for(var g=f.value,k=[],m=a[g],n=0;n<m.length;n++)k.push(m[n].aa);d.push(g+":"+k.join(","))}return d.length>0?d.join(";"):""}
function ir(a,b,c){for(var d=Zp(Yp())?Gp("_gac_gb",!0):{},e=[],f=!1,g=oa(Object.keys(d)),k=g.next();!k.done;k=g.next()){var m=k.value,n=Fq("_gac_gb_"+m,a,b,c);f=f||n.length!==0&&n.some(function(p){return p===1});e.push(m+":"+n.join(","))}return{Ol:f?e.join(";"):"",Nl:hr(d,gr)}}function jr(a){var b=H.location.href.match(new RegExp(";"+a+"=([^;?]+)"));return b&&b.length===2&&b[1].match(dr)?b[1]:void 0}
function kr(a){var b={vh:void 0,wh:void 0},c,d;er.test(H.location.host)&&(c=jr("gclgs"),d=jr("gclst"));if(c&&d)b.vh=c,b.wh=d;else{var e=Ob(),f=gq((a||"_gcl")+"_gs"),g=f.map(function(m){return m.aa}),k=f.map(function(m){return e-m.timestamp});g.length>0&&k.length>0&&(b.vh=g.join("."),b.wh=k.join("."))}return b}
function lr(a,b,c){if(er.test(H.location.host)){var d=jr(c);if(d)return[{aa:d}]}else{if(b==="gclid")return bq((a||"_gcl")+"_aw");if(b==="wbraid")return bq((a||"_gcl")+"_gb");if(b==="braids")return dq({prefix:a})}return[]}function mr(a){return lr(a,"gclid","gclaw").map(function(b){return b.aa}).join(".")}function nr(a){return lr(a,"wbraid","gclgb").map(function(b){return b.aa}).join(".")}function or(a){return lr(a,"braids","gclgb").map(function(b){return b.aa}).join(".")}
function pr(a,b){return er.test(H.location.host)?!(jr("gclaw")||jr("gac")):Jq(a,b)}function qr(a,b,c){var d;d=c?Gq(a,b):Fq((b&&b.prefix||"_gcl")+"_gb",a,b);return d.length===0||d.every(function(e){return e===0})?"":d.join(".")};function rr(){var a=G.__uspapi;if(Bb(a)){var b="";try{a("getUSPData",1,function(c,d){if(d&&c){var e=c.uspString;e&&RegExp("^[\\da-zA-Z-]{1,20}$").test(e)&&(b=e)}})}catch(c){}return b}};
var vr=function(a){if(a.eventName===P.g.ba&&a.metadata.hit_type==="page_view")if(T(18)){a.metadata.redact_click_ids=U(a.m,P.g.fa)!=null&&U(a.m,P.g.fa)!==!1&&!W([P.g.R,P.g.P]);var b=sr(a),c=U(a.m,P.g.ra)!==!1;c||(a.o[P.g.Li]="1");var d=eq(b.prefix),e=a.metadata.is_server_side_destination;if(!a.metadata.consent_updated&&!a.metadata.user_id_updated){var f=U(a.m,P.g.Xa),g=U(a.m,P.g.sa)||{};tr({pd:c,xd:g,Dd:f,jc:b});var k;if(k=!e){var m;var n=vi.ads_pageview=vi.ads_pageview||{};m=n[d]?!1:n[d]=!0;k=!m}if(k){a.isAborted=
!0;return}}if(e)a.isAborted=!0;else{a.o[P.g.xc]=P.g.Vb;if(a.metadata.consent_updated)a.o[P.g.xc]=P.g.Ek,a.o[P.g.Tb]="1";else if(a.metadata.user_id_updated)a.o[P.g.xc]=P.g.Jk;else{var p=oq();a.o[P.g.Gd]=p.gclid;a.o[P.g.Od]=p.dclid;a.o[P.g.Gi]=p.gclsrc;a.o[P.g.Gd]||a.o[P.g.Od]||(a.o[P.g.df]=p.wbraid,a.o[P.g.lg]=p.gbraid);a.o[P.g.Fa]=H.referrer?hj(nj(H.referrer),"host"):"";a.o[P.g.wa]=Oq();T(21)&&(a.o[P.g.cb]=ur());var q;if(T(64)){var r=Lq();q=r.rd;a.o[P.g.Fi]=r.Uj}else q=Mq();a.o[P.g.Ei]=q;a.o[P.g.Kb]=
pn(!0);var t=br();ar(t)&&(a.o[P.g.ed]="1");a.o[P.g.Ii]=Yq();hp(!1)._up==="1"&&(a.o[P.g.Yi]="1")}Wk=!0;var u=W([P.g.R,P.g.P]);c&&u&&(vp(b),a.o[P.g.Hb]=tp[wp(b.prefix)]);a.o[P.g.nb]=void 0;a.o[P.g.Va]=void 0;var v=T(66);if(!a.o[P.g.Gd]&&!a.o[P.g.Od]&&pr(d,v)){var w=v?cq(b):aq(d+"_gb");w.length>0&&(a.o[P.g.nb]=w.join("."))}else if(!a.o[P.g.df]&&u){var x=aq(d+"_aw");x.length>0&&(a.o[P.g.Va]=x.join("."))}a.m.isGtmEvent&&(a.m.j[P.g.ka]=Bm.D[P.g.ka]);Tn(a.m)?a.o[P.g.Pb]=!1:a.o[P.g.Pb]=!0;a.metadata.add_tag_timing=
!0;var y=rr();y!==void 0&&(a.o[P.g.he]=y||"error");var B=Nn();B&&(a.o[P.g.Ac]=B);var A=Mn();A&&(a.o[P.g.Dc]=A);a.metadata.speculative=!1}}else a.isAborted=!0},sr=function(a){var b={prefix:U(a.m,P.g.Za)||U(a.m,P.g.Qa),domain:U(a.m,P.g.Wa),Cb:U(a.m,P.g.Pa),flags:U(a.m,P.g.ab)};a.m.isGtmEvent&&(b.path=U(a.m,P.g.Ib));return b},wr=function(a,b){var c,d,e,f,g,k,m,n;c=a.pd;d=a.xd;e=a.Dd;f=a.xa;g=a.m;k=a.yd;m=a.Sn;n=a.vk;tr({pd:c,xd:d,Dd:e,jc:b});c&&m!==!0&&(n!=null?n=String(n):n=void 0,Xq(b,f,g,k,n))},tr=
function(a){var b,c,d,e;b=a.pd;c=a.xd;d=a.Dd;e=a.jc;b&&(rp(c[P.g.Cc],!!c[P.g.X])&&(sq(xr,e),uq(e),Dp(e)),pq(e),yq(xr,e),zq(e));c[P.g.X]&&(wq(xr,c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e.prefix),xq(c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e.prefix),Ep(wp(e.prefix),c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e),Ep("FPAU",c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e));d&&Bq(yr);Dq(yr)},zr=function(a,b,c,d){var e,f,g;e=a.wk;f=a.callback;g=a.Zj;if(typeof f==="function")if(e===P.g.Va&&g===void 0){var k=d(b.prefix,c);k.length===0?f(void 0):k.length===
1?f(k[0]):f(k)}else e===P.g.Hb?(O(65),vp(b,!1),f(tp[wp(b.prefix)])):f(g)},xr=["aw","dc","gb"],yr=["aw","dc","gb","ag"];function Ar(a){var b=U(a.m,P.g.Lb),c=U(a.m,P.g.Zb);b&&!c?(a.eventName!==P.g.ba&&a.eventName!==P.g.Nc&&O(131),a.isAborted=!0):!b&&c&&(O(132),a.isAborted=!0)}function Br(a){var b=W(P.g.R)?vi.pscdl:"denied";b!=null&&(a.o[P.g.jf]=b)}function Cr(a){var b=pn(!0);a.o[P.g.Kb]=b}function Dr(a){ko()&&(a.o[P.g.Bc]=1)}
function ur(){var a=H.title;if(a===void 0||a==="")return"";var b=function(d){try{return decodeURIComponent(d),!0}catch(e){return!1}};a=encodeURIComponent(a);for(var c=256;c>0&&!b(a.substring(0,c));)c--;return decodeURIComponent(a.substring(0,c))}function Er(a){if(T(12)){var b=U(a.m,P.g.Pa);a.o[P.g.ke]||(a.o[P.g.ke]={});a.o[P.g.ke].ce=b}};function Lr(a,b,c,d){var e=Mc(),f;if(e===1)a:{var g=Hi;g=g.toLowerCase();for(var k="https://"+g,m="http://"+g,n=1,p=H.getElementsByTagName("script"),q=0;q<p.length&&q<100;q++){var r=p[q].src;if(r){r=r.toLowerCase();if(r.indexOf(m)===0){f=3;break a}n===1&&r.indexOf(k)===0&&(n=2)}}f=n}else f=e;return(f===2||d||"http:"!=G.location.protocol?a:b)+c};function Yr(a){return{getDestinationId:function(){return a.target.ia},getEventName:function(){return a.eventName},setEventName:function(b){a.eventName=b},getHitData:function(b){return a.o[b]},setHitData:function(b,c){a.o[b]=c},setHitDataIfNotDefined:function(b,c){a.o[b]===void 0&&(a.o[b]=c)},copyToHitData:function(b,c){a.copyToHitData(b,c)},getMetadata:function(b){return a.metadata[b]},setMetadata:function(b,c){a.metadata[b]=c},isAborted:function(){return a.isAborted},abort:function(){a.isAborted=
!0},getFromEventContext:function(b){return U(a.m,b)},Vj:function(){return a},getHitKeys:function(){return Object.keys(a.o)}}};var $r=function(a){var b=Zr[a.target.ia];if(!a.isAborted&&b)for(var c=Yr(a),d=0;d<b.length;++d){try{b[d](c)}catch(e){a.isAborted=!0}if(a.isAborted)break}},as=function(a,b){var c=Zr[a];c||(c=Zr[a]=[]);c.push(b)},Zr={};var es,fs=!1;function gs(){fs=!0;es=es||{}}function hs(a){fs||gs();return es[a]}function is(){var a=G.screen;return{width:a?a.width:0,height:a?a.height:0}}
function js(a){if(H.hidden)return!0;var b=a.getBoundingClientRect();if(b.top===b.bottom||b.left===b.right||!G.getComputedStyle)return!0;var c=G.getComputedStyle(a,null);if(c.visibility==="hidden")return!0;for(var d=a,e=c;d;){if(e.display==="none")return!0;var f=e.opacity,g=e.filter;if(g){var k=g.indexOf("opacity(");k>=0&&(g=g.substring(k+8,g.indexOf(")",k)),g.charAt(g.length-1)==="%"&&(g=g.substring(0,g.length-1)),f=String(Math.min(Number(g),Number(f))))}if(f!==void 0&&Number(f)<=0)return!0;(d=d.parentElement)&&
(e=G.getComputedStyle(d,null))}return!1}
var ls=function(a){var b=ks(),c=b.height,d=b.width,e=a.getBoundingClientRect(),f=e.bottom-e.top,g=e.right-e.left;return f&&g?(1-Math.min((Math.max(0-e.left,0)+Math.max(e.right-d,0))/g,1))*(1-Math.min((Math.max(0-e.top,0)+Math.max(e.bottom-c,0))/f,1)):0},ks=function(){var a=H.body,b=H.documentElement||a&&a.parentElement,c,d;if(H.compatMode&&H.compatMode!=="BackCompat")c=b?b.clientHeight:0,d=b?b.clientWidth:0;else{var e=function(f,g){return f&&g?Math.min(f,g):Math.max(f,g)};c=e(b?b.clientHeight:0,a?
a.clientHeight:0);d=e(b?b.clientWidth:0,a?a.clientWidth:0)}return{width:d,height:c}};var os=function(a){if(ms){if(a>=0&&a<ns.length&&ns[a]){var b;(b=ns[a])==null||b.disconnect();ns[a]=void 0}}else G.clearInterval(a)},rs=function(a,b,c){for(var d=0;d<c.length;d++)c[d]>1?c[d]=1:c[d]<0&&(c[d]=0);if(ms){var e=!1;I(function(){e||ps(a,b,c)()});return qs(function(f){e=!0;for(var g={Me:0};g.Me<f.length;g={Me:g.Me},g.Me++)I(function(k){return function(){a(f[k.Me])}}(g))},
b,c)}return G.setInterval(ps(a,b,c),1E3)},ps=function(a,b,c){function d(k,m){var n={top:0,bottom:0,right:0,left:0,width:0,height:0},p={boundingClientRect:k.getBoundingClientRect(),intersectionRatio:m,intersectionRect:n,isIntersecting:m>0,rootBounds:n,target:k,time:Ob()};I(function(){a(p)})}for(var e=[],f=[],g=0;g<b.length;g++)e.push(0),f.push(-1);c.sort(function(k,m){return k-m});return function(){for(var k=0;k<b.length;k++){var m=ls(b[k]);if(m>e[k])for(;f[k]<c.length-1&&m>=c[f[k]+1];)d(b[k],m),f[k]++;
else if(m<e[k])for(;f[k]>=0&&m<=c[f[k]];)d(b[k],m),f[k]--;e[k]=m}}},qs=function(a,b,c){for(var d=new G.IntersectionObserver(a,{threshold:c}),e=0;e<b.length;e++)d.observe(b[e]);for(var f=0;f<ns.length;f++)if(!ns[f])return ns[f]=d,f;return ns.push(d)-1},ns=[],ms=!(!G.IntersectionObserver||!G.IntersectionObserverEntry);
var ts=function(a){return a.tagName+":"+a.isVisible+":"+a.Z.length+":"+ss.test(a.Z)},Hs=function(a){a=a||{vd:!0,wd:!0,Zf:void 0};a.zb=a.zb||{email:!0,phone:!1,address:!1};var b=us(a),c=vs[b];if(c&&Ob()-c.timestamp<200)return c.result;var d=ws(),e=d.status,f=[],g,k,m=[];if(!T(25)){if(a.zb&&a.zb.email){var n=xs(d.elements);f=ys(n,a&&a.De);g=zs(f);n.length>10&&(e="3")}!a.Zf&&g&&(f=[g]);for(var p=0;p<f.length;p++)m.push(As(f[p],!!a.vd,!!a.wd));m=m.slice(0,10)}else if(a.zb){}g&&(k=As(g,!!a.vd,!!a.wd));var C={elements:m,
Rh:k,status:e};vs[b]={timestamp:Ob(),result:C};return C},Gs=function(a,b,c){var d=a.element,e={Z:a.Z,type:a.qa,tagName:d.tagName};b&&(e.querySelector=Is(d));c&&(e.isVisible=!js(d));return e},As=function(a,b,c){return Gs({element:a.element,Z:a.Z,qa:Fs.nc},b,c)},us=function(a){var b=!(a==null||!a.vd)+"."+!(a==null||!a.wd);a&&a.De&&a.De.length&&(b+="."+a.De.join("."));a&&a.zb&&(b+="."+a.zb.email+"."+a.zb.phone+"."+a.zb.address);return b},zs=function(a){if(a.length!==0){var b;b=Js(a,function(c){return!Ks.test(c.Z)});
b=Js(b,function(c){return c.element.tagName.toUpperCase()==="INPUT"});b=Js(b,function(c){return!js(c.element)});return b[0]}},ys=function(a,b){if(!b||b.length===0)return a;for(var c=[],d=0;d<a.length;d++){for(var e=!0,f=0;f<b.length;f++){var g=b[f];if(g&&zh(a[d].element,g)){e=!1;break}}e&&c.push(a[d])}return c},Js=function(a,b){if(a.length<=1)return a;var c=a.filter(b);return c.length===0?a:c},Is=function(a){var b;if(a===H.body)b="body";else{var c;if(a.id)c="#"+a.id;else{var d;if(a.parentElement){var e;
a:{var f=a.parentElement;if(f){for(var g=0;g<f.childElementCount;g++)if(f.children[g]===a){e=g+1;break a}e=-1}else e=1}d=Is(a.parentElement)+">:nth-child("+e.toString()+")"}else d="";c=d}b=c}return b},xs=function(a){for(var b=[],c=0;c<a.length;c++){var d=a[c],e=d.textContent;d.tagName.toUpperCase()==="INPUT"&&d.value&&(e=d.value);if(e){var f=e.match(Ls);if(f){var g=f[0],k;if(G.location){var m=jj(G.location,"host",!0);k=g.toLowerCase().indexOf(m)>=0}else k=!1;k||b.push({element:d,Z:g})}}}return b},
ws=function(){var a=[],b=H.body;if(!b)return{elements:a,status:"4"};for(var c=b.querySelectorAll("*"),d=0;d<c.length&&d<1E4;d++){var e=c[d];if(!(Ms.indexOf(e.tagName.toUpperCase())>=0)&&e.children instanceof HTMLCollection){for(var f=!1,g=0;g<e.childElementCount&&g<1E4;g++)if(!(Ns.indexOf(e.children[g].tagName.toUpperCase())>=0)){f=!0;break}(!f||T(25)&&Os.indexOf(e.tagName)!==-1)&&a.push(e)}}return{elements:a,status:c.length>1E4?"2":"1"}},Ps=!1;var Ls=/[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,}/i,ss=/@(gmail|googlemail)\./i,Ks=/support|noreply/i,Ms="SCRIPT STYLE IMG SVG PATH BR NOSCRIPT TEXTAREA".split(" "),Ns=["BR"],Fs={nc:"1",qe:"2",je:"3",ne:"4",fg:"5",Xg:"6",Jf:"7"},vs={},Os=["INPUT","SELECT"];var dt=function(a,b,c){a.o[P.g.te]||(a.o[P.g.te]={});a.o[P.g.te][b]=c},ft=function(a,b){var c=et(a,P.g.Ud,a.m.D[P.g.Ud]);if(c&&c[b||a.eventName]!==void 0)return c[b||a.eventName]},gt=function(a){var b=a.metadata.user_data;if(fb(b))return b},ht=function(a){if(a.metadata.is_merchant_center||!uj(a.m))return!1;if(!U(a.m,P.g.jd)){var b=U(a.m,P.g.yc);return b===!0||b==="true"}return!0},it=function(a){return et(a,P.g.Yb,U(a.m,P.g.Yb))||!!et(a,"google_ng",!1)};var jt=Number('')||5,kt=Number('')||50,lt=Fb();var qt={pl:Number('')||500,Wk:Number('')||5E3,uj:Number('20')||10,Dk:Number('')||5E3};function rt(a){return a.performance&&a.performance.now()||Date.now()}
var st=function(a,b){var c;return c};var tt="https://"+ui.Fd+"/gtm/static/",ut;
function At(a,b){}
var Bt=function(a,b,c,d){};
function Ct(a,b,c,d){}
function Dt(a,b,c,d){}var Et=void 0;function Ft(a){var b=[];return b};var Gt=function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}return b};cn();fn()||$m("iPod");$m("iPad");!$m("Android")||dn()||cn()||bn()||$m("Silk");dn();!$m("Safari")||dn()||(an()?0:$m("Coast"))||bn()||(an()?0:$m("Edge"))||(an()?Zm("Microsoft Edge"):$m("Edg/"))||(an()?Zm("Opera"):$m("OPR"))||cn()||$m("Silk")||$m("Android")||gn();var Ht={},It=null,Jt=function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);e>255&&(b[c++]=e&255,e>>=8);b[c++]=e}var f=4;f===void 0&&(f=0);if(!It){It={};for(var g="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),k=["+/=","+/","-_=","-_.","-_"],m=0;m<5;m++){var n=g.concat(k[m].split(""));Ht[m]=n;for(var p=0;p<n.length;p++){var q=n[p];It[q]===void 0&&(It[q]=p)}}}for(var r=Ht[f],t=Array(Math.floor(b.length/3)),u=r[64]||"",v=0,w=0;v<b.length-2;v+=3){var x=b[v],
y=b[v+1],B=b[v+2],A=r[x>>2],C=r[(x&3)<<4|y>>4],E=r[(y&15)<<2|B>>6],D=r[B&63];t[w++]=""+A+C+E+D}var F=0,L=u;switch(b.length-v){case 2:F=b[v+1],L=r[(F&15)<<2]||u;case 1:var M=b[v];t[w]=""+r[M>>2]+r[(M&3)<<4|F>>4]+L+u}return t.join("")};var Kt="platform platformVersion architecture model uaFullVersion bitness fullVersionList wow64".split(" ");function Lt(a){var b;return(b=a.google_tag_data)!=null?b:a.google_tag_data={}}function Mt(){var a=G.google_tag_data,b;if(a!=null&&a.uach){var c=a.uach,d=Object.assign({},c);c.fullVersionList&&(d.fullVersionList=c.fullVersionList.slice(0));b=d}else b=null;return b}function Nt(){var a,b;return(b=(a=G.google_tag_data)==null?void 0:a.uach_promise)!=null?b:null}
function Ot(a){var b,c;return typeof((b=a.navigator)==null?void 0:(c=b.userAgentData)==null?void 0:c.getHighEntropyValues)==="function"}function Pt(){var a=G;if(!Ot(a))return null;var b=Lt(a);if(b.uach_promise)return b.uach_promise;var c=a.navigator.userAgentData.getHighEntropyValues(Kt).then(function(d){b.uach!=null||(b.uach=d);return d});return b.uach_promise=c};
var Qt,Rt=function(){if(Ot(G)&&(Qt=Ob(),!Nt())){var a=Pt();a&&(a.then(function(){O(95);}),a.catch(function(){O(96)}))}},Tt=function(a){var b=St.qn,c=function(g,k){try{a(g,k)}catch(m){}},d=Mt();if(d)c(d);else{var e=Nt();if(e){b=
Math.min(Math.max(isFinite(b)?b:0,0),1E3);var f=G.setTimeout(function(){c.Oe||(c.Oe=!0,O(106),c(null,Error("Timeout")))},b);e.then(function(g){c.Oe||(c.Oe=!0,O(104),G.clearTimeout(f),c(g))}).catch(function(g){c.Oe||(c.Oe=!0,O(105),G.clearTimeout(f),c(null,g))})}else c(null)}},Ut=function(a,b){a&&(b.o[P.g.zf]=a.architecture,b.o[P.g.Af]=a.bitness,a.fullVersionList&&(b.o[P.g.Bf]=a.fullVersionList.map(function(c){return encodeURIComponent(c.brand||"")+";"+encodeURIComponent(c.version||"")}).join("|")),
b.o[P.g.Cf]=a.mobile?"1":"0",b.o[P.g.Df]=a.model,b.o[P.g.Ef]=a.platform,b.o[P.g.Ff]=a.platformVersion,b.o[P.g.Gf]=a.wow64?"1":"0")};function Vt(a){var b;b=b===void 0?document:b;var c;return!((c=b.featurePolicy)==null||!c.allowedFeatures().includes(a))};function Wt(){return Vt("join-ad-interest-group")&&Bb(Cc.joinAdInterestGroup)}
function Xt(a,b){var c=yb[3]===void 0?1:yb[3],d='iframe[data-tagging-id="'+b+'"]',e=[];try{if(c===1){var f=H.querySelector(d);f&&(e=[f])}else e=Array.from(H.querySelectorAll(d))}catch(q){}var g;a:{try{g=H.querySelectorAll('iframe[allow="join-ad-interest-group"][data-tagging-id*="-"]');break a}catch(q){}g=void 0}var k=g,m=((k==null?void 0:k.length)||0)>=(yb[2]===void 0?50:yb[2]),n;if(n=e.length>=1){var p=Number(e[e.length-1].dataset.loadTime);p!==void 0&&Ob()-p<(yb[1]===void 0?6E4:yb[1])?(ub("TAGGING",
9),n=!0):n=!1}if(!n){if(c===1)if(e.length>=1)Yt(e[0]);else{if(m){ub("TAGGING",10);return}}else e.length>=c?Yt(e[0]):m&&Yt(k[0]);Nc(a,void 0,{allow:"join-ad-interest-group"},{taggingId:b,loadTime:Ob()})}}function Yt(a){try{a.parentNode.removeChild(a)}catch(b){}}function Zt(){return"https://td.doubleclick.net"};
var Pu=function(a,b){var c={},d=function(f,g){var k;k=g===!0?"1":g===!1?"0":encodeURIComponent(String(g));c[f]=k};z(a.o,function(f,g){var k=Ou[f];k&&g!==void 0&&g!==""&&(!a.metadata.redact_click_ids||f!==P.g.Gd&&f!==P.g.Od&&f!==P.g.df&&f!==P.g.lg||(g="0"),d(k,g))});d("gtm",no({xa:a.metadata.source_canonical_id}));Un()&&d("gcs",Vn());d("gcd",fo(a.m));io()&&d("dma_cps",go());d("dma",ho());yn(Gn())&&d("tcfd",jo());Oi.j&&d("tag_exp",Oi.j);if(a.metadata.add_tag_timing){d("tft",Ob());var e=ad();e!==void 0&&
d("tfd",Math.round(e))}T(17)&&d("apve",T(18)?"1":"0");T(19)&&d("apvf",Yc()?T(20)?"f":"sb":"nf");b(c)},Qu=function(a){Pu(a,function(b){if(a.metadata.hit_type==="page_view"){var c=[];z(b,function(e,f){c.push(e+"="+f)});var d=vj(W([P.g.R,P.g.P])?"https://www.google.com":"https://pagead2.googlesyndication.com",!0)+"/ccm/collect?"+c.join("&");T(19)&&T(20)&&Yc()?Zc(d,void 0,{noFallback:!0}):Vc(d);if(Bb(a.m.onSuccess))a.m.onSuccess()}})},Ru={},Ou=(Ru[P.g.Tb]="gcu",Ru[P.g.nb]="gclgb",Ru[P.g.Va]="gclaw",Ru[P.g.Ei]=
"gad_source",Ru[P.g.Fi]="gad_source_src",Ru[P.g.Gd]="gclid",Ru[P.g.Gi]="gclsrc",Ru[P.g.lg]="gbraid",Ru[P.g.df]="wbraid",Ru[P.g.Hb]="auid",Ru[P.g.Ii]="rnd",Ru[P.g.Li]="ncl",Ru[P.g.og]="gcldc",Ru[P.g.Od]="dclid",Ru[P.g.rb]="edid",Ru[P.g.xc]="en",Ru[P.g.Ac]="gdpr",Ru[P.g.ub]="gdid",Ru[P.g.Bc]="_ng",Ru[P.g.Yi]="gtm_up",Ru[P.g.Kb]="frm",Ru[P.g.ed]="lps",Ru[P.g.ae]="did",Ru[P.g.wa]="dl",Ru[P.g.Fa]="dr",Ru[P.g.cb]="dt",Ru[P.g.wf]="ga_uid",Ru[P.g.Dc]="gdpr_consent",Ru[P.g.Ba]="uid",Ru[P.g.he]="us_privacy",
Ru[P.g.Pb]="npa",Ru);var Su={M:{fi:"ads_conversion_hit",Ed:"container_execute_start",ii:"container_setup_end",dg:"container_setup_start",gi:"container_blocking_end",hi:"container_execute_end",ji:"container_yield_end",eg:"container_yield_start",jj:"event_execute_end",ij:"event_evaluation_end",Ug:"event_evaluation_start",kj:"event_setup_end",ie:"event_setup_start",mj:"ga4_conversion_hit",pe:"page_load",Hn:"pageview",hc:"snippet_load",Hj:"tag_callback_error",Ij:"tag_callback_failure",Jj:"tag_callback_success",Kj:"tag_execute_end",
nd:"tag_execute_start"}};function Tu(){function a(c,d){var e=vb(d);e&&b.push([c,e])}var b=[];a("u","GTM");a("ut","TAGGING");a("h","HEALTH");return b};var Uu=!1;function Cv(a,b){}
function Dv(a,b){}function Ev(a,b){}
function Fv(a,b){}function Gv(){var a={};return a}
function uv(a){a=a===void 0?!0:a;var b={};return b}
function Hv(){}function Iv(a,b){}
function Jv(a,b,c){}
function Kv(){}function Lv(a,b){var c=G,d,e=c.GooglebQhCsO;e||(e={},c.GooglebQhCsO=e);d=e;if(d[a])return!1;d[a]=[];d[a][0]=b;return!0};var Mv=function(a,b,c,d){var e=kn(a,"fmt");if(b){var f=kn(a,"random"),g=kn(a,"label")||"";if(!f)return!1;var k=Jt(decodeURIComponent(g.replace(/\+/g," "))+":"+decodeURIComponent(f.replace(/\+/g," ")));if(!Lv(k,b))return!1}e&&e!=4&&(a=mn(a,"rfmt",e));var m=mn(a,"fmt",4);Lc(m,function(){G.google_noFurtherRedirects&&b&&b.call&&(G.google_noFurtherRedirects=null,b())},c,d,H.getElementsByTagName("script")[0].parentElement||void 0);return!0};function dw(a,b){if(data.entities){var c=data.entities[a];if(c)return c[b]}};function ew(a,b,c){c=c===void 0?!1:c;fw().addRestriction(0,a,b,c)}function gw(a,b,c){c=c===void 0?!1:c;fw().addRestriction(1,a,b,c)}function hw(){var a=Xj();return fw().getRestrictions(1,a)}var iw=function(){this.j={};this.D={}},jw=function(a,b){var c=a.j[b];c||(c={_entity:{internal:[],external:[]},_event:{internal:[],external:[]}},a.j[b]=c);return c};
iw.prototype.addRestriction=function(a,b,c,d){d=d===void 0?!1:d;if(!d||!this.D[b]){var e=jw(this,b);a===0?d?e._entity.external.push(c):e._entity.internal.push(c):a===1&&(d?e._event.external.push(c):e._event.internal.push(c))}};
iw.prototype.getRestrictions=function(a,b){var c=jw(this,b);if(a===0){var d,e;return[].concat(qa((c==null?void 0:(d=c._entity)==null?void 0:d.internal)||[]),qa((c==null?void 0:(e=c._entity)==null?void 0:e.external)||[]))}if(a===1){var f,g;return[].concat(qa((c==null?void 0:(f=c._event)==null?void 0:f.internal)||[]),qa((c==null?void 0:(g=c._event)==null?void 0:g.external)||[]))}return[]};
iw.prototype.getExternalRestrictions=function(a,b){var c=jw(this,b),d,e;return a===0?(c==null?void 0:(d=c._entity)==null?void 0:d.external)||[]:(c==null?void 0:(e=c._event)==null?void 0:e.external)||[]};iw.prototype.removeExternalRestrictions=function(a){var b=jw(this,a);b._event&&(b._event.external=[]);b._entity&&(b._entity.external=[]);this.D[a]=!0};function fw(){var a=vi.r;a||(a=new iw,vi.r=a);return a};var kw=new RegExp(/^(.*\.)?(google|youtube|blogger|withgoogle)(\.com?)?(\.[a-z]{2})?\.?$/),lw={cl:["ecl"],customPixels:["nonGooglePixels"],ecl:["cl"],ehl:["hl"],gaawc:["googtag"],hl:["ehl"],html:["customScripts","customPixels","nonGooglePixels","nonGoogleScripts","nonGoogleIframes"],customScripts:["html","customPixels","nonGooglePixels","nonGoogleScripts","nonGoogleIframes"],nonGooglePixels:[],nonGoogleScripts:["nonGooglePixels"],nonGoogleIframes:["nonGooglePixels"]},mw={cl:["ecl"],customPixels:["customScripts",
"html"],ecl:["cl"],ehl:["hl"],gaawc:["googtag"],hl:["ehl"],html:["customScripts"],customScripts:["html"],nonGooglePixels:["customPixels","customScripts","html","nonGoogleScripts","nonGoogleIframes"],nonGoogleScripts:["customScripts","html"],nonGoogleIframes:["customScripts","html","nonGoogleScripts"]},nw="google customPixels customScripts html nonGooglePixels nonGoogleScripts nonGoogleIframes".split(" ");
function ow(){var a=Wi("gtm.allowlist")||Wi("gtm.whitelist");a&&O(9);Bi&&(a=["google","gtagfl","lcl","zone"]);kw.test(G.location&&G.location.hostname)&&(Bi?O(116):(O(117),pw&&(a=[],window.console&&window.console.log&&window.console.log("GTM blocked. See go/13687728."))));var b=a&&Sb(Lb(a),lw),c=Wi("gtm.blocklist")||Wi("gtm.blacklist");c||(c=Wi("tagTypeBlacklist"))&&O(3);c?O(8):c=[];kw.test(G.location&&G.location.hostname)&&(c=Lb(c),c.push("nonGooglePixels","nonGoogleScripts","sandboxedScripts"));
Lb(c).indexOf("google")>=0&&O(2);var d=c&&Sb(Lb(c),mw),e={};return function(f){var g=f&&f[Xe.oa];if(!g||typeof g!=="string")return!0;g=g.replace(/^_*/,"");if(e[g]!==void 0)return e[g];var k=Li[g]||[],m=!0;if(a){var n;if(n=m)a:{if(b.indexOf(g)<0)if(k&&k.length>0)for(var p=0;p<k.length;p++){if(b.indexOf(k[p])<0){O(11);n=!1;break a}}else{n=!1;break a}n=!0}m=n}var q=!1;if(c){var r=d.indexOf(g)>=0;if(r)q=r;else{var t=Gb(d,k||[]);t&&O(10);q=t}}var u=!m||q;u||!(k.indexOf("sandboxedScripts")>=0)||b&&b.indexOf("sandboxedScripts")!==
-1||(u=Gb(d,nw));return e[g]=u}}var pw=!1;pw=!0;function qw(){Pj&&ew(Xj(),function(a){var b=Hf(a.entityId),c;if(Kf(b)){var d=b[Xe.oa];if(!d)throw Error("Error: No function name given for function call.");var e=zf[d];c=!!e&&!!e.runInSiloedMode}else c=!!dw(b[Xe.oa],4);return c})}function rw(a,b,c,d,e){if(!sw()){var f=d.siloed?Sj(a):a;if(!gk(f)){var g=tw(a),k=Tb(a,"GTM-"),m=tj(),n=c?"/gtag/js":"/gtm.js",p=sj(b,n+g);if(!p){var q=ui.Fd+n;m&&Fc&&k?(q=Fc.replace(/^(?:https?:\/\/)?/i,"").split(/[?#]/)[0],p=Lr("https://","http://",q+g)):p=Qi()?Pi()+n+g:Lr("https://","http://",q+g)}d.siloed&&ik({ctid:f,isDestination:!1});var r=ak();Jj().container[f]={state:1,context:d,parent:r};Ij({ctid:f,isDestination:!1},e);Lc(p)}}}
function uw(a,b,c,d){if(!sw()){var e=c.siloed?Sj(a):a;if(!hk(e))if(!c.siloed&&jk())Jj().destination[e]={state:0,transportUrl:b,context:c,parent:ak()},Ij({ctid:e,isDestination:!0},d),O(91);else{var f="/gtag/destination"+tw(a,!0),g=sj(b,f);g||(g=Qi()?Pi()+f:Lr("https://","http://",ui.Fd+f));c.siloed&&ik({ctid:e,isDestination:!0});Jj().destination[e]={state:1,context:c,parent:ak()};Ij({ctid:e,isDestination:!0},d);Lc(g)}}}
function tw(a,b){b=b===void 0?!1:b;var c="?id="+encodeURIComponent(a)+"&l="+ui.jb;if(!Tb(a,"GTM-")||b)c+="&cx=c";T(68)&&(c+="&gtm="+no());tj()&&(c+="&sign="+ui.Zg);var d=Oi.D;d===1?c+="&fps=fc":d===2&&(c+="&fps=fe");return c}function sw(){if(lo()){return!0}return!1};var vw=[];function ww(){var a=ag.ctid;if(a){var b=Lj.oe?1:0,c,d=Zj(ak());c=d&&d.context;return a+";"+ag.canonicalContainerId+";"+(c&&c.fromContainerExecution?1:0)+";"+(c&&c.source||0)+";"+b}}function xw(){var a=nj(G.location.href);return a.hostname+a.pathname}function yw(){var a=xw();a&&rk("dl",encodeURIComponent(a));if(T(85)){var b=ww();b&&rk("tdp",b)}else rk("tdp",function(){return vw.length>0?vw.join("."):void 0});var c=pn(!0);c!==void 0&&rk("frm",String(c))};var zw=!1,Aw=0,Bw=[];function Cw(a){if(!zw){var b=H.createEventObject,c=H.readyState==="complete",d=H.readyState==="interactive";if(!a||a.type!=="readystatechange"||c||!b&&d){zw=!0;for(var e=0;e<Bw.length;e++)I(Bw[e])}Bw.push=function(){for(var f=Ma.apply(0,arguments),g=0;g<f.length;g++)I(f[g]);return 0}}}function Dw(){if(!zw&&Aw<140){Aw++;try{var a,b;(b=(a=H.documentElement).doScroll)==null||b.call(a,"left");Cw()}catch(c){G.setTimeout(Dw,50)}}}function Ew(a){zw?a():Bw.push(a)};var Fw=function(){this.K=0;this.j={}};Fw.prototype.addListener=function(a,b,c){var d=++this.K;this.j[a]=this.j[a]||{};this.j[a][String(d)]={listener:b,Eb:c};return d};Fw.prototype.D=function(a,b){var c=this.j[a],d=String(b);if(!c||!c[d])return!1;delete c[d];return!0};Fw.prototype.H=function(a,b){var c=[];z(this.j[a],function(d,e){c.indexOf(e.listener)<0&&(e.Eb===void 0||b.indexOf(e.Eb)>=0)&&c.push(e.listener)});return c};function Gw(a,b,c){return{entityType:a,indexInOriginContainer:b,nameInOriginContainer:c,originContainerId:Vj()}};var Iw=function(a,b){this.j=!1;this.K=[];this.eventData={tags:[]};this.O=!1;this.D=this.H=0;Hw(this,a,b)},Jw=function(a,b,c,d){if(xi.hasOwnProperty(b)||b==="__zone")return-1;var e={};fb(d)&&(e=h(d,e));e.id=c;e.status="timeout";return a.eventData.tags.push(e)-1},Kw=function(a,b,c,d){var e=a.eventData.tags[b];e&&(e.status=c,e.executionTime=d)},Lw=function(a){if(!a.j){for(var b=a.K,c=0;c<b.length;c++)b[c]();a.j=!0;a.K.length=0}},Hw=function(a,b,c){b!==void 0&&a.we(b);c&&G.setTimeout(function(){Lw(a)},
Number(c))};Iw.prototype.we=function(a){var b=this,c=Qb(function(){I(function(){a(Vj(),b.eventData)})});this.j?c():this.K.push(c)};var Mw=function(a){a.H++;return Qb(function(){a.D++;a.O&&a.D>=a.H&&Lw(a)})},Nw=function(a){a.O=!0;a.D>=a.H&&Lw(a)};var Ow={},Qw=function(){return G[Pw()]};
function Pw(){return G.GoogleAnalyticsObject||"ga"}
var Tw=function(){var a=Vj();},Uw=function(a,b){return function(){var c=Qw(),d=c&&c.getByName&&c.getByName(a);if(d){var e=d.get("sendHitTask");d.set("sendHitTask",function(f){var g=f.get("hitPayload"),k=f.get("hitCallback"),m=g.indexOf("&tid="+b)<0;m&&(f.set("hitPayload",g.replace(/&tid=UA-[0-9]+-[0-9]+/,"&tid="+b),!0),f.set("hitCallback",void 0,!0));e(f);
m&&(f.set("hitPayload",g,!0),f.set("hitCallback",k,!0),f.set("_x_19",void 0,!0),e(f))})}}};var Zw=["es","1"],$w={},ax={};function bx(a,b){if(Cj){var c;c=b.match(/^(gtm|gtag)\./)?encodeURIComponent(b):"*";$w[a]=[["e",c],["eid",a]];tm(a)}}function cx(a){var b=a.eventId,c=a.mc;if(!$w[b])return[];var d=[];ax[b]||d.push(Zw);d.push.apply(d,qa($w[b]));c&&(ax[b]=!0);return d};var dx={},ex={},fx={};function gx(a,b,c,d){Cj&&T(76)&&((d===void 0?0:d)?(fx[b]=fx[b]||0,++fx[b]):c!==void 0?(ex[a]=ex[a]||{},ex[a][b]=Math.round(c)):(dx[a]=dx[a]||{},dx[a][b]=(dx[a][b]||0)+1))}function hx(a){var b=a.eventId,c=a.mc,d=dx[b]||{},e=[],f;for(f in d)d.hasOwnProperty(f)&&e.push(""+f+d[f]);c&&delete dx[b];return e.length?[["md",e.join(".")]]:[]}
function ix(a){var b=a.eventId,c=a.mc,d=ex[b]||{},e=[],f;for(f in d)d.hasOwnProperty(f)&&e.push(""+f+d[f]);c&&delete ex[b];return e.length?[["mtd",e.join(".")]]:[]}function jx(){for(var a=[],b=oa(Object.keys(fx)),c=b.next();!c.done;c=b.next()){var d=c.value;a.push(""+d+fx[d])}return a.length?[["mec",a.join(".")]]:[]};var kx={},lx={};function mx(a,b,c){if(Cj&&b){var d=wj(b);kx[a]=kx[a]||[];kx[a].push(c+d);var e=(Kf(b)?"1":"2")+d;lx[a]=lx[a]||[];lx[a].push(e);tm(a)}}function nx(a){var b=a.eventId,c=a.mc,d=[],e=kx[b]||[];e.length&&d.push(["tr",e.join(".")]);var f=lx[b]||[];f.length&&d.push(["ti",f.join(".")]);c&&(delete kx[b],delete lx[b]);return d};function ox(a,b,c,d){var e=xf[a],f=px(a,b,c,d);if(!f)return null;var g=Lf(e[Xe.Fj],c,[]);if(g&&g.length){var k=g[0];f=ox(k.index,{onSuccess:f,onFailure:k.Tj===1?b.terminate:f,terminate:b.terminate},c,d)}return f}
function px(a,b,c,d){function e(){function w(){$k(3);var D=Ob()-E;mx(c.id,f,"7");Kw(c.ic,A,"exception",D);T(69)&&Jv(c,f,Su.M.Hj);C||(C=!0,k())}if(f[Xe.bl])k();else{var x=Jf(f,c,[]),y=x[Xe.Bk];if(y!=null)for(var B=0;B<y.length;B++)if(!W(y[B])){k();return}var A=Jw(c.ic,String(f[Xe.oa]),Number(f[Xe.ve]),x[Xe.fl]),C=!1;x.vtp_gtmOnSuccess=function(){if(!C){C=!0;var D=Ob()-E;mx(c.id,xf[a],"5");Kw(c.ic,A,"success",D);T(69)&&Jv(c,f,Su.M.Jj);g()}};x.vtp_gtmOnFailure=function(){if(!C){C=!0;var D=Ob()-E;mx(c.id,
xf[a],"6");Kw(c.ic,A,"failure",D);T(69)&&Jv(c,f,Su.M.Ij);k()}};x.vtp_gtmTagId=f.tag_id;x.vtp_gtmEventId=c.id;c.priorityId&&(x.vtp_gtmPriorityId=c.priorityId);mx(c.id,f,"1");T(69)&&Iv(c,f);var E=Ob();try{Mf(x,{event:c,index:a,type:1})}catch(D){w(D)}T(69)&&Jv(c,f,Su.M.Kj)}}var f=xf[a],g=b.onSuccess,k=b.onFailure,m=b.terminate;if(c.isBlocked(f))return null;var n=Lf(f[Xe.Lj],c,[]);if(n&&n.length){var p=n[0],q=ox(p.index,{onSuccess:g,onFailure:k,terminate:m},c,d);if(!q)return null;g=q;k=p.Tj===2?m:q}if(f[Xe.xj]||
f[Xe.jl]){var r=f[Xe.xj]?yf:c.hn,t=g,u=k;if(!r[a]){var v=qx(a,r,Qb(e));g=v.onSuccess;k=v.onFailure}return function(){r[a](t,u)}}return e}function qx(a,b,c){var d=[],e=[];b[a]=rx(d,e,c);return{onSuccess:function(){b[a]=sx;for(var f=0;f<d.length;f++)d[f]()},onFailure:function(){b[a]=tx;for(var f=0;f<e.length;f++)e[f]()}}}function rx(a,b,c){return function(d,e){a.push(d);b.push(e);c()}}function sx(a){a()}function tx(a,b){b()};var wx=function(a,b){for(var c=[],d=0;d<xf.length;d++)if(a[d]){var e=xf[d];var f=Mw(b.ic);try{var g=ox(d,{onSuccess:f,onFailure:f,terminate:f},b,d);if(g){var k=e[Xe.oa];if(!k)throw Error("Error: No function name given for function call.");var m=zf[k];c.push({sk:d,ik:(m?m.priorityOverride||0:0)||dw(e[Xe.oa],1)||0,execute:g})}else ux(d,b),f()}catch(p){f()}}c.sort(vx);for(var n=0;n<c.length;n++)c[n].execute();return c.length>
0};var yx=function(a,b){if(!xx)return!1;var c=a["gtm.triggers"]&&String(a["gtm.triggers"]),d=xx.H(a.event,c?String(c).split(","):[]);if(!d.length)return!1;for(var e=0;e<d.length;++e){var f=Mw(b);try{d[e](a,f)}catch(g){f()}}return!0};function vx(a,b){var c,d=b.ik,e=a.ik;c=d>e?1:d<e?-1:0;var f;if(c!==0)f=c;else{var g=a.sk,k=b.sk;f=g>k?1:g<k?-1:0}return f}
function ux(a,b){if(Cj){var c=function(d){var e=b.isBlocked(xf[d])?"3":"4",f=Lf(xf[d][Xe.Fj],b,[]);f&&f.length&&c(f[0].index);mx(b.id,xf[d],e);var g=Lf(xf[d][Xe.Lj],b,[]);g&&g.length&&c(g[0].index)};c(a)}}var zx=!1,xx;var Ax=function(){xx||(xx=new Fw);return xx};
var Fx=function(a){var b=a["gtm.uniqueEventId"],c=a["gtm.priorityId"],d=a.event;if(T(69)){}if(d==="gtm.js"){if(zx)return!1;zx=!0}var e=!1,f=hw(),g=h(a);if(!f.every(function(t){return t({originalEventData:g})})){if(d!=="gtm.js"&&d!=="gtm.init"&&d!=="gtm.init_consent")return!1;e=!0}bx(b,d);var k=a.eventCallback,m=a.eventTimeout,n={id:b,
priorityId:c,name:d,isBlocked:Bx(g,e),hn:[],logMacroError:function(){O(6);$k(0)},cachedModelValues:Cx(),ic:new Iw(function(){if(T(69)){}k&&
k.apply(k,[].slice.call(arguments,0))},m),originalEventData:g};T(76)&&Cj&&(n.reportMacroDiscrepancy=gx);T(69)&&Ev(n.id,n.name);var p=Sf(n);T(69)&&Fv(n.id,n.name);e&&(p=Dx(p));if(T(69)){}var q=wx(p,n),r=!1;
r=yx(a,n.ic);Nw(n.ic);d!=="gtm.js"&&d!=="gtm.sync"||Tw();return Ex(p,q)||r};function Cx(){var a={};a.event=aj("event",1);a.ecommerce=aj("ecommerce",1);a.gtm=aj("gtm");a.eventModel=aj("eventModel");return a}
function Bx(a,b){var c=ow();return function(d){if(c(d))return!0;var e=d&&d[Xe.oa];if(!e||typeof e!="string")return!0;e=e.replace(/^_*/,"");var f,g=Xj();f=fw().getRestrictions(0,g);var k=a;b&&(k=h(a),k["gtm.uniqueEventId"]=Number.MAX_SAFE_INTEGER);for(var m=Li[e]||[],n=oa(f),p=n.next();!p.done;p=n.next()){var q=p.value;try{if(!q({entityId:e,securityGroups:m,originalEventData:k}))return!0}catch(r){return!0}}return!1}}
function Dx(a){for(var b=[],c=0;c<a.length;c++)if(a[c]){var d=String(xf[c][Xe.oa]);if(wi[d]||xf[c][Xe.kl]!==void 0||dw(d,2))b[c]=!0}return b}function Ex(a,b){if(!b)return b;for(var c=0;c<a.length;c++)if(a[c]&&xf[c]&&!xi[String(xf[c][Xe.oa])])return!0;return!1}var Lx=0;function Mx(a,b){return arguments.length===1?Nx("set",a):Nx("set",a,b)}function Ox(a,b){return arguments.length===1?Nx("config",a):Nx("config",a,b)}function Px(a,b,c){c=c||{};c[P.g.bc]=a;return Nx("event",b,c)}function Nx(){return arguments};var Qx=function(){this.messages=[];this.j=[]};Qx.prototype.enqueue=function(a,b,c){var d=this.messages.length+1;a["gtm.uniqueEventId"]=b;a["gtm.priorityId"]=d;var e=Object.assign({},c,{eventId:b,priorityId:d,fromContainerExecution:!0}),f={message:a,notBeforeEventId:b,priorityId:d,messageContext:e};this.messages.push(f);for(var g=0;g<this.j.length;g++)try{this.j[g](f)}catch(k){}};Qx.prototype.listen=function(a){this.j.push(a)};
Qx.prototype.get=function(){for(var a={},b=0;b<this.messages.length;b++){var c=this.messages[b],d=a[c.notBeforeEventId];d||(d=[],a[c.notBeforeEventId]=d);d.push(c)}return a};Qx.prototype.prune=function(a){for(var b=[],c=[],d=0;d<this.messages.length;d++){var e=this.messages[d];e.notBeforeEventId===a?b.push(e):c.push(e)}this.messages=c;return b};function Rx(a,b,c){c.eventMetadata=c.eventMetadata||{};c.eventMetadata.source_canonical_id=ag.canonicalContainerId;Sx().enqueue(a,b,c)}
function Tx(){var a=Ux;Sx().listen(a)}function Sx(){var a=vi.mb;a||(a=new Qx,vi.mb=a);return a};var Xf;var Vx={},Wx={};function Xx(a,b){for(var c=[],d=[],e={},f=0;f<a.length;e={Qh:void 0,yh:void 0},f++){var g=a[f];if(g.indexOf("-")>=0){if(e.Qh=zl(g,b),e.Qh){var k=Tj();Eb(k,function(r){return function(t){return r.Qh.ia===t}}(e))?c.push(g):d.push(g)}}else{var m=Vx[g]||[];e.yh={};m.forEach(function(r){return function(t){r.yh[t]=!0}}(e));for(var n=Qj(),p=0;p<n.length;p++)if(e.yh[n[p]]){c=c.concat(Tj());break}var q=Wx[g]||[];q.length&&(c=c.concat(q))}}return{zm:c,Cm:d}}
function Yx(a){z(Vx,function(b,c){var d=c.indexOf(a);d>=0&&c.splice(d,1)})}function Zx(a){z(Wx,function(b,c){var d=c.indexOf(a);d>=0&&c.splice(d,1)})}var $x="HA GF G UA AW DC MC".split(" "),ay=!1,by=!1,cy=!1,dy=!1;function ey(a,b){a.hasOwnProperty("gtm.uniqueEventId")||Object.defineProperty(a,"gtm.uniqueEventId",{value:Mi()});b.eventId=a["gtm.uniqueEventId"];b.priorityId=a["gtm.priorityId"];return{eventId:b.eventId,priorityId:b.priorityId}}var fy=void 0,gy=void 0;
function hy(a,b,c){var d=h(a,null);d.eventId=void 0;d.inheritParentConfig=void 0;Object.keys(b).some(function(f){return b[f]!==void 0})&&O(136);var e=h(b,null);h(c,e);Rx(Ox(Qj()[0],e),a.eventId,d)}function iy(a){for(var b=oa([P.g.jd,P.g.Ob]),c=b.next();!c.done;c=b.next()){var d=c.value,e=a&&a[d]||Bm.D[d];if(e)return e}}
var jy=[P.g.jd,P.g.Ob,P.g.yc,P.g.pb,P.g.wb,P.g.Ba,P.g.sa,P.g.Qa,P.g.Wa,P.g.Ib],ky={config:function(a,b){var c=ey(a,b);if(!(a.length<2)&&l(a[1])){var d={};if(a.length>2){if(a[2]!==void 0&&!fb(a[2])||a.length>3)return;d=a[2]}var e=zl(a[1],b.isGtmEvent);if(e){var f,g,k;a:{if(!Lj.oe){var m=Zj(ak());if(lk(m)){var n=m.parent,p=n.isDestination;k={Jm:Zj(n),ym:p};break a}}k=void 0}var q=k;q&&(f=q.Jm,g=q.ym);bx(c.eventId,"gtag.config");var r=e.ia,t=e.id!==r;if(t?Tj().indexOf(r)===-1:Qj().indexOf(r)===-1){if(!b.inheritParentConfig&&
!d[P.g.Lb]){var u=iy(d);if(t)uw(r,u,{source:2,fromContainerExecution:b.fromContainerExecution});else if(f!==void 0&&f.containers.indexOf(r)!==-1){var v=d;fy?hy(b,v,fy):gy||(gy=h(v,null))}else rw(r,u,!0,{source:2,fromContainerExecution:b.fromContainerExecution})}}else{if(f&&(O(128),g&&O(130),b.inheritParentConfig)){var w;var x=d;gy?(hy(b,gy,x),w=!1):(!x[P.g.fc]&&zi&&fy||(fy=h(x,null)),w=!0);w&&f.containers&&f.containers.join(",");return}var y=d;if(!cy&&(cy=!0,by))for(var B=oa(jy),A=B.next();!A.done;A=
B.next())if(y.hasOwnProperty(A.value)){Zk("erc");break}Dj&&!Pj&&(Lx===1&&(pk.mcc=!1),Lx=2);Wk=!0;if(zi&&!t&&!d[P.g.fc]){var C=dy;dy=!0;if(C)return}ay||O(43);if(!b.noTargetGroup)if(t){Zx(e.id);var E=e.id,D=d[P.g.Yd]||"default";D=String(D).split(",");for(var F=0;F<D.length;F++){var L=Wx[D[F]]||[];Wx[D[F]]=L;L.indexOf(E)<0&&L.push(E)}}else{Yx(e.id);var M=e.id,S=d[P.g.Yd]||"default";S=S.toString().split(",");for(var V=0;V<S.length;V++){var aa=Vx[S[V]]||[];Vx[S[V]]=aa;aa.indexOf(M)<0&&aa.push(M)}}delete d[P.g.Yd];
var X=b.eventMetadata||{};X.hasOwnProperty("is_external_event")||(X.is_external_event=!b.fromContainerExecution);b.eventMetadata=X;delete d[P.g.bd];for(var R=t?[e.id]:Tj(),ma=0;ma<R.length;ma++){var la=d,ha=R[ma],ya=h(b,null),Na=zl(ha,ya.isGtmEvent);Na&&Bm.push("config",[la],Na,ya)}}}}},consent:function(a,b){if(a.length===3){O(39);var c=ey(a,b),d=a[1],e=a[2];b.fromContainerExecution||(e[P.g.P]&&O(139),e[P.g.ya]&&O(140));d==="default"?ml(e):d==="update"?ol(e,c):d==="declare"&&b.fromContainerExecution&&
ll(e)}},event:function(a,b){var c=a[1];if(!(a.length<2)&&l(c)){var d=void 0;if(a.length>2){if(!fb(a[2])&&a[2]!==void 0||a.length>3)return;d=a[2]}var e=d,f={},g=(f.event=c,f);e&&(g.eventModel=h(e,null),e[P.g.bd]&&(g.eventCallback=e[P.g.bd]),e[P.g.Vd]&&(g.eventTimeout=e[P.g.Vd]));var k=ey(a,b),m=k.eventId,n=k.priorityId;g["gtm.uniqueEventId"]=m;n&&(g["gtm.priorityId"]=n);if(c==="optimize.callback")return g.eventModel=g.eventModel||{},g;var p;var q=d,r=q&&q[P.g.bc];r===void 0&&(r=Wi(P.g.bc,2),r===void 0&&
(r="default"));if(l(r)||Array.isArray(r)){var t;t=b.isGtmEvent?l(r)?[r]:r:r.toString().replace(/\s+/g,"").split(",");var u=Xx(t,b.isGtmEvent),v=u.zm,w=u.Cm;if(w.length)for(var x=iy(q),y=0;y<w.length;y++){var B=zl(w[y],b.isGtmEvent);B&&uw(B.ia,x,{source:3,fromContainerExecution:b.fromContainerExecution})}p=Al(v,b.isGtmEvent)}else p=void 0;var A=p;if(A){var C;!A.length||((C=b.eventMetadata)==null?0:C.em_event)||(by=!0);bx(m,c);for(var E=[],D=0;D<A.length;D++){var F=A[D],L=h(b,null);if($x.indexOf(bk(F.prefix))!==
-1){var M=h(d,null),S=L.eventMetadata||{};S.hasOwnProperty("is_external_event")||(S.is_external_event=!L.fromContainerExecution);L.eventMetadata=S;delete M[P.g.bd];Cm(c,M,F.id,L);Dj&&!Pj&&Lx===0&&(rk("mcc","1"),Lx=1);Wk=!0}E.push(F.id)}g.eventModel=g.eventModel||{};A.length>0?g.eventModel[P.g.bc]=E.join():delete g.eventModel[P.g.bc];ay||O(43);b.noGtmEvent===void 0&&b.eventMetadata&&b.eventMetadata.syn_or_mod&&(b.noGtmEvent=!0);g.eventModel[P.g.Zb]&&(b.noGtmEvent=!0);return b.noGtmEvent?void 0:g}}},
get:function(a,b){O(53);if(a.length===4&&l(a[1])&&l(a[2])&&Bb(a[3])){var c=zl(a[1],b.isGtmEvent),d=String(a[2]),e=a[3];if(c){ay||O(43);var f=iy();if(!Eb(Tj(),function(k){return c.ia===k}))uw(c.ia,f,{source:4,fromContainerExecution:b.fromContainerExecution});else if($x.indexOf(bk(c.prefix))!==-1){Wk=!0;ey(a,b);var g={};h((g[P.g.tb]=d,g[P.g.Jb]=e,g),null);Dm(d,function(k){I(function(){e(k)})},c.id,b)}}}},js:function(a,b){if(a.length===2&&a[1].getTime){ay=!0;var c=ey(a,b),d=c.eventId,e=c.priorityId,
f={};return f.event="gtm.js",f["gtm.start"]=a[1].getTime(),f["gtm.uniqueEventId"]=d,f["gtm.priorityId"]=e,f}},policy:function(a){if(a.length===3&&l(a[1])&&Bb(a[2])){if(Yf(a[1],a[2]),O(74),a[1]==="all"){O(75);var b=!1;try{b=a[2](Vj(),"unknown",{})}catch(c){}b||O(76)}}else O(73)},set:function(a,b){var c=void 0;a.length===2&&fb(a[1])?c=h(a[1],null):a.length===3&&l(a[1])&&(c={},fb(a[2])||Array.isArray(a[2])?c[a[1]]=h(a[2],null):c[a[1]]=a[2]);if(c){var d=ey(a,b),e=d.eventId,f=d.priorityId;h(c,null);var g=
h(c,null);Bm.push("set",[g],void 0,b);c["gtm.uniqueEventId"]=e;f&&(c["gtm.priorityId"]=f);delete c.event;b.overwriteModelFields=!0;return c}}},ly={policy:!0};var ny=function(a){if(my(a))return a;this.value=a};ny.prototype.getUntrustedMessageValue=function(){return this.value};var my=function(a){return!a||db(a)!=="object"||fb(a)?!1:"getUntrustedMessageValue"in a};ny.prototype.getUntrustedMessageValue=ny.prototype.getUntrustedMessageValue;var oy=!1,py=[];function qy(){if(!oy){oy=!0;for(var a=0;a<py.length;a++)I(py[a])}}function ry(a){oy?I(a):py.push(a)};var sy=0,ty={},uy=[],vy=[],wy=!1,xy=!1;function yy(a,b){return a.messageContext.eventId-b.messageContext.eventId||a.messageContext.priorityId-b.messageContext.priorityId}
var zy=function(a){return G[ui.jb].push(a)},Ay=function(a,b,c){a.eventCallback=b;c&&(a.eventTimeout=c);return zy(a)},By=function(a,b){if(!Cb(b)||b<0)b=0;var c=vi[ui.jb],d=0,e=!1,f=void 0;f=G.setTimeout(function(){e||(e=!0,a());f=void 0},b);return function(){var g=c?c.subscribers:1;++d===g&&(f&&(G.clearTimeout(f),f=void 0),e||(a(),e=!0))}};
function Cy(a,b){var c=a._clear||b.overwriteModelFields;z(a,function(e,f){e!=="_clear"&&(c&&Zi(e),Zi(e,f))});Ii||(Ii=a["gtm.start"]);var d=a["gtm.uniqueEventId"];if(!a.event)return!1;typeof d!=="number"&&(d=Mi(),a["gtm.uniqueEventId"]=d,Zi("gtm.uniqueEventId",d));return Fx(a)}function Dy(a){if(a==null||typeof a!=="object")return!1;if(a.event)return!0;if(Ib(a)){var b=a[0];if(b==="config"||b==="event"||b==="js"||b==="get")return!0}return!1}
function Ey(){var a;if(vy.length)a=vy.shift();else if(uy.length)a=uy.shift();else return;var b;var c=a;if(wy||!Dy(c.message))b=c;else{wy=!0;var d=c.message["gtm.uniqueEventId"];typeof d!=="number"&&(d=c.message["gtm.uniqueEventId"]=Mi());var e={},f={message:(e.event="gtm.init_consent",e["gtm.uniqueEventId"]=d-2,e),messageContext:{eventId:d-2}},g={},k={message:(g.event="gtm.init",g["gtm.uniqueEventId"]=d-1,g),messageContext:{eventId:d-1}};uy.unshift(k,c);if(Dj){if(!T(85)){var m=ww();m&&vw.push(m)}vk()}b=
f}return b}
function Fy(){for(var a=!1,b;!xy&&(b=Ey());){xy=!0;delete Ti.eventModel;Vi();var c=b,d=c.message,e=c.messageContext;if(d==null)xy=!1;else{e.fromContainerExecution&&$i();try{if(Bb(d))try{d.call(Xi)}catch(v){}else if(Array.isArray(d)){var f=d;if(l(f[0])){var g=f[0].split("."),k=g.pop(),m=f.slice(1),n=Wi(g.join("."),2);if(n!=null)try{n[k].apply(n,m)}catch(v){}}}else{var p=void 0;if(Ib(d))a:{if(d.length&&l(d[0])){var q=ky[d[0]];if(q&&(!e.fromContainerExecution||!ly[d[0]])){p=q(d,e);break a}}p=void 0}else p=
d;p&&(a=Cy(p,e)||a)}}finally{e.fromContainerExecution&&Vi(!0);var r=d["gtm.uniqueEventId"];if(typeof r==="number"){for(var t=ty[String(r)]||[],u=0;u<t.length;u++)vy.push(Gy(t[u]));t.length&&vy.sort(yy);delete ty[String(r)];r>sy&&(sy=r)}xy=!1}}}return!a}
function Hy(){if(T(69)){var a=Iy();}var b=Fy();if(T(69)){}try{var c=Vj(),d=G[ui.jb].hide;if(d&&d[c]!==void 0&&d.end){d[c]=!1;var e=!0,f;for(f in d)if(d.hasOwnProperty(f)&&d[f]===
!0){e=!1;break}e&&(d.end(),d.end=null)}}catch(g){}return b}function Ux(a){if(sy<a.notBeforeEventId){var b=String(a.notBeforeEventId);ty[b]=ty[b]||[];ty[b].push(a)}else vy.push(Gy(a)),vy.sort(yy),I(function(){xy||Fy()})}function Gy(a){return{message:a.message,messageContext:a.messageContext}}
var Jy=function(){function a(f){var g={};if(my(f)){var k=f;f=my(k)?k.getUntrustedMessageValue():void 0;g.fromContainerExecution=!0}return{message:f,messageContext:g}}var b=Gc(ui.jb,[]),c=vi[ui.jb]=vi[ui.jb]||{};c.pruned===!0&&O(83);ty=Sx().get();Tx();Ew(function(){if(!c.gtmDom){c.gtmDom=!0;var f={};b.push((f.event="gtm.dom",f))}});ry(function(){if(!c.gtmLoad){c.gtmLoad=!0;var f={};b.push((f.event="gtm.load",f))}});c.subscribers=(c.subscribers||0)+1;var d=b.push;b.push=function(){var f;if(vi.SANDBOXED_JS_SEMAPHORE>
0){f=[];for(var g=0;g<arguments.length;g++)f[g]=new ny(arguments[g])}else f=[].slice.call(arguments,0);var k=f.map(function(q){return a(q)});uy.push.apply(uy,k);var m=d.apply(b,f),n=Math.max(100,Number("1000")||300);if(this.length>n)for(O(4),c.pruned=!0;this.length>n;)this.shift();var p=typeof m!=="boolean"||m;return Fy()&&p};var e=b.slice(0).map(function(f){return a(f)});uy.push.apply(uy,e);if(Iy()){if(T(69)){}I(Hy)}},Iy=function(){var a=!0;return a};function Ky(a){if(a==null||a.length===0)return!1;var b=Number(a),c=Ob();return b<c+3E5&&b>c-9E5}function Ly(a){return a&&a.indexOf("pending:")===0?Ky(a.substr(8)):!1};

var fz=function(){};var gz=function(){};gz.prototype.toString=function(){return"undefined"};var hz=new gz;function oz(a,b){function c(g){var k=nj(g),m=hj(k,"protocol"),n=hj(k,"host",!0),p=hj(k,"port"),q=hj(k,"path").toLowerCase().replace(/\/$/,"");if(m===void 0||m==="http"&&p==="80"||m==="https"&&p==="443")m="web",p="default";return[m,n,p,q]}for(var d=c(String(a)),e=c(String(b)),f=0;f<d.length;f++)if(d[f]!==e[f])return!1;return!0}
function pz(a){return qz(a)?1:0}
function qz(a){var b=a.arg0,c=a.arg1;if(a.any_of&&Array.isArray(c)){for(var d=0;d<c.length;d++){var e=h(a,{});h({arg1:c[d],any_of:void 0},e);if(pz(e))return!0}return!1}switch(a["function"]){case "_cn":return Ag(b,c);case "_css":var f;a:{if(b)try{for(var g=0;g<wg.length;g++){var k=wg[g];if(b[k]!=null){f=b[k](c);break a}}}catch(m){}f=!1}return f;case "_ew":return xg(b,c);case "_eq":return Bg(b,c);case "_ge":return Cg(b,c);case "_gt":return Eg(b,c);case "_lc":return String(b).split(",").indexOf(String(c))>=
0;case "_le":return Dg(b,c);case "_lt":return Fg(b,c);case "_re":return zg(b,c,a.ignore_case);case "_sw":return Gg(b,c);case "_um":return oz(b,c)}return!1};function rz(){var a;a=a===void 0?"":a;var b,c;return((b=data)==null?0:(c=b.blob)==null?0:c.hasOwnProperty(1))?String(data.blob[1]):a};function sz(){var a=[["cv",T(92)?rz():"1"],["rv",ui.Yg],["tc",xf.filter(function(b){return b}).length]];ui.se&&a.push(["x",ui.se]);Oi.j&&a.push(["tag_exp",Oi.j]);return a};var tz={},uz={};function vz(){var a=0;return function(b){switch(b){case 1:a|=1;break;case 2:a|=2;break;case 3:a|=4}return a}}function wz(a,b,c,d){if(Cj){var e=String(c)+b;tz[a]=tz[a]||[];tz[a].push(e);uz[a]=uz[a]||[];uz[a].push(d+b)}}function xz(a){var b=a.eventId,c=a.mc,d=[],e=tz[b]||[];e.length&&d.push(["hf",e.join(".")]);var f=uz[b]||[];f.length&&d.push(["ht",f.join(".")]);c&&(delete tz[b],delete uz[b]);return d};function yz(){return!1}function zz(){var a={};return function(b,c,d){}};function Az(){var a=Bz;return function(b,c,d){var e=d&&d.event;Cz(c);var f=Tb(b,"__cvt_")?void 0:1,g=new lb;z(c,function(r,t){var u=qd(t,void 0,f);u===void 0&&t!==void 0&&O(44);g.set(r,u)});a.j.j.D=Qf();var k={Pj:eg(b),eventId:e==null?void 0:e.id,priorityId:e!==void 0?e.priorityId:void 0,we:e!==void 0?function(r){e.ic.we(r)}:void 0,fb:function(){return b},log:function(){},Ll:{index:d==null?void 0:d.index,type:d==null?void 0:d.type,name:d==null?void 0:d.name},Tm:!!dw(b,3),originalEventData:e==null?
void 0:e.originalEventData};e&&e.cachedModelValues&&(k.cachedModelValues={gtm:e.cachedModelValues.gtm,ecommerce:e.cachedModelValues.ecommerce});if(yz()){var m=zz(),n,p;k.Ta={bi:[],xe:{},Ab:function(r,t,u){t===1&&(n=r);t===7&&(p=u);m(r,t,u)},Xf:oh()};k.log=function(r){var t=Ma.apply(1,arguments);n&&m(n,4,{level:r,source:p,message:t})}}var q=Re(a,k,[b,g]);a.j.j.D=void 0;q instanceof Qa&&q.type==="return"&&(q=q.data);return J(q,void 0,f)}}
function Cz(a){var b=a.gtmOnSuccess,c=a.gtmOnFailure;Bb(b)&&(a.gtmOnSuccess=function(){I(b)});Bb(c)&&(a.gtmOnFailure=function(){I(c)})};function Dz(a,b){var c=this;}Dz.T="addConsentListener";var Ez=!1;function Fz(a){for(var b=0;b<a.length;++b)if(Ez)try{a[b]()}catch(c){O(77)}else a[b]()}function Gz(a,b,c){var d=this,e;K(this.getName(),["eventName:!string","callback:!Fn","triggerId:?string"],arguments),Fz([function(){N(d,"listen_data_layer",a)}]),e=Ax().addListener(a,J(b),c);return e}Gz.J="internal.addDataLayerEventListener";function Hz(a,b,c){}Hz.T="addDocumentEventListener";function Iz(a,b,c,d){}Iz.T="addElementEventListener";function Jz(a){return a.F.j};function Kz(a){}Kz.T="addEventCallback";
var Lz=function(a){return typeof a==="string"?a:String(Mi())},Oz=function(a,b){Mz(a,"init",!1)||(Nz(a,"init",!0),b())},Mz=function(a,b,c){var d=Pz(a);return Pb(d,b,c)},Qz=function(a,b,c,d){var e=Pz(a),f=Pb(e,b,d);e[b]=c(f)},Nz=function(a,b,c){Pz(a)[b]=c},Pz=function(a){vi.hasOwnProperty("autoEventsSettings")||(vi.autoEventsSettings={});var b=vi.autoEventsSettings;b.hasOwnProperty(a)||(b[a]={});return b[a]},Rz=function(a,b,c){var d={event:b,"gtm.element":a,"gtm.elementClasses":$c(a,"className"),"gtm.elementId":a["for"]||
Rc(a,"id")||"","gtm.elementTarget":a.formTarget||$c(a,"target")||""};c&&(d["gtm.triggers"]=c.join(","));d["gtm.elementUrl"]=(a.attributes&&a.attributes.formaction?a.formAction:"")||a.action||$c(a,"href")||a.src||a.code||a.codebase||"";return d};
function $z(a){}$z.J="internal.addFormAbandonmentListener";function aA(a,b,c,d){}
aA.J="internal.addFormData";var bA={},cA=[],dA={},eA=0,fA=0;
function mA(a,b){}mA.J="internal.addFormInteractionListener";
function tA(a,b){}tA.J="internal.addFormSubmitListener";
function yA(a){}yA.J="internal.addGaSendListener";function zA(a){if(!a)return{};var b=a.Ll;return Gw(b.type,b.index,b.name)}function AA(a){return a?{originatingEntity:zA(a)}:{}};function IA(a){var b=vi.zones;return b?b.getIsAllowedFn(Qj(),a):function(){return!0}}
function JA(){gw(Xj(),function(a){var b=a.originalEventData["gtm.uniqueEventId"],c=vi.zones;return c?c.isActive(Qj(),b):!0});ew(Xj(),function(a){var b,c;b=a.entityId;c=a.securityGroups;return IA(Number(a.originalEventData["gtm.uniqueEventId"]))(b,c)})};var KA=function(a,b){this.tagId=a;this.ze=b};
function LA(a,b){var c=this,d;return d}
LA.J="internal.loadGoogleTag";function MA(a){return new id("",function(b){var c=this.evaluate(b);if(c instanceof id)return new id("",function(){var d=Ma.apply(0,arguments),e=this,f=h(Jz(this),null);f.eventId=a.eventId;f.priorityId=a.priorityId;f.originalEventData=a.originalEventData;var g=d.map(function(m){return e.evaluate(m)}),k=Wa(this.F);k.j=f;return c.ib.apply(c,[k].concat(qa(g)))})})};function NA(a,b,c){var d=this;}NA.J="internal.addGoogleTagRestriction";var OA={},PA=[];
function WA(a,b){}
WA.J="internal.addHistoryChangeListener";function XA(a,b,c){}XA.T="addWindowEventListener";function YA(a,b){return!0}YA.T="aliasInWindow";function ZA(a,b,c){}ZA.J="internal.appendRemoteConfigParameter";function $A(a){var b;return b}$A.T="callInWindow";function aB(a){}aB.T="callLater";function bB(a){}bB.J="callOnDomReady";function cB(a){}cB.J="callOnWindowLoad";function dB(a,b){var c;return c}dB.J="internal.computeGtmParameter";function eB(a){var b;K(this.getName(),["key:!string"],arguments);if(!qo(a))throw Error("copyFromCrossContainerData requires valid CrossContainerSchema key.");var c=to(a);b=qd(c,this.F,1);return b}eB.J="internal.copyFromCrossContainerData";function fB(a,b){var c;var d=qd(c,this.F,Tb(Jz(this).fb(),"__cvt_")?2:1);d===void 0&&c!==void 0&&O(45);return d}fB.T="copyFromDataLayer";
function gB(a){var b=void 0;return b}gB.J="internal.copyFromDataLayerCache";function hB(a){var b;return b}hB.T="copyFromWindow";function iB(a){var b=void 0;return qd(b,this.F,1)}iB.J="internal.copyKeyFromWindow";var jB=function(a,b,c){this.eventName=b;this.m=c;this.o={};this.isAborted=!1;this.target=a;this.metadata=h(c.eventMetadata||{},{})};jB.prototype.copyToHitData=function(a,b,c){var d=U(this.m,a);d===void 0&&(d=b);if(d!==void 0&&c!==void 0&&l(d)&&T(63))try{d=c(d)}catch(e){}d!==void 0&&(this.o[a]=d)};var et=function(a,b,c){var d=hs(a.target.ia);return d&&d[b]!==void 0?d[b]:c};function kB(a,b){var c;K(this.getName(),["preHit:!PixieMap","dustOptions:?PixieMap"],arguments);var d=J(b)||{},e=J(a,this.F,1).Vj(),f=e.m;d.omitEventContext&&(f=gm(new Wl(e.m.eventId,e.m.priorityId)));var g=new jB(e.target,e.eventName,f);d.omitHitData||h(e.o,g.o);d.omitMetadata?g.metadata={}:h(e.metadata,g.metadata);g.isAborted=e.isAborted;c=qd(Yr(g),this.F,1);return c}kB.J="internal.copyPreHit";function lB(a,b){var c=null;return qd(c,this.F,2)}lB.T="createArgumentsQueue";function mB(a){return qd(function(c){var d=Qw();if(typeof c==="function")d(function(){c(function(f,g,k){var m=Qw(),n=m&&m.getByName&&
m.getByName(f);return Mm(G.gaplugins.Linker,n).decorate(g,k)})});else if(Array.isArray(c)){var e=String(c[0]).split(".");b[e.length===1?e[0]:e[1]]&&d.apply(null,c)}else if(c==="isLoaded")return!!d.loaded},this.F,1)}mB.J="internal.createGaCommandQueue";function nB(a){return qd(function(){if(!Bb(e.push))throw Error("Object at "+a+" in window is not an array.");e.push.apply(e,Array.prototype.slice.call(arguments,0))},this.F,Tb(Jz(this).fb(),
"__cvt_")?2:1)}nB.T="createQueue";function oB(a,b){var c=null;K(this.getName(),["pattern:!string","flags:?string"],arguments);try{var d=(b||"").split("").filter(function(e){return"ig".indexOf(e)>=0}).join("");c=new nd(new RegExp(a,d))}catch(e){}return c}oB.J="internal.createRegex";function pB(){var a={};a={SHARED_USER_ID:oo.ah,SHARED_USER_ID_REQUESTED:oo.bh,SHARED_USER_ID_SOURCE:oo.ue};return a};function qB(a){}qB.J="internal.declareConsentState";function rB(a){var b="";return b}rB.J="internal.decodeUrlHtmlEntities";function sB(a,b,c){var d;return d}sB.J="internal.decorateUrlWithGaCookies";function tB(){}tB.J="internal.deferCustomEvents";function uB(a){var b;N(this,"detect_user_provided_data","auto");var c=J(a)||{},d=Hs({vd:!!c.includeSelector,wd:!!c.includeVisibility,De:c.excludeElementSelectors,zb:c.fieldFilters,Zf:!!c.selectMultipleElements});b=new lb;var e=new ib;b.set("elements",e);for(var f=d.elements,g=0;g<f.length;g++)e.push(vB(f[g]));d.Rh!==void 0&&b.set("preferredEmailElement",vB(d.Rh));b.set("status",d.status);
return b}
var vB=function(a){var b=new lb;b.set("userData",a.Z);b.set("tagName",a.tagName);a.querySelector!==void 0&&b.set("querySelector",a.querySelector);a.isVisible!==void 0&&b.set("isVisible",a.isVisible);if(T(25)){}else switch(a.type){case Fs.nc:b.set("type","email")}return b};uB.J="internal.detectUserProvidedData";
function yB(a,b){return b}yB.J="internal.enableAutoEventOnClick";var BB=function(a){if(!zB){var b=function(){var c=H.body;if(c)if(AB)(new MutationObserver(function(){for(var e=0;e<zB.length;e++)I(zB[e])})).observe(c,{childList:!0,subtree:!0});else{var d=!1;Pc(c,"DOMNodeInserted",function(){d||(d=!0,I(function(){d=!1;for(var e=0;e<zB.length;e++)I(zB[e])}))})}};zB=[];H.body?b():I(b)}zB.push(a)},AB=!!G.MutationObserver,zB;
function GB(a,b){return b}GB.J="internal.enableAutoEventOnElementVisibility";function HB(){}HB.J="internal.enableAutoEventOnError";var IB={},JB=[],KB={},LB=0,MB=0;
function SB(a,b){var c=this;return b}SB.J="internal.enableAutoEventOnFormInteraction";
function XB(a,b){var c=this;return b}XB.J="internal.enableAutoEventOnFormSubmit";
function bC(){var a=this;}bC.J="internal.enableAutoEventOnGaSend";var cC={},dC=[];
var fC=function(a,b){var c=""+b;if(cC[c])cC[c].push(a);else{var d=[a];cC[c]=d;var e=eC("gtm.historyChange-v2"),f=-1;dC.push(function(g){f>=0&&G.clearTimeout(f);b?f=G.setTimeout(function(){e(g,d);f=-1},b):e(g,d)})}},eC=function(a){var b=G.location.href,c={source:null,state:G.history.state||null,url:kj(nj(b)),Ia:hj(nj(b),"fragment")};return function(d,e){var f=c,g={};g[f.source]=!0;g[d.source]=!0;if(!g.popstate||!g.hashchange||f.Ia!==d.Ia){var k={event:a,"gtm.historyChangeSource":d.source,"gtm.oldUrlFragment":c.Ia,
"gtm.newUrlFragment":d.Ia,"gtm.oldHistoryState":c.state,"gtm.newHistoryState":d.state,"gtm.oldUrl":c.url,"gtm.newUrl":d.url};e&&(k["gtm.triggers"]=e.join(","));c=d;zy(k)}}},gC=function(a,b){var c=G.history,d=c[a];if(Bb(d))try{c[a]=function(e,f,g){d.apply(c,[].slice.call(arguments,0));var k=G.location.href;b({source:a,state:e,url:kj(nj(k)),Ia:hj(nj(k),"fragment")})}}catch(e){}},iC=function(a){G.addEventListener("popstate",function(b){var c=hC(b);a({source:"popstate",state:b.state,url:kj(nj(c)),Ia:hj(nj(c),
"fragment")})})},jC=function(a){G.addEventListener("hashchange",function(b){var c=hC(b);a({source:"hashchange",state:null,url:kj(nj(c)),Ia:hj(nj(c),"fragment")})})},hC=function(a){var b,c;return((b=a.target)==null?void 0:(c=b.location)==null?void 0:c.href)||G.location.href};
function kC(a,b){var c=this;K(this.getName(),["options:?PixieMap","triggerId:?*"],arguments);Fz([function(){N(c,"detect_history_change_events")}]);var d=a&&a.get("useV2EventName")?"ehl":"hl",e=Number(a&&a.get("interval"));e>0&&isFinite(e)||(e=0);if(!Mz(d,"init",!1)){var f;d==="ehl"?(f=function(k){for(var m=0;m<dC.length;m++)dC[m](k)},b=Lz(b),fC(b,e),Nz(d,"reg",fC)):f=eC("gtm.historyChange");jC(f);iC(f);gC("pushState",f);
gC("replaceState",f);Nz(d,"init",!0)}else if(d==="ehl"){var g=Mz(d,"reg");g&&(b=Lz(b),g(b,e))}d==="hl"&&(b=void 0);return b}kC.J="internal.enableAutoEventOnHistoryChange";var lC=["http://","https://","javascript:","file://"];
var mC=function(a,b){if(a.which===2||a.ctrlKey||a.shiftKey||a.altKey||a.metaKey)return!1;var c=$c(b,"href");if(c.indexOf(":")!==-1&&!lC.some(function(k){return Tb(c,k)}))return!1;var d=c.indexOf("#"),e=$c(b,"target");if(e&&e!=="_self"&&e!=="_parent"&&e!=="_top"||d===0)return!1;if(d>0){var f=kj(nj(c)),g=kj(nj(G.location.href));return f!==g}return!0},nC=function(a,b){for(var c=hj(nj((b.attributes&&b.attributes.formaction?b.formAction:"")||b.action||$c(b,"href")||b.src||b.code||b.codebase||""),"host"),
d=0;d<a.length;d++)try{if((new RegExp(a[d])).test(c))return!1}catch(e){}return!0},oC=function(){function a(c){var d=c.target;if(d&&c.which!==3&&!(c.j||c.timeStamp&&c.timeStamp===b)){b=c.timeStamp;d=Uc(d,["a","area"],100);if(!d)return c.returnValue;var e=c.defaultPrevented||c.returnValue===!1,f=Mz("lcl",e?"nv.mwt":"mwt",0),g;g=e?Mz("lcl","nv.ids",[]):Mz("lcl","ids",[]);for(var k=[],m=0;m<g.length;m++){var n=g[m],p=Mz("lcl","aff.map",{})[n];p&&!nC(p,d)||k.push(n)}if(k.length){var q=mC(c,d),r=Rz(d,"gtm.linkClick",
k);r["gtm.elementText"]=Sc(d);r["gtm.willOpenInNewWindow"]=!q;if(q&&!e&&f&&d.href){var t=!!Eb(String($c(d,"rel")||"").split(" "),function(x){return x.toLowerCase()==="noreferrer"}),u=G[($c(d,"target")||"_self").substring(1)],v=!0,w=By(function(){var x;if(x=v&&u){var y;a:if(t){var B;try{B=new MouseEvent(c.type,{bubbles:!0})}catch(A){if(!H.createEvent){y=!1;break a}B=H.createEvent("MouseEvents");B.initEvent(c.type,!0,!0)}B.j=!0;c.target.dispatchEvent(B);y=!0}else y=!1;x=!y}x&&(u.location.href=$c(d,
"href"))},f);if(Ay(r,w,f))v=!1;else return c.preventDefault&&c.preventDefault(),c.returnValue=!1}else Ay(r,function(){},f||2E3);return!0}}}var b=0;Pc(H,"click",a,!1);Pc(H,"auxclick",a,!1)};
function pC(a,b){var c=this;K(this.getName(),["dustOptions:?PixieMap","triggerId:?*"],arguments);var d=J(a);Fz([function(){N(c,"detect_link_click_events",d)}]);var e=d&&!!d.waitForTags,f=d&&!!d.checkValidation,g=d?d.affiliateDomains:void 0;b=Lz(b);if(e){var k=Number(d.waitForTagsTimeout);k>0&&isFinite(k)||(k=2E3);var m=function(p){return Math.max(k,p)};Qz("lcl","mwt",m,0);f||Qz("lcl","nv.mwt",m,0)}var n=function(p){p.push(b);
return p};Qz("lcl","ids",n,[]);f||Qz("lcl","nv.ids",n,[]);g&&Qz("lcl","aff.map",function(p){p[b]=g;return p},{});Mz("lcl","init",!1)||(oC(),Nz("lcl","init",!0));return b}pC.J="internal.enableAutoEventOnLinkClick";var qC,rC;
var sC=function(a){return Mz("sdl",a,{})},tC=function(a,b,c){if(b){var d=Array.isArray(a)?a:[a];Qz("sdl",c,function(e){for(var f=0;f<d.length;f++){var g=String(d[f]);e.hasOwnProperty(g)||(e[g]=[]);e[g].push(b)}return e},{})}},wC=function(){function a(){uC();vC(a,!0)}return a},xC=function(){function a(){f?e=G.setTimeout(a,c):(e=0,uC(),vC(b));f=!1}function b(){d&&qC();e?f=!0:(e=G.setTimeout(a,c),Nz("sdl","pending",!0))}var c=250,d=!1;H.scrollingElement&&H.documentElement&&(c=50,d=!0);var e=0,f=!1;return b},
vC=function(a,b){Mz("sdl","init",!1)&&!yC()&&(b?Qc(G,"scrollend",a):Qc(G,"scroll",a),Qc(G,"resize",a),Nz("sdl","init",!1))},uC=function(){var a=qC(),b=a.mh,c=a.nh,d=b/rC.scrollWidth*100,e=c/rC.scrollHeight*100;zC(b,"horiz.pix","PIXELS","horizontal");zC(d,"horiz.pct","PERCENT","horizontal");zC(c,"vert.pix","PIXELS","vertical");zC(e,"vert.pct","PERCENT","vertical");Nz("sdl","pending",!1)},zC=function(a,b,c,d){var e=sC(b),f={},g;for(g in e)if(f={Bd:f.Bd},f.Bd=g,e.hasOwnProperty(f.Bd)){var k=Number(f.Bd);
if(!(a<k)){var m={};zy((m.event="gtm.scrollDepth",m["gtm.scrollThreshold"]=k,m["gtm.scrollUnits"]=c.toLowerCase(),m["gtm.scrollDirection"]=d,m["gtm.triggers"]=e[f.Bd].join(","),m));Qz("sdl",b,function(n){return function(p){delete p[n.Bd];return p}}(f),{})}}},BC=function(){Qz("sdl","scr",function(a){a||(a=H.scrollingElement||H.body&&H.body.parentNode);return rC=a},!1);Qz("sdl","depth",function(a){a||(a=AC());return qC=a},!1)},AC=function(){var a=0,b=0;return function(){var c=ks(),d=c.height;a=Math.max(rC.scrollLeft+
c.width,a);b=Math.max(rC.scrollTop+d,b);return{mh:a,nh:b}}},yC=function(){return!!(Object.keys(sC("horiz.pix")).length||Object.keys(sC("horiz.pct")).length||Object.keys(sC("vert.pix")).length||Object.keys(sC("vert.pct")).length)};
function CC(a,b){var c=this;K(this.getName(),["options:!PixieMap","triggerId:?*"],arguments);Fz([function(){N(c,"detect_scroll_events")}]);BC();if(!rC)return;b=Lz(b);var d=J(a);switch(d.horizontalThresholdUnits){case "PIXELS":tC(d.horizontalThresholds,b,"horiz.pix");break;case "PERCENT":tC(d.horizontalThresholds,b,"horiz.pct")}switch(d.verticalThresholdUnits){case "PIXELS":tC(d.verticalThresholds,b,"vert.pix");break;case "PERCENT":tC(d.verticalThresholds,
b,"vert.pct")}Mz("sdl","init",!1)?Mz("sdl","pending",!1)||I(function(){uC()}):(Nz("sdl","init",!0),Nz("sdl","pending",!0),I(function(){uC();if(yC()){var e=xC();"onscrollend"in G?(e=wC(),Pc(G,"scrollend",e)):Pc(G,"scroll",e);Pc(G,"resize",e)}else Nz("sdl","init",!1)}));return b}CC.J="internal.enableAutoEventOnScroll";function DC(a){return function(){if(a.Jh&&a.Lh>=a.Jh)a.Vf&&G.clearInterval(a.Vf);else{a.Lh++;var b=Ob();zy({event:a.eventName,"gtm.timerId":a.Vf,"gtm.timerEventNumber":a.Lh,"gtm.timerInterval":a.interval,"gtm.timerLimit":a.Jh,"gtm.timerStartTime":a.rk,"gtm.timerCurrentTime":b,"gtm.timerElapsedTime":b-a.rk,"gtm.triggers":a.pn})}}}
function EC(a,b){
return b}EC.J="internal.enableAutoEventOnTimer";
var FC=function(a,b,c){function d(){var g=a();f+=e?(Ob()-e)*g.playbackRate/1E3:0;e=Ob()}var e=0,f=0;return{createEvent:function(g,k,m){var n=a(),p=n.oh,q=m?Math.round(m):k?Math.round(n.oh*k):Math.round(n.Qj),r=k!==void 0?Math.round(k*100):p<=0?0:Math.round(q/p*100),t=H.hidden?!1:ls(c)>=.5;d();var u=void 0;b!==void 0&&(u=[b]);var v=Rz(c,"gtm.video",u);v["gtm.videoProvider"]="youtube";v["gtm.videoStatus"]=g;v["gtm.videoUrl"]=n.url;v["gtm.videoTitle"]=n.title;v["gtm.videoDuration"]=Math.round(p);v["gtm.videoCurrentTime"]=
Math.round(q);v["gtm.videoElapsedTime"]=Math.round(f);v["gtm.videoPercent"]=r;v["gtm.videoVisible"]=t;return v},mk:function(){e=Ob()},od:function(){d()}}};var uc=ka(["data-gtm-yt-inspected-"]),GC=["www.youtube.com","www.youtube-nocookie.com"],HC,IC=!1;
var JC=function(a,b,c){var d=a.map(function(g){return{Ha:g,Ye:g,Ve:void 0}});if(!b.length)return d;var e=b.map(function(g){return{Ha:g*c,Ye:void 0,Ve:g}});if(!d.length)return e;var f=d.concat(e);f.sort(function(g,k){return g.Ha-k.Ha});return f},KC=function(a){a=a===void 0?[]:a;for(var b=[],c=0;c<a.length;c++)a[c]<0||b.push(a[c]);b.sort(function(d,e){return d-e});return b},LC=function(a){a=a===void 0?[]:a;for(var b=[],c=0;c<a.length;c++)a[c]>100||a[c]<0||(b[c]=a[c]/100);b.sort(function(d,e){return d-
e});return b},MC=function(a,b){var c,d;function e(){t=FC(function(){return{url:w,title:x,oh:v,Qj:a.getCurrentTime(),playbackRate:y}},b.Eb,a.getIframe());v=0;x=w="";y=1;return f}function f(E){switch(E){case 1:v=Math.round(a.getDuration());w=a.getVideoUrl();if(a.getVideoData){var D=a.getVideoData();x=D?D.title:""}y=a.getPlaybackRate();b.hh?zy(t.createEvent("start")):t.od();u=JC(b.Th,b.Sh,a.getDuration());return g(E);default:return f}}function g(){B=a.getCurrentTime();A=Nb().getTime();t.mk();r();return k}
function k(E){var D;switch(E){case 0:return n(E);case 2:D="pause";case 3:var F=a.getCurrentTime()-B;D=Math.abs((Nb().getTime()-A)/1E3*y-F)>1?"seek":D||"buffering";a.getCurrentTime()&&(b.gh?zy(t.createEvent(D)):t.od());q();return m;case -1:return e(E);default:return k}}function m(E){switch(E){case 0:return n(E);case 1:return g(E);case -1:return e(E);default:return m}}function n(){for(;d;){var E=c;G.clearTimeout(d);E()}b.fh&&zy(t.createEvent("complete",1));return e(-1)}function p(){}function q(){d&&
(G.clearTimeout(d),d=0,c=p)}function r(){if(u.length&&y!==0){var E=-1,D;do{D=u[0];if(D.Ha>a.getDuration())return;E=(D.Ha-a.getCurrentTime())/y;if(E<0&&(u.shift(),u.length===0))return}while(E<0);c=function(){d=0;c=p;u.length>0&&u[0].Ha===D.Ha&&(u.shift(),zy(t.createEvent("progress",D.Ve,D.Ye)));r()};d=G.setTimeout(c,E*1E3)}}var t,u=[],v,w,x,y,B,A,C=e(-1);d=0;c=p;return{onStateChange:function(E){C=C(E)},onPlaybackRateChange:function(E){B=a.getCurrentTime();A=Nb().getTime();t.od();y=E;q();r()}}},OC=
function(a){I(function(){function b(){for(var d=c.getElementsByTagName("iframe"),e=d.length,f=0;f<e;f++)NC(d[f],a)}var c=H;b();BB(b)})},NC=function(a,b){if(!a.getAttribute("data-gtm-yt-inspected-"+b.Eb)&&(zc(a,"data-gtm-yt-inspected-"+b.Eb),PC(a,b.He))){a.id||(a.id=QC());var c=G.YT,d=c.get(a.id);d||(d=new c.Player(a.id));var e=MC(d,b),f={},g;for(g in e)f={Pe:f.Pe},f.Pe=g,e.hasOwnProperty(f.Pe)&&d.addEventListener(f.Pe,function(k){return function(m){return e[k.Pe](m.data)}}(f))}},PC=function(a,b){var c=
a.getAttribute("src");if(RC(c,"embed/")){if(c.indexOf("enablejsapi=1")>0)return!0;if(b){var d;var e=c.indexOf("?")!==-1?"&":"?";c.indexOf("origin=")>-1?d=c+e+"enablejsapi=1":(HC||(HC=H.location.protocol+"//"+H.location.hostname,H.location.port&&(HC+=":"+H.location.port)),d=c+e+"enablejsapi=1&origin="+encodeURIComponent(HC));var f;f=fc(d);a.src=dc(f).toString();return!0}}return!1},RC=function(a,b){if(!a)return!1;for(var c=0;c<GC.length;c++)if(a.indexOf("//"+GC[c]+"/"+b)>=0)return!0;return!1},QC=function(){var a=
""+Math.round(Math.random()*1E9);return H.getElementById(a)?QC():a};
function SC(a,b){var c=this;var d=function(){OC(p)};K(this.getName(),["dustOptions:!PixieMap","triggerId:?*"],arguments);Fz([function(){N(c,"detect_youtube_activity_events",{fixMissingApi:!!a.get("fixMissingApi")})}]);b=Lz(b);var e=!!a.get("captureStart"),f=!!a.get("captureComplete"),g=!!a.get("capturePause"),k=LC(J(a.get("progressThresholdsPercent"))),m=KC(J(a.get("progressThresholdsTimeInSeconds"))),n=!!a.get("fixMissingApi");
if(!(e||f||g||k.length||m.length))return;var p={hh:e,fh:f,gh:g,Sh:k,Th:m,He:n,Eb:b},q=G.YT;if(q)return q.ready&&q.ready(d),b;var r=G.onYouTubeIframeAPIReady;G.onYouTubeIframeAPIReady=function(){r&&r();d()};I(function(){for(var t=H.getElementsByTagName("script"),u=t.length,v=0;v<u;v++){var w=t[v].getAttribute("src");if(RC(w,"iframe_api")||RC(w,"player_api"))return b}for(var x=H.getElementsByTagName("iframe"),y=x.length,B=0;B<y;B++)if(!IC&&PC(x[B],p.He))return Lc("https://www.youtube.com/iframe_api"),
IC=!0,b});return b}SC.J="internal.enableAutoEventOnYouTubeActivity";function TC(a,b){K(this.getName(),["booleanExpression:!string","context:?PixieMap"],arguments);var c=b?J(b):{},d=a,e=!1;var f=JSON.parse(d);if(!f)throw Error("Invalid boolean expression string was given.");e=dh(f,c);return e}TC.J="internal.evaluateBooleanExpression";var UC;function VC(a){var b=!1;return b}VC.J="internal.evaluateMatchingRules";function CD(){return On(7)&&On(9)&&On(10)};function xE(a,b,c,d){}xE.J="internal.executeEventProcessor";function yE(a){var b;return qd(b,this.F,1)}yE.J="internal.executeJavascriptString";function zE(a){var b;return b};var AE=null;
function BE(){var a=new lb;N(this,"read_container_data"),T(40)&&AE?a=AE:(a.set("containerId",'G-DBEM2FVVRF'),a.set("version",'1'),a.set("environmentName",''),a.set("debugMode",fg),a.set("previewMode",gg.tk),a.set("environmentMode",gg.Hl),a.set("firstPartyServing",Qi()||Di),a.set("containerUrl",Fc),a.Ma(),T(40)&&(AE=a));return a}
BE.T="getContainerVersion";function CE(a,b){b=b===void 0?!0:b;var c;return c}CE.T="getCookieValues";function DE(){return bl()}DE.J="internal.getCountryCode";function EE(){var a=[];a=Tj();return qd(a)}EE.J="internal.getDestinationIds";function FE(a,b){var c=null;return c}FE.J="internal.getElementAttribute";function GE(a){var b=null;return b}GE.J="internal.getElementById";function HE(a){var b="";return b}HE.J="internal.getElementInnerText";function IE(a,b){var c=null;return c}IE.J="internal.getElementProperty";function JE(a){var b;return b}JE.J="internal.getElementValue";function KE(a){var b=0;return b}KE.J="internal.getElementVisibilityRatio";function LE(a){var b=null;return b}LE.J="internal.getElementsByCssSelector";
function ME(a){var b;K(this.getName(),["keyPath:!string"],arguments);N(this,"read_event_data",a);var c;a:{var d=a,e=Jz(this).originalEventData;if(e){for(var f=e,g={},k={},m={},n=[],p=d.split("\\\\"),q=0;q<p.length;q++){for(var r=p[q].split("\\."),t=0;t<r.length;t++){for(var u=r[t].split("."),v=0;v<u.length;v++)n.push(u[v]),v!==u.length-1&&n.push(m);t!==r.length-1&&n.push(k)}q!==p.length-1&&n.push(g)}for(var w=[],x="",y=oa(n),B=y.next();!B.done;B=
y.next()){var A=B.value;A===m?(w.push(x),x=""):x=A===g?x+"\\":A===k?x+".":x+A}x&&w.push(x);for(var C=oa(w),E=C.next();!E.done;E=C.next()){if(f==null){c=void 0;break a}f=f[E.value]}c=f}else c=void 0}b=qd(c,this.F,1);return b}ME.J="internal.getEventData";var NE={};NE.enableAWFledge=T(26);NE.enableAdsConversionValidation=T(14);NE.enableAutoPiiOnPhoneAndAddress=T(25);NE.enableCachedEcommerceData=T(32);NE.enableCcdPreAutoPiiDetection=T(33);NE.enableCloudRecommentationsErrorLogging=T(34);NE.enableCloudRecommentationsSchemaIngestion=T(35);NE.enableCloudRetailInjectPurchaseMetadata=T(37);NE.enableCloudRetailLogging=T(36);NE.enableCloudRetailPageCategories=T(38);NE.enableConsentDisclosureActivity=T(39);NE.enableConversionMarkerPageViewRename=T(41);
NE.enableDCFledge=T(45);NE.enableDecodeUri=T(63);NE.enableDeferAllEnhancedMeasurement=T(46);NE.enableDmaBlockDisclosure=T(49);NE.enableEuidAutoMode=T(54);NE.enableFormSkipValidation=T(59);NE.enableUrlDecodeEventUsage=T(91);NE.enableZoneConfigInChildContainers=T(93);NE.useEnableAutoEventOnFormApis=T(102);NE.autoPiiEligible=gl();function OE(){return qd(NE)}OE.J="internal.getFlags";function PE(){return new nd(hz)}PE.J="internal.getHtmlId";function QE(a,b){var c;K(this.getName(),["targetId:!string","name:!string"],arguments);var d=hs(a)||{};c=qd(d[b],this.F);return c}QE.J="internal.getProductSettingsParameter";function RE(a,b){var c;K(this.getName(),["queryKey:!string","retrieveAll:?boolean"],arguments);N(this,"get_url","query",a);var d=hj(nj(G.location.href),"query"),e=gj(d,a,b);c=qd(e,this.F);return c}RE.T="getQueryParameters";function SE(a,b){var c;return c}SE.T="getReferrerQueryParameters";function TE(a){var b="";return b}TE.T="getReferrerUrl";function UE(){return cl()}UE.J="internal.getRegionCode";function VE(a,b){var c;K(this.getName(),["targetId:!string","name:!string"],arguments);var d=Em(a);c=qd(d[b],this.F);return c}VE.J="internal.getRemoteConfigParameter";function WE(a){var b="";K(this.getName(),["component:?string"],arguments),N(this,"get_url",a),b=hj(nj(G.location.href),a);return b}WE.T="getUrl";function XE(){N(this,"get_user_agent");return Cc.userAgent}XE.J="internal.getUserAgent";var YE=!1,ZE=function(a){var b=a.eventName===P.g.Vb&&Qk()&&ht(a),c=a.metadata.is_sgtm_service_worker,d=a.metadata.batch_on_navigation,e=a.metadata.is_conversion,f=a.metadata.is_session_start,g=a.metadata.create_dc_join,k=a.metadata.create_google_join,m=a.metadata.euid_mode_enabled&&!!gt(a);return!(!Yc()&&!Cc.sendBeacon||e||m||f||g||k||b||c||!d&&YE)};
var $E=function(a){var b=0,c=0;return{start:function(){b=Ob()},stop:function(){c=this.get()},get:function(){var d=0;a.Dh()&&(d=Ob()-b);return d+c}}},aF=function(){this.j=void 0;this.D=0;this.isActive=this.isVisible=this.H=!1;this.O=this.K=void 0};ba=aF.prototype;ba.Yk=function(a){var b=this;if(!this.j){this.H=H.hasFocus();this.isVisible=!H.hidden;this.isActive=!0;var c=function(d,e,f){Pc(d,e,function(g){b.j.stop();f(g);b.Dh()&&b.j.start()})};c(G,"focus",function(){b.H=!0});c(G,"blur",function(){b.H=
!1});c(G,"pageshow",function(d){b.isActive=!0;d.persisted&&O(56);b.O&&b.O()});c(G,"pagehide",function(){b.isActive=!1;b.K&&b.K()});c(H,"visibilitychange",function(){b.isVisible=!H.hidden});ht(a)&&!Hc("Firefox")&&!Hc("FxiOS")&&c(G,"beforeunload",function(){YE=!0});this.Wh();this.D=0}};ba.Wh=function(){this.D+=this.Rf();this.j=$E(this);this.Dh()&&this.j.start()};ba.on=function(a){var b=this.Rf();b>0&&(a.o[P.g.Qd]=b)};ba.am=function(a){a.o[P.g.Qd]=void 0;this.Wh();this.D=0};ba.Dh=function(){return this.H&&
this.isVisible&&this.isActive};ba.Sl=function(){return this.D+this.Rf()};ba.Rf=function(){return this.j&&this.j.get()||0};ba.Rm=function(a){this.K=a};ba.lk=function(a){this.O=a};var cF=function(a){var b=a.metadata.event_usage;if(Array.isArray(b))for(var c=0;c<b.length;c++)bF(b[c]);var d=vb("GA4_EVENT");d&&(a.o._eu=d)},dF=function(){delete tb.GA4_EVENT},bF=function(a){ub("GA4_EVENT",a)};function eF(){return G.gaGlobal=G.gaGlobal||{}}function fF(){var a=eF();a.hid=a.hid||Fb();return a.hid}function gF(a,b){var c=eF();if(c.vid===void 0||b&&!c.from_cookie)c.vid=a,c.from_cookie=b};
var hF=function(a,b,c){var d=a.metadata.client_id_source;if(d===void 0||c<=d)a.o[P.g.pb]=b,a.metadata.client_id_source=c},kF=function(a,b){var c;var d=b.metadata.cookie_options,e=d.prefix+"_ga",f=So(d,void 0,void 0,P.g.U);if(U(b.m,P.g.vc)===!1&&iF(b)===a)c=!0;else{var g=Ro(a,jF[0],d.domain,d.path);c=Io(e,g,f)!==1}return c},iF=function(a){var b=a.metadata.cookie_options,c=b.prefix+"_ga",d=Qo(c,b.domain,b.path,jF,P.g.U);if(!d){var e=String(U(a.m,P.g.uc,""));e&&e!=c&&(d=Qo(e,b.domain,b.path,jF,P.g.U))}return d},
jF=["GA1"],lF=function(a,b){var c=a.o[P.g.pb];if(U(a.m,P.g.Lb)&&U(a.m,P.g.Zb)||b&&c===b)return c;if(c){c=""+c;if(!kF(c,a))return O(31),a.isAborted=!0,"";gF(c,W(P.g.U));return c}O(32);a.isAborted=!0;return""};
var oF=function(a,b,c){if(!b)return a;if(!a)return b;var d=mF(a);if(!d)return b;var e,f=Jb((e=U(c.m,P.g.kd))!=null?e:30);if(!(Math.floor(c.metadata.event_start_timestamp_ms/1E3)>d.Re+f*60))return a;var g=mF(b);if(!g)return a;g.Lc=d.Lc+1;var k;return(k=nF(g.sessionId,g.Lc,g.zd,g.Re,g.Hh,g.Hc,g.Ce))!=null?k:b},rF=function(a,b){var c=b.metadata.cookie_options,d=pF(b,c),e=Ro(a,qF[0],c.domain,c.path),f={Db:P.g.U,domain:c.domain,path:c.path,expires:c.Cb?new Date(Ob()+Number(c.Cb)*1E3):void 0,flags:c.flags};
Io(d,void 0,f);return Io(d,e,f)!==1},sF=function(a){var b=a.metadata.cookie_options,c=pF(a,b),d=Qo(c,b.domain,b.path,qF,P.g.U);if(!d)return d;var e=xo(c,void 0,void 0,P.g.U);if(d&&e.length>1){O(114);for(var f=void 0,g=void 0,k=0;k<e.length;k++){var m=e[k].split(".");if(!(m.length<7)){var n=Number(m[5]);n&&(!g||n>g)&&(g=n,f=e[k])}}f&&!Ub(f,d)&&(O(115),d=f.split(".").slice(2).join("."))}return d},tF=function(a){return nF(a.o[P.g.wb],a.o[P.g.ee],a.o[P.g.de],Math.floor(a.metadata.event_start_timestamp_ms/
1E3),a.metadata.join_timer_sec||0,!!a.metadata[P.g.pf],a.o[P.g.Rd])},nF=function(a,b,c,d,e,f,g){if(a&&b){var k=[a,b,Jb(c),d,e];k.push(f?"1":"0");k.push(g||"0");return k.join(".")}},pF=function(a,b){return b.prefix+"_ga_"+a.target.ma[Cl[0]]},qF=["GS1"],mF=function(a){if(a){var b=a.split(".");if(!(b.length<5||b.length>7)){b.length<7&&O(67);var c=Number(b[1]),d=Number(b[3]),e=Number(b[4]||0);c||O(118);d||O(119);isNaN(e)&&O(120);if(c&&d&&!isNaN(e))return{sessionId:b[0],Lc:c,zd:!!Number(b[2]),Re:d,Hh:e,
Hc:b[5]==="1",Ce:b[6]!=="0"?b[6]:void 0}}}};
var uF=function(a){var b=U(a.m,P.g.sa),c=a.m.D[P.g.sa];if(c===b)return c;var d=h(b);c&&c[P.g.X]&&(d[P.g.X]=(d[P.g.X]||[]).concat(c[P.g.X]));return d},vF=function(a,b){var c=hp(!0);return c._up!=="1"?{}:{clientId:c[a],Ya:c[b]}},wF=function(a,b,c){var d=hp(!0),e=d[b];e&&(hF(a,e,2),kF(e,a));var f=d[c];f&&rF(f,a);return{clientId:e,Ya:f}},xF=!1,yF=function(a){var b=uF(a)||{},c=a.metadata.cookie_options,d=c.prefix+"_ga",e=pF(a,c),f={};rp(b[P.g.Cc],!!b[P.g.X])&&(f=wF(a,d,e),f.clientId&&f.Ya&&(xF=!0));b[P.g.X]&&
op(function(){var g={},k=iF(a);k&&(g[d]=k);var m=sF(a);m&&(g[e]=m);var n=xo("FPLC",void 0,void 0,P.g.U);n.length&&(g._fplc=n[0]);return g},b[P.g.X],b[P.g.Mb],!!b[P.g.vb]);return f},AF=function(a){if(!U(a.m,P.g.Xa))return{};var b=a.metadata.cookie_options,c=b.prefix+"_ga",d=pF(a,b);pp(function(){var e;if(W("analytics_storage"))e={};else{var f={};e=(f._up="1",f[c]=a.o[P.g.pb],f[d]=tF(a),f)}return e},1);return!W("analytics_storage")&&zF()?vF(c,d):{}},zF=function(){var a=jj(G.location,"host"),b=jj(nj(H.referrer),
"host");return a&&b?a===b||a.indexOf("."+b)>=0||b.indexOf("."+a)>=0?!0:!1:!1};var BF=function(a){if(!a.metadata.is_merchant_center&&uj(a.m)){var b=uF(a)||{},c=(rp(b[P.g.Cc],!!b[P.g.X])?hp(!0)._fplc:void 0)||(xo("FPLC",void 0,void 0,P.g.U).length>0?void 0:"0");a.o._fplc=c}};function CF(a){var b=T(60)&&Qi();if(ht(a)||b)a.o[P.g.gj]=cl()||bl()};var EF=function(a,b){var c=vi.grl;c||(c=DF(),vi.grl=c);c(b)||(O(35),a.isAborted=!0)},DF=function(){var a=Ob(),b=a+864E5,c=20,d=5E3;return function(e){var f=Ob();f>=b&&(b=f+864E5,d=5E3);c=Math.min(c+(f-a)/1E3*5,20);a=f;var g=!1;d<1||c<1||(g=!0,d--,c--);e&&(e.Fl=d,e.zl=c);return g}};
var FF=function(a){if(U(a.m,P.g.dd)!==void 0)a.copyToHitData(P.g.dd);else{var b=U(a.m,P.g.tf),c,d;a:{if(xF){var e=uF(a)||{};if(e&&e[P.g.X])for(var f=hj(nj(a.o[P.g.Fa]),"host",!0),g=e[P.g.X],k=0;k<g.length;k++)if(g[k]instanceof RegExp){if(g[k].test(f)){d=!0;break a}}else if(f.indexOf(g[k])>=0){d=!0;break a}}d=!1}if(!(c=d)){var m;if(m=b)a:{for(var n=b.include_conditions||[],p=hj(nj(a.o[P.g.Fa]),"host",!0),q=0;q<n.length;q++)if(n[q].test(p)){m=!0;break a}m=!1}c=m}c&&(a.o[P.g.dd]="1",bF(4))}};
var GF=function(a,b){Un()&&(a.gcs=Vn(),b.metadata.is_consent_update&&(a.gcu="1"));a.gcd=fo(b.m);Tn(b.m)?a.npa="0":a.npa="1";ko()&&(a._ng="1")},JF=function(a){if(a.metadata.is_merchant_center)return{url:vj("https://www.merchant-center-analytics.goog")+"/mc/collect",endpoint:20};var b=rj(uj(a.m),"/g/collect");if(b)return{url:b,endpoint:16};if(Qi())return{url:""+Pi()+"/g/collect",endpoint:16};var c=it(a),d=U(a.m,P.g.ob);return c&&!dl()&&d!==!1&&CD()&&W(P.g.R)&&W(P.g.U)?{url:HF(),endpoint:17}:{url:IF(),
endpoint:16}},KF=!1;KF=!0;var LF={};LF[P.g.pb]="cid";LF[P.g.ng]="gcut";LF[P.g.Xb]="are";LF[P.g.jf]="pscdl";LF[P.g.qf]="_fid";LF[P.g.Cg]="_geo";LF[P.g.ub]="gdid";LF[P.g.Bc]="_ng";LF[P.g.Kb]="frm";LF[P.g.dd]="ir";LF[P.g.Ra]="ul";LF[P.g.Mg]="pae";LF[P.g.be]="_rdi";LF[P.g.Nb]="sr";LF[P.g.fj]="tid";LF[P.g.yf]="tt";LF[P.g.md]="ec_mode";LF[P.g.rj]="gtm_up";LF[P.g.zf]="uaa";LF[P.g.Af]="uab";LF[P.g.Bf]="uafvl";LF[P.g.Cf]="uamb";LF[P.g.Df]="uam";LF[P.g.Ef]="uap";LF[P.g.Ff]="uapv";LF[P.g.Gf]="uaw";LF[P.g.gj]="ur";LF[P.g.ed]="lps";var MF={};MF[P.g.Oc]="cc";MF[P.g.Pc]="ci";MF[P.g.Qc]="cm";MF[P.g.Rc]="cn";MF[P.g.Tc]="cs";MF[P.g.Uc]="ck";MF[P.g.za]="cu";MF[P.g.wa]=
"dl";MF[P.g.Fa]="dr";MF[P.g.cb]="dt";MF[P.g.de]="seg";MF[P.g.wb]="sid";MF[P.g.ee]="sct";MF[P.g.Ba]="uid";T(95)&&(MF[P.g.gd]="dp");var NF={};NF[P.g.Qd]="_et";NF[P.g.rb]="edid";var OF={};OF[P.g.Oc]="cc";OF[P.g.Pc]=
"ci";OF[P.g.Qc]="cm";OF[P.g.Rc]="cn";OF[P.g.Tc]="cs";OF[P.g.Uc]="ck";var PF={},QF=Object.freeze((PF[P.g.Ga]=1,PF)),IF=function(){var a="www";KF&&fl()&&(a=fl());return"https://"+a+".google-analytics.com/g/collect"},HF=function(){var a;KF&&fl()!==""&&(a=fl());return"https://"+(a?a+".":"")+"analytics.google.com/g/collect"},RF=function(a,b,c){var d={},e={},f={};d.v="2";d.tid=a.target.ia;d.gtm=no({xa:a.metadata.source_canonical_id});d._p=T(104)?Ii:fF();c&&(d.em=c);a.metadata.create_google_join&&(d._gaz=
1);GF(d,a);io()&&(d.dma_cps=go());d.dma=ho();yn(Gn())&&(d.tcfd=jo());Oi.j&&(d.tag_exp=Oi.j);var g=a.o[P.g.ub];g&&(d.gdid=g);e.en=String(a.eventName);a.metadata.is_first_visit&&(e._fv=a.metadata.is_first_visit_conversion?2:1);a.metadata.is_new_to_site&&(e._nsi=1);a.metadata.is_session_start&&(e._ss=a.metadata.is_session_start_conversion?2:1);a.metadata.is_conversion&&(e._c=1);a.metadata.is_external_event&&(e._ee=1);if(a.metadata.is_ecommerce){var k=a.o[P.g.da]||U(a.m,P.g.da);if(Array.isArray(k))for(var m=
0;m<k.length&&m<200;m++)e["pr"+(m+1)]=kg(k[m])}var n=a.o[P.g.rb];n&&(e.edid=n);var p=function(t,u){if(typeof u!=="object"||!QF[t]){var v="ep."+t,w="epn."+t;t=Cb(u)?w:v;var x=Cb(u)?v:w;e.hasOwnProperty(x)&&delete e[x];e[t]=String(u)}};z(a.o,function(t,u){if(u!==void 0&&!ci.hasOwnProperty(t)){u===null&&(u="");var v;var w=u;t!==P.g.Rd?v=!1:a.metadata.euid_mode_enabled||ht(a)?(d.ecid=w,v=!0):v=void 0;if(!v&&t!==P.g.pf){var x=u;u===!0&&(x="1");u===!1&&(x="0");x=String(x);var y;if(LF[t])y=LF[t],d[y]=x;
else if(MF[t])y=MF[t],f[y]=x;else if(NF[t])y=NF[t],e[y]=x;else if(t.charAt(0)==="_")d[t]=x;else{var B;OF[t]?B=!0:t!==P.g.Sc?B=!1:(typeof u!=="object"&&p(t,u),B=!0);B||p(t,u)}}}});(function(t){ht(a)&&typeof t==="object"&&z(t||{},function(u,v){typeof v!=="object"&&(d["sst."+u]=String(v))})})(a.o[P.g.te]);var q=a.o[P.g.eb]||{};T(70)&&U(a.m,P.g.ob,void 0,4)===!1&&(d.ngs="1");z(q,function(t,u){u!==void 0&&((u===null&&(u=""),t!==P.g.Ba||f.uid)?b[t]!==u&&(e[(Cb(u)?"upn.":"up.")+String(t)]=String(u),b[t]=
u):f.uid=String(u))});var r=JF(a);sg.call(this,{ja:d,Mc:f,sh:e},r.url,r.endpoint,ht(a),void 0)};za(RF,sg);var SF=function(a){this.D=a;this.H="";this.j=this.D},TF=function(a,b){a.j=b;return a},UF=function(a,b){a.K=b;return a},WF=function(a,b){b=a.H+b;for(var c=b.indexOf("\n\n");c!==-1;){var d=a,e;a:{var f=oa(b.substring(0,c).split("\n")),g=f.next().value,k=f.next().value;if(g.indexOf("event: message")===0&&k.indexOf("data: ")===0)try{e=JSON.parse(k.substring(k.indexOf(":")+1));break a}catch(x){}e=void 0}var m=d,n=e;if(n){VF(n.send_pixel,n.options,m.D);VF(n.send_beacon,void 0,m.j);var p=n.create_iframe,
q=n.options,r=m.K;if(p&&r){var t=p||[];if(Array.isArray(t))for(var u=fb(q)?q:{},v=oa(t),w=v.next();!w.done;w=v.next())r(w.value,u)}}b=b.substring(c+2);c=b.indexOf("\n\n")}a.H=b};function XF(a){var b=a.search;return a.protocol+"//"+a.hostname+a.pathname+(b?b+"&richsstsse":"?richsstsse")}function VF(a,b,c){if(a){var d=a||[];if(Array.isArray(d))for(var e=fb(b)?b:{},f=oa(d),g=f.next();!g.done;g=f.next())c(g.value,e)}};
var YF=function(a,b){return a.replace(/\$\{([^\}]+)\}/g,function(c,d){return b[d]||c})},ZF=function(a){var b={},c="",d=a.pathname.indexOf("/g/collect");d>=0&&(c=a.pathname.substring(0,d));b.transport_url=a.protocol+"//"+a.hostname+c;return b},$F=function(a,b,c){var d=0,e=new G.XMLHttpRequest;e.withCredentials=!0;e.onprogress=function(f){if(e.status===200){var g=e.responseText.substring(d);d=f.loaded;WF(c,g)}};e.open(b?"POST":"GET",a);e.setAttributionReporting&&e.setAttributionReporting({eventSourceEligible:!1,triggerEligible:!0});
e.send(b)},bG=function(a,b,c){var d=Object.assign({},aG);b&&(d.body=b,d.method="POST");G.fetch(a,d).then(function(e){if(e.ok&&e.body){var f=e.body.getReader();return new Promise(function(g){function k(){f.read().then(function(m){var n,p;n=m.done;p=m.value;if(n)g();else{var q=(new TextDecoder).decode(p);WF(c,q);k()}}).catch(function(){g()})}k()})}}).catch(function(){T(81)&&(a+="&_z=retryFetch",b?Wc(a,b):Vc(a))})},cG=function(a,b){return UF(TF(new SF(function(c,d){var e=YF(c,a);b&&(e=e.replace("_is_sw=0",
b));var f={};d.attribution_reporting&&(f.attributionsrc="");Oc(e,void 0,void 0,f)}),function(c){var d=YF(c,a);Vc(d)}),function(c,d){var e=YF(c,a),f=d.dedupe_key;f&&Xt(e,f)})},dG=function(a,b,c,d){var e=cG(c,d);T(80)&&Yc()?bG(a,b,e):$F(a,b,e)},eG=function(a,b){var c=nj(a),d=ZF(c),e=XF(c);T(83)?Dt(e,b,d,function(f){dG(e,b,d,f)}):dG(e,b,d)},aG=Object.freeze({cache:"no-store",credentials:"include",method:"GET",keepalive:!0,redirect:"follow"});
var fG=function(a,b){return a?[a,b].join("&"):b},iG=function(a,b,c,d){var e=b,f=ad();f!==void 0&&(e+="&tfd="+Math.round(f));b=e;var g=a+"?"+b;gG&&(d=!Tb(g,IF())&&!Tb(g,HF()));if(d&&!YE)eG(g,c);else{var k=b;Yc()?Zc(a+"?"+k,c,{Wn:!0})||hG(a,fG(k,"_z=failedfetch"),c):hG(a,fG(k,"_z=nofetch"),c)}},jG=function(a,b){function c(u){n.push(u+"="+encodeURIComponent(""+a.ja[u]))}var d=b.bn,e=b.dn,f=b.Ul,g=b.om,k=b.lm,m=b.Qm;if(d||e){var n=[];a.ja._ng&&c("_ng");c("tid");c("cid");c("gtm");n.push("aip=1");a.Mc.uid&&
!k&&n.push("uid="+encodeURIComponent(""+a.Mc.uid));var p=function(){c("dma");a.ja.dma_cps!=null&&c("dma_cps");a.ja.gcs!=null&&c("gcs");c("gcd");a.ja.npa!=null&&c("npa")};p();a.ja.frm!=null&&c("frm");d&&(Oi.j&&n.push("tag_exp="+Oi.j),hG("https://stats.g.doubleclick.net/g/collect","v=2&"+n.join("&")),n.join("&"));if(e){var q=function(){var u=Zt()+"/td/ga/rul?";n=[];c("tid");n.push("gacid="+encodeURIComponent(String(a.ja.cid)));c("gtm");p();c("pscdl");a.ja._ng!=null&&c("_ng");n.push("aip=1");n.push("fledge=1");
a.ja.frm!=null&&c("frm");Oi.j&&n.push("tag_exp="+Oi.j);n.push("z="+Fb());var v=u+n.join("&");Xt(v,a.ja.tid)};Oi.j&&n.push("tag_exp="+Oi.j);n.push("z="+Fb());if(!g){var r=f&&Tb(f,"google.")&&f!=="google.com"?"https://www.%/ads/ga-audiences?v=1&t=sr&slf_rd=1&_r=4&".replace("%",f):void 0;if(r){var t=r+n.join("&");Oc(t)}}T(70)&&m&&!YE&&q()}}},gG=!1;var kG=function(){this.K=
1;this.O={};this.j=new lg;this.D=-1};kG.prototype.H=function(a,b){var c=this,d=new RF(a,this.O,b),e=ZE(a);e&&this.j.O(d)||this.flush();if(e&&this.j.add(d)){if(this.D<0){var f=G.setTimeout,g;ht(a)?lG?(lG=!1,g=mG):g=nG:g=5E3;this.D=f.call(G,function(){return c.flush()},g)}}else{var k=og(d,this.K++);iG(d.baseUrl,k.params,k.body,d.H);var m=a.metadata.create_dc_join,n=a.metadata.create_google_join,p=U(a.m,P.g.Ea)!==!1,q=Tn(a.m),r={eventId:a.m.eventId,priorityId:a.m.priorityId},t=a.o[P.g.Mg],u={bn:m,dn:n,
Ul:hl(),Pn:p,On:q,om:dl(),lm:a.metadata.euid_mode_enabled,Un:r,Qm:t,m:a.m};jG(d,u)}Cv(a.m.eventId,a.eventName)};kG.prototype.add=function(a){a.metadata.euid_mode_enabled&&!YE?this.W(a):this.H(a)};kG.prototype.flush=function(){if(this.j.events.length){var a=qg(this.j,this.K++);iG(this.j.baseUrl,a.params,a.body,this.j.D);this.j=new lg;this.D>=0&&(G.clearTimeout(this.D),this.D=-1)}};kG.prototype.W=function(a){var b=this,c=gt(a);c?Jh(c,function(d){b.H(a,d.split("~").length===1?void 0:d)}):this.H(a)};
var hG=function(a,b,c){var d=a+"?"+b;c?Wc(d,c):Vc(d)},mG=ri('',500),nG=ri('',5E3),lG=!0;
var oG=function(a,b,c){c===void 0&&(c={});if(typeof b==="object")for(var d in b)oG(a+"."+d,b[d],c);else c[a]=b;return c},pG=function(a){for(var b={},c=oa(a),d=c.next();!d.done;d=c.next()){var e=d.value;b[e]=!!W(e)}return b},rG=function(a,b){var c=qG.filter(function(e){return!W(e)});if(c.length){var d=pG(c);ql(c,function(){for(var e=pG(c),f=[],g=oa(c),k=g.next();!k.done;k=g.next()){var m=k.value;!d[m]&&e[m]&&f.push(m);e[m]&&(d[m]=!0)}if(f.length){b.metadata.is_consent_update=!0;var n=f.map(function(p){return mi[p]}).join(".");
n&&dt(b,"gcut",n);a(b)}})}},qG=[P.g.R,P.g.P],sG=function(a){ht(a)&&Qk()&&dt(a,"rnd",Yq())},tG=function(a){},uG=function(a){if(T(67)&&ht(a)){et(a,P.g.Yb,!1)&&dt(a,"gse",1);U(a.m,P.g.ob,void 0,4)===!1&&dt(a,"ngs",1);dl()&&dt(a,"ga_rd",1);CD()||dt(a,"ngst",1);var b=hl();b&&dt(a,"etld",b)}},vG=function(a){if(ht(a)){var b=KF?fl():"";b&&dt(a,
"gcsub",b)}},wG=function(a){ht(a)&&Qk()&&U(a.m,P.g.fa)&&dt(a,"adr",1)},xG=function(a){if(ht(a)){var b=rr();b&&dt(a,"us_privacy",b);var c=Nn();c&&dt(a,"gdpr",c);var d=Mn();d&&dt(a,"gdpr_consent",d)}},yG=function(a){if(ht(a)){var b=et(a,"ccd_add_1p_data",!1)?1:0;dt(a,"ude",b);var c=function(e){var f=oG(P.g.Ga,e);z(f,function(g,k){a.o[g]=k})},d=U(a.m,P.g.Ga);d!==void 0?(c(d),a.o[P.g.md]="c"):c(a.metadata.user_data);a.metadata.user_data=void 0}},zG=function(a){if(ht(a)){var b=Ii;b&&dt(a,"tft",Number(b))}},
AG=function(a){ht(a)&&(a.metadata.speculative&&dt(a,"sp",1),a.metadata.is_syn&&dt(a,"syn",1),a.metadata.em_event&&(dt(a,"em_event",1),dt(a,"sp",1)))},BG=function(a){ht(a)&&(a.metadata.speculative=!1)},CG=function(a){T(99)&&ht(a)&&U(a.m,P.g.Ea)!==!1&&Vt("join-ad-interest-group")&&Bb(Cc.joinAdInterestGroup)&&dt(a,"flg",1)},DG=function(a){if(ht(a)&&a.eventName===P.g.Nc&&a.metadata.is_consent_update){var b=a.o[P.g.ng];b&&(dt(a,"gcut",b),dt(a,"syn",1))}},EG=function(a,b){if(ht(b)){var c=b.metadata.is_conversion;
(b.eventName==="page_view"||c)&&rG(a,b)}},FG=function(a){T(98)&&ht(a)&&U(a.m,P.g.Hd,!0)===!1&&(a.o[P.g.Hd]=0)};
var GG=function(a,b){var c;a:{var d=tF(a);if(d){if(rF(d,a)){c=d;break a}O(25);a.isAborted=!0}c=void 0}var e=c;return{clientId:lF(a,b),Ya:e}},HG=function(a,b,c,d,e){var f=U(a.m,P.g.pb);if(U(a.m,P.g.Lb)&&U(a.m,P.g.Zb))f?hF(a,f,1):(O(127),a.isAborted=!0);else{var g=f?1:8;a.metadata.is_new_to_site=!1;f||(f=iF(a),g=3);f||(f=b,g=5);if(!f){var k=W(P.g.U),m=eF();f=!m.from_cookie||k?m.vid:void 0;g=6}f?f=""+f:(f=Po(),g=7,a.metadata.is_first_visit=a.metadata.is_new_to_site=!0);hF(a,f,g)}var n=Math.floor(a.metadata.event_start_timestamp_ms/
1E3),p=void 0;a.metadata.is_new_to_site||(p=sF(a)||c);var q=Jb(U(a.m,P.g.kd,30));q=Math.min(475,q);q=Math.max(5,q);var r=Jb(U(a.m,P.g.vf,1E4)),t=mF(p);a.metadata.is_first_visit=!1;a.metadata.is_session_start=!1;a.metadata.join_timer_sec=0;t&&t.Hh&&(a.metadata.join_timer_sec=Math.max(0,t.Hh-Math.max(0,n-t.Re)));var u=!1;t||(u=a.metadata.is_first_visit=!0,t={sessionId:String(n),Lc:1,zd:!1,Re:n,Hc:!1,Ce:void 0});n>t.Re+q*60&&(u=!0,t.sessionId=String(n),t.Lc++,t.zd=!1,t.Ce=void 0);if(u)a.metadata.is_session_start=
!0,d.am(a);else if(d.Sl()>r||a.eventName===P.g.Vb)t.zd=!0;a.metadata.euid_mode_enabled?U(a.m,P.g.Ba)?t.Hc=!0:(t.Hc&&!T(11)&&(t.Ce=void 0),t.Hc=!1):t.Hc=!1;var v=t.Ce;if(a.metadata.euid_mode_enabled||ht(a)){var w=U(a.m,P.g.Rd),x=w?1:8;w||(w=v,x=4);w||(w=Oo(),x=7);var y=w.toString(),B=x,A=a.metadata.enhanced_client_id_source;if(A===void 0||B<=A)a.o[P.g.Rd]=y,a.metadata.enhanced_client_id_source=B}e?(a.copyToHitData(P.g.wb,t.sessionId),a.copyToHitData(P.g.ee,t.Lc),a.copyToHitData(P.g.de,t.zd?1:0)):(a.o[P.g.wb]=
t.sessionId,a.o[P.g.ee]=t.Lc,a.o[P.g.de]=t.zd?1:0);a.metadata[P.g.pf]=t.Hc?1:0};var IG=window,JG=document,KG=function(a){var b=IG._gaUserPrefs;if(b&&b.ioo&&b.ioo()||JG.documentElement.hasAttribute("data-google-analytics-opt-out")||a&&IG["ga-disable-"+a]===!0)return!0;try{var c=IG.external;if(c&&c._gaUserPrefs&&c._gaUserPrefs=="oo")return!0}catch(p){}for(var d=[],e=String(JG.cookie).split(";"),f=0;f<e.length;f++){var g=e[f].split("="),k=g[0].replace(/^\s*|\s*$/g,"");if(k&&k=="AMP_TOKEN"){var m=g.slice(1).join("=").replace(/^\s*|\s*$/g,"");m&&(m=decodeURIComponent(m));d.push(m)}}for(var n=
0;n<d.length;n++)if(d[n]=="$OPT_OUT")return!0;return JG.getElementById("__gaOptOutExtension")?!0:!1};
var MG=function(a){return!a||LG.test(a)||ei.hasOwnProperty(a)},NG=function(a){var b=P.g.Nb,c;c||(c=function(){});a.o[b]!==void 0&&(a.o[b]=c(a.o[b]))},OG=function(a){var b=a.indexOf("?"),c=b===-1?a:a.substring(0,b);try{c=decodeURIComponent(c)}catch(d){}return b===-1?c:""+c+a.substring(b)},PG=function(a){U(a.m,P.g.Xa)&&(W(P.g.U)||U(a.m,P.g.pb)||(a.o[P.g.rj]=!0));var b;var c;c=c===void 0?3:c;var d=G.location.href;if(d){var e=nj(d).search.replace("?",""),f=gj(e,"_gl",!1,!0)||"";b=f?ip(f,c)!==void 0:!1}else b=
!1;b&&ht(a)&&dt(a,"glv",1);if(a.eventName!==P.g.ba)return{};U(a.m,P.g.Xa)&&Bq(["aw","dc"]);Dq(["aw","dc"]);var g=yF(a),k=AF(a);return Object.keys(g).length?g:k},QG=function(a){var b=Yb(Ul(a.m,P.g.la,1),".");b&&(a.o[P.g.ub]=b);var c=Yb(Ul(a.m,P.g.la,2),".");c&&(a.o[P.g.rb]=c)},St={Jl:"",qn:Number("")},RG={},SG=(RG[P.g.Oc]=1,RG[P.g.Pc]=1,RG[P.g.Qc]=1,RG[P.g.Rc]=1,RG[P.g.Tc]=1,RG[P.g.Uc]=1,RG),LG=/^(_|ga_|google_|gtag\.|firebase_).*$/,TG=[vr,
QG,$r],UG=function(a){this.H=a;this.j=this.Ya=this.clientId=void 0;this.Ca=this.O=!1;this.xb=0;this.K=!1;this.W=new kG;this.D=new aF};ba=UG.prototype;ba.Om=function(a,b,c){var d=this,e=zl(this.H);if(e)if(c.eventMetadata.is_external_event&&a.charAt(0)==="_")c.onFailure();else{a!==P.g.ba&&a!==P.g.Ua&&MG(a)&&O(58);VG(c.j);var f=new jB(e,a,c);f.metadata.event_start_timestamp_ms=b;var g=[P.g.U];if(et(f,P.g.Yb,U(f.m,P.g.Yb))||ht(f))g.push(P.g.R),g.push(P.g.P);Tt(function(){sl(function(){d.Pm(f)},g)});this.Mm(a,
c,f)}else c.onFailure()};ba.Mm=function(a,b,c){var d=zl(this.H);if(T(61)&&a===P.g.ba&&et(c,"ga4_ads_linked",!1)){var e=function(){for(var k=oa(TG),m=k.next();!m.done;m=k.next()){var n=m.value;n(f);if(f.isAborted)break}f.metadata.speculative||f.isAborted||Qu(f)},f=new jB(d,a,b);f.metadata.hit_type="page_view";f.metadata.speculative=!0;f.metadata.is_server_side_destination=ht(c);var g=[P.g.R,P.g.P];sl(function(){e();W(g)||rl(function(k){var m,n;m=k.consentEventId;n=k.consentPriorityId;f.metadata.consent_updated=
!0;f.metadata.consent_event_id=m;f.metadata.consent_priority_id=n;e()},g)},g)}};ba.Pm=function(a){var b=this;this.j=a;try{WG(a);XG(a);YG(a);ZG(a);T(88)&&(a.isAborted=!0);Ar(a);var c={};EF(a,c);if(a.isAborted){a.m.onFailure();dF();return}var d=c.zl;c.Fl===0&&bF(25);d===0&&bF(26);$G(a);aH(a);this.Zk(a);this.D.on(a);bH(a);cH(a);dH(a);this.kk(PG(a));var e=a.eventName===P.g.ba;e&&(this.K=!0);eH(a);e&&!a.isAborted&&this.xb++>0&&bF(17);fH(a);HG(a,this.clientId,this.Ya,this.D,!this.Ca);gH(a);hH(a);iH(a);
jH(a);kH(a);lH(a);mH(a);BF(a);FF(a);sG(a);tG(a);uG(a);vG(a);wG(a);xG(a);zG(a);AG(a);CG(a);DG(a);FG(a);CF(a);nH(a);oH(a);pH(a);Cr(a);Br(a);qH(a);rH(a);$r(a);yG(a);BG(a);sH(a);!this.K&&a.metadata.em_event&&bF(18);cF(a);if(a.metadata.speculative||a.isAborted){a.m.onFailure();dF();return}this.kk(GG(a,this.clientId));this.Ca=!0;this.jn(a);tH(a);EG(function(f){b.Nj(f)},a);this.D.Wh();uH(a);if(a.isAborted){a.m.onFailure();dF();return}this.Nj(a);a.m.onSuccess()}catch(f){a.m.onFailure()}dF()};ba.Nj=function(a){this.W.add(a)};
ba.kk=function(a){var b=a.clientId,c=a.Ya;b&&c&&(this.clientId=b,this.Ya=c)};ba.flush=function(){this.W.flush()};ba.jn=function(a){var b=this;if(!this.O){var c=W(P.g.P),d=W(P.g.U);ql([P.g.P,P.g.U],function(){var e=W(P.g.P),f=W(P.g.U),g=!1,k={},m={};if(d!==f&&b.j&&b.Ya&&b.clientId){var n=b.clientId;if(f){var p=iF(b.j);if(p){b.clientId=p;var q=sF(b.j);q&&(b.Ya=oF(q,b.Ya,b.j))}else kF(b.clientId,b.j),gF(b.clientId,!0);rF(b.Ya,b.j);g=!0;k[P.g.Bg]=n}else b.Ya=void 0,b.clientId=void 0,G.gaGlobal={}}e&&
!c&&(g=!0,m.is_consent_update=!0,k[P.g.ng]=mi[P.g.P]);if(g){var r=Px(b.H,P.g.Nc,k);Rx(r,a.m.eventId,{eventMetadata:m})}d=f;c=e});this.O=!0}};ba.Zk=function(a){a.eventName!==P.g.Ua&&this.D.Yk(a)};var YG=function(a){var b=H.location.protocol;b!=="http:"&&b!=="https:"&&(O(29),a.isAborted=!0)},ZG=function(a){Cc&&Cc.loadPurpose==="preview"&&(O(30),a.isAborted=!0)},$G=function(a){var b={prefix:String(U(a.m,P.g.Qa,"")),path:String(U(a.m,P.g.Ib,"/")),flags:String(U(a.m,P.g.ab,"")),domain:String(U(a.m,P.g.Wa,
"auto")),Cb:Number(U(a.m,P.g.Pa,63072E3))};a.metadata.cookie_options=b},bH=function(a){if(a.metadata.is_merchant_center)a.metadata.euid_mode_enabled=!1;else if(et(a,"ccd_add_1p_data",!1)||et(a,"ccd_add_ec_stitching",!1))a.metadata.euid_mode_enabled=!0},cH=function(a){if(a.metadata.euid_mode_enabled&&et(a,"ccd_add_1p_data",!1)){var b=a.m.D[P.g.fe];if(dj(b)){var c=U(a.m,P.g.Ga);c===null?a.metadata.user_data_from_code=null:(b.enable_code&&fb(c)&&(a.metadata.user_data_from_code=c),fb(b.selectors)&&!a.metadata.user_data_from_manual&&
(a.metadata.user_data_from_manual=cj(b.selectors)))}}},dH=function(a){if(T(62)&&!T(61)&&et(a,"ga4_ads_linked",!1)&&a.eventName===P.g.ba){var b=U(a.m,P.g.ra)!==!1;if(b){var c=sr(a);c.Cb&&(c.Cb=Math.min(c.Cb,7776E3));tr({pd:b,xd:U(a.m,P.g.sa)||{},Dd:U(a.m,P.g.Xa),jc:c})}}},nH=function(a){if(!Ot(G))O(87);else if(Qt!==void 0){O(85);var b=Mt();b?U(a.m,P.g.be)&&!ht(a)||Ut(b,a):O(86)}},eH=function(a){a.eventName===P.g.ba&&(U(a.m,P.g.Ka,!0)?(a.m.j[P.g.la]&&(a.m.H[P.g.la]=a.m.j[P.g.la],a.m.j[P.g.la]=void 0,
a.o[P.g.la]=void 0),a.eventName=P.g.Vb):a.isAborted=!0)},aH=function(a){function b(c,d){ci[c]||d===void 0||(a.o[c]=d)}z(a.m.H,b);z(a.m.j,b)},gH=function(a){var b=Vl(a.m),c=function(d,e){SG[d]&&(a.o[d]=e)};fb(b[P.g.Sc])?z(b[P.g.Sc],function(d,e){c((P.g.Sc+"_"+d).toLowerCase(),e)}):z(b,c)},fH=QG,tH=function(a){if(T(83)&&W(P.g.U)){ht(a)&&(a.metadata.is_sgtm_service_worker=!0);a:{}}},qH=function(a){if(a.eventName===P.g.Ua){var b=U(a.m,P.g.tb);U(a.m,P.g.Jb)(a.o[b]||U(a.m,b));a.isAborted=!0}},hH=function(a){if(!U(a.m,P.g.Zb)||!U(a.m,P.g.Lb)){var b=a.copyToHitData,c=P.g.wa,d="",e=H.location;if(e){var f=e.pathname||"";f.charAt(0)!=="/"&&(f="/"+f);var g=e.search||"";if(g&&g[0]==="?")for(var k=g.substring(1).split("&"),m=0;m<k.length;++m){var n=k[m].split("=");n&&n.length===2&&n[0]==="wbraid"&&
(g=g.replace(/([?&])wbraid=[^&]+/,"$1wbraid="+$b(n[1])))}d=e.protocol+"//"+e.hostname+f+g}b.call(a,c,d,OG);var p=a.copyToHitData,q=P.g.Fa,r;a:{var t=xo("_opt_expid",void 0,void 0,P.g.U)[0];if(t){var u=decodeURIComponent(t).split("$");if(u.length===3){r=u[2];break a}}if(vi.ga4_referrer_override!==void 0)r=vi.ga4_referrer_override;else{var v=Wi("gtm.gtagReferrer."+a.target.ia),w=H.referrer;r=v?""+v:w}}p.call(a,q,r||void 0,OG);a.copyToHitData(P.g.cb,H.title);a.copyToHitData(P.g.Ra,(Cc.language||"").toLowerCase());
var x=is();a.copyToHitData(P.g.Nb,x.width+"x"+x.height);T(95)&&a.copyToHitData(P.g.gd,void 0,OG);T(65)&&ar()&&a.copyToHitData(P.g.ed,"1")}},jH=function(a){a.metadata.create_dc_join=!1;a.metadata.create_google_join=!1;if(!(Qi()||T(6)&&ht(a)||a.metadata.is_merchant_center||U(a.m,P.g.ob)===!1)&&CD()&&W(P.g.R)){var b=it(a);(a.metadata.is_session_start||U(a.m,P.g.Bg))&&(a.metadata.create_dc_join=!!b);var c=a.metadata.join_timer_sec;b&&(c||0)===0&&(a.metadata.join_timer_sec=60,a.metadata.create_google_join=
!0)}},mH=function(a){a.copyToHitData(P.g.yf);for(var b=U(a.m,P.g.rf)||[],c=0;c<b.length;c++){var d=b[c];if(d.rule_result){a.copyToHitData(P.g.yf,d.traffic_type);bF(3);break}}},uH=function(a){a.copyToHitData(P.g.Cg);U(a.m,P.g.be)&&(a.o[P.g.be]=!0,ht(a)||NG(a))},rH=function(a){a.copyToHitData(P.g.Ba);a.copyToHitData(P.g.eb)},iH=function(a){et(a,"google_ng")&&!dl()?a.copyToHitData(P.g.Bc,1):Dr(a)},pH=function(a){if(U(a.m,P.g.Ea)!==!1&&Tn(a.m)){var b=it(a),c=U(a.m,P.g.ob);b&&c!==!1&&CD()&&W(P.g.R)&&Mk(P.g.P)&&
Ok(["ads"]).ads&&Wt()&&(a.o[P.g.Mg]=!0)}},sH=function(a){var b=U(a.m,P.g.Lb);b&&bF(12);a.metadata.em_event&&bF(14);var c=Zj(ak());(b||lk(c)||c&&c.parent&&c.context&&c.context.source===5)&&bF(19)},WG=function(a){if(KG(a.target.ia))O(28),a.isAborted=!0;else if(T(94)){var b=Yj();if(b&&Array.isArray(b.destinations))for(var c=0;c<b.destinations.length;c++)if(KG(b.destinations[c])){O(125);a.isAborted=!0;break}}},oH=function(a){Vt("attribution-reporting")&&(a.o[P.g.Xb]="1")},XG=function(a){if(St.Jl.replace(/\s+/g,
"").split(",").indexOf(a.eventName)>=0)a.isAborted=!0;else{var b=ft(a);b&&b.blacklisted&&(a.isAborted=!0)}},kH=function(a){var b=function(c){return!!c&&c.conversion};a.metadata.is_conversion=b(ft(a));a.metadata.is_first_visit&&(a.metadata.is_first_visit_conversion=b(ft(a,"first_visit")));a.metadata.is_session_start&&(a.metadata.is_session_start_conversion=b(ft(a,"session_start")))},lH=function(a){gi.hasOwnProperty(a.eventName)&&(a.metadata.is_ecommerce=!0,a.copyToHitData(P.g.da),a.copyToHitData(P.g.za))};
function VG(a){z(a,function(c){c.charAt(0)==="_"&&delete a[c]});var b=a[P.g.eb]||{};z(b,function(c){c.charAt(0)==="_"&&delete b[c]})}var wH=function(a){if(!vH(a)){var b=!1,c=function(){!b&&vH(a)&&(b=!0,Qc(H,"visibilitychange",c),T(4)&&Qc(H,"prerenderingchange",c),O(55))};Pc(H,"visibilitychange",c);T(4)&&Pc(H,"prerenderingchange",c);O(54)}},vH=function(a){if(T(4)&&"prerendering"in H?H.prerendering:H.visibilityState==="prerender")return!1;a();return!0};var yH=function(a,b){wH(function(){var c=zl(a);if(c){var d=xH(c,b);Am(a,d)}});};function xH(a,b){var c=function(){};var d=new UG(a.id),e=a.prefix==="MC";c=function(f,g,k,m){e&&(m.eventMetadata.is_merchant_center=!0);d.Om(g,k,m)};Pj||zH(a,d,b);return c}
function zH(a,b,c){var d=b.D,e={},f={eventId:c,eventMetadata:(e.batch_on_navigation=!0,e)};T(46)&&(f.deferrable=!0);d.Rm(function(){YE=!0;Bm.flush();d.Rf()>=1E3&&Cc.sendBeacon&&Cm(P.g.Nc,{},a.id,f);b.flush();d.lk(function(){YE=!1;d.lk()})});};var AH=xH;function CH(a,b,c){var d=this;}CH.J="internal.gtagConfig";function DH(){var a={};a={EventNames:{APP_REMOVE:P.g.si,APP_STORE_REFUND:P.g.ui,APP_STORE_SUBSCRIPTION_CANCEL:P.g.vi,APP_STORE_SUBSCRIPTION_CONVERT:P.g.wi,APP_STORE_SUBSCRIPTION_RENEW:P.g.xi,ECOMMERCE_ADD_PAYMENT:P.g.hg,ECOMMERCE_ADD_SHIPPING:P.g.ig,ECOMMERCE_CART_ADD:P.g.oc,ECOMMERCE_CART_REMOVE:P.g.qc,ECOMMERCE_CART_VIEW:P.g.jg,ECOMMERCE_CHECKOUT:P.g.Ub,ECOMMERCE_ITEM_LIST_CLICK:P.g.rc,ECOMMERCE_ITEM_LIST_VIEW:P.g.kb,ECOMMERCE_PROMOTION_CLICK:P.g.Gb,
ECOMMERCE_PROMOTION_VIEW:P.g.lb,ECOMMERCE_PURCHASE:P.g.Ja,ECOMMERCE_REFUND:P.g.sc,ECOMMERCE_VIEW_ITEM:P.g.Oa,ECOMMERCE_WISHLIST_ADD:P.g.kg,FIRST_OPEN:P.g.yi,FIRST_VISIT:P.g.zi,GTAG_CONFIG:P.g.ba,GTAG_GET:P.g.Ua,IN_APP_PURCHASE:P.g.Ai,PAGE_VIEW:P.g.Vb,SESSION_START:P.g.Bi,USER_ENGAGEMENT:P.g.Nc},EventParameters:{ACCEPT_INCOMING:P.g.Cc,ADS_DATA_REDACTION:P.g.fa,AFFILIATION:P.g.qg,ALLOW_AD_PERSONALIZATION_SIGNALS:P.g.ka,ALLOW_CUSTOM_SCRIPTS:P.g.ef,ALLOW_DISPLAY_FEATURES:P.g.ff,ALLOW_ENHANCED_CONVERSIONS:P.g.Id,
ALLOW_GOOGLE_SIGNALS:P.g.ob,ALLOW_INTEREST_GROUPS:P.g.Ea,AUID:P.g.Hb,AUTO_DETECTION_ENABLED:P.g.Hi,AW_BASKET_ITEMS:P.g.da,AW_BASKET_TYPE:P.g.mg,AW_FEED_COUNTRY:P.g.Kd,AW_FEED_LANGUAGE:P.g.Ld,AW_MERCHANT_ID:P.g.Md,AW_REMARKETING:P.g.Wb,AW_REMARKETING_ONLY:P.g.hf,CAMPAIGN:P.g.Sc,CAMPAIGN_CONTENT:P.g.Oc,CAMPAIGN_ID:P.g.Pc,CAMPAIGN_MEDIUM:P.g.Qc,CAMPAIGN_NAME:P.g.Rc,CAMPAIGN_SOURCE:P.g.Tc,CAMPAIGN_TERM:P.g.Uc,CHECKOUT_OPTION:P.g.Pd,CHECKOUT_STEP:P.g.kf,CLIENT_ID:P.g.pb,CONTENT_GROUP:P.g.Ji,CONTENT_TYPE:P.g.Ki,
CONVERSION_API:P.g.Xb,CONVERSION_COOKIE_PREFIX:P.g.Za,CONVERSION_ID:P.g.Vc,CONVERSION_LABEL:P.g.qb,CONVERSION_LINKER:P.g.ra,COOKIE_DOMAIN:P.g.Wa,COOKIE_EXPIRES:P.g.Pa,COOKIE_FLAGS:P.g.ab,COOKIE_NAME:P.g.uc,COOKIE_PATH:P.g.Ib,COOKIE_PREFIX:P.g.Qa,COOKIE_UPDATE:P.g.vc,COUNTRY:P.g.wc,COUPON:P.g.rg,CURRENCY:P.g.za,CUSTOMER_LIFETIME_VALUE:P.g.Nd,CUSTOM_MAP:P.g.Wc,DC_CUSTOM_PARAMS:P.g.Xc,DC_NATURAL_SEARCH:P.g.Oi,DEBUG_MODE:P.g.Mi,DECORATE_FORMS:P.g.vb,DELIVERY_POSTAL_CODE:P.g.ld,DEVELOPER_ID:P.g.la,DISABLE_MERCHANT_REPORTED_PURCHASES:P.g.Ni,
DISCOUNT:P.g.Jd,DYNAMIC_EVENT_SETTINGS:P.g.pg,ENGAGEMENT_TIME_MSEC:P.g.Qd,ENHANCED_CLIENT_ID:P.g.Rd,ENHANCED_CONVERSIONS:P.g.Sd,ENHANCED_CONVERSIONS_AUTOMATIC_SETTINGS:P.g.sg,ESTIMATED_DELIVERY_DATE:P.g.Td,EUID_LOGGED_IN_STATE:P.g.pf,EVENT:P.g.xc,EVENT_CALLBACK:P.g.bd,EVENT_DEVELOPER_ID_STRING:P.g.rb,EVENT_SETTINGS:P.g.Ud,EVENT_TIMEOUT:P.g.Vd,EXPERIMENTS:P.g.Qi,FIREBASE_ID:P.g.qf,FIRST_PARTY_COLLECTION:P.g.yc,FIRST_PARTY_DUAL_TAGGING_ID:P.g.Wd,FIRST_PARTY_URL:P.g.sb,FLEDGE:P.g.ug,FLIGHT_ERROR_CODE:P.g.vg,
FLIGHT_ERROR_MESSAGE:P.g.wg,GAC_GCLID:P.g.Xd,GAC_WBRAID:P.g.zc,GAC_WBRAID_MULTIPLE_CONVERSIONS:P.g.zg,GA_RESTRICT_DOMAIN:P.g.Ag,GA_TEMP_CLIENT_ID:P.g.Bg,GCLID:P.g.Va,GDPR_APPLIES:P.g.Ac,GEO_GRANULARITY:P.g.Cg,GLOBAL_DEVELOPER_ID_STRING:P.g.ub,GOOGLE_NG:P.g.Bc,GOOGLE_SIGNALS:P.g.Yb,GOOGLE_TLD:P.g.Dg,GROUPS:P.g.Yd,GSA_EXPERIMENT_ID:P.g.Eg,IFRAME_STATE:P.g.Kb,IGNORE_REFERRER:P.g.dd,INTERNAL_TRAFFIC_RESULTS:P.g.rf,IS_LEGACY_LOADED:P.g.Lb,IS_PASSTHROUGH:P.g.Zd,ITEM_LIST_NAME:P.g.Yc,LANGUAGE:P.g.Ra,LEGACY_DEVELOPER_ID_STRING:P.g.ae,
LINKER:P.g.sa,LINKER_DOMAINS:P.g.X,LINKER_URL_POSITION:P.g.Mb,LIST_NAME:P.g.lf,METHOD:P.g.Fg,NEW_CUSTOMER:P.g.fd,NON_INTERACTION:P.g.Gg,OPTIMIZE_ID:P.g.Zi,PAGE_HOSTNAME:P.g.aj,PAGE_LOCATION:P.g.wa,PAGE_PATH:P.g.gd,PAGE_REFERRER:P.g.Fa,PAGE_TITLE:P.g.cb,PASSENGERS:P.g.Hg,PHONE_CONVERSION_CALLBACK:P.g.Ig,PHONE_CONVERSION_COUNTRY_CODE:P.g.bj,PHONE_CONVERSION_CSS_CLASS:P.g.Jg,PHONE_CONVERSION_IDS:P.g.cj,PHONE_CONVERSION_NUMBER:P.g.Kg,PHONE_CONVERSION_OPTIONS:P.g.Lg,PROMOTIONS:P.g.Pi,QUANTITY:P.g.hd,REDACT_DEVICE_INFO:P.g.be,
REFERRAL_EXCLUSION_DEFINITION:P.g.tf,RESTRICTED_DATA_PROCESSING:P.g.ac,RETOKEN:P.g.dj,SCREEN_NAME:P.g.uf,SCREEN_RESOLUTION:P.g.Nb,SEARCH_TERM:P.g.ej,SEND_PAGE_VIEW:P.g.Ka,SEND_TO:P.g.bc,SESSION_DURATION:P.g.kd,SESSION_ENGAGED:P.g.de,SESSION_ENGAGED_TIME:P.g.vf,SESSION_ID:P.g.wb,SESSION_NUMBER:P.g.ee,SHIPPING:P.g.Zc,TAX:P.g.nf,TC_PRIVACY_STRING:P.g.Dc,TEMPORARY_CLIENT_ID:P.g.Uk,TOPMOST_URL:P.g.xf,TRACKING_ID:P.g.fj,TRAFFIC_TYPE:P.g.yf,TRANSACTION_ID:P.g.Aa,TRANSPORT_URL:P.g.Ob,TRIP_TYPE:P.g.Ng,UPDATE:P.g.fc,
URL_PASSTHROUGH:P.g.Xa,USER_DATA:P.g.Ga,USER_DATA_AUTO_LATENCY:P.g.Og,USER_DATA_AUTO_META:P.g.Pg,USER_DATA_AUTO_MULTI:P.g.Qg,USER_DATA_AUTO_SELECTORS:P.g.Rg,USER_DATA_AUTO_STATUS:P.g.Sg,USER_DATA_MODE:P.g.md,USER_DATA_SETTINGS:P.g.fe,USER_ID:P.g.Ba,USER_PROPERTIES:P.g.eb,US_PRIVACY_STRING:P.g.he,VALUE:P.g.na,VALUE_CALLBACK:P.g.Jb,VALUE_KEY:P.g.tb,WBRAID:P.g.nb,WBRAID_MULTIPLE_CONVERSIONS:P.g.Tg},Consent:{AD_STORAGE:P.g.R,ANALYTICS_STORAGE:P.g.U,CONSENT_UPDATED:P.g.Tb,REGION:P.g.Fb,WAIT_FOR_UPDATE:P.g.cf}};
return a};
function FH(a,b){}FH.T="gtagSet";function GH(a,b){}GH.T="injectHiddenIframe";var HH=vz();
function IH(a,b,c,d,e){}IH.J="internal.injectHtml";var MH={};
function OH(a,b,c,d){}var PH={dl:1,id:1},QH={};
function RH(a,b,c,d){}OH.T="injectScript";RH.J="internal.injectScript";function SH(a){var b=!0;return b}SH.T="isConsentGranted";function TH(){return el()}TH.J="internal.isDmaRegion";function UH(a){var b=!1;return b}UH.J="internal.isEntityInfrastructure";function VH(){var a=jh(function(b){Jz(this).log("error",b)});a.T="JSON";return a};function WH(a){var b=void 0;return qd(b)}WH.J="internal.legacyParseUrl";function XH(){return!1}
var YH={getItem:function(a){var b=null;return b},setItem:function(a,b){return!1},removeItem:function(a){}};function ZH(){}ZH.T="logToConsole";function $H(a,b){}$H.J="internal.mergeRemoteConfig";function aI(a,b,c){c=c===void 0?!0:c;var d=[];return qd(d)}aI.J="internal.parseCookieValuesFromString";function bI(a){var b=void 0;if(typeof a!=="string")return;a&&Tb(a,"//")&&(a=H.location.protocol+a);if(typeof URL==="function"){var c;a:{var d;try{d=new URL(a)}catch(w){c=void 0;break a}for(var e={},f=Array.from(d.searchParams),g=0;g<f.length;g++){var k=f[g][0],m=f[g][1];e.hasOwnProperty(k)?typeof e[k]==="string"?e[k]=[e[k],m]:e[k].push(m):e[k]=m}c=qd({href:d.href,origin:d.origin,protocol:d.protocol,username:d.username,password:d.password,host:d.host,
hostname:d.hostname,port:d.port,pathname:d.pathname,search:d.search,searchParams:e,hash:d.hash})}return c}var n;try{n=nj(a)}catch(w){return}if(!n.protocol||!n.host)return;var p={};if(n.search)for(var q=n.search.replace("?","").split("&"),r=0;r<q.length;r++){var t=q[r].split("="),u=t[0],v=decodeURIComponent(t.splice(1).join("=")).replace(/\+/g," ");p.hasOwnProperty(u)?typeof p[u]==="string"?p[u]=[p[u],v]:p[u].push(v):p[u]=v}n.searchParams=p;n.origin=n.protocol+"//"+n.host;n.username="";n.password=
"";b=qd(n);return b}bI.T="parseUrl";function cI(a){K(this.getName(),["preHit:!PixieMap"],arguments);var b=J(a,this.F,1).Vj(),c={};h(b.m.j,c);h(b.o,c);var d={};h(b.metadata,d);d.syn_or_mod=!0;var e={eventMetadata:d},f=b.m.eventId,g=Px(b.target.ia,b.eventName,c);Rx(g,f,e);}cI.J="internal.processAsNewEvent";function dI(a,b,c){var d;return d}dI.J="internal.pushToDataLayer";function eI(a){var b=!1;return b}eI.T="queryPermission";function fI(){var a="";return a}fI.T="readCharacterSet";function gI(){return ui.jb}gI.J="internal.readDataLayerName";function hI(){var a="";return a}hI.T="readTitle";function iI(a,b){var c=this;K(this.getName(),["destinationId:!string","callback:!Fn"],arguments),as(a,function(d){b.invoke(c.F,qd(d,c.F,1))});}iI.J="internal.registerCcdCallback";function jI(a){return!0}
jI.J="internal.registerDestination";var kI=["config","event","get","set"];function lI(a,b,c){}lI.J="internal.registerGtagCommandListener";function mI(a,b){var c=!1;return c}mI.J="internal.removeDataLayerEventListener";function nI(a,b){}
nI.J="internal.removeFormData";function oI(){}oI.T="resetDataLayer";function pI(a,b,c,d){K(this.getName(),["destinationIds:!*","eventName:!*","eventParameters:?PixieMap","messageContext:?PixieMap"],arguments);var e=c?J(c):{},f=J(a);Array.isArray(f)||(f=[f]);b=String(b);var g=d?J(d):{},k=Jz(this);g.originatingEntity=zA(k);var m=f;for(var n=0;n<m.length;n++){var p=m[n];if(typeof p==="string"){var q=
{};h(e,q);var r={};h(g,r);var t=Px(p,b,q);Rx(t,g.eventId||k.eventId,r)}}}pI.J="internal.sendGtagEvent";function qI(a,b,c){}qI.T="sendPixel";function rI(a,b){}rI.J="internal.setAnchorHref";function sI(a){}sI.J="internal.setContainerConsentDefaults";function tI(a,b,c,d){var e=this;d=d===void 0?!0:d;var f=!1;return f}tI.T="setCookie";function uI(a){}uI.J="internal.setCorePlatformServices";function vI(a,b){}vI.J="internal.setDataLayerValue";function wI(a){}wI.T="setDefaultConsentState";function xI(a,b){}xI.J="internal.setDelegatedConsentType";function yI(a,b){}yI.J="internal.setFormAction";function zI(a,b,c){K(this.getName(),["key:!string","value:?*","overrideExisting:?boolean"],arguments);if(!qo(a))throw Error("setInCrossContainerData requires valid CrossContainerSchema key.");(c||to(a)===void 0)&&so(a,J(b,this.F,1));}zI.J="internal.setInCrossContainerData";function AI(a,b,c){return!1}AI.T="setInWindow";function BI(a,b,c){K(this.getName(),["targetId:!string","name:!string","value:!*"],arguments);var d=hs(a)||{};d[b]=J(c,this.F);var e=a;fs||gs();es[e]=d;}BI.J="internal.setProductSettingsParameter";function CI(a,b,c){K(this.getName(),["targetId:!string","name:!string","value:!*"],arguments);for(var d=b.split("."),e=Em(a),f=0;f<d.length-1;f++){if(e[d[f]]===void 0)e[d[f]]={};else if(!fb(e[d[f]]))throw Error("setRemoteConfigParameter failed, path contains a non-object type: "+d[f]);e=e[d[f]]}e[d[f]]=J(c,this.F,1);}CI.J="internal.setRemoteConfigParameter";function DI(a,b,c,d){var e=this;}DI.T="sha256";function EI(a,b,c){}
EI.J="internal.sortRemoteConfigParameters";function FI(a,b){var c=void 0;return c}FI.J="internal.subscribeToCrossContainerData";var GI={},HI={};GI.getItem=function(a){var b=null;N(this,"access_template_storage");var c=Jz(this).fb();HI[c]&&(b=HI[c].hasOwnProperty("gtm."+a)?HI[c]["gtm."+a]:null);return b};GI.setItem=function(a,b){N(this,"access_template_storage");var c=Jz(this).fb();HI[c]=HI[c]||{};HI[c]["gtm."+a]=b;};
GI.removeItem=function(a){N(this,"access_template_storage");var b=Jz(this).fb();if(!HI[b]||!HI[b].hasOwnProperty("gtm."+a))return;delete HI[b]["gtm."+a];};GI.clear=function(){N(this,"access_template_storage"),delete HI[Jz(this).fb()];};GI.T="templateStorage";function II(a,b){var c=!1;K(this.getName(),["regex:!OpaqueValue","testString:!string"],arguments);if(!(a.getValue()instanceof RegExp))return!1;c=a.getValue().test(b);return c}II.J="internal.testRegex";function JI(a){var b;return b};function KI(a){var b;return b}KI.J="internal.unsiloId";function LI(a,b){var c;return c}LI.J="internal.unsubscribeFromCrossContainerData";function MI(a){}MI.T="updateConsentState";var NI;function OI(a,b,c){NI=NI||new uh;NI.add(a,b,c)}function PI(a,b){var c=NI=NI||new uh;if(c.D.hasOwnProperty(a))throw Error("Attempting to add a private function which already exists: "+a+".");if(c.j.hasOwnProperty(a))throw Error("Attempting to add a private function with an existing API name: "+a+".");c.D[a]=Bb(b)?Rg(a,b):Sg(a,b)}
function QI(){return function(a){var b;var c=NI;if(c.j.hasOwnProperty(a))b=c.get(a,this);else{var d;if(d=c.D.hasOwnProperty(a)){var e=!1,f=this.F.j;if(f){var g=f.fb();if(g){g.indexOf("__cvt_")!==0&&(e=!0);}}else e=!0;d=e}if(d){var k=c.D.hasOwnProperty(a)?c.D[a]:void 0;b=k}else throw Error(a+" is not a valid API name.");}return b}};var RI=function(){var a=function(c){return PI(c.J,c)},b=function(c){return OI(c.T,c)};b(Dz);b(Kz);b(YA);b($A);b(aB);b(fB);b(hB);b(lB);b(nB);b(BE);b(CE);b(RE);b(SE);b(TE);b(WE);b(FH);b(GH);b(OH);b(SH);b(ZH);b(bI);b(eI);b(fI);b(hI);b(qI);b(tI);b(wI);b(AI);b(DI);b(GI);b(MI);b(VH());OI("Math",Wg());OI("Object",sh);OI("TestHelper",wh());OI("assertApi",Tg);OI("assertThat",Ug);OI("decodeUri",Yg);OI("decodeUriComponent",Zg);OI("encodeUri",$g);OI("encodeUriComponent",ah);OI("fail",fh);OI("generateRandom",
gh);OI("getTimestamp",hh);OI("getTimestampMillis",hh);OI("getType",ih);OI("makeInteger",kh);OI("makeNumber",lh);OI("makeString",mh);OI("makeTableMap",nh);OI("mock",qh);OI("fromBase64",zE,!("atob"in G));OI("localStorage",YH,!XH());OI("toBase64",JI,!("btoa"in G));a(Gz);a(aA);a(mA);a(tA);a(yA);a(NA);a(WA);a(ZA);a(bB);a(cB);a(dB);a(eB);a(gB);a(iB);a(kB);a(mB);a(oB);a(qB);a(rB);a(sB);a(tB);a(uB);a(yB);a(GB);a(HB);a(SB);a(XB);a(bC);a(kC);a(pC);a(CC);a(EC);a(SC);a(TC);a(VC);a(xE);a(yE);a(DE);a(EE);a(FE);
a(GE);a(HE);a(IE);a(JE);a(KE);a(LE);a(ME);a(OE);a(PE);a(QE);a(UE);a(VE);a(CH);a(IH);a(RH);a(TH);a(UH);a(WH);a(LA);a($H);a(aI);a(cI);a(dI);a(gI);a(iI);a(jI);a(lI);a(mI);a(nI);a(pI);a(rI);a(sI);a(uI);a(vI);a(xI);a(yI);a(zI);a(BI);a(CI);a(EI);a(FI);a(II);a(KI);a(LI);PI("internal.CrossContainerSchema",pB());PI("internal.GtagSchema",DH());OI("mockObject",rh);return QI()};var Bz;function SI(){Bz.j.j.H=function(a,b,c){vi.SANDBOXED_JS_SEMAPHORE=vi.SANDBOXED_JS_SEMAPHORE||0;vi.SANDBOXED_JS_SEMAPHORE++;try{return a.apply(b,c)}finally{vi.SANDBOXED_JS_SEMAPHORE--}}}function TI(a){a&&z(a,function(b,c){for(var d=0;d<c.length;d++){var e=c[d].replace(/^_*/,"");Li[e]=Li[e]||[];Li[e].push(b)}})};var UI=encodeURI,Y=encodeURIComponent,VI=Array.isArray,WI=function(a,b,c){Oc(a,b,c)},XI=function(a,b){if(!a)return!1;var c=hj(nj(a),"host");if(!c)return!1;for(var d=0;b&&d<b.length;d++){var e=b[d]&&b[d].toLowerCase();if(e){var f=c.length-e.length;f>0&&e.charAt(0)!="."&&(f--,e="."+e);if(f>=0&&c.indexOf(e,f)==f)return!0}}return!1},YI=function(a,b,c){for(var d={},e=!1,f=0;a&&f<a.length;f++)a[f]&&
a[f].hasOwnProperty(b)&&a[f].hasOwnProperty(c)&&(d[a[f][b]]=a[f][c],e=!0);return e?d:null};var gJ=G.clearTimeout,hJ=G.setTimeout,iJ=function(a,b,c){if(lo()){b&&I(b)}else return Lc(a,b,c)},jJ=function(){return G.location.href},kJ=function(a,b){return Wi(a,b||2)},lJ=function(a,b){G[a]=b},mJ=function(a,b,c){b&&(G[a]===void 0||c&&!G[a])&&(G[a]=b);return G[a]},nJ=function(a,b){if(lo()){b&&I(b)}else Nc(a,b)};
var oJ={};var Z={securityGroups:{}};

Z.securityGroups.access_template_storage=["google"],Z.__access_template_storage=function(){return{assert:function(){},N:function(){return{}}}},Z.__access_template_storage.C="access_template_storage",Z.__access_template_storage.isVendorTemplate=!0,Z.__access_template_storage.priorityOverride=0,Z.__access_template_storage.isInfrastructure=!1,Z.__access_template_storage.runInSiloedMode=!1;
Z.securityGroups.v=["google"],Z.__v=function(a){var b=a.vtp_name;if(!b||!b.replace)return!1;var c=kJ(b.replace(/\\\./g,"."),a.vtp_dataLayerVersion||1);return c!==void 0?c:a.vtp_defaultValue},Z.__v.C="v",Z.__v.isVendorTemplate=!0,Z.__v.priorityOverride=0,Z.__v.isInfrastructure=!0,Z.__v.runInSiloedMode=!1;

Z.securityGroups.read_event_data=["google"],function(){function a(b,c){return{key:c}}(function(b){Z.__read_event_data=b;Z.__read_event_data.C="read_event_data";Z.__read_event_data.isVendorTemplate=!0;Z.__read_event_data.priorityOverride=0;Z.__read_event_data.isInfrastructure=!1;Z.__read_event_data.runInSiloedMode=!1})(function(b){var c=b.vtp_eventDataAccess,d=b.vtp_keyPatterns||[],e=b.vtp_createPermissionError;return{assert:function(f,g){if(g!=null&&!l(g))throw e(f,{key:g},"Key must be a string.");
if(c!=="any"){try{if(c==="specific"&&g!=null&&vg(g,d))return}catch(k){throw e(f,{key:g},"Invalid key filter.");}throw e(f,{key:g},"Prohibited read from event data.");}},N:a}})}();
Z.securityGroups.process_dom_events=["google"],function(){function a(b,c,d){return{targetType:c,eventName:d}}(function(b){Z.__process_dom_events=b;Z.__process_dom_events.C="process_dom_events";Z.__process_dom_events.isVendorTemplate=!0;Z.__process_dom_events.priorityOverride=0;Z.__process_dom_events.isInfrastructure=!1;Z.__process_dom_events.runInSiloedMode=!1})(function(b){for(var c=b.vtp_targets||[],d=b.vtp_createPermissionError,e={},f=0;f<c.length;f++){var g=c[f];e[g.targetType]=e[g.targetType]||
[];e[g.targetType].push(g.eventName)}return{assert:function(k,m,n){if(!e[m])throw d(k,{},"Prohibited event target "+m+".");if(e[m].indexOf(n)===-1)throw d(k,{},"Prohibited listener registration for DOM event "+n+".");},N:a}})}();
Z.securityGroups.detect_youtube_activity_events=["google"],function(){function a(b,c){return{options:{fixMissingApi:!!c.fixMissingApi}}}(function(b){Z.__detect_youtube_activity_events=b;Z.__detect_youtube_activity_events.C="detect_youtube_activity_events";Z.__detect_youtube_activity_events.isVendorTemplate=!0;Z.__detect_youtube_activity_events.priorityOverride=0;Z.__detect_youtube_activity_events.isInfrastructure=!1;Z.__detect_youtube_activity_events.runInSiloedMode=!1})(function(b){var c=!!b.vtp_allowFixMissingJavaScriptApi,
d=b.vtp_createPermissionError;return{assert:function(e,f){if(!c&&f&&f.fixMissingApi)throw d(e,{},"Prohibited option: fixMissingApi.");},N:a}})}();


Z.securityGroups.detect_history_change_events=["google"],function(){function a(){return{}}(function(b){Z.__detect_history_change_events=b;Z.__detect_history_change_events.C="detect_history_change_events";Z.__detect_history_change_events.isVendorTemplate=!0;Z.__detect_history_change_events.priorityOverride=0;Z.__detect_history_change_events.isInfrastructure=!1;Z.__detect_history_change_events.runInSiloedMode=!1})(function(){return{assert:function(){},N:a}})}();



Z.securityGroups.detect_link_click_events=["google"],function(){function a(b,c){return{options:c}}(function(b){Z.__detect_link_click_events=b;Z.__detect_link_click_events.C="detect_link_click_events";Z.__detect_link_click_events.isVendorTemplate=!0;Z.__detect_link_click_events.priorityOverride=0;Z.__detect_link_click_events.isInfrastructure=!1;Z.__detect_link_click_events.runInSiloedMode=!1})(function(b){var c=b.vtp_allowWaitForTags,d=b.vtp_createPermissionError;return{assert:function(e,f){if(!c&&
f&&f.waitForTags)throw d(e,{},"Prohibited option waitForTags.");},N:a}})}();Z.securityGroups.read_container_data=["google"],Z.__read_container_data=function(){return{assert:function(){},N:function(){return{}}}},Z.__read_container_data.C="read_container_data",Z.__read_container_data.isVendorTemplate=!0,Z.__read_container_data.priorityOverride=0,Z.__read_container_data.isInfrastructure=!1,Z.__read_container_data.runInSiloedMode=!1;

Z.securityGroups.listen_data_layer=["google"],function(){function a(b,c){return{eventName:c}}(function(b){Z.__listen_data_layer=b;Z.__listen_data_layer.C="listen_data_layer";Z.__listen_data_layer.isVendorTemplate=!0;Z.__listen_data_layer.priorityOverride=0;Z.__listen_data_layer.isInfrastructure=!1;Z.__listen_data_layer.runInSiloedMode=!1})(function(b){var c=b.vtp_accessType,d=b.vtp_allowedEvents||[],e=b.vtp_createPermissionError;return{assert:function(f,g){if(!l(g))throw e(f,{eventName:g},"Event name must be a string.");
if(!(c==="any"||c==="specific"&&d.indexOf(g)>=0))throw e(f,{eventName:g},"Prohibited listen on data layer event.");},N:a}})}();
Z.securityGroups.detect_user_provided_data=["google"],function(){function a(b,c){return{dataSource:c}}(function(b){Z.__detect_user_provided_data=b;Z.__detect_user_provided_data.C="detect_user_provided_data";Z.__detect_user_provided_data.isVendorTemplate=!0;Z.__detect_user_provided_data.priorityOverride=0;Z.__detect_user_provided_data.isInfrastructure=!1;Z.__detect_user_provided_data.runInSiloedMode=!1})(function(b){var c=b.vtp_createPermissionError;return{assert:function(d,e){if(e!=="auto"&&e!=="manual"&&
e!=="code")throw c(d,{},"Unknown user provided data source.");if(b.vtp_limitDataSources)if(e!=="auto"||b.vtp_allowAutoDataSources){if(e==="manual"&&!b.vtp_allowManualDataSources)throw c(d,{},"Detection of user provided data via manually specified CSS selectors is not allowed.");if(e==="code"&&!b.vtp_allowCodeDataSources)throw c(d,{},"Detection of user provided data from an in-page variable is not allowed.");}else throw c(d,{},"Automatic detection of user provided data is not allowed.");},N:a}})}();



Z.securityGroups.get_url=["google"],function(){function a(b,c,d){return{component:c,queryKey:d}}(function(b){Z.__get_url=b;Z.__get_url.C="get_url";Z.__get_url.isVendorTemplate=!0;Z.__get_url.priorityOverride=0;Z.__get_url.isInfrastructure=!1;Z.__get_url.runInSiloedMode=!1})(function(b){var c=b.vtp_urlParts==="any"?null:[];c&&(b.vtp_protocol&&c.push("protocol"),b.vtp_host&&c.push("host"),b.vtp_port&&c.push("port"),b.vtp_path&&c.push("path"),b.vtp_extension&&c.push("extension"),b.vtp_query&&c.push("query"),
b.vtp_fragment&&c.push("fragment"));var d=c&&b.vtp_queriesAllowed!=="any"?b.vtp_queryKeys||[]:null,e=b.vtp_createPermissionError;return{assert:function(f,g,k){if(g){if(!l(g))throw e(f,{},"URL component must be a string.");if(c&&c.indexOf(g)<0)throw e(f,{},"Prohibited URL component: "+g);if(g==="query"&&d){if(!k)throw e(f,{},"Prohibited from getting entire URL query when query keys are specified.");if(!l(k))throw e(f,{},"Query key must be a string.");if(d.indexOf(k)<0)throw e(f,{},"Prohibited query key: "+
k);}}else if(c)throw e(f,{},"Prohibited from getting entire URL when components are specified.");},N:a}})}();



Z.securityGroups.gct=["google"],function(){function a(b){for(var c=[],d=0;d<b.length;d++)try{c.push(new RegExp(b[d]))}catch(e){}return c}(function(b){Z.__gct=b;Z.__gct.C="gct";Z.__gct.isVendorTemplate=!0;Z.__gct.priorityOverride=0;Z.__gct.isInfrastructure=!1;Z.__gct.runInSiloedMode=!0})(function(b){var c={},d=b.vtp_sessionDuration;d>0&&(c[P.g.kd]=d);c[P.g.Ud]=b.vtp_eventSettings;c[P.g.pg]=b.vtp_dynamicEventSettings;c[P.g.Yb]=b.vtp_googleSignals===1;c[P.g.Dg]=b.vtp_foreignTld;c[P.g.Ag]=b.vtp_restrictDomain===
1;c[P.g.rf]=b.vtp_internalTrafficResults;var e=P.g.sa,f=b.vtp_linker;f&&f[P.g.X]&&(f[P.g.X]=a(f[P.g.X]));c[e]=f;var g=P.g.tf,k=b.vtp_referralExclusionDefinition;k&&k.include_conditions&&(k.include_conditions=a(k.include_conditions));c[g]=k;var m=bk(b.vtp_trackingId);Gm(m,c);yH(m,b.vtp_gtmEventId);I(b.vtp_gtmOnSuccess)})}();



Z.securityGroups.get=["google"],Z.__get=function(a){var b=a.vtp_settings,c=b.eventParameters||{},d=String(a.vtp_eventName),e={};e.eventId=a.vtp_gtmEventId;e.priorityId=a.vtp_gtmPriorityId;a.vtp_deferrable&&(e.deferrable=!0);var f=Px(String(b.streamId),d,c);Rx(f,e.eventId,e);a.vtp_gtmOnSuccess()},Z.__get.C="get",Z.__get.isVendorTemplate=!0,Z.__get.priorityOverride=0,Z.__get.isInfrastructure=!1,Z.__get.runInSiloedMode=!1;
Z.securityGroups.detect_scroll_events=["google"],function(){function a(){return{}}(function(b){Z.__detect_scroll_events=b;Z.__detect_scroll_events.C="detect_scroll_events";Z.__detect_scroll_events.isVendorTemplate=!0;Z.__detect_scroll_events.priorityOverride=0;Z.__detect_scroll_events.isInfrastructure=!1;Z.__detect_scroll_events.runInSiloedMode=!1})(function(){return{assert:function(){},N:a}})}();


var pJ={};pJ.dataLayer=Xi;pJ.callback=function(a){Ki.hasOwnProperty(a)&&Bb(Ki[a])&&Ki[a]();delete Ki[a]};pJ.bootstrap=0;pJ._spx=!1;
function qJ(){vi[Vj()]=vi[Vj()]||pJ;fk();jk()||z(kk(),function(d,e){uw(d,e.transportUrl,e.context);O(92)});Rb(Li,Z.securityGroups);var a=Zj(ak()),b,c=a==null?void 0:(b=a.context)==null?void 0:b.source;c!==2&&c!==4&&c!==3||O(142);Ef=Vf}var rJ=!1;
(function(a){function b(){n=H.documentElement.getAttribute("data-tag-assistant-present");Ky(n)&&(m=k.lj)}function c(){m&&Fc?g(m):a()}if(!G["__TAGGY_INSTALLED"]){var d=!1;if(H.referrer){var e=nj(H.referrer);d=jj(e,"host")==="cct.google"}if(!d){var f=xo("googTaggyReferrer");d=!(!f.length||!f[0].length)}d&&(G["__TAGGY_INSTALLED"]=!0,Lc("https://cct.google/taggy/agent.js"))}var g=function(u){var v="GTM",w="GTM";Bi&&(v="OGT",w="GTAG");var x=G["google.tagmanager.debugui2.queue"];x||(x=
[],G["google.tagmanager.debugui2.queue"]=x,Lc("https://"+ui.Fd+"/debug/bootstrap?id="+ag.ctid+"&src="+w+"&cond="+u+"&gtm="+no()));var y={messageType:"CONTAINER_STARTING",data:{scriptSource:Fc,containerProduct:v,debug:!1,id:ag.ctid,targetRef:{ctid:ag.ctid,isDestination:Lj.oe},aliases:Rj(),destinations:Uj()}};y.data.resume=function(){a()};ui.Ck&&(y.data.initialPublish=!0);x.push(y)},k={Vk:1,nj:2,Cj:3,ri:4,lj:5};k[k.Vk]="GTM_DEBUG_LEGACY_PARAM";k[k.nj]="GTM_DEBUG_PARAM";k[k.Cj]="REFERRER";k[k.ri]="COOKIE";k[k.lj]="EXTENSION_PARAM";
var m=void 0,n=void 0,p=hj(G.location,"query",!1,void 0,"gtm_debug");Ky(p)&&(m=k.nj);if(!m&&H.referrer){var q=nj(H.referrer);jj(q,"host")==="tagassistant.google.com"&&(m=k.Cj)}if(!m){var r=xo("__TAG_ASSISTANT");r.length&&r[0].length&&(m=k.ri)}m||b();if(!m&&Ly(n)){var t=!1;Pc(H,"TADebugSignal",function(){t||(t=!0,b(),c())},!1);G.setTimeout(function(){t||(t=!0,b(),c())},200)}else c()})(function(){try{var a;if(!(a=!T(55))){var b;if(!(b=rJ)){var c;a:{for(var d=Jj().injectedFirstPartyContainers,e=oa(Qj()),
f=e.next();!f.done;f=e.next())if(d[f.value]){c=!0;break a}c=!1}b=!c}a=b}if(a){dk();if(T(69)){}Hk().D();Hn();vl();var g=Xj();if(Jj().canonical[g]){var k=vi.zones;k&&k.unregisterChild(Qj());fw().removeExternalRestrictions(Xj());}else{
Rt();a:{}Oi.j="0";Oi.K="";Oi.W="ad_storage|analytics_storage|ad_user_data|ad_personalization";Oi.O="ad_storage|analytics_storage|ad_user_data";Oi.Ca="";qw();for(var m=data.resource||{},n=m.macros||[],p=
0;p<n.length;p++)uf.push(n[p]);for(var q=m.tags||[],r=0;r<q.length;r++)xf.push(q[r]);for(var t=m.predicates||[],u=0;u<t.length;u++)wf.push(t[u]);for(var v=m.rules||[],w=0;w<v.length;w++){for(var x=v[w],y={},B=0;B<x.length;B++){var A=x[B][0];y[A]=Array.prototype.slice.call(x[B],1);A!=="if"&&A!=="unless"||Df(y[A])}vf.push(y)}zf=Z;Af=pz;Xf=new dg;var C=data.sandboxed_scripts,E=data.security_groups;a:{var D=data.runtime||[],F=data.runtime_lines;Bz=new Pe;SI();tf=Az();var L=Bz,M=RI(),S=new id("require",
M);S.Ma();L.j.j.set("require",S);for(var V=[],aa=0;aa<D.length;aa++){var X=D[aa];if(!Array.isArray(X)||X.length<3){if(X.length===0)continue;break a}F&&F[aa]&&F[aa].length&&Of(X,F[aa]);try{Bz.execute(X),T(76)&&Cj&&X[0]===50&&V.push(X[1])}catch(Yn){}}T(76)&&(Ff=V)}if(C&&C.length)for(var R=["sandboxedScripts"],ma=0;ma<C.length;ma++){var la=C[ma].replace(/^_*/,"");Li[la]=R}TI(E);qJ();if(!Fi)for(var ha=el()?Ri(Oi.O):Ri(Oi.W),ya=0;ya<il.length;ya++){var Na=il[ya],Fa=Na,Sa=ha[Na]?"granted":"denied";Bk().implicit(Fa,
Sa)}Jy();zw=!1;Aw=0;if(H.readyState==="interactive"&&!H.createEventObject||H.readyState==="complete")Cw();else{Pc(H,"DOMContentLoaded",Cw);Pc(H,"readystatechange",Cw);if(H.createEventObject&&H.documentElement.doScroll){var bb=!0;try{bb=!G.frameElement}catch(Yn){}bb&&Dw()}Pc(G,"load",Cw)}oy=!1;H.readyState==="complete"?qy():Pc(G,"load",qy);
Cj&&(jm(wm),G.setInterval(vm,864E5),jm(sz),jm(cx),jm(Tu),jm(zm),jm(xz),jm(nx),jm(Ft),T(76)&&(jm(hx),jm(ix),jm(jx)));if(Dj){zk();Ql();yw();var ud;var vd=Zj(ak());if(vd){for(;vd.parent;){var Gx=Zj(vd.parent);if(!Gx)break;vd=Gx}ud=vd}else ud=void 0;var Oe=ud;if(!Oe)O(144);else if(Oe.canonicalContainerId){var Zn;a:{if(Oe.scriptSource){var Mj;try{var Hx;Mj=(Hx=bd())==null?void 0:Hx.getEntriesByType("resource")}catch(Yn){}if(Mj){for(var $n={},Nj=0;Nj<Mj.length;++Nj){var Ix=Mj[Nj],ao=Ix.initiatorType;if(ao===
"script"&&Ix.name===Oe.scriptSource){Zn={Um:Nj,Vm:$n};break a}$n[ao]=1+($n[ao]||0)}O(146)}else O(145)}Zn=void 0}var bo=Zn;bo&&(rk("rtg",String(Oe.canonicalContainerId)),rk("rlo",String(bo.Um)),rk("slo",String(bo.Vm.script||"0")),rk("hlo",Oe.htmlLoadOrder||"-1"),rk("lst",String(Oe.loadScriptType||"0")))}var co;var Oj=Yj();if(Oj){var Jx;co=Oj.canonicalContainerId||"_"+(Oj.scriptContainerId||((Jx=Oj.destinations)==null?void 0:Jx[0]))}else co=void 0;var Kx=co;Kx&&rk("pcid",Kx);T(31)&&(rk("bt",String(Oi.H?
2:Di?1:0)),rk("ct",String(Oi.H?0:Di?1:lo()?2:3)))}fz();$k(1);JA();Ji=Ob();pJ.bootstrap=Ji;if(T(69)){}}}}catch(Yn){if($k(4),
Cj){var sJ=qm(!0,!0);Oc(sJ)}}});

})()
const app_name = document.currentScript.getAttribute('data-app-name');
const initial_category = document.currentScript.getAttribute('data-category');
const initial_sub_category = document.currentScript.getAttribute('data-sub-category');

// Google Consent Mode
window.dataLayer = window.dataLayer || [];
function gtag() {
  dataLayer.push(arguments)
}
gtag("consent", "default", {
  ad_personalization: "denied",
  ad_storage: "denied",
  ad_user_data: "denied",
  analytics_storage: "denied",
  functionality_storage: "denied",
  personalization_storage: "denied",
  security_storage: "granted",
  wait_for_update: 500
});
gtag("set", "ads_data_redaction", true);
gtag("set", "url_passthrough", true);
// End Google Consent Mode

// Set custom layer data
if(app_name) {
    gtag("set", "app_name", app_name);
}
if(initial_category) {
    gtag("set", "page_category", initial_category);
}
if(initial_sub_category) {
    gtag("set", "page_sub_category", initial_sub_category);
}


gtag("set", "env", 'prod');
gtag("set", "logged_status", 'anonymous');
// EndSet custom layer data

// Google Tag Manager
(function (w, d, s, l, i) {
  w[l] = w[l] || [];
  w[l].push({ 'gtm.start': new Date().getTime(), event: 'gtm.js' });
  var f = d.getElementsByTagName(s)[0],
    j = d.createElement(s),
    dl = l != 'dataLayer' ? '&l=' + l : '';
  j.async = true;
  j.src = 'https://www.googletagmanager.com/gtm.js?id=' + i + dl + '';
  f.parentNode.insertBefore(j, f);
})(window, document, 'script', 'dataLayer', 'GTM-KHNFZPT');
// EndGoogle Tag Manager

class RSITagManager {
  constructor(gtag) {
    if (!gtag) {
      console.log('gtag not found');
      return;
    }

    this.gtag = gtag;

    this.#listentoRSITagManagerPageView();
    this.#listentoRSITagManagerEvent();

    // fire the RSITagManager_ready event so other application can listen to it
    requestAnimationFrame(() => {
      const rsiTMReady = new CustomEvent('RSITagManager_ready');
      window.dispatchEvent(rsiTMReady);
    });
  }

  #listentoRSITagManagerPageView() {
    window.addEventListener('RSITagManager_page_view', this.#pageViewCallback.bind(this));
  }

  #listentoRSITagManagerEvent() {
    window.addEventListener('RSITagManager_event', this.#eventCallback.bind(this));
  }

  #eventCallback(e) {
    const { action, data } = e.detail;
    if (this.isReady) {
      return this.event(action, data);
    }
  }

  #pageViewCallback(e) {
    const { page_title, page_location, page_category, page_sub_category, data } = e.detail;
    if (this.isReady) {
      return this.pageView(page_title, page_location, page_category, page_sub_category, data);
    }
  }

  isReady() {
    return this.gtag !== undefined;
  }

  event(action, data) {
    this.gtag('event', action, data);
  }

  // this method must be called only when a custom page view needs to be tracked
  // to not trigger a pageview when the url changes because it will be tracked by default
  pageView(page_title, page_location, page_category, page_sub_category, data) {
    this.event('page_view', {
      page_title,
      page_location,
      page_category,
      page_sub_category,
      ...data,
    });
  }

  setPageCategory(category) {
    this.gtag('set', 'page_category', category);
  }

  setPageSubCategory(sub_category) {
    this.gtag('set', 'page_sub_category', sub_category);
  }

  set(...args) {
    this.gtag('set', ...args);
  }

  get(...args) {
    this.gtag('get', ...args);
  }

  config(...args) {
    this.gtag('config', ...args);
  }

  consent(...args) {
    this.gtag('consent', ...args);
  }
}

// RSI Tag Manager
if (!window.RSITM) {
  // instanciate the GA class and make it available in the window
  window.RSITM = new RSITagManager(gtag);
} else {
  console.warn('RSITagManager - RSITM already exists');
}
// EndRSI Tag Manager


// Copyright 2012 Google Inc. All rights reserved.
 
(function(){

var data = {
"resource": {
  "version":"4",
  
  "macros":[{"function":"__e"},{"function":"__c","vtp_value":false},{"function":"__c","vtp_value":""},{"function":"__c","vtp_value":0}],
  "tags":[{"function":"__ogt_auto_events","priority":19,"vtp_enableScroll":true,"vtp_enableOutboundClick":false,"vtp_enableDownload":false,"vtp_enableHistoryEvents":true,"vtp_enableForm":false,"vtp_enableVideo":false,"vtp_enablePageView":true,"tag_id":10},{"function":"__ogt_dma","priority":9,"vtp_delegationMode":"ON","vtp_dmaDefault":"DENIED","tag_id":12},{"function":"__ogt_ip_mark","priority":9,"vtp_instanceOrder":0,"vtp_paramValue":"internal","vtp_ruleResult":["macro",1],"tag_id":14},{"function":"__ogt_1p_data_v2","priority":9,"vtp_isAutoEnabled":true,"vtp_autoCollectExclusionSelectors":["list",["map","exclusionSelector",""]],"vtp_isEnabled":true,"vtp_cityType":"CSS_SELECTOR","vtp_manualEmailEnabled":false,"vtp_firstNameType":"CSS_SELECTOR","vtp_countryType":"CSS_SELECTOR","vtp_cityValue":"","vtp_emailType":"CSS_SELECTOR","vtp_regionType":"CSS_SELECTOR","vtp_autoEmailEnabled":true,"vtp_postalCodeValue":"","vtp_lastNameValue":"","vtp_phoneType":"CSS_SELECTOR","vtp_phoneValue":"","vtp_streetType":"CSS_SELECTOR","vtp_autoPhoneEnabled":false,"vtp_postalCodeType":"CSS_SELECTOR","vtp_emailValue":"","vtp_firstNameValue":"","vtp_streetValue":"","vtp_lastNameType":"CSS_SELECTOR","vtp_autoAddressEnabled":false,"vtp_regionValue":"","vtp_countryValue":"","vtp_isAutoCollectPiiEnabledFlag":false,"tag_id":15},{"function":"__ccd_ga_first","priority":8,"vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":24},{"function":"__set_product_settings","priority":7,"vtp_instanceDestinationId":"G-CSLL4ZEK4L","vtp_foreignTldMacroResult":["macro",2],"vtp_isChinaVipRegionMacroResult":["macro",3],"tag_id":23},{"function":"__ogt_google_signals","priority":6,"vtp_googleSignals":"DISABLED","vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":22},{"function":"__ccd_ga_regscope","priority":5,"vtp_settingsTable":["list",["map","redactFieldGroup","DEVICE_AND_GEO","disallowAllRegions",false,"disallowedRegions",""],["map","redactFieldGroup","GOOGLE_SIGNALS","disallowAllRegions",true,"disallowedRegions",""]],"vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":21},{"function":"__ccd_em_page_view","priority":4,"vtp_historyEvents":true,"vtp_includeParams":true,"vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":20},{"function":"__ccd_em_scroll","priority":3,"vtp_includeParams":true,"vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":19},{"function":"__ccd_conversion_marking","priority":2,"vtp_conversionRules":["list",["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"purchase\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"video_complete\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"telephone_click\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"file_download\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"email_click\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"],["map","matchingRules","{\"type\":5,\"args\":[{\"stringValue\":\"dap_event\"},{\"contextValue\":{\"namespaceType\":1,\"keyParts\":[\"eventName\"]}}]}"]],"vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":18},{"function":"__ccd_auto_redact","priority":1,"vtp_redactEmail":true,"vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":17},{"function":"__gct","vtp_trackingId":"G-CSLL4ZEK4L","vtp_sessionDuration":0,"tag_id":7},{"function":"__ccd_ga_last","priority":0,"vtp_instanceDestinationId":"G-CSLL4ZEK4L","tag_id":16}],
  "predicates":[{"function":"_eq","arg0":["macro",0],"arg1":"gtm.js"},{"function":"_eq","arg0":["macro",0],"arg1":"gtm.init"},{"function":"_eq","arg0":["macro",0],"arg1":"gtm.init_consent"}],
  "rules":[[["if",0],["add",12]],[["if",1],["add",0,2,3,13,11,10,9,8,7,6,5,4]],[["if",2],["add",1]]]
},
"runtime":[ [50,"__c",[46,"a"],[36,[17,[15,"a"],"value"]]]
 ,[50,"__ccd_auto_redact",[46,"a"],[50,"v",[46,"bk"],[36,[2,[15,"bk"],"replace",[7,[15,"u"],"\\$1"]]]],[50,"w",[46,"bk"],[52,"bl",["c",[15,"bk"]]],[52,"bm",[7]],[65,"bn",[2,[15,"bl"],"split",[7,""]],[46,[53,[52,"bo",[7,["v",[15,"bn"]]]],[52,"bp",["d",[15,"bn"]]],[22,[12,[15,"bp"],[45]],[46,[36,["d",["v",[15,"bk"]]]]]],[22,[21,[15,"bp"],[15,"bn"]],[46,[2,[15,"bo"],"push",[7,[15,"bp"]]],[22,[21,[15,"bn"],[2,[15,"bn"],"toLowerCase",[7]]],[46,[2,[15,"bo"],"push",[7,["d",[2,[15,"bn"],"toLowerCase",[7]]]]]],[46,[22,[21,[15,"bn"],[2,[15,"bn"],"toUpperCase",[7]]],[46,[2,[15,"bo"],"push",[7,["d",[2,[15,"bn"],"toUpperCase",[7]]]]]]]]]]],[22,[18,[17,[15,"bo"],"length"],1],[46,[2,[15,"bm"],"push",[7,[0,[0,"(?:",[2,[15,"bo"],"join",[7,"|"]]],")"]]]],[46,[2,[15,"bm"],"push",[7,[16,[15,"bo"],0]]]]]]]],[36,[2,[15,"bm"],"join",[7,""]]]],[50,"x",[46,"bk","bl","bm"],[52,"bn",["z",[15,"bk"],[15,"bm"]]],[22,[28,[15,"bn"]],[46,[36,[15,"bk"]]]],[22,[28,[17,[15,"bn"],"search"]],[46,[36,[15,"bk"]]]],[41,"bo"],[3,"bo",[17,[15,"bn"],"search"]],[65,"bp",[15,"bl"],[46,[53,[52,"bq",[7,["v",[15,"bp"]],["w",[15,"bp"]]]],[65,"br",[15,"bq"],[46,[53,[52,"bs",[30,[16,[15,"t"],[15,"br"]],[43,[15,"t"],[15,"br"],["b",[0,[0,"([?&]",[15,"br"]],"=)([^&]*)"],"gi"]]]],[3,"bo",[2,[15,"bo"],"replace",[7,[15,"bs"],[0,"$1",[15,"r"]]]]]]]]]]],[22,[20,[15,"bo"],[17,[15,"bn"],"search"]],[46,[36,[15,"bk"]]]],[22,[20,[16,[15,"bo"],0],"&"],[46,[3,"bo",[2,[15,"bo"],"substring",[7,1]]]]],[22,[21,[16,[15,"bo"],0],"?"],[46,[3,"bo",[0,"?",[15,"bo"]]]]],[22,[20,[15,"bo"],"?"],[46,[3,"bo",""]]],[43,[15,"bn"],"search",[15,"bo"]],[36,["ba",[15,"bn"],[15,"bm"]]]],[50,"z",[46,"bk","bl"],[22,[20,[15,"bl"],[17,[15,"s"],"PATH"]],[46,[3,"bk",[0,[15,"y"],[15,"bk"]]]]],[36,["g",[15,"bk"]]]],[50,"ba",[46,"bk","bl"],[41,"bm"],[3,"bm",""],[22,[20,[15,"bl"],[17,[15,"s"],"URL"]],[46,[53,[41,"bn"],[3,"bn",""],[22,[30,[17,[15,"bk"],"username"],[17,[15,"bk"],"password"]],[46,[3,"bn",[0,[15,"bn"],[0,[0,[0,[17,[15,"bk"],"username"],[39,[17,[15,"bk"],"password"],":",""]],[17,[15,"bk"],"password"]],"@"]]]]],[3,"bm",[0,[0,[0,[17,[15,"bk"],"protocol"],"//"],[15,"bn"]],[17,[15,"bk"],"host"]]]]]],[36,[0,[0,[0,[15,"bm"],[17,[15,"bk"],"pathname"]],[17,[15,"bk"],"search"]],[17,[15,"bk"],"hash"]]]],[50,"bb",[46,"bk","bl"],[41,"bm"],[3,"bm",[2,[15,"bk"],"replace",[7,[15,"n"],[15,"r"]]]],[22,[30,[20,[15,"bl"],[17,[15,"s"],"URL"]],[20,[15,"bl"],[17,[15,"s"],"PATH"]]],[46,[53,[52,"bn",["z",[15,"bm"],[15,"bl"]]],[22,[20,[15,"bn"],[44]],[46,[36,[15,"bm"]]]],[52,"bo",[17,[15,"bn"],"search"]],[52,"bp",[2,[15,"bo"],"replace",[7,[15,"o"],[15,"r"]]]],[22,[20,[15,"bo"],[15,"bp"]],[46,[36,[15,"bm"]]]],[43,[15,"bn"],"search",[15,"bp"]],[3,"bm",["ba",[15,"bn"],[15,"bl"]]]]]],[36,[15,"bm"]]],[50,"bc",[46,"bk"],[22,[20,[15,"bk"],[15,"q"]],[46,[36,[17,[15,"s"],"PATH"]]],[46,[22,[21,[2,[15,"p"],"indexOf",[7,[15,"bk"]]],[27,1]],[46,[36,[17,[15,"s"],"URL"]]],[46,[36,[17,[15,"s"],"TEXT"]]]]]]],[50,"bd",[46,"bk","bl"],[41,"bm"],[3,"bm",false],[52,"bn",["f",[15,"bk"]]],[38,[15,"bn"],[46,"string","array","object"],[46,[5,[46,[52,"bo",["bb",[15,"bk"],[15,"bl"]]],[22,[21,[15,"bk"],[15,"bo"]],[46,[36,[15,"bo"]]]],[4]]],[5,[46,[53,[41,"bp"],[3,"bp",0],[63,[7,"bp"],[23,[15,"bp"],[17,[15,"bk"],"length"]],[33,[15,"bp"],[3,"bp",[0,[15,"bp"],1]]],[46,[53,[52,"bq",["bd",[16,[15,"bk"],[15,"bp"]],[17,[15,"s"],"TEXT"]]],[22,[21,[15,"bq"],[44]],[46,[43,[15,"bk"],[15,"bp"],[15,"bq"]],[3,"bm",true]]]]]]],[4]]],[5,[46,[54,"bp",[15,"bk"],[46,[53,[52,"bq",["bd",[16,[15,"bk"],[15,"bp"]],[17,[15,"s"],"TEXT"]]],[22,[21,[15,"bq"],[44]],[46,[43,[15,"bk"],[15,"bp"],[15,"bq"]],[3,"bm",true]]]]]],[4]]]]],[36,[39,[15,"bm"],[15,"bk"],[44]]]],[50,"bj",[46,"bk","bl"],[52,"bm",[30,[2,[15,"bk"],"getMetadata",[7,[15,"bi"]]],[7]]],[22,[20,[2,[15,"bm"],"indexOf",[7,[15,"bl"]]],[27,1]],[46,[2,[15,"bm"],"push",[7,[15,"bl"]]]]],[2,[15,"bk"],"setMetadata",[7,[15,"bi"],[15,"bm"]]]],[52,"b",["require","internal.createRegex"]],[52,"c",["require","decodeUriComponent"]],[52,"d",["require","encodeUriComponent"]],[52,"e",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"f",["require","getType"]],[52,"g",["require","parseUrl"]],[52,"h",["require","internal.registerCcdCallback"]],[52,"i",[17,[15,"a"],"instanceDestinationId"]],[52,"j",[17,[15,"a"],"redactEmail"]],[52,"k",[17,[15,"a"],"redactQueryParams"]],[52,"l",[39,[15,"k"],[2,[15,"k"],"split",[7,","]],[7]]],[52,"m","is_sgtm_prehit"],[22,[1,[28,[17,[15,"l"],"length"]],[28,[15,"j"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"n",["b","[A-Z0-9._%+-]+@[A-Z0-9.-]+\\.[A-Z]{2,}","gi"]],[52,"o",["b",[0,"([A-Z0-9._-]|%25|%2B)+%40[A-Z0-9.-]","+\\.[A-Z]{2,}"],"gi"]],[52,"p",[7,"page_location","page_referrer","page_path","link_url","video_url","form_destination"]],[52,"q","page_path"],[52,"r","(redacted)"],[52,"s",[8,"TEXT",0,"URL",1,"PATH",2]],[52,"t",[8]],[52,"u",["b","([\\\\^$.|?*+(){}]|\\[|\\[)","g"]],[52,"y","http://."],[52,"be",15],[52,"bf",16],[52,"bg",23],[52,"bh",24],[52,"bi","event_usage"],["h",[15,"i"],[51,"",[7,"bk"],[22,[15,"j"],[46,[53,[52,"bl",[2,[15,"bk"],"getHitKeys",[7]]],[65,"bm",[15,"bl"],[46,[53,[22,[20,[15,"bm"],"_sst_parameters"],[46,[6]]],[52,"bn",[2,[15,"bk"],"getHitData",[7,[15,"bm"]]]],[22,[28,[15,"bn"]],[46,[6]]],[52,"bo",["bc",[15,"bm"]]],[52,"bp",["bd",[15,"bn"],[15,"bo"]]],[22,[21,[15,"bp"],[44]],[46,[2,[15,"bk"],"setHitData",[7,[15,"bm"],[15,"bp"]]],["bj",[15,"bk"],[39,[2,[15,"bk"],"getMetadata",[7,[15,"m"]]],[15,"bg"],[15,"be"]]]]]]]]]]],[22,[17,[15,"l"],"length"],[46,[65,"bl",[15,"p"],[46,[53,[52,"bm",[2,[15,"bk"],"getHitData",[7,[15,"bl"]]]],[22,[28,[15,"bm"]],[46,[6]]],[52,"bn",[39,[20,[15,"bl"],[15,"q"]],[17,[15,"s"],"PATH"],[17,[15,"s"],"URL"]]],[52,"bo",["x",[15,"bm"],[15,"l"],[15,"bn"]]],[22,[21,[15,"bo"],[15,"bm"]],[46,[2,[15,"bk"],"setHitData",[7,[15,"bl"],[15,"bo"]]],["bj",[15,"bk"],[39,[2,[15,"bk"],"getMetadata",[7,[15,"m"]]],[15,"bh"],[15,"bf"]]]]]]]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_conversion_marking",[46,"a"],[22,[30,[28,[17,[15,"a"],"conversionRules"]],[20,[17,[17,[15,"a"],"conversionRules"],"length"],0]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"b",["require","internal.copyPreHit"]],[52,"c",["require","internal.evaluateBooleanExpression"]],[52,"d",["require","internal.registerCcdCallback"]],[52,"e","is_conversion"],[52,"f","is_first_visit"],[52,"g","is_first_visit_conversion"],[52,"h","is_session_start"],[52,"i","is_session_start_conversion"],[52,"j","first_visit"],[52,"k","session_start"],[41,"l"],[41,"m"],["d",[17,[15,"a"],"instanceDestinationId"],[51,"",[7,"n"],[52,"o",[8,"preHit",[15,"n"]]],[65,"p",[17,[15,"a"],"conversionRules"],[46,[22,["c",[17,[15,"p"],"matchingRules"],[15,"o"]],[46,[2,[15,"n"],"setMetadata",[7,[15,"e"],true]],[4]]]]],[22,[2,[15,"n"],"getMetadata",[7,[15,"f"]]],[46,[22,[28,[15,"l"]],[46,[53,[52,"p",["b",[15,"n"],[8,"omitHitData",true,"omitMetadata",true]]],[2,[15,"p"],"setEventName",[7,[15,"j"]]],[3,"l",[8,"preHit",[15,"p"]]]]]],[65,"p",[17,[15,"a"],"conversionRules"],[46,[22,["c",[17,[15,"p"],"matchingRules"],[15,"l"]],[46,[2,[15,"n"],"setMetadata",[7,[15,"g"],true]],[4]]]]]]],[22,[2,[15,"n"],"getMetadata",[7,[15,"h"]]],[46,[22,[28,[15,"m"]],[46,[53,[52,"p",["b",[15,"n"],[8,"omitHitData",true,"omitMetadata",true]]],[2,[15,"p"],"setEventName",[7,[15,"k"]]],[3,"m",[8,"preHit",[15,"p"]]]]]],[65,"p",[17,[15,"a"],"conversionRules"],[46,[22,["c",[17,[15,"p"],"matchingRules"],[15,"m"]],[46,[2,[15,"n"],"setMetadata",[7,[15,"i"],true]],[4]]]]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]],[36]]
 ,[50,"__ccd_em_page_view",[46,"a"],[50,"s",[46,"t"],[52,"u",[8]],[43,[15,"u"],[15,"k"],true],[43,[15,"u"],[15,"g"],true],[43,[15,"t"],"eventMetadata",[15,"u"]]],[22,[28,[17,[15,"a"],"historyEvents"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getProductSettingsParameter"]],[52,"d",["require","internal.setRemoteConfigParameter"]],[52,"e",["require","templateStorage"]],[52,"f",[15,"__module_ccdEmPageViewActivity"]],[52,"g","speculative"],[52,"h","ae_block_history"],[52,"i","page_view"],[52,"j","isRegistered"],[52,"k","em_event"],[52,"l",[17,[15,"a"],"instanceDestinationId"]],[22,["c",[15,"l"],[15,"h"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"f"],"registerPageViewActivityCallback",[7,[15,"l"]]],[22,[2,[15,"e"],"getItem",[7,[15,"j"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"m",["require","internal.addDataLayerEventListener"]],[52,"n",["require","internal.enableAutoEventOnHistoryChange"]],[52,"o",["require","internal.getDestinationIds"]],[52,"p",["require","internal.sendGtagEvent"]],[52,"q",[8,"interval",1000,"useV2EventName",true]],[52,"r",["n",[15,"q"]]],[22,[28,[15,"r"]],[46,[2,[15,"a"],"gtmOnFailure",[7]],[36]]],[2,[15,"e"],"setItem",[7,[15,"j"],true]],["m","gtm.historyChange-v2",[51,"",[7,"t","u"],["u"],[52,"v",[16,[15,"t"],"gtm.oldUrl"]],[22,[20,[16,[15,"t"],"gtm.newUrl"],[15,"v"]],[46,[36]]],[52,"w",[16,[15,"t"],"gtm.historyChangeSource"]],[22,[1,[1,[21,[15,"w"],"pushState"],[21,[15,"w"],"popstate"]],[21,[15,"w"],"replaceState"]],[46,[36]]],[52,"x",[8]],[22,[17,[15,"a"],"includeParams"],[46,[43,[15,"x"],"page_location",[16,[15,"t"],"gtm.newUrl"]],[43,[15,"x"],"page_referrer",[15,"v"]]]],[52,"y",[8,"eventId",[16,[15,"t"],"gtm.uniqueEventId"]]],[22,[16,[15,"b"],"enableDeferAllEnhancedMeasurement"],[46,[43,[15,"y"],"deferrable",true]]],["s",[15,"y"]],["p",["o"],[15,"i"],[15,"x"],[15,"y"]]],[15,"r"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_em_scroll",[46,"a"],[50,"q",[46,"r"],[52,"s",[8]],[43,[15,"s"],[15,"j"],true],[43,[15,"s"],[15,"f"],true],[43,[15,"r"],"eventMetadata",[15,"s"]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getProductSettingsParameter"]],[52,"d",["require","templateStorage"]],[52,"e",[15,"__module_ccdEmScrollActivity"]],[52,"f","speculative"],[52,"g","ae_block_scroll"],[52,"h","scroll"],[52,"i","isRegistered"],[52,"j","em_event"],[52,"k",[17,[15,"a"],"instanceDestinationId"]],[22,["c",[15,"k"],[15,"g"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[2,[15,"e"],"registerScrollActivityCallback",[7,[15,"k"],[17,[15,"a"],"includeParams"]]],[22,[2,[15,"d"],"getItem",[7,[15,"i"]]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"l",["require","internal.addDataLayerEventListener"]],[52,"m",["require","internal.enableAutoEventOnScroll"]],[52,"n",["require","internal.getDestinationIds"]],[52,"o",["require","internal.sendGtagEvent"]],[52,"p",["m",[8,"verticalThresholdUnits","PERCENT","verticalThresholds",90]]],[22,[28,[15,"p"]],[46,[2,[15,"a"],"gtmOnFailure",[7]],[36]]],[2,[15,"d"],"setItem",[7,[15,"i"],true]],["l","gtm.scrollDepth",[51,"",[7,"r","s"],["s"],[52,"t",[8,"eventId",[16,[15,"r"],"gtm.uniqueEventId"]]],[22,[16,[15,"b"],"enableDeferAllEnhancedMeasurement"],[46,[43,[15,"t"],"deferrable",true]]],[52,"u",[8,"percent_scrolled",[16,[15,"r"],"gtm.scrollThreshold"]]],["q",[15,"t"]],["o",["n"],[15,"h"],[15,"u"],[15,"t"]]],[15,"p"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_ga_first",[46,"a"],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_ga_last",[46,"a"],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ccd_ga_regscope",[46,"a"],[52,"b",[15,"__module_ccdGaRegionScopedSettings"]],[52,"c",[2,[15,"b"],"extractRedactedLocations",[7,[15,"a"]]]],[2,[15,"b"],"applyRegionScopedSettings",[7,[15,"a"],[15,"c"]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__e",[46,"a"],[36,[13,[41,"$0"],[3,"$0",["require","internal.getEventData"]],["$0","event"]]]]
 ,[50,"__ogt_1p_data_v2",[46,"a"],[50,"j",[46,"m","n","o"],[22,[20,[16,[15,"n"],"type"],[15,"o"]],[46,[22,[28,[15,"m"]],[46,[3,"m",[8]]]],[22,[28,[16,[15,"m"],[15,"o"]]],[46,[43,[15,"m"],[15,"o"],[16,[15,"n"],"userData"]]]]]],[36,[15,"m"]]],[50,"k",[46,"m","n"],[52,"o",[16,[15,"a"],[15,"m"]]],[41,"p"],[22,[20,[15,"o"],"CSS_SELECTOR"],[46,[3,"p","css_selector"]],[46,[22,[20,[15,"o"],"JS_VAR"],[46,[3,"p","js_variable"]]]]],[36,[8,"selector_type",[15,"p"],"value",[16,[15,"a"],[15,"n"]]]]],[50,"l",[46,"m","n","o","p"],[22,[28,[16,[15,"a"],[15,"p"]]],[46,[36]]],[43,[15,"m"],[15,"n"],["k",[15,"o"],[15,"p"]]]],[22,[28,[17,[15,"a"],"isEnabled"]],[46,[2,[15,"a"],"gtmOnSuccess",[7]],[36]]],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"c",["require","internal.getDestinationIds"]],[52,"d",["require","internal.getProductSettingsParameter"]],[52,"e",["require","internal.detectUserProvidedData"]],[52,"f",["require","internal.setRemoteConfigParameter"]],[52,"g",["require","internal.registerCcdCallback"]],[52,"h",[30,["c"],[7]]],[52,"i",[8,"enable_code",true]],[22,[17,[15,"a"],"isAutoEnabled"],[46,[53,[52,"m",[7]],[22,[1,[17,[15,"a"],"autoCollectExclusionSelectors"],[17,[17,[15,"a"],"autoCollectExclusionSelectors"],"length"]],[46,[53,[41,"o"],[3,"o",0],[63,[7,"o"],[23,[15,"o"],[17,[17,[15,"a"],"autoCollectExclusionSelectors"],"length"]],[33,[15,"o"],[3,"o",[0,[15,"o"],1]]],[46,[53,[52,"p",[17,[16,[17,[15,"a"],"autoCollectExclusionSelectors"],[15,"o"]],"exclusionSelector"]],[22,[15,"p"],[46,[2,[15,"m"],"push",[7,[15,"p"]]]]]]]]]]],[52,"n",[39,[17,[15,"a"],"isAutoCollectPiiEnabledFlag"],[17,[15,"a"],"autoEmailEnabled"],true]],[43,[15,"i"],"auto_detect",[8,"email",[15,"n"],"phone",[17,[15,"a"],"autoPhoneEnabled"],"address",[17,[15,"a"],"autoAddressEnabled"],"exclude_element_selectors",[15,"m"]]]]]],[22,[17,[15,"a"],"isManualEnabled"],[46,[53,[52,"m",[8]],[22,[17,[15,"a"],"manualEmailEnabled"],[46,["l",[15,"m"],"email","emailType","emailValue"]]],[22,[17,[15,"a"],"manualPhoneEnabled"],[46,["l",[15,"m"],"phone","phoneType","phoneValue"]]],[22,[17,[15,"a"],"manualAddressEnabled"],[46,[53,[52,"n",[8]],["l",[15,"n"],"first_name","firstNameType","firstNameValue"],["l",[15,"n"],"last_name","lastNameType","lastNameValue"],["l",[15,"n"],"street","streetType","streetValue"],["l",[15,"n"],"city","cityType","cityValue"],["l",[15,"n"],"region","regionType","regionValue"],["l",[15,"n"],"country","countryType","countryValue"],["l",[15,"n"],"postal_code","postalCodeType","postalCodeValue"],[43,[15,"m"],"name_and_address",[7,[15,"n"]]]]]],[43,[15,"i"],"selectors",[15,"m"]]]]],[65,"m",[15,"h"],[46,[53,[41,"n"],[3,"n",[15,"i"]],[22,[1,[20,[2,[15,"m"],"indexOf",[7,"G-"]],0],[28,[16,[15,"b"],"enableEuidAutoMode"]]],[46,[53,[52,"q",[8,"enable_code",true,"selectors",[16,[15,"i"],"selectors"]]],[3,"n",[15,"q"]]]]],["f",[15,"m"],"user_data_settings",[15,"n"]],[52,"o",[16,[15,"n"],"auto_detect"]],[22,[28,[15,"o"]],[46,[6]]],[52,"p",[51,"",[7,"q"],[52,"r",[2,[15,"q"],"getMetadata",[7,"user_data_from_automatic"]]],[22,[15,"r"],[46,[36,[15,"r"]]]],[52,"s",["e",[8,"excludeElementSelectors",[16,[15,"o"],"exclude_element_selectors"],"fieldFilters",[8,"email",[16,[15,"o"],"email"],"phone",[16,[15,"o"],"phone"],"address",[16,[15,"o"],"address"]]]]],[52,"t",[1,[15,"s"],[16,[15,"s"],"elements"]]],[52,"u",[8]],[22,[1,[15,"t"],[18,[17,[15,"t"],"length"],0]],[46,[53,[41,"v"],[53,[41,"w"],[3,"w",0],[63,[7,"w"],[23,[15,"w"],[17,[15,"t"],"length"]],[33,[15,"w"],[3,"w",[0,[15,"w"],1]]],[46,[53,[52,"x",[16,[15,"t"],[15,"w"]]],["j",[15,"u"],[15,"x"],"email"],[22,[16,[15,"b"],"enableAutoPiiOnPhoneAndAddress"],[46,["j",[15,"u"],[15,"x"],"phone_number"],[3,"v",["j",[15,"v"],[15,"x"],"first_name"]],[3,"v",["j",[15,"v"],[15,"x"],"last_name"]],[3,"v",["j",[15,"v"],[15,"x"],"country"]],[3,"v",["j",[15,"v"],[15,"x"],"postal_code"]]]]]]]],[22,[1,[15,"v"],[28,[16,[15,"u"],"address"]]],[46,[43,[15,"u"],"address",[15,"v"]]]]]]],[2,[15,"q"],"setMetadata",[7,"user_data_from_automatic",[15,"u"]]],[36,[15,"u"]]]],["g",[15,"m"],[51,"",[7,"q"],[2,[15,"q"],"setMetadata",[7,"user_data_from_automatic_getter",[15,"p"]]]]]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ogt_auto_events",[46,"a"],[52,"b",["require","internal.getDestinationIds"]],[52,"c",["require","internal.setProductSettingsParameter"]],[41,"d"],[3,"d",[30,["b"],[7]]],[52,"e",[51,"",[7,"f","g"],[22,[15,"f"],[46,[36]]],[65,"h",[15,"d"],[46,["c",[15,"h"],[15,"g"],true]]]]],["e",[17,[15,"a"],"enableHistoryEvents"],"ae_block_history"],["e",[17,[15,"a"],"enableScroll"],"ae_block_scroll"],["e",[17,[15,"a"],"enableOutboundClick"],"ae_block_outbound_click"],["e",[17,[15,"a"],"enableForm"],"ae_block_form"],["e",[17,[15,"a"],"enableVideo"],"ae_block_video"],["e",[17,[15,"a"],"enableDownload"],"ae_block_downloads"],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ogt_dma",[46,"a"],[52,"b",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[22,[20,[17,[15,"a"],"delegationMode"],"ON"],[46,[53,[52,"e",["require","internal.isDmaRegion"]],[22,["e"],[46,[53,[52,"f",["require","internal.setDelegatedConsentType"]],["f","ad_user_data","ad_storage"]]]]]]],[52,"c",["require","internal.declareConsentState"]],[52,"d",[8]],[22,[1,[16,[15,"b"],"enableDmaBlockDisclosure"],[20,[17,[15,"a"],"dmaDefault"],"GRANTED"]],[46,[43,[15,"d"],"ad_user_data","granted"]]],[22,[21,[16,[15,"d"],"ad_user_data"],[44]],[46,["c",[15,"d"]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ogt_google_signals",[46,"a"],[52,"b",["require","internal.setProductSettingsParameter"]],[52,"c",["require","getContainerVersion"]],[52,"d",[30,[17,[15,"a"],"instanceDestinationId"],[17,["c"],"containerId"]]],["b",[15,"d"],"google_signals",[20,[17,[15,"a"],"googleSignals"],"ENABLED"]],["b",[15,"d"],"google_ng",[20,[17,[15,"a"],"googleSignals"],"NON_GAIA_REMARKETING"]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__ogt_ip_mark",[46,"a"],[52,"b",["require","internal.appendRemoteConfigParameter"]],[52,"c",["require","internal.getDestinationIds"]],[52,"d",["require","internal.sortRemoteConfigParameters"]],[52,"e",[8,"instance_order",[17,[15,"a"],"instanceOrder"],"traffic_type",[17,[15,"a"],"paramValue"],"rule_result",[17,[15,"a"],"ruleResult"]]],[41,"f"],[3,"f",[30,["c"],[7]]],[65,"g",[15,"f"],[46,["b",[15,"g"],"internal_traffic_results",[15,"e"]],["d",[15,"g"],"internal_traffic_results",[8,"sortKey","instance_order"]]]],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[50,"__set_product_settings",[46,"a"],[2,[15,"a"],"gtmOnSuccess",[7]]]
 ,[52,"__module_activities",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"b",[46,"c","d"],[36,[39,[15,"d"],["d",[15,"c"]],[15,"c"]]]],[36,[8,"withRequestContext",[15,"b"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmPageViewActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"j",[46,"k"],["c",[15,"k"],[51,"",[7,"l"],[22,[30,[21,[2,[15,"l"],"getEventName",[7]],[15,"h"]],[28,[2,[15,"l"],"getMetadata",[7,[15,"i"]]]]],[46,[36]]],[22,["b",[15,"k"],[15,"g"]],[46,[2,[15,"l"],"abort",[7]],[36]]],[22,[28,[2,[15,"l"],"getMetadata",[7,[15,"f"]]]],[46,["d",[15,"k"],"page_referrer",[2,[15,"l"],"getHitData",[7,"page_referrer"]]]]],[2,[15,"l"],"setMetadata",[7,[15,"e"],false]]]]],[52,"b",["require","internal.getProductSettingsParameter"]],[52,"c",["require","internal.registerCcdCallback"]],[52,"d",["require","internal.setRemoteConfigParameter"]],[52,"e","speculative"],[52,"f","is_sgtm_prehit"],[52,"g","ae_block_history"],[52,"h","page_view"],[52,"i","em_event"],[36,[8,"registerPageViewActivityCallback",[15,"j"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdEmScrollActivity",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"h",[46,"i","j"],["c",[15,"i"],[51,"",[7,"k"],[22,[30,[21,[2,[15,"k"],"getEventName",[7]],[15,"f"]],[28,[2,[15,"k"],"getMetadata",[7,[15,"g"]]]]],[46,[36]]],[22,["b",[15,"i"],[15,"e"]],[46,[2,[15,"k"],"abort",[7]],[36]]],[2,[15,"k"],"setMetadata",[7,[15,"d"],false]],[22,[28,[15,"j"]],[46,[2,[15,"k"],"setHitData",[7,"percent_scrolled",[44]]]]]]]],[52,"b",["require","internal.getProductSettingsParameter"]],[52,"c",["require","internal.registerCcdCallback"]],[52,"d","speculative"],[52,"e","ae_block_scroll"],[52,"f","scroll"],[52,"g","em_event"],[36,[8,"registerScrollActivityCallback",[15,"h"]]]],[36,["a"]]]],["$0"]]]
 ,[52,"__module_ccdGaRegionScopedSettings",[13,[41,"$0"],[3,"$0",[51,"",[7],[50,"a",[46],[50,"n",[46,"q","r","s"],[50,"x",[46,"z"],[52,"ba",[16,[15,"m"],[15,"z"]]],[22,[28,[15,"ba"]],[46,[36]]],[53,[41,"bb"],[3,"bb",0],[63,[7,"bb"],[23,[15,"bb"],[17,[15,"ba"],"length"]],[33,[15,"bb"],[3,"bb",[0,[15,"bb"],1]]],[46,[53,[52,"bc",[16,[15,"ba"],[15,"bb"]]],["u",[15,"t"],[17,[15,"bc"],"name"],[17,[15,"bc"],"value"]]]]]]],[50,"y",[46,"z"],[22,[30,[28,[15,"v"]],[21,[17,[15,"v"],"length"],2]],[46,[36,false]]],[41,"ba"],[3,"ba",[16,[15,"z"],[15,"w"]]],[22,[20,[15,"ba"],[44]],[46,[3,"ba",[16,[15,"z"],[15,"v"]]]]],[36,[28,[28,[15,"ba"]]]]],[22,[28,[15,"r"]],[46,[36]]],[52,"t",[30,[17,[15,"q"],"instanceDestinationId"],[17,["d"],"containerId"]]],[52,"u",["i",[15,"g"],[15,"s"]]],[52,"v",[13,[41,"$0"],[3,"$0",["i",[15,"e"],[15,"s"]]],["$0"]]],[52,"w",[13,[41,"$0"],[3,"$0",["i",[15,"f"],[15,"s"]]],["$0"]]],[53,[41,"z"],[3,"z",0],[63,[7,"z"],[23,[15,"z"],[17,[15,"r"],"length"]],[33,[15,"z"],[3,"z",[0,[15,"z"],1]]],[46,[53,[52,"ba",[16,[15,"r"],[15,"z"]]],[22,[30,[17,[15,"ba"],"disallowAllRegions"],["y",[17,[15,"ba"],"disallowedRegions"]]],[46,["x",[17,[15,"ba"],"redactFieldGroup"]]]]]]]]],[50,"o",[46,"q"],[52,"r",[8]],[22,[28,[15,"q"]],[46,[36,[15,"r"]]]],[52,"s",[2,[15,"q"],"split",[7,","]]],[53,[41,"t"],[3,"t",0],[63,[7,"t"],[23,[15,"t"],[17,[15,"s"],"length"]],[33,[15,"t"],[3,"t",[0,[15,"t"],1]]],[46,[53,[52,"u",[2,[16,[15,"s"],[15,"t"]],"trim",[7]]],[22,[28,[15,"u"]],[46,[6]]],[52,"v",[2,[15,"u"],"split",[7,"-"]]],[52,"w",[16,[15,"v"],0]],[52,"x",[39,[20,[17,[15,"v"],"length"],2],[15,"u"],[44]]],[22,[30,[28,[15,"w"]],[21,[17,[15,"w"],"length"],2]],[46,[6]]],[22,[1,[21,[15,"x"],[44]],[30,[23,[17,[15,"x"],"length"],4],[18,[17,[15,"x"],"length"],6]]],[46,[6]]],[43,[15,"r"],[15,"u"],true]]]]],[36,[15,"r"]]],[50,"p",[46,"q"],[22,[28,[17,[15,"q"],"settingsTable"]],[46,[36,[7]]]],[52,"r",[8]],[53,[41,"s"],[3,"s",0],[63,[7,"s"],[23,[15,"s"],[17,[17,[15,"q"],"settingsTable"],"length"]],[33,[15,"s"],[3,"s",[0,[15,"s"],1]]],[46,[53,[52,"t",[16,[17,[15,"q"],"settingsTable"],[15,"s"]]],[52,"u",[17,[15,"t"],"redactFieldGroup"]],[22,[28,[16,[15,"m"],[15,"u"]]],[46,[6]]],[43,[15,"r"],[15,"u"],[8,"redactFieldGroup",[15,"u"],"disallowAllRegions",false,"disallowedRegions",[8]]],[52,"v",[16,[15,"r"],[15,"u"]]],[22,[17,[15,"t"],"disallowAllRegions"],[46,[43,[15,"v"],"disallowAllRegions",true],[6]]],[43,[15,"v"],"disallowedRegions",["o",[17,[15,"t"],"disallowedRegions"]]]]]]],[36,[2,[15,"b"],"values",[7,[15,"r"]]]]],[52,"b",["require","Object"]],[52,"c",[13,[41,"$0"],[3,"$0",["require","internal.getFlags"]],["$0"]]],[52,"d",["require","getContainerVersion"]],[52,"e",["require","internal.getCountryCode"]],[52,"f",["require","internal.getRegionCode"]],[52,"g",["require","internal.setRemoteConfigParameter"]],[52,"h",[15,"__module_activities"]],[52,"i",[17,[15,"h"],"withRequestContext"]],[41,"j"],[41,"k"],[41,"l"],[52,"m",[8,"GOOGLE_SIGNALS",[7,[8,"name","allow_google_signals","value",false]],"DEVICE_AND_GEO",[7,[8,"name","geo_granularity","value",true],[8,"name","redact_device_info","value",true]]]],[36,[8,"applyRegionScopedSettings",[15,"n"],"extractRedactedLocations",[15,"p"]]]],[36,["a"]]]],["$0"]]]
 
]
,"entities":{
"__c":{"2":true,"4":true}
,
"__ccd_auto_redact":{"2":true,"4":true}
,
"__ccd_conversion_marking":{"2":true,"4":true}
,
"__ccd_em_page_view":{"2":true,"4":true}
,
"__ccd_em_scroll":{"2":true,"4":true}
,
"__ccd_ga_first":{"2":true,"4":true}
,
"__ccd_ga_last":{"2":true,"4":true}
,
"__ccd_ga_regscope":{"2":true,"4":true}
,
"__e":{"2":true,"4":true}
,
"__ogt_1p_data_v2":{"2":true}
,
"__ogt_auto_events":{"2":true}
,
"__ogt_dma":{"2":true,"4":true}
,
"__ogt_google_signals":{"2":true,"4":true}
,
"__ogt_ip_mark":{"2":true}
,
"__set_product_settings":{"2":true,"4":true}


}
,"blob":{"1":"4"}
,"permissions":{
"__c":{}
,
"__ccd_auto_redact":{}
,
"__ccd_conversion_marking":{}
,
"__ccd_em_page_view":{"listen_data_layer":{"accessType":"specific","allowedEvents":["gtm.historyChange-v2"]},"access_template_storage":{},"detect_history_change_events":{}}
,
"__ccd_em_scroll":{"listen_data_layer":{"accessType":"specific","allowedEvents":["gtm.scrollDepth"]},"process_dom_events":{"targets":[{"targetType":"window","eventName":"resize"},{"targetType":"window","eventName":"scroll"},{"targetType":"window","eventName":"scrollend"}]},"access_template_storage":{},"detect_scroll_events":{}}
,
"__ccd_ga_first":{}
,
"__ccd_ga_last":{}
,
"__ccd_ga_regscope":{"read_container_data":{}}
,
"__e":{"read_event_data":{"eventDataAccess":"specific","keyPatterns":["event"]}}
,
"__ogt_1p_data_v2":{"detect_user_provided_data":{"limitDataSources":true,"allowAutoDataSources":true,"allowManualDataSources":false,"allowCodeDataSources":false}}
,
"__ogt_auto_events":{}
,
"__ogt_dma":{"access_consent":{"consentTypes":[{"consentType":"ad_user_data","read":false,"write":true},{"consentType":"ad_storage","read":true,"write":false}]}}
,
"__ogt_google_signals":{"read_container_data":{}}
,
"__ogt_ip_mark":{}
,
"__set_product_settings":{}


}



,"security_groups":{
"google":[
"__c"
,
"__ccd_auto_redact"
,
"__ccd_conversion_marking"
,
"__ccd_em_page_view"
,
"__ccd_em_scroll"
,
"__ccd_ga_first"
,
"__ccd_ga_last"
,
"__ccd_ga_regscope"
,
"__e"
,
"__ogt_1p_data_v2"
,
"__ogt_auto_events"
,
"__ogt_dma"
,
"__ogt_google_signals"
,
"__ogt_ip_mark"
,
"__set_product_settings"

]


}



};




var ba,ca=function(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}},da=typeof Object.defineProperties=="function"?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a},ea=function(a){for(var b=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global],c=0;c<b.length;++c){var d=b[c];if(d&&d.Math==Math)return d}throw Error("Cannot find global object");
},fa=ea(this),ia=function(a,b){if(b)a:{for(var c=fa,d=a.split("."),e=0;e<d.length-1;e++){var f=d[e];if(!(f in c))break a;c=c[f]}var g=d[d.length-1],k=c[g],m=b(k);m!=k&&m!=null&&da(c,g,{configurable:!0,writable:!0,value:m})}};
ia("Symbol",function(a){if(a)return a;var b=function(f,g){this.j=f;da(this,"description",{configurable:!0,writable:!0,value:g})};b.prototype.toString=function(){return this.j};var c="jscomp_symbol_"+(Math.random()*1E9>>>0)+"_",d=0,e=function(f){if(this instanceof e)throw new TypeError("Symbol is not a constructor");return new b(c+(f||"")+"_"+d++,f)};return e});
ia("Symbol.iterator",function(a){if(a)return a;for(var b=Symbol("Symbol.iterator"),c="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),d=0;d<c.length;d++){var e=fa[c[d]];typeof e==="function"&&typeof e.prototype[b]!="function"&&da(e.prototype,b,{configurable:!0,writable:!0,value:function(){return ja(ca(this))}})}return b});
var ja=function(a){var b={next:a};b[Symbol.iterator]=function(){return this};return b},ka=function(a){return a.raw=a},na=function(a,b){a.raw=b;return a},oa=function(a){var b=typeof Symbol!="undefined"&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if(typeof a.length=="number")return{next:ca(a)};throw Error(String(a)+" is not an iterable or ArrayLike");},pa=function(a){for(var b,c=[];!(b=a.next()).done;)c.push(b.value);return c},qa=function(a){return a instanceof Array?a:pa(oa(a))},ra=
typeof Object.assign=="function"?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Object.prototype.hasOwnProperty.call(d,e)&&(a[e]=d[e])}return a};ia("Object.assign",function(a){return a||ra});var sa=typeof Object.create=="function"?Object.create:function(a){var b=function(){};b.prototype=a;return new b},ta;
if(typeof Object.setPrototypeOf=="function")ta=Object.setPrototypeOf;else{var ua;a:{var va={a:!0},wa={};try{wa.__proto__=va;ua=wa.a;break a}catch(a){}ua=!1}ta=ua?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}
var xa=ta,za=function(a,b){a.prototype=sa(b.prototype);a.prototype.constructor=a;if(xa)xa(a,b);else for(var c in b)if(c!="prototype")if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.bo=b.prototype},Aa=function(){this.K=!1;this.D=null;this.xb=void 0;this.j=1;this.Ca=this.O=0;this.H=null},Ba=function(a){if(a.K)throw new TypeError("Generator is already running");a.K=!0};Aa.prototype.W=function(a){this.xb=a};
var Ca=function(a,b){a.H={Sj:b,mm:!0};a.j=a.O||a.Ca};Aa.prototype.return=function(a){this.H={return:a};this.j=this.Ca};
var Da=function(a,b){a.j=4;return{value:b}},Ea=function(a){a.O=0;var b=a.H.Sj;a.H=null;return b},Ga=function(a){this.j=new Aa;this.D=a},Ja=function(a,b){Ba(a.j);var c=a.j.D;if(c)return Ha(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.j.return);a.j.return(b);return Ia(a)},Ha=function(a,b,c,d){try{var e=b.call(a.j.D,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.j.K=!1,e;var f=e.value}catch(g){return a.j.D=null,Ca(a.j,
g),Ia(a)}a.j.D=null;d.call(a.j,f);return Ia(a)},Ia=function(a){for(;a.j.j;)try{var b=a.D(a.j);if(b)return a.j.K=!1,{value:b.value,done:!1}}catch(d){a.j.xb=void 0,Ca(a.j,d)}a.j.K=!1;if(a.j.H){var c=a.j.H;a.j.H=null;if(c.mm)throw c.Sj;return{value:c.return,done:!0}}return{value:void 0,done:!0}},Ka=function(a){this.next=function(b){var c;Ba(a.j);a.j.D?c=Ha(a,a.j.D.next,b,a.j.W):(a.j.W(b),c=Ia(a));return c};this.throw=function(b){var c;Ba(a.j);a.j.D?c=Ha(a,a.j.D["throw"],b,a.j.W):(Ca(a.j,b),c=Ia(a));
return c};this.return=function(b){return Ja(a,b)};this[Symbol.iterator]=function(){return this}},La=function(a){function b(d){return a.next(d)}function c(d){return a.throw(d)}new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}f(a.next())})},Ma=function(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b};/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var Oa=this||self,Pa=function(a){return a};var Qa=function(a,b){this.type=a;this.data=b};var Ra=function(){this.j={};this.H={}};ba=Ra.prototype;ba.get=function(a){return this.j["dust."+a]};ba.set=function(a,b){a="dust."+a;this.H.hasOwnProperty(a)||(this.j[a]=b)};ba.Zh=function(a,b){this.set(a,b);this.H["dust."+a]=!0};ba.has=function(a){return this.j.hasOwnProperty("dust."+a)};ba.Hf=function(a){a="dust."+a;this.H.hasOwnProperty(a)||delete this.j[a]};var Ta=function(){};Ta.prototype.reset=function(){};var Ua=function(a,b){this.O=a;this.parent=b;this.j=this.D=void 0;this.K=!1;this.H=function(c,d,e){return c.apply(d,e)};this.values=new Ra};Ua.prototype.add=function(a,b){Va(this,a,b,!1)};var Va=function(a,b,c,d){a.K||(d?a.values.Zh(b,c):a.values.set(b,c))};Ua.prototype.set=function(a,b){this.K||(!this.values.has(a)&&this.parent&&this.parent.has(a)?this.parent.set(a,b):this.values.set(a,b))};Ua.prototype.get=function(a){return this.values.has(a)?this.values.get(a):this.parent?this.parent.get(a):void 0};
Ua.prototype.has=function(a){return!!this.values.has(a)||!(!this.parent||!this.parent.has(a))};var Wa=function(a){var b=new Ua(a.O,a);a.D&&(b.D=a.D);b.H=a.H;b.j=a.j;return b};Ua.prototype.sd=function(){return this.O};Ua.prototype.Ma=function(){this.K=!0};function Xa(a,b){for(var c,d=0;d<b.length&&!(c=Ya(a,b[d]),c instanceof Qa);d++);return c}function Ya(a,b){try{var c=a.get(String(b[0]));if(!c||typeof c.invoke!=="function")throw Error("Attempting to execute non-function "+b[0]+".");return c.invoke.apply(c,[a].concat(b.slice(1)))}catch(e){var d=a.D;d&&d(e,b.context?{id:b[0],line:b.context.line}:null);throw e;}};var Za=function(){this.D=new Ta;this.j=new Ua(this.D)};ba=Za.prototype;ba.sd=function(){return this.D};ba.execute=function(a){var b=Array.prototype.slice.call(arguments,0);return this.Xh(b)};ba.Xh=function(){for(var a,b=0;b<arguments.length;b++)a=Ya(this.j,arguments[b]);return a};ba.Xk=function(a){var b=Wa(this.j);b.j=a;for(var c,d=1;d<arguments.length;d++)c=Ya(b,arguments[d]);return c};ba.Ma=function(){this.j.Ma()};var $a=function(){Ra.call(this);this.D=!1};za($a,Ra);var ab=function(a,b){var c=[],d;for(d in a.j)if(a.j.hasOwnProperty(d))switch(d=d.substr(5),b){case 1:c.push(d);break;case 2:c.push(a.get(d));break;case 3:c.push([d,a.get(d)])}return c};$a.prototype.set=function(a,b){this.D||Ra.prototype.set.call(this,a,b)};$a.prototype.Zh=function(a,b){this.D||Ra.prototype.Zh.call(this,a,b)};$a.prototype.Hf=function(a){this.D||Ra.prototype.Hf.call(this,a)};$a.prototype.Ma=function(){this.D=!0};/*
 jQuery (c) 2005, 2012 jQuery Foundation, Inc. jquery.org/license.
*/
var cb=/\[object (Boolean|Number|String|Function|Array|Date|RegExp)\]/,db=function(a){if(a==null)return String(a);var b=cb.exec(Object.prototype.toString.call(Object(a)));return b?b[1].toLowerCase():"object"},eb=function(a,b){return Object.prototype.hasOwnProperty.call(Object(a),b)},fb=function(a){if(!a||db(a)!="object"||a.nodeType||a==a.window)return!1;try{if(a.constructor&&!eb(a,"constructor")&&!eb(a.constructor.prototype,"isPrototypeOf"))return!1}catch(c){return!1}for(var b in a);return b===void 0||
eb(a,b)},h=function(a,b){var c=b||(db(a)=="array"?[]:{}),d;for(d in a)if(eb(a,d)){var e=a[d];db(e)=="array"?(db(c[d])!="array"&&(c[d]=[]),c[d]=h(e,c[d])):fb(e)?(fb(c[d])||(c[d]={}),c[d]=h(e,c[d])):c[d]=e}return c};function gb(a){if(a==void 0||Array.isArray(a)||fb(a))return!0;switch(typeof a){case "boolean":case "number":case "string":case "function":return!0}return!1}function hb(a){return typeof a==="number"&&a>=0&&isFinite(a)&&a%1===0||typeof a==="string"&&a[0]!=="-"&&a===""+parseInt(a)};var ib=function(a){this.j=[];this.H=!1;this.D=new $a;a=a||[];for(var b in a)a.hasOwnProperty(b)&&(hb(b)?this.j[Number(b)]=a[Number(b)]:this.D.set(b,a[b]))};ba=ib.prototype;ba.toString=function(a){if(a&&a.indexOf(this)>=0)return"";for(var b=[],c=0;c<this.j.length;c++){var d=this.j[c];d===null||d===void 0?b.push(""):d instanceof ib?(a=a||[],a.push(this),b.push(d.toString(a)),a.pop()):b.push(String(d))}return b.join(",")};
ba.set=function(a,b){if(!this.H)if(a==="length"){if(!hb(b))throw Error("RangeError: Length property must be a valid integer.");this.j.length=Number(b)}else hb(a)?this.j[Number(a)]=b:this.D.set(a,b)};ba.get=function(a){return a==="length"?this.length():hb(a)?this.j[Number(a)]:this.D.get(a)};ba.length=function(){return this.j.length};ba.Qb=function(){for(var a=ab(this.D,1),b=0;b<this.j.length;b++)a.push(b+"");return new ib(a)};var jb=function(a,b){hb(b)?delete a.j[Number(b)]:a.D.Hf(b)};ba=ib.prototype;
ba.pop=function(){return this.j.pop()};ba.push=function(){return this.j.push.apply(this.j,Array.prototype.slice.call(arguments))};ba.shift=function(){return this.j.shift()};ba.splice=function(a,b){return new ib(this.j.splice.apply(this.j,arguments))};ba.unshift=function(){return this.j.unshift.apply(this.j,Array.prototype.slice.call(arguments))};ba.has=function(a){return hb(a)&&this.j.hasOwnProperty(a)||this.D.has(a)};ba.Ma=function(){this.H=!0;Object.freeze(this.j);this.D.Ma()};
function kb(a){for(var b=[],c=0;c<a.length();c++)a.has(c)&&(b[c]=a.get(c));return b};var lb=function(){$a.call(this)};za(lb,$a);lb.prototype.Qb=function(){return new ib(ab(this,1))};var mb=function(a){for(var b=ab(a,3),c=new ib,d=0;d<b.length;d++){var e=new ib(b[d]);c.push(e)}return c};function nb(){for(var a=ob,b={},c=0;c<a.length;++c)b[a[c]]=c;return b}function pb(){var a="ABCDEFGHIJKLMNOPQRSTUVWXYZ";a+=a.toLowerCase()+"0123456789-_";return a+"."}var ob,qb;function rb(a){ob=ob||pb();qb=qb||nb();for(var b=[],c=0;c<a.length;c+=3){var d=c+1<a.length,e=c+2<a.length,f=a.charCodeAt(c),g=d?a.charCodeAt(c+1):0,k=e?a.charCodeAt(c+2):0,m=f>>2,n=(f&3)<<4|g>>4,p=(g&15)<<2|k>>6,q=k&63;e||(q=64,d||(p=64));b.push(ob[m],ob[n],ob[p],ob[q])}return b.join("")}
function sb(a){function b(m){for(;d<a.length;){var n=a.charAt(d++),p=qb[n];if(p!=null)return p;if(!/^[\s\xa0]*$/.test(n))throw Error("Unknown base64 encoding at char: "+n);}return m}ob=ob||pb();qb=qb||nb();for(var c="",d=0;;){var e=b(-1),f=b(0),g=b(64),k=b(64);if(k===64&&e===-1)return c;c+=String.fromCharCode(e<<2|f>>4);g!==64&&(c+=String.fromCharCode(f<<4&240|g>>2),k!==64&&(c+=String.fromCharCode(g<<6&192|k)))}};var tb={};function ub(a,b){tb[a]=tb[a]||[];tb[a][b]=!0}function vb(a){var b=tb[a];if(!b||b.length===0)return"";for(var c=[],d=0,e=0;e<b.length;e++)e%8===0&&e>0&&(c.push(String.fromCharCode(d)),d=0),b[e]&&(d|=1<<e%8);d>0&&c.push(String.fromCharCode(d));return rb(c.join("")).replace(/\.+$/,"")}function wb(){for(var a=[],b=tb.fdr||[],c=0;c<b.length;c++)b[c]&&a.push(c);return a.length>0?a:void 0};var xb=[],yb={};function zb(a){return xb[a]===void 0?!1:xb[a]};function Ab(){}function Bb(a){return typeof a==="function"}function l(a){return typeof a==="string"}function Cb(a){return typeof a==="number"&&!isNaN(a)}function Db(a){return Array.isArray(a)?a:[a]}function Eb(a,b){if(a&&Array.isArray(a))for(var c=0;c<a.length;c++)if(a[c]&&b(a[c]))return a[c]}function Fb(a,b){if(!Cb(a)||!Cb(b)||a>b)a=0,b=2147483647;return Math.floor(Math.random()*(b-a+1)+a)}
function Gb(a,b){for(var c=new Hb,d=0;d<a.length;d++)c.set(a[d],!0);for(var e=0;e<b.length;e++)if(c.get(b[e]))return!0;return!1}function z(a,b){for(var c in a)Object.prototype.hasOwnProperty.call(a,c)&&b(c,a[c])}function Ib(a){return!!a&&(Object.prototype.toString.call(a)==="[object Arguments]"||Object.prototype.hasOwnProperty.call(a,"callee"))}function Jb(a){return Math.round(Number(a))||0}function Kb(a){return"false"===String(a).toLowerCase()?!1:!!a}
function Lb(a){var b=[];if(Array.isArray(a))for(var c=0;c<a.length;c++)b.push(String(a[c]));return b}function Mb(a){return a?a.replace(/^\s+|\s+$/g,""):""}function Nb(){return new Date(Date.now())}function Ob(){return Nb().getTime()}var Hb=function(){this.prefix="gtm.";this.values={}};Hb.prototype.set=function(a,b){this.values[this.prefix+a]=b};Hb.prototype.get=function(a){return this.values[this.prefix+a]};function Pb(a,b,c){return a&&a.hasOwnProperty(b)?a[b]:c}
function Qb(a){var b=a;return function(){if(b){var c=b;b=void 0;try{c()}catch(d){}}}}function Rb(a,b){for(var c in b)b.hasOwnProperty(c)&&(a[c]=b[c])}function Sb(a,b){for(var c=[],d=0;d<a.length;d++)c.push(a[d]),c.push.apply(c,b[a[d]]||[]);return c}function Tb(a,b){return a.length>=b.length&&a.substring(0,b.length)===b}function Ub(a,b){return a.length>=b.length&&a.substring(a.length-b.length,a.length)===b}
function Vb(a,b){var c=G;b=b||[];for(var d=c,e=0;e<a.length-1;e++){if(!d.hasOwnProperty(a[e]))return;d=d[a[e]];if(b.indexOf(d)>=0)return}return d}function Wb(a,b){for(var c={},d=c,e=a.split("."),f=0;f<e.length-1;f++)d=d[e[f]]={};d[e[e.length-1]]=b;return c}var Xb=/^\w{1,9}$/;function Yb(a,b){a=a||{};b=b||",";var c=[];z(a,function(d,e){Xb.test(d)&&e&&c.push(d)});return c.join(b)}function Zb(a,b){function c(){e&&++d===b&&(e(),e=null,c.done=!0)}var d=0,e=a;c.done=!1;return c}
function $b(a){if(!a)return a;var b=a;if(zb(3))try{b=decodeURIComponent(a)}catch(d){}var c=b.split(",");return c.length===2&&c[0]===c[1]?c[0]:a};var ac,bc=function(){if(ac===void 0){var a=null,b=Oa.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Pa,createScript:Pa,createScriptURL:Pa})}catch(c){Oa.console&&Oa.console.error(c.message)}ac=a}else ac=a}return ac};var cc=function(a){this.j=a};cc.prototype.toString=function(){return this.j+""};var dc=function(a){return a instanceof cc&&a.constructor===cc?a.j:"type_error:TrustedResourceUrl"},ec={},fc=function(a){var b=a,c=bc(),d=c?c.createScriptURL(b):b;return new cc(d,ec)};/*

 SPDX-License-Identifier: Apache-2.0
*/
var gc=ka([""]),hc=na(["\x00"],["\\0"]),ic=na(["\n"],["\\n"]),jc=na(["\x00"],["\\u0000"]);function kc(a){return a.toString().indexOf("`")===-1}kc(function(a){return a(gc)})||kc(function(a){return a(hc)})||kc(function(a){return a(ic)})||kc(function(a){return a(jc)});var lc=function(a){this.j=a};lc.prototype.toString=function(){return this.j};var mc=new lc("about:invalid#zClosurez");var nc=function(a){this.wm=a};function oc(a){return new nc(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}var pc=[oc("data"),oc("http"),oc("https"),oc("mailto"),oc("ftp"),new nc(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function qc(a,b){b=b===void 0?pc:b;if(a instanceof lc)return a;for(var c=0;c<b.length;++c){var d=b[c];if(d instanceof nc&&d.wm(a))return new lc(a)}}function rc(a){var b;b=b===void 0?pc:b;return qc(a,b)||mc}var sc=/^\s*(?!javascript:)(?:[\w+.-]+:|[^:/?#]*(?:[/?#]|$))/i;
function tc(a){var b;if(a instanceof lc)if(a instanceof lc)b=a.j;else throw Error("");else b=sc.test(a)?a:void 0;return b};var vc=function(){this.j=uc[0].toLowerCase()};vc.prototype.toString=function(){return this.j};var wc=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if(typeof a==="string")return typeof b!=="string"||b.length!=1?-1:a.indexOf(b,0);for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1};var xc={},yc=function(a){this.j=a};yc.prototype.toString=function(){return this.j.toString()};function zc(a,b){var c=[new vc];if(c.length===0)throw Error("");var d=c.map(function(f){var g;if(f instanceof vc)g=f.j;else throw Error("");return g}),e=b.toLowerCase();if(d.every(function(f){return e.indexOf(f)!==0}))throw Error('Attribute "'+b+'" does not match any of the allowed prefixes.');a.setAttribute(b,"true")};function Ac(a,b){var c=tc(b);c!==void 0&&(a.action=c)};"ARTICLE SECTION NAV ASIDE H1 H2 H3 H4 H5 H6 HEADER FOOTER ADDRESS P HR PRE BLOCKQUOTE OL UL LH LI DL DT DD FIGURE FIGCAPTION MAIN DIV EM STRONG SMALL S CITE Q DFN ABBR RUBY RB RT RTC RP DATA TIME CODE VAR SAMP KBD SUB SUP I B U MARK BDI BDO SPAN BR WBR NOBR INS DEL PICTURE PARAM TRACK MAP TABLE CAPTION COLGROUP COL TBODY THEAD TFOOT TR TD TH SELECT DATALIST OPTGROUP OPTION OUTPUT PROGRESS METER FIELDSET LEGEND DETAILS SUMMARY MENU DIALOG SLOT CANVAS FONT CENTER ACRONYM BASEFONT BIG DIR HGROUP STRIKE TT".split(" ").concat(["BUTTON",
"INPUT"]);function Bc(a){return a===null?"null":a===void 0?"undefined":a};var G=window,H=document,Cc=navigator,Dc=function(){var a;try{a=Cc.serviceWorker}catch(b){return}return a},Ec=H.currentScript,Fc=Ec&&Ec.src,Gc=function(a,b){var c=G[a];G[a]=c===void 0?b:c;return G[a]};function Hc(a){return(Cc.userAgent||"").indexOf(a)!==-1}var Ic={async:1,nonce:1,onerror:1,onload:1,src:1,type:1},Jc={onload:1,src:1,width:1,height:1,style:1};function Kc(a,b,c){b&&z(b,function(d,e){d=d.toLowerCase();c.hasOwnProperty(d)||a.setAttribute(d,e)})}
var Lc=function(a,b,c,d,e){var f=H.createElement("script");Kc(f,d,Ic);f.type="text/javascript";f.async=d&&d.async===!1?!1:!0;var g;g=fc(Bc(a));f.src=dc(g);var k,m,n,p=(n=(m=(f.ownerDocument&&f.ownerDocument.defaultView||window).document).querySelector)==null?void 0:n.call(m,"script[nonce]");(k=p?p.nonce||p.getAttribute("nonce")||"":"")&&f.setAttribute("nonce",k);b&&(f.onload=b);c&&(f.onerror=c);if(e)e.appendChild(f);else{var q=H.getElementsByTagName("script")[0]||H.body||H.head;q.parentNode.insertBefore(f,
q)}return f},Mc=function(){if(Fc){var a=Fc.toLowerCase();if(a.indexOf("https://")===0)return 2;if(a.indexOf("http://")===0)return 3}return 1},Nc=function(a,b,c,d,e){var f;f=f===void 0?!0:f;var g=e,k=!1;g||(g=H.createElement("iframe"),k=!0);Kc(g,c,Jc);d&&z(d,function(n,p){g.dataset[n]=p});f&&(g.height="0",g.width="0",g.style.display="none",g.style.visibility="hidden");a!==void 0&&(g.src=a);if(k){var m=H.body&&H.body.lastChild||H.body||H.head;m.parentNode.insertBefore(g,m)}b&&(g.onload=b);return g},
Oc=function(a,b,c,d){var e=new Image(1,1);Kc(e,d,{});e.onload=function(){e.onload=null;b&&b()};e.onerror=function(){e.onerror=null;c&&c()};e.src=a;return e},Pc=function(a,b,c,d){a.addEventListener?a.addEventListener(b,c,!!d):a.attachEvent&&a.attachEvent("on"+b,c)},Qc=function(a,b,c){a.removeEventListener?a.removeEventListener(b,c,!1):a.detachEvent&&a.detachEvent("on"+b,c)},I=function(a){G.setTimeout(a,0)},Rc=function(a,b){return a&&b&&a.attributes&&a.attributes[b]?a.attributes[b].value:null},Sc=function(a){function b(e){e&&
e!=" "&&(e=e.replace(/^[\s\xa0]+|[\s\xa0]+$/g,""));e&&e!=" "&&(e=e.replace(/^[\s\xa0]+|[\s\xa0]+$/g,""));e&&(e=e.replace(/(\xa0+|\s{2,}|\n|\r\t)/g," "));return e}var c=b(a.innerText||a.textContent||"");if(zb(10)){var d=b(a.textContent||"");ub("TAGGING",26);d!==c&&ub("TAGGING",25)}return c},Tc=function(a){var b=H.createElement("div"),c=b,d,e=Bc("A<div>"+a+"</div>"),f=bc(),g=f?f.createHTML(e):e;d=new yc(g,xc);if(c.nodeType===1){var k=c.tagName;if(k==="SCRIPT"||k==="STYLE")throw Error("");}c.innerHTML=
d instanceof yc&&d.constructor===yc?d.j:"type_error:SafeHtml";b=b.lastChild;for(var m=[];b.firstChild;)m.push(b.removeChild(b.firstChild));return m},Uc=function(a,b,c){c=c||100;for(var d={},e=0;e<b.length;e++)d[b[e]]=!0;for(var f=a,g=0;f&&g<=c;g++){if(d[String(f.tagName).toLowerCase()])return f;f=f.parentElement}return null},Vc=function(a){var b;try{b=Cc.sendBeacon&&Cc.sendBeacon(a)}catch(c){ub("TAGGING",15)}b||Oc(a)},Wc=function(a,b){try{return Cc.sendBeacon(a,b)}catch(c){ub("TAGGING",15)}return!1},
Xc={cache:"no-store",credentials:"include",keepalive:!0,method:"POST",mode:"no-cors",redirect:"follow"},Zc=function(a,b,c){if(Yc()){var d=Object.assign({},Xc);b&&(d.body=b);c&&(c.attributionReporting&&(d.attributionReporting=c.attributionReporting),c.browsingTopics&&(d.browsingTopics=c.browsingTopics));try{var e=G.fetch(a,d);e&&e.catch(Ab);return!0}catch(f){}}if(c&&c.noFallback)return!1;if(b)return Wc(a,b);Vc(a);return!0},Yc=function(){return typeof G.fetch==="function"},$c=function(a,b){var c=a[b];
c&&typeof c.animVal==="string"&&(c=c.animVal);return c},ad=function(){var a=G.performance;if(a&&Bb(a.now))return a.now()},bd=function(){return G.performance||void 0};function cd(a,b){return this.evaluate(a)&&this.evaluate(b)}function dd(a,b){return this.evaluate(a)===this.evaluate(b)}function ed(a,b){return this.evaluate(a)||this.evaluate(b)}function fd(a,b){a=this.evaluate(a);b=this.evaluate(b);return String(a).indexOf(String(b))>-1}function gd(a,b){var c=String(this.evaluate(a)),d=String(this.evaluate(b));return c.substring(0,d.length)===d}
function hd(a,b){a=this.evaluate(a);b=this.evaluate(b);switch(a){case "pageLocation":var c=G.location.href;b instanceof lb&&b.get("stripProtocol")&&(c=c.replace(/^https?:\/\//,""));return c}};var id=function(a,b){$a.call(this);this.bk=a;this.uh=b};za(id,$a);ba=id.prototype;ba.toString=function(){return this.bk};ba.getName=function(){return this.bk};ba.Qb=function(){return new ib(ab(this,1))};ba.invoke=function(a){return this.uh.apply(new jd(this,a),Array.prototype.slice.call(arguments,1))};ba.ib=function(a){try{return this.invoke.apply(this,Array.prototype.slice.call(arguments,0))}catch(b){}};var jd=function(a,b){this.uh=a;this.F=b};
jd.prototype.evaluate=function(a){var b=this.F;return Array.isArray(a)?Ya(b,a):a};jd.prototype.getName=function(){return this.uh.getName()};jd.prototype.sd=function(){return this.F.sd()};var kd=function(){this.map=new Map};kd.prototype.set=function(a,b){this.map.set(a,b)};kd.prototype.get=function(a){return this.map.get(a)};var ld=function(){this.keys=[];this.values=[]};ld.prototype.set=function(a,b){this.keys.push(a);this.values.push(b)};ld.prototype.get=function(a){var b=this.keys.indexOf(a);if(b>-1)return this.values[b]};function md(){try{return Map?new kd:new ld}catch(a){return new ld}};var nd=function(a){if(a instanceof nd)return a;if(gb(a))throw Error("Type of given value has an equivalent Pixie type.");this.value=a};nd.prototype.getValue=function(){return this.value};nd.prototype.toString=function(){return String(this.value)};var pd=function(a){$a.call(this);this.promise=a;this.set("then",od(this));this.set("catch",od(this,!0));this.set("finally",od(this,!1,!0))};za(pd,lb);var od=function(a,b,c){b=b===void 0?!1:b;c=c===void 0?!1:c;return new id("",function(d,e){b&&(e=d,d=void 0);c&&(e=d);d instanceof id||(d=void 0);e instanceof id||(e=void 0);var f=Wa(this.F),g=function(m){return function(n){return c?(m.invoke(f),a.promise):m.invoke(f,n)}},k=a.promise.then(d&&g(d),e&&g(e));return new pd(k)})};function J(a,b,c){var d=md(),e=function(g,k){for(var m=ab(g,1),n=0;n<m.length;n++)k[m[n]]=f(g.get(m[n]))},f=function(g){var k=d.get(g);if(k)return k;if(g instanceof ib){var m=[];d.set(g,m);for(var n=g.Qb(),p=0;p<n.length();p++)m[n.get(p)]=f(g.get(n.get(p)));return m}if(g instanceof pd)return g.promise;if(g instanceof lb){var q={};d.set(g,q);e(g,q);return q}if(g instanceof id){var r=function(){for(var u=Array.prototype.slice.call(arguments,0),v=0;v<u.length;v++)u[v]=qd(u[v],b,c);var w=new Ua(b?b.sd():
new Ta);b&&(w.j=b.j);return f(g.invoke.apply(g,[w].concat(u)))};d.set(g,r);e(g,r);return r}var t=!1;switch(c){case 1:t=!0;break;case 2:t=!1;break;case 3:t=!1;break;default:}if(g instanceof nd&&t)return g.getValue();switch(typeof g){case "boolean":case "number":case "string":case "undefined":return g;case "object":if(g===null)return null}};return f(a)}
function qd(a,b,c){var d=md(),e=function(g,k){for(var m in g)g.hasOwnProperty(m)&&k.set(m,f(g[m]))},f=function(g){var k=d.get(g);if(k)return k;if(Array.isArray(g)||Ib(g)){var m=new ib([]);d.set(g,m);for(var n in g)g.hasOwnProperty(n)&&m.set(n,f(g[n]));return m}if(fb(g)){var p=new lb;d.set(g,p);e(g,p);return p}if(typeof g==="function"){var q=new id("",function(){for(var x=Array.prototype.slice.call(arguments,0),y=0;y<x.length;y++)x[y]=J(this.evaluate(x[y]),b,c);return f((0,this.F.H)(g,g,x))});d.set(g,
q);e(g,q);return q}var v=typeof g;if(g===null||v==="string"||v==="number"||v==="boolean")return g;var w=!1;switch(c){case 1:w=
!0;break;case 2:w=!1;break;default:}if(g!==void 0&&w)return new nd(g)};return f(a)};function rd(){var a=!1;return a};var sd={supportedMethods:"concat every filter forEach hasOwnProperty indexOf join lastIndexOf map pop push reduce reduceRight reverse shift slice some sort splice unshift toString".split(" "),concat:function(a){for(var b=[],c=0;c<this.length();c++)b.push(this.get(c));for(var d=1;d<arguments.length;d++)if(arguments[d]instanceof ib)for(var e=arguments[d],f=0;f<e.length();f++)b.push(e.get(f));else b.push(arguments[d]);return new ib(b)},every:function(a,b){for(var c=this.length(),d=0;d<this.length()&&
d<c;d++)if(this.has(d)&&!b.invoke(a,this.get(d),d,this))return!1;return!0},filter:function(a,b){for(var c=this.length(),d=[],e=0;e<this.length()&&e<c;e++)this.has(e)&&b.invoke(a,this.get(e),e,this)&&d.push(this.get(e));return new ib(d)},forEach:function(a,b){for(var c=this.length(),d=0;d<this.length()&&d<c;d++)this.has(d)&&b.invoke(a,this.get(d),d,this)},hasOwnProperty:function(a,b){return this.has(b)},indexOf:function(a,b,c){var d=this.length(),e=c===void 0?0:Number(c);e<0&&(e=Math.max(d+e,0));for(var f=
e;f<d;f++)if(this.has(f)&&this.get(f)===b)return f;return-1},join:function(a,b){for(var c=[],d=0;d<this.length();d++)c.push(this.get(d));return c.join(b)},lastIndexOf:function(a,b,c){var d=this.length(),e=d-1;c!==void 0&&(e=c<0?d+c:Math.min(c,e));for(var f=e;f>=0;f--)if(this.has(f)&&this.get(f)===b)return f;return-1},map:function(a,b){for(var c=this.length(),d=[],e=0;e<this.length()&&e<c;e++)this.has(e)&&(d[e]=b.invoke(a,this.get(e),e,this));return new ib(d)},pop:function(){return this.pop()},push:function(a){return this.push.apply(this,
Array.prototype.slice.call(arguments,1))},reduce:function(a,b,c){var d=this.length(),e,f=0;if(c!==void 0)e=c;else{if(d===0)throw Error("TypeError: Reduce on List with no elements.");for(var g=0;g<d;g++)if(this.has(g)){e=this.get(g);f=g+1;break}if(g===d)throw Error("TypeError: Reduce on List with no elements.");}for(var k=f;k<d;k++)this.has(k)&&(e=b.invoke(a,e,this.get(k),k,this));return e},reduceRight:function(a,b,c){var d=this.length(),e,f=d-1;if(c!==void 0)e=c;else{if(d===0)throw Error("TypeError: ReduceRight on List with no elements.");
for(var g=1;g<=d;g++)if(this.has(d-g)){e=this.get(d-g);f=d-(g+1);break}if(g>d)throw Error("TypeError: ReduceRight on List with no elements.");}for(var k=f;k>=0;k--)this.has(k)&&(e=b.invoke(a,e,this.get(k),k,this));return e},reverse:function(){for(var a=kb(this),b=a.length-1,c=0;b>=0;b--,c++)a.hasOwnProperty(b)?this.set(c,a[b]):jb(this,c);return this},shift:function(){return this.shift()},slice:function(a,b,c){var d=this.length();b===void 0&&(b=0);b=b<0?Math.max(d+b,0):Math.min(b,d);c=c===void 0?d:
c<0?Math.max(d+c,0):Math.min(c,d);c=Math.max(b,c);for(var e=[],f=b;f<c;f++)e.push(this.get(f));return new ib(e)},some:function(a,b){for(var c=this.length(),d=0;d<this.length()&&d<c;d++)if(this.has(d)&&b.invoke(a,this.get(d),d,this))return!0;return!1},sort:function(a,b){var c=kb(this);b===void 0?c.sort():c.sort(function(e,f){return Number(b.invoke(a,e,f))});for(var d=0;d<c.length;d++)c.hasOwnProperty(d)?this.set(d,c[d]):jb(this,d);return this},splice:function(a,b,c){return this.splice.apply(this,Array.prototype.splice.call(arguments,
1,arguments.length-1))},toString:function(){return this.toString()},unshift:function(a){return this.unshift.apply(this,Array.prototype.slice.call(arguments,1))}};var td=function(a){var b;b=Error.call(this,a);this.message=b.message;"stack"in b&&(this.stack=b.stack)};za(td,Error);var wd={charAt:1,concat:1,indexOf:1,lastIndexOf:1,match:1,replace:1,search:1,slice:1,split:1,substring:1,toLowerCase:1,toLocaleLowerCase:1,toString:1,toUpperCase:1,toLocaleUpperCase:1,trim:1},xd=new Qa("break"),yd=new Qa("continue");function zd(a,b){return this.evaluate(a)+this.evaluate(b)}function Ad(a,b){return this.evaluate(a)&&this.evaluate(b)}
function Bd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);if(!(c instanceof ib))throw Error("Error: Non-List argument given to Apply instruction.");if(a===null||a===void 0){var d="TypeError: Can't read property "+b+" of "+a+".";if(rd())throw new td(d);throw Error(d);}var e=typeof a==="number";if(typeof a==="boolean"||e){if(b==="toString"){if(e&&c.length()){var f=J(c.get(0));try{return a.toString(f)}catch(y){}}return a.toString()}var g="TypeError: "+a+"."+b+" is not a function.";
if(rd())throw new td(g);throw Error(g);}if(typeof a==="string"){if(wd.hasOwnProperty(b)){var k=2;k=1;var m=J(c,void 0,k);return qd(a[b].apply(a,m),this.F)}var n="TypeError: "+b+" is not a function";if(rd())throw new td(n);throw Error(n);}if(a instanceof ib){if(a.has(b)){var p=a.get(b);if(p instanceof id){var q=kb(c);q.unshift(this.F);return p.invoke.apply(p,q)}var r=
"TypeError: "+b+" is not a function";if(rd())throw new td(r);throw Error(r);}if(sd.supportedMethods.indexOf(b)>=0){var t=kb(c);t.unshift(this.F);return sd[b].apply(a,t)}}if(a instanceof id||a instanceof lb){if(a.has(b)){var u=a.get(b);if(u instanceof id){var v=kb(c);v.unshift(this.F);return u.invoke.apply(u,v)}var w="TypeError: "+b+" is not a function";if(rd())throw new td(w);throw Error(w);}if(b==="toString")return a instanceof id?a.getName():a.toString();if(b==="hasOwnProperty")return a.has.apply(a,
kb(c))}if(a instanceof nd&&b==="toString")return a.toString();var x="TypeError: Object has no '"+b+"' property.";if(rd())throw new td(x);throw Error(x);}function Cd(a,b){a=this.evaluate(a);if(typeof a!=="string")throw Error("Invalid key name given for assignment.");var c=this.F;if(!c.has(a))throw Error("Attempting to assign to undefined value "+b);var d=this.evaluate(b);c.set(a,d);return d}function Dd(){var a=Wa(this.F),b=Xa(a,Array.prototype.slice.apply(arguments));if(b instanceof Qa)return b}
function Ed(){return xd}function Fd(a){for(var b=this.evaluate(a),c=0;c<b.length;c++){var d=this.evaluate(b[c]);if(d instanceof Qa)return d}}function Gd(){for(var a=this.F,b=0;b<arguments.length-1;b+=2){var c=arguments[b];if(typeof c==="string"){var d=this.evaluate(arguments[b+1]);Va(a,c,d,!0)}}}function Hd(){return yd}function Id(a,b){return new Qa(a,this.evaluate(b))}
function Jd(a,b){var c=new ib;b=this.evaluate(b);for(var d=0;d<b.length;d++)c.push(b[d]);var e=[51,a,c].concat(Array.prototype.splice.call(arguments,2,arguments.length-2));this.F.add(a,this.evaluate(e))}function Kd(a,b){return this.evaluate(a)/this.evaluate(b)}function Ld(a,b){a=this.evaluate(a);b=this.evaluate(b);var c=a instanceof nd,d=b instanceof nd;return c||d?c&&d?a.getValue()===b.getValue():!1:a==b}function Md(){for(var a,b=0;b<arguments.length;b++)a=this.evaluate(arguments[b]);return a}
function Nd(a,b,c,d){for(var e=0;e<b();e++){var f=a(c(e)),g=Xa(f,d);if(g instanceof Qa){if(g.type==="break")break;if(g.type==="return")return g}}}function Od(a,b,c){if(typeof b==="string")return Nd(a,function(){return b.length},function(f){return f},c);if(b instanceof lb||b instanceof ib||b instanceof id){var d=b.Qb(),e=d.length();return Nd(a,function(){return e},function(f){return d.get(f)},c)}}
function Pd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Od(function(e){d.set(a,e);return d},b,c)}function Qd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Od(function(e){var f=Wa(d);Va(f,a,e,!0);return f},b,c)}function Rd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Od(function(e){var f=Wa(d);f.add(a,e);return f},b,c)}
function Sd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Td(function(e){d.set(a,e);return d},b,c)}function Ud(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Td(function(e){var f=Wa(d);Va(f,a,e,!0);return f},b,c)}function Vd(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);var d=this.F;return Td(function(e){var f=Wa(d);f.add(a,e);return f},b,c)}
function Td(a,b,c){if(typeof b==="string")return Nd(a,function(){return b.length},function(d){return b[d]},c);if(b instanceof ib)return Nd(a,function(){return b.length()},function(d){return b.get(d)},c);if(rd())throw new td("The value is not iterable.");throw new TypeError("The value is not iterable.");}
function Wd(a,b,c,d){function e(p,q){for(var r=0;r<f.length();r++){var t=f.get(r);q.add(t,p.get(t))}}var f=this.evaluate(a);if(!(f instanceof ib))throw Error("TypeError: Non-List argument given to ForLet instruction.");var g=this.F;d=this.evaluate(d);var k=Wa(g);for(e(g,k);Ya(k,b);){var m=Xa(k,d);if(m instanceof Qa){if(m.type==="break")break;if(m.type==="return")return m}var n=Wa(g);e(k,n);Ya(n,c);k=n}}
function Xd(a,b){var c=this.F,d=this.evaluate(b);if(!(d instanceof ib))throw Error("Error: non-List value given for Fn argument names.");var e=Array.prototype.slice.call(arguments,2);return new id(a,function(){return function(f){var g=Wa(c);g.j===void 0&&(g.j=this.F.j);for(var k=Array.prototype.slice.call(arguments,0),m=0;m<k.length;m++)if(k[m]=this.evaluate(k[m]),k[m]instanceof Qa)return k[m];for(var n=d.get("length"),p=0;p<n;p++)p<k.length?g.add(d.get(p),k[p]):g.add(d.get(p),void 0);g.add("arguments",
new ib(k));var q=Xa(g,e);if(q instanceof Qa)return q.type==="return"?q.data:q}}())}function Yd(a){a=this.evaluate(a);var b=this.F;if(Zd&&!b.has(a))throw new ReferenceError(a+" is not defined.");return b.get(a)}
function $d(a,b){var c;a=this.evaluate(a);b=this.evaluate(b);if(a===void 0||a===null){var d="TypeError: Cannot read properties of "+a+" (reading '"+b+"')";if(rd())throw new td(d);throw Error(d);}if(a instanceof lb||a instanceof ib||a instanceof id)c=a.get(b);else if(typeof a==="string")b==="length"?c=a.length:hb(b)&&(c=a[b]);else if(a instanceof nd)return;return c}function ae(a,b){return this.evaluate(a)>this.evaluate(b)}function be(a,b){return this.evaluate(a)>=this.evaluate(b)}
function ce(a,b){a=this.evaluate(a);b=this.evaluate(b);a instanceof nd&&(a=a.getValue());b instanceof nd&&(b=b.getValue());return a===b}function de(a,b){return!ce.call(this,a,b)}function ee(a,b,c){var d=[];this.evaluate(a)?d=this.evaluate(b):c&&(d=this.evaluate(c));var e=Xa(this.F,d);if(e instanceof Qa)return e}var Zd=!1;
function fe(a,b){return this.evaluate(a)<this.evaluate(b)}function ge(a,b){return this.evaluate(a)<=this.evaluate(b)}function he(){for(var a=new ib,b=0;b<arguments.length;b++){var c=this.evaluate(arguments[b]);a.push(c)}return a}function ie(){for(var a=new lb,b=0;b<arguments.length-1;b+=2){var c=this.evaluate(arguments[b])+"",d=this.evaluate(arguments[b+1]);a.set(c,d)}return a}function je(a,b){return this.evaluate(a)%this.evaluate(b)}function ke(a,b){return this.evaluate(a)*this.evaluate(b)}
function le(a){return-this.evaluate(a)}function me(a){return!this.evaluate(a)}function ne(a,b){return!Ld.call(this,a,b)}function oe(){return null}function pe(a,b){return this.evaluate(a)||this.evaluate(b)}function qe(a,b){var c=this.evaluate(a);this.evaluate(b);return c}function re(a){return this.evaluate(a)}function se(){return Array.prototype.slice.apply(arguments)}function te(a){return new Qa("return",this.evaluate(a))}
function ue(a,b,c){a=this.evaluate(a);b=this.evaluate(b);c=this.evaluate(c);if(a===null||a===void 0){var d="TypeError: Can't set property "+b+" of "+a+".";if(rd())throw new td(d);throw Error(d);}(a instanceof id||a instanceof ib||a instanceof lb)&&a.set(b,c);return c}function ve(a,b){return this.evaluate(a)-this.evaluate(b)}
function we(a,b,c){a=this.evaluate(a);var d=this.evaluate(b),e=this.evaluate(c);if(!Array.isArray(d)||!Array.isArray(e))throw Error("Error: Malformed switch instruction.");for(var f,g=!1,k=0;k<d.length;k++)if(g||a===this.evaluate(d[k]))if(f=this.evaluate(e[k]),f instanceof Qa){var m=f.type;if(m==="break")return;if(m==="return"||m==="continue")return f}else g=!0;if(e.length===d.length+1&&(f=this.evaluate(e[e.length-1]),f instanceof Qa&&(f.type==="return"||f.type==="continue")))return f}
function xe(a,b,c){return this.evaluate(a)?this.evaluate(b):this.evaluate(c)}function ye(a){a=this.evaluate(a);return a instanceof id?"function":typeof a}function ze(){for(var a=this.F,b=0;b<arguments.length;b++){var c=arguments[b];typeof c!=="string"||a.add(c,void 0)}}
function Ae(a,b,c,d){var e=this.evaluate(d);if(this.evaluate(c)){var f=Xa(this.F,e);if(f instanceof Qa){if(f.type==="break")return;if(f.type==="return")return f}}for(;this.evaluate(a);){var g=Xa(this.F,e);if(g instanceof Qa){if(g.type==="break")break;if(g.type==="return")return g}this.evaluate(b)}}function Be(a){return~Number(this.evaluate(a))}function Ce(a,b){return Number(this.evaluate(a))<<Number(this.evaluate(b))}function De(a,b){return Number(this.evaluate(a))>>Number(this.evaluate(b))}
function Ee(a,b){return Number(this.evaluate(a))>>>Number(this.evaluate(b))}function Fe(a,b){return Number(this.evaluate(a))&Number(this.evaluate(b))}function Ge(a,b){return Number(this.evaluate(a))^Number(this.evaluate(b))}function He(a,b){return Number(this.evaluate(a))|Number(this.evaluate(b))}function Ie(){}
function Je(a,b,c,d,e){var f=!0;try{var g=this.evaluate(c);if(g instanceof Qa)return g}catch(r){if(!(r instanceof td&&a))throw f=r instanceof td,r;var k=Wa(this.F),m=new nd(r);k.add(b,m);var n=this.evaluate(d),p=Xa(k,n);if(p instanceof Qa)return p}finally{if(f&&e!==void 0){var q=this.evaluate(e);if(q instanceof Qa)return q}}};var Le=function(){this.j=new Za;Ke(this)};Le.prototype.execute=function(a){return this.j.Xh(a)};var Ke=function(a){var b=function(c,d){var e=new id(String(c),d);e.Ma();a.j.j.set(String(c),e)};b("map",ie);b("and",cd);b("contains",fd);b("equals",dd);b("or",ed);b("startsWith",gd);b("variable",hd)};var Pe=function(){this.D=!1;this.j=new Za;Me(this);this.D=!0};Pe.prototype.execute=function(a){return Qe(this.j.Xh(a))};var Re=function(a,b,c){return Qe(a.j.Xk(b,c))};Pe.prototype.Ma=function(){this.j.Ma()};
var Me=function(a){var b=function(c,d){var e=String(c),f=new id(e,d);f.Ma();a.j.j.set(e,f)};b(0,zd);b(1,Ad);b(2,Bd);b(3,Cd);b(56,Fe);b(57,Ce);b(58,Be);b(59,He);b(60,De);b(61,Ee);b(62,Ge);b(53,Dd);b(4,Ed);b(5,Fd);b(52,Gd);b(6,Hd);b(49,Id);b(7,he);b(8,ie);b(9,Fd);b(50,Jd);b(10,Kd);b(12,Ld);b(13,Md);b(51,Xd);b(47,Pd);b(54,Qd);b(55,Rd);b(63,Wd);b(64,Sd);b(65,Ud);b(66,Vd);b(15,Yd);b(16,$d);b(17,$d);b(18,ae);b(19,be);b(20,ce);b(21,de);b(22,ee);b(23,fe);b(24,ge);b(25,je);b(26,ke);b(27,le);b(28,me);b(29,
ne);b(45,oe);b(30,pe);b(32,qe);b(33,qe);b(34,re);b(35,re);b(46,se);b(36,te);b(43,ue);b(37,ve);b(38,we);b(39,xe);b(67,Je);b(40,ye);b(44,Ie);b(41,ze);b(42,Ae)};Pe.prototype.sd=function(){return this.j.sd()};function Qe(a){if(a instanceof Qa||a instanceof id||a instanceof ib||a instanceof lb||a instanceof nd||a===null||a===void 0||typeof a==="string"||typeof a==="number"||typeof a==="boolean")return a};var Se=function(a){this.message=a};function Te(a){var b="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[a];return b===void 0?new Se("Value "+a+" can not be encoded in web-safe base64 dictionary."):b};function Ue(a){switch(a){case 1:return"1";case 2:case 4:return"0";default:return"-"}};var Ve=/^[1-9a-zA-Z_-][1-9a-c][1-9a-v]\d$/;function We(a,b){for(var c="",d=!0;a>7;){var e=a&31;a>>=5;d?d=!1:e|=32;c=""+Te(e)+c}a<<=2;d||(a|=32);return c=""+Te(a|b)+c};var Xe=function(){function a(b){return{toString:function(){return b}}}return{Bk:a("consent"),ki:a("convert_case_to"),li:a("convert_false_to"),mi:a("convert_null_to"),ni:a("convert_true_to"),oi:a("convert_undefined_to"),wn:a("debug_mode_metadata"),oa:a("function"),Wg:a("instance_name"),al:a("live_only"),bl:a("malware_disabled"),fl:a("metadata"),kl:a("original_activity_id"),Gn:a("original_vendor_template_id"),En:a("once_on_load"),jl:a("once_per_event"),xj:a("once_per_load"),In:a("priority_override"),
Jn:a("respected_consent_types"),Fj:a("setup_tags"),ve:a("tag_id"),Lj:a("teardown_tags")}}();var tf;var uf=[],vf=[],wf=[],xf=[],yf=[],zf={},Af,Bf;function Cf(a){Bf=Bf||a}
function Df(a){}var Ef,Ff=[],Gf=[];function Hf(a,b){var c={};c[Xe.oa]="__"+a;for(var d in b)b.hasOwnProperty(d)&&(c["vtp_"+d]=b[d]);return c}
function If(a,b,c){try{return Af(Jf(a,b,c))}catch(d){JSON.stringify(a)}return 2}function Kf(a){var b=a[Xe.oa];if(!b)throw Error("Error: No function name given for function call.");return!!zf[b]}
var Jf=function(a,b,c){c=c||[];var d={},e;for(e in a)a.hasOwnProperty(e)&&(d[e]=Lf(a[e],b,c));return d},Lf=function(a,b,c){if(Array.isArray(a)){var d;switch(a[0]){case "function_id":return a[1];case "list":d=[];for(var e=1;e<a.length;e++)d.push(Lf(a[e],b,c));return d;case "macro":var f=a[1];if(c[f])return;var g=uf[f];if(!g||b.isBlocked(g))return;c[f]=!0;var k=String(g[Xe.Wg]);try{var m=Jf(g,b,c);m.vtp_gtmEventId=b.id;b.priorityId&&(m.vtp_gtmPriorityId=b.priorityId);d=Mf(m,{event:b,index:f,type:2,
name:k});Ef&&(d=Ef.Bl(d,m))}catch(y){b.logMacroError&&b.logMacroError(y,Number(f),k),d=!1}c[f]=!1;return d;case "map":d={};for(var n=1;n<a.length;n+=2)d[Lf(a[n],b,c)]=Lf(a[n+1],b,c);return d;case "template":d=[];for(var p=!1,q=1;q<a.length;q++){var r=Lf(a[q],b,c);Bf&&(p=p||Bf.qm(r));d.push(r)}return Bf&&p?Bf.El(d):d.join("");case "escape":d=Lf(a[1],b,c);if(Bf&&Array.isArray(a[1])&&a[1][0]==="macro"&&Bf.sm(a))return Bf.Nm(d);d=String(d);for(var t=2;t<a.length;t++)Ye[a[t]]&&(d=Ye[a[t]](d));return d;
case "tag":var u=a[1];if(!xf[u])throw Error("Unable to resolve tag reference "+u+".");return{Tj:a[2],index:u};case "zb":var v={arg0:a[2],arg1:a[3],ignore_case:a[5]};v[Xe.oa]=a[1];var w=If(v,b,c),x=!!a[4];return x||w!==2?x!==(w===1):null;default:throw Error("Attempting to expand unknown Value type: "+a[0]+".");}}return a},Mf=function(a,b){var c=a[Xe.oa],d=b&&b.event;if(!c)throw Error("Error: No function name given for function call.");var e=zf[c],f=b&&b.type===2&&(d==null?void 0:d.reportMacroDiscrepancy)&&
e&&Ff.indexOf(c)!==-1,g={},k={},m;for(m in a)a.hasOwnProperty(m)&&Tb(m,"vtp_")&&(e&&(g[m]=a[m]),!e||f)&&(k[m.substring(4)]=a[m]);e&&d&&d.cachedModelValues&&(g.vtp_gtmCachedValues=d.cachedModelValues);if(b){if(b.name==null){var n;a:{var p=b.type,q=b.index;if(q==null)n="";else{var r;switch(p){case 2:r=uf[q];break;case 1:r=xf[q];break;default:n="";break a}var t=r&&r[Xe.Wg];n=t?String(t):""}}b.name=n}e&&(g.vtp_gtmEntityIndex=b.index,g.vtp_gtmEntityName=b.name)}var u,v,w;if(f&&Gf.indexOf(c)===-1){Gf.push(c);
var x=Ob();u=e(g);var y=Ob()-x,B=Ob();v=tf(c,k,b);w=y-(Ob()-B)}else if(e&&(u=e(g)),!e||f)v=tf(c,k,b);f&&d&&(d.reportMacroDiscrepancy(d.id,c,void 0,!0),gb(u)?(Array.isArray(u)?Array.isArray(v):fb(u)?fb(v):typeof u==="function"?typeof v==="function":u===v)||d.reportMacroDiscrepancy(d.id,c):u!==v&&d.reportMacroDiscrepancy(d.id,c),w!==void 0&&d.reportMacroDiscrepancy(d.id,c,w));return e?u:v};var Nf=function(a,b,c){var d;d=Error.call(this,c);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.permissionId=a;this.parameters=b;this.name="PermissionError"};za(Nf,Error);function Of(a,b){if(Array.isArray(a)){Object.defineProperty(a,"context",{value:{line:b[0]}});for(var c=1;c<a.length;c++)Of(a[c],b[c])}};var Pf=function(a,b){var c;c=Error.call(this,"Wrapped error for Dust debugging. Original error message: "+a.message);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.Hm=a;this.j=[];this.D=b};za(Pf,Error);function Qf(){return function(a,b){a instanceof Pf||(a=new Pf(a,Rf));b&&a instanceof Pf&&a.j.push(b);throw a;}}function Rf(a){if(!a.length)return a;a.push({id:"main",line:0});for(var b=a.length-1;b>0;b--)Cb(a[b].id)&&a.splice(b++,1);for(var c=a.length-1;c>0;c--)a[c].line=a[c-1].line;a.splice(0,1);return a};function Sf(a){function b(r){for(var t=0;t<r.length;t++)d[r[t]]=!0}for(var c=[],d=[],e=Tf(a),f=0;f<vf.length;f++){var g=vf[f],k=Uf(g,e);if(k){for(var m=g.add||[],n=0;n<m.length;n++)c[m[n]]=!0;b(g.block||[])}else k===null&&b(g.block||[]);}for(var p=[],q=0;q<xf.length;q++)c[q]&&!d[q]&&(p[q]=!0);return p}
function Uf(a,b){for(var c=a["if"]||[],d=0;d<c.length;d++){var e=b(c[d]);if(e===0)return!1;if(e===2)return null}for(var f=a.unless||[],g=0;g<f.length;g++){var k=b(f[g]);if(k===2)return null;if(k===1)return!1}return!0}function Tf(a){var b=[];return function(c){b[c]===void 0&&(b[c]=If(wf[c],a));return b[c]}};var Vf={Bl:function(a,b){b[Xe.ki]&&typeof a==="string"&&(a=b[Xe.ki]===1?a.toLowerCase():a.toUpperCase());b.hasOwnProperty(Xe.mi)&&a===null&&(a=b[Xe.mi]);b.hasOwnProperty(Xe.oi)&&a===void 0&&(a=b[Xe.oi]);b.hasOwnProperty(Xe.ni)&&a===!0&&(a=b[Xe.ni]);b.hasOwnProperty(Xe.li)&&a===!1&&(a=b[Xe.li]);return a}};var Wf=function(){this.j={}},Yf=function(a,b){var c=Xf.D,d;(d=c.j)[a]!=null||(d[a]=[]);c.j[a].push(function(){return b.apply(null,qa(Ma.apply(0,arguments)))})};function Zf(a,b,c,d){if(a)for(var e=0;e<a.length;e++){var f=void 0,g="A policy function denied the permission request";try{f=a[e](b,c,d),g+="."}catch(k){g=typeof k==="string"?g+(": "+k):k instanceof Error?g+(": "+k.message):g+"."}if(!f)throw new Nf(c,d,g);}}
function $f(a,b,c){return function(){var d=arguments[0];if(d){var e=a.j[d],f=a.j.all;if(e||f){var g=c.apply(void 0,Array.prototype.slice.call(arguments,0));Zf(e,b,d,g);Zf(f,b,d,g)}}}};var dg=function(){var a=data.permissions||{},b=ag.ctid,c=this;this.j={};this.D=new Wf;var d={},e={},f=$f(this.D,b,function(){var g=arguments[0];return g&&d[g]?d[g].apply(void 0,Array.prototype.slice.call(arguments,0)):{}});z(a,function(g,k){function m(p){var q=Ma.apply(1,arguments);if(!n[p])throw bg(p,{},"The requested additional permission "+p+" is not configured.");f.apply(null,[p].concat(qa(q)))}var n={};z(k,function(p,q){var r=cg(p,q);n[p]=r.assert;d[p]||(d[p]=r.N);r.Oj&&!e[p]&&(e[p]=r.Oj)});
c.j[g]=function(p,q){var r=n[p];if(!r)throw bg(p,{},"The requested permission "+p+" is not configured.");var t=Array.prototype.slice.call(arguments,0);r.apply(void 0,t);f.apply(void 0,t);var u=e[p];u&&u.apply(null,[m].concat(qa(t.slice(1))))}})},eg=function(a){return Xf.j[a]||function(){}};
function cg(a,b){var c=Hf(a,b);c.vtp_permissionName=a;c.vtp_createPermissionError=bg;try{return Mf(c)}catch(d){return{assert:function(e){throw new Nf(e,{},"Permission "+e+" is unknown.");},N:function(){throw new Nf(a,{},"Permission "+a+" is unknown.");}}}}function bg(a,b,c){return new Nf(a,b,c)};var fg=!1;var gg={};gg.tk=Kb('');gg.Hl=Kb('');
var kg=function(a){var b={},c=0;z(a,function(e,f){if(f!=null){var g=(""+f).replace(/~/g,"~~");if(hg.hasOwnProperty(e))b[hg[e]]=g;else if(ig.hasOwnProperty(e)){var k=ig[e];b.hasOwnProperty(k)||(b[k]=g)}else if(e==="category")for(var m=g.split("/",5),n=0;n<m.length;n++){var p=b,q=jg[n],r=m[n];p.hasOwnProperty(q)||(p[q]=r)}else if(c<27){var t=String.fromCharCode(c<10?48+c:65+c-10);b["k"+t]=(""+String(e)).replace(/~/g,"~~");b["v"+t]=g;c++}}});var d=[];z(b,function(e,f){d.push(""+e+f)});return d.join("~")},
hg={item_id:"id",item_name:"nm",item_brand:"br",item_category:"ca",item_category2:"c2",item_category3:"c3",item_category4:"c4",item_category5:"c5",item_variant:"va",price:"pr",quantity:"qt",coupon:"cp",item_list_name:"ln",index:"lp",item_list_id:"li",discount:"ds",affiliation:"af",promotion_id:"pi",promotion_name:"pn",creative_name:"cn",creative_slot:"cs",location_id:"lo"},ig={id:"id",name:"nm",brand:"br",variant:"va",list_name:"ln",list_position:"lp",list:"ln",position:"lp",creative:"cn"},jg=["ca",
"c2","c3","c4","c5"];
var lg=function(){this.events=[];this.j="";this.ja={};this.baseUrl="";this.H=0;this.K=this.D=!1;};lg.prototype.add=function(a){return this.O(a)?(this.events.push(a),this.j=a.D,this.ja=a.ja,this.baseUrl=a.baseUrl,this.H+=a.K,this.D=a.H,!0):!1};lg.prototype.O=function(a){return this.events.length?this.events.length>=20||a.K+this.H>=16384?!1:this.baseUrl===
a.baseUrl&&this.D===a.H&&this.W(a):!0};lg.prototype.W=function(a){var b=this;if(!this.K)return this.j===a.D;var c=Object.keys(this.ja);return c.length===Object.keys(a.ja).length&&c.every(function(d){return a.ja.hasOwnProperty(d)&&String(b.ja[d])===String(a.ja[d])})};var mg={},ng=(mg.uaa=!0,mg.uab=!0,mg.uafvl=!0,mg.uamb=!0,mg.uam=!0,mg.uap=!0,mg.uapv=!0,mg.uaw=!0,mg);
var qg=function(a,b){var c=a.events;if(c.length===1)return og(c[0],b);var d=[];a.j&&d.push(a.j);for(var e={},f=0;f<c.length;f++)z(c[f].Mc,function(t,u){u!=null&&(e[t]=e[t]||{},e[t][String(u)]=e[t][String(u)]+1||1)});var g={};z(e,function(t,u){var v,w=-1,x=0;z(u,function(y,B){x+=B;var A=(y.length+t.length+2)*(B-1);A>w&&(v=y,w=A)});x===c.length&&(g[t]=v)});pg(g,d);b&&d.push("_s="+b);for(var k=d.join("&"),m=[],n={},p=0;p<c.length;n={Kh:void 0},p++){var q=[];n.Kh={};z(c[p].Mc,function(t){return function(u,
v){g[u]!==""+v&&(t.Kh[u]=v)}}(n));c[p].j&&q.push(c[p].j);pg(n.Kh,q);m.push(q.join("&"))}var r=m.join("\r\n");return{params:k,body:r}},og=function(a,b){var c=[];a.D&&c.push(a.D);b&&c.push("_s="+b);pg(a.Mc,c);var d=!1;a.j&&(c.push(a.j),d=!0);var e=c.join("&"),f="",g=e.length+a.baseUrl.length+1;d&&g>2048&&(f=c.pop(),e=c.join("&"));return{params:e,body:f}},pg=function(a,b){z(a,function(c,d){d!=null&&b.push(encodeURIComponent(c)+"="+encodeURIComponent(d))})};var rg=function(a){var b=[];z(a,function(c,d){d!=null&&b.push(encodeURIComponent(c)+"="+encodeURIComponent(String(d)))});return b.join("&")},sg=function(a,b,c,d,e){this.baseUrl=b;this.endpoint=c;this.ja=a.ja;this.Mc=a.Mc;this.sh=a.sh;this.H=d;this.D=rg(a.ja);this.j=rg(a.sh);this.K=this.j.length;if(e&&this.K>16384)throw Error("EVENT_TOO_LARGE");};
var vg=function(a,b){for(var c=0;c<b.length;c++){var d=a,e=b[c];if(!tg.exec(e))throw Error("Invalid key wildcard");var f=e.indexOf(".*"),g=f!==-1&&f===e.length-2,k=g?e.slice(0,e.length-2):e,m;a:if(d.length===0)m=!1;else{for(var n=d.split("."),p=0;p<n.length;p++)if(!ug.exec(n[p])){m=!1;break a}m=!0}if(!m||k.length>d.length||!g&&d.length!==e.length?0:g?Tb(d,k)&&(d===k||d.charAt(k.length)==="."):d===k)return!0}return!1},ug=/^[a-z$_][\w$]*$/i,tg=/^(?:[a-z_$][a-z_$0-9]*\.)*[a-z_$][a-z_$0-9]*(?:\.\*)?$/i;
var wg=["matches","webkitMatchesSelector","mozMatchesSelector","msMatchesSelector","oMatchesSelector"];function xg(a,b){var c=String(a),d=String(b),e=c.length-d.length;return e>=0&&c.indexOf(d,e)===e}var yg=new Hb;function zg(a,b,c){var d=c?"i":void 0;try{var e=String(b)+String(d),f=yg.get(e);f||(f=new RegExp(b,d),yg.set(e,f));return f.test(a)}catch(g){return!1}}function Ag(a,b){return String(a).indexOf(String(b))>=0}function Bg(a,b){return String(a)===String(b)}
function Cg(a,b){return Number(a)>=Number(b)}function Dg(a,b){return Number(a)<=Number(b)}function Eg(a,b){return Number(a)>Number(b)}function Fg(a,b){return Number(a)<Number(b)}function Gg(a,b){return Tb(String(a),String(b))};var Ng=/^([a-z][a-z0-9]*):(!|\?)(\*|string|boolean|number|Fn|PixieMap|List|OpaqueValue)$/i,Og={Fn:"function",PixieMap:"Object",List:"Array"};
function K(a,b,c){for(var d=0;d<b.length;d++){var e=Ng.exec(b[d]);if(!e)throw Error("Internal Error in "+a);var f=e[1],g=e[2]==="!",k=e[3],m=c[d];if(m==null){if(g)throw Error("Error in "+a+". Required argument "+f+" not supplied.");}else if(k!=="*"){var n=typeof m;m instanceof id?n="Fn":m instanceof ib?n="List":m instanceof lb?n="PixieMap":m instanceof nd&&(n="OpaqueValue");if(n!==k)throw Error("Error in "+a+". Argument "+f+" has type "+((Og[n]||n)+", which does not match required type ")+((Og[k]||
k)+"."));}}};function Pg(a){return""+a}
function Qg(a,b){var c=[];return c};function Rg(a,b){var c=new id(a,function(){for(var d=Array.prototype.slice.call(arguments,0),e=0;e<d.length;e++)d[e]=this.evaluate(d[e]);try{return b.apply(this,d)}catch(g){if(rd())throw new td(g.message);throw g;}});c.Ma();return c}
function Sg(a,b){var c=new lb,d;for(d in b)if(b.hasOwnProperty(d)){var e=b[d];Bb(e)?c.set(d,Rg(a+"_"+d,e)):fb(e)?c.set(d,Sg(a+"_"+d,e)):(Cb(e)||l(e)||typeof e==="boolean")&&c.set(d,e)}c.Ma();return c};function Tg(a,b){K(this.getName(),["apiName:!string","message:?string"],arguments);var c={},d=new lb;return d=Sg("AssertApiSubject",c)};function Ug(a,b){K(this.getName(),["actual:?*","message:?string"],arguments);if(a instanceof pd)throw Error("Argument actual cannot have type Promise. Assertions on asynchronous code aren't supported.");var c={},d=new lb;return d=Sg("AssertThatSubject",c)};function Vg(a){return function(){for(var b=[],c=this.F,d=0;d<arguments.length;++d)b.push(J(arguments[d],c));return qd(a.apply(null,b))}}function Wg(){for(var a=Math,b=Xg,c={},d=0;d<b.length;d++){var e=b[d];a.hasOwnProperty(e)&&(c[e]=Vg(a[e].bind(a)))}return c};function Yg(a){var b;return b};function Zg(a){var b;K(this.getName(),["uri:!string"],arguments);try{b=decodeURIComponent(a)}catch(c){}return b};function $g(a){try{return encodeURI(a)}catch(b){}};function ah(a){try{return encodeURIComponent(a)}catch(b){}};
var bh=function(a,b){for(var c=0;c<b.length;c++){if(a===void 0)return;a=a[b[c]]}return a},ch=function(a,b){var c=b.preHit;if(c){var d=a[0];switch(d){case "hitData":return a.length<2?void 0:bh(c.getHitData(a[1]),a.slice(2));case "metadata":return a.length<2?void 0:bh(c.getMetadata(a[1]),a.slice(2));case "eventName":return c.getEventName();case "destinationId":return c.getDestinationId();default:throw Error(d+" is not a valid field that can be accessed\n                      from PreHit data.");}}},
eh=function(a,b){if(a){if(a.contextValue!==void 0){var c;a:{var d=a.contextValue,e=d.keyParts;if(e&&e.length!==0){var f=d.namespaceType;switch(f){case 1:c=ch(e,b);break a;case 2:var g=b.macro;c=g?g[e[0]]:void 0;break a;default:throw Error("Unknown Namespace Type used: "+f);}}c=void 0}return c}if(a.booleanExpressionValue!==void 0)return dh(a.booleanExpressionValue,b);if(a.booleanValue!==void 0)return!!a.booleanValue;if(a.stringValue!==void 0)return String(a.stringValue);if(a.integerValue!==void 0)return Number(a.integerValue);
if(a.doubleValue!==void 0)return Number(a.doubleValue);throw Error("Unknown field used for variable of type ExpressionValue:"+a);}},dh=function(a,b){var c=a.args;if(!Array.isArray(c)||c.length===0)throw Error('Invalid boolean expression format. Expected "args":'+c+" property to\n         be non-empty array.");var d=function(g){return eh(g,b)};switch(a.type){case 1:for(var e=0;e<c.length;e++)if(d(c[e]))return!0;return!1;case 2:for(var f=0;f<c.length;f++)if(!d(c[f]))return!1;return c.length>0;case 3:return!d(c[0]);
case 4:return zg(d(c[0]),d(c[1]),!1);case 5:return Bg(d(c[0]),d(c[1]));case 6:return Gg(d(c[0]),d(c[1]));case 7:return xg(d(c[0]),d(c[1]));case 8:return Ag(d(c[0]),d(c[1]));case 9:return Fg(d(c[0]),d(c[1]));case 10:return Dg(d(c[0]),d(c[1]));case 11:return Eg(d(c[0]),d(c[1]));case 12:return Cg(d(c[0]),d(c[1]));default:throw Error('Invalid boolean expression format. Expected "type" property tobe a positive integer which is less than 13.');}};function fh(a){K(this.getName(),["message:?string"],arguments);};function gh(a,b){K(this.getName(),["min:!number","max:!number"],arguments);return Fb(a,b)};function hh(){return(new Date).getTime()};function ih(a){if(a===null)return"null";if(a instanceof ib)return"array";if(a instanceof id)return"function";if(a instanceof nd){var b;a=(b=a)==null?void 0:b.getValue();var c;if(((c=a)==null?void 0:c.constructor)===void 0||a.constructor.name===void 0){var d=String(a);return d.substring(8,d.length-1)}return String(a.constructor.name)}return typeof a};function jh(a){function b(c){return function(d){try{return c(d)}catch(e){(fg||gg.tk)&&a.call(this,e.message)}}}return{parse:b(function(c){return qd(JSON.parse(c))}),stringify:b(function(c){return JSON.stringify(J(c))})}};function kh(a){return Jb(J(a,this.F))};function lh(a){return Number(J(a,this.F))};function mh(a){return a===null?"null":a===void 0?"undefined":a.toString()};function nh(a,b,c){var d=null,e=!1;return e?d:null};var Xg="floor ceil round max min abs pow sqrt".split(" ");function oh(){var a={};return{Rl:function(b){return a.hasOwnProperty(b)?a[b]:void 0},qk:function(b,c){a[b]=c},reset:function(){a={}}}}function ph(a,b){return function(){var c=Array.prototype.slice.call(Ma.apply(0,arguments),0);c.unshift(b);return id.prototype.invoke.apply(a,c)}}
function qh(a,b){K(this.getName(),["apiName:!string","mock:?*"],arguments);}
function rh(a,b){K(this.getName(),["apiName:!string","mock:!PixieMap"],arguments);};var sh={};var th=function(a){var b=new lb;if(a instanceof ib)for(var c=a.Qb(),d=0;d<c.length();d++){var e=c.get(d);a.has(e)&&b.set(e,a.get(e))}else if(a instanceof id)for(var f=ab(a,1),g=0;g<f.length;g++){var k=f[g];b.set(k,a.get(k))}else for(var m=0;m<a.length;m++)b.set(m,a[m]);return b};
sh.keys=function(a){K(this.getName(),["input:!*"],arguments);if(a instanceof ib||a instanceof id||typeof a==="string")a=th(a);if(a instanceof lb)return a.Qb();return new ib};
sh.values=function(a){K(this.getName(),["input:!*"],arguments);if(a instanceof ib||a instanceof id||typeof a==="string")a=th(a);if(a instanceof lb)return new ib(ab(a,2));return new ib};
sh.entries=function(a){K(this.getName(),["input:!*"],arguments);if(a instanceof ib||a instanceof id||typeof a==="string")a=th(a);if(a instanceof lb)return mb(a);return new ib};sh.freeze=function(a){(a instanceof lb||a instanceof ib||a instanceof id)&&a.Ma();return a};
sh.delete=function(a,b){if(a instanceof lb&&!a.D)return a.Hf(b),!0;return!1};function N(a,b){var c=Ma.apply(2,arguments),d=a.F.j;if(!d)throw Error("Missing program state.");if(d.Tm){try{d.Pj.apply(null,[b].concat(qa(c)))}catch(e){throw ub("TAGGING",21),e;}return}d.Pj.apply(null,[b].concat(qa(c)))};var uh=function(){this.j={};this.D={};this.H=!0;};uh.prototype.get=function(a,b){var c=this.j.hasOwnProperty(a)?this.j[a]:void 0;return c};
uh.prototype.add=function(a,b,c){if(this.j.hasOwnProperty(a))throw Error("Attempting to add a function which already exists: "+a+".");if(this.D.hasOwnProperty(a))throw Error("Attempting to add an API with an existing private API name: "+a+".");this.j[a]=c?void 0:Bb(b)?Rg(a,b):Sg(a,b)};function vh(a,b){var c=void 0;return c};function wh(){var a={};
return a};function xh(a){return yh?H.querySelectorAll(a):null}
function zh(a,b){if(!yh)return null;if(Element.prototype.closest)try{return a.closest(b)}catch(e){return null}var c=Element.prototype.matches||Element.prototype.webkitMatchesSelector||Element.prototype.mozMatchesSelector||Element.prototype.msMatchesSelector||Element.prototype.oMatchesSelector,d=a;if(!H.documentElement.contains(d))return null;do{try{if(c.call(d,b))return d}catch(e){break}d=d.parentElement||d.parentNode}while(d!==null&&d.nodeType===1);return null}var Ah=!1;
if(H.querySelectorAll)try{var Bh=H.querySelectorAll(":root");Bh&&Bh.length==1&&Bh[0]==H.documentElement&&(Ah=!0)}catch(a){}var yh=Ah;var Ch=/^[0-9A-Fa-f]{64}$/;function Dh(a){try{return(new TextEncoder).encode(a)}catch(e){for(var b=[],c=0;c<a.length;c++){var d=a.charCodeAt(c);d<128?b.push(d):d<2048?b.push(192|d>>6,128|d&63):d<55296||d>=57344?b.push(224|d>>12,128|d>>6&63,128|d&63):(d=65536+((d&1023)<<10|a.charCodeAt(++c)&1023),b.push(240|d>>18,128|d>>12&63,128|d>>6&63,128|d&63))}return new Uint8Array(b)}}
function Eh(a){if(a===""||a==="e0")return Promise.resolve(a);var b;if((b=G.crypto)==null?0:b.subtle){if(Ch.test(a))return Promise.resolve(a);try{var c=Dh(a);return G.crypto.subtle.digest("SHA-256",c).then(function(d){var e=Array.from(new Uint8Array(d)).map(function(f){return String.fromCharCode(f)}).join("");return G.btoa(e).replace(/\+/g,"-").replace(/\//g,"_").replace(/=+$/,"")}).catch(function(){return"e2"})}catch(d){return Promise.resolve("e2")}}else return Promise.resolve("e1")};function O(a){ub("GTM",a)};
var Ih=function(a){var b={},c=["tv.1"],d=0;var u=c.join("~");return{ai:{userData:b},
kn:u,sn:d}},Kh=function(a){if(G.Promise)try{return new Promise(function(b){Jh(a,function(c,d){b({dk:c,We:d})})})}catch(b){}},Lh=function(a){for(var b=["tv.1"],c=0,d=0;d<a.length;++d){var e=a[d].name,f=a[d].value,g=a[d].index,k=Fh[e];k&&f&&(Gh.indexOf(e)===-1||/^e\d+$/.test(f)||Hh.test(f)||Ch.test(f))&&(g!==void 0&&(k+=g),b.push(k+"."+f),c++)}a.length===1&&a[0].name==="error_code"&&(c=0);return{ek:encodeURIComponent(b.join("~")),We:c}},Jh=function(a,b){Mh(a,function(c){var d=Lh(c);b(d.ek,d.We)})},
Uh=function(a){function b(r,t,u,v){var w=Nh(r);w!==""&&(Ch.test(w)?k.push({name:t,value:w,index:v}):k.push({name:t,value:u(w),index:v}))}function c(r,t){var u=r;if(l(u)||Array.isArray(u)){u=Db(r);for(var v=0;v<u.length;++v){var w=Nh(u[v]),x=Ch.test(w);t&&!x&&O(89);!t&&x&&O(88)}}}function d(r,t){var u=r[t];c(u,!1);var v=Oh[t];r[v]&&(r[t]&&O(90),u=r[v],c(u,!0));return u}function e(r,t,u){for(var v=Db(d(r,t)),w=0;w<v.length;++w)b(v[w],t,u)}function f(r,t,u,v){var w=d(r,t);b(w,t,u,v)}function g(r){return function(t){O(64);
return r(t)}}var k=[];if(G.location.protocol!=="https:")return k.push({name:"error_code",value:"e3",index:void 0}),k;e(a,"email",Ph);e(a,"phone_number",Qh);e(a,"first_name",g(Rh));e(a,"last_name",g(Rh));var m=a.home_address||{};e(m,"street",g(Sh));e(m,"city",g(Sh));e(m,"postal_code",g(Th));e(m,"region",g(Sh));e(m,"country",g(Th));for(var n=Db(a.address||{}),p=0;p<n.length;p++){var q=n[p];f(q,"first_name",Rh,p);f(q,"last_name",Rh,p);f(q,"street",Sh,p);f(q,"city",Sh,p);f(q,"postal_code",Th,p);f(q,"region",
Sh,p);f(q,"country",Th,p)}return k},Mh=function(a,b){var c=Uh(a);Vh(c,b)},Nh=function(a){return a==null?"":l(a)?Mb(String(a)):"e0"},Th=function(a){return a.replace(Wh,"")},Rh=function(a){return Sh(a.replace(/\s/g,""))},Sh=function(a){return Mb(a.replace(Xh,"").toLowerCase())},Qh=function(a){a=a.replace(/[\s-()/.]/g,"");a.charAt(0)!=="+"&&(a="+"+a);return Yh.test(a)?a:"e0"},Ph=function(a){var b=a.toLowerCase().split("@");if(b.length===2){var c=b[0];/^(gmail|googlemail)\./.test(b[1])&&(c=c.replace(/\./g,
""));c=c+"@"+b[1];if(Zh.test(c))return c}return"e0"},Vh=function(a,b){a.some(function(c){c.value&&Gh.indexOf(c.name)})?b(a):G.Promise?Promise.all(a.map(function(c){return c.value&&Gh.indexOf(c.name)!==-1?Eh(c.value).then(function(d){c.value=d}):Promise.resolve()})).then(function(){b(a)}).catch(function(){b([])}):b([])},Xh=/[0-9`~!@#$%^&*()_\-+=:;<>,.?|/\\[\]]/g,Zh=/^\S+@\S+\.\S+$/,Yh=/^\+\d{10,15}$/,Wh=/[.~]/g,Hh=/^[0-9A-Za-z_-]{43}$/,$h={},Fh=($h.email="em",$h.phone_number="pn",$h.first_name="fn",
$h.last_name="ln",$h.street="sa",$h.city="ct",$h.region="rg",$h.country="co",$h.postal_code="pc",$h.error_code="ec",$h),ai={},Oh=(ai.email="sha256_email_address",ai.phone_number="sha256_phone_number",ai.first_name="sha256_first_name",ai.last_name="sha256_last_name",ai.street="sha256_street",ai),Gh=Object.freeze(["email","phone_number","first_name","last_name","street"]);var P={g:{ya:"ad_personalization",R:"ad_storage",P:"ad_user_data",U:"analytics_storage",Fb:"region",Tb:"consent_updated",cf:"wait_for_update",si:"app_remove",ui:"app_store_refund",vi:"app_store_subscription_cancel",wi:"app_store_subscription_convert",xi:"app_store_subscription_renew",Ek:"consent_update",hg:"add_payment_info",ig:"add_shipping_info",oc:"add_to_cart",qc:"remove_from_cart",jg:"view_cart",Ub:"begin_checkout",rc:"select_item",kb:"view_item_list",Gb:"select_promotion",lb:"view_promotion",
Ja:"purchase",sc:"refund",Oa:"view_item",kg:"add_to_wishlist",Fk:"exception",yi:"first_open",zi:"first_visit",ba:"gtag.config",Ua:"gtag.get",Ai:"in_app_purchase",Vb:"page_view",Gk:"screen_view",Bi:"session_start",Hk:"timing_complete",Ik:"track_social",Nc:"user_engagement",Jk:"user_id_update",nb:"gclgb",Va:"gclid",Ci:"gclgs",Di:"gclst",fa:"ads_data_redaction",Ei:"gad_source",Fi:"gad_source_src",Gd:"gclid_url",Gi:"gclsrc",lg:"gbraid",df:"wbraid",ka:"allow_ad_personalization_signals",ef:"allow_custom_scripts",
Hd:"allow_direct_google_requests",ff:"allow_display_features",Id:"allow_enhanced_conversions",ob:"allow_google_signals",Ea:"allow_interest_groups",Kk:"app_id",Lk:"app_installer_id",Mk:"app_name",Nk:"app_version",Hb:"auid",Hi:"auto_detection_enabled",Wb:"aw_remarketing",hf:"aw_remarketing_only",Jd:"discount",Kd:"aw_feed_country",Ld:"aw_feed_language",da:"items",Md:"aw_merchant_id",mg:"aw_basket_type",Oc:"campaign_content",Pc:"campaign_id",Qc:"campaign_medium",Rc:"campaign_name",Sc:"campaign",Tc:"campaign_source",
Uc:"campaign_term",pb:"client_id",Ii:"rnd",ng:"consent_update_type",Ji:"content_group",Ki:"content_type",Za:"conversion_cookie_prefix",Vc:"conversion_id",ra:"conversion_linker",Li:"conversion_linker_disabled",Xb:"conversion_api",jf:"cookie_deprecation",Wa:"cookie_domain",Pa:"cookie_expires",ab:"cookie_flags",uc:"cookie_name",Ib:"cookie_path",Qa:"cookie_prefix",vc:"cookie_update",wc:"country",za:"currency",Nd:"customer_lifetime_value",Wc:"custom_map",og:"gcldc",Od:"dclid",Mi:"debug_mode",la:"developer_id",
Ni:"disable_merchant_reported_purchases",Xc:"dc_custom_params",Oi:"dc_natural_search",pg:"dynamic_event_settings",qg:"affiliation",Pd:"checkout_option",kf:"checkout_step",rg:"coupon",Yc:"item_list_name",lf:"list_name",Pi:"promotions",Zc:"shipping",nf:"tax",Qd:"engagement_time_msec",Rd:"enhanced_client_id",Sd:"enhanced_conversions",sg:"enhanced_conversions_automatic_settings",Td:"estimated_delivery_date",pf:"euid_logged_in_state",bd:"event_callback",Ok:"event_category",rb:"event_developer_id_string",
Pk:"event_label",xc:"event",Ud:"event_settings",Vd:"event_timeout",Qk:"description",Rk:"fatal",Qi:"experiments",qf:"firebase_id",yc:"first_party_collection",Wd:"_x_20",sb:"_x_19",Ri:"fledge_drop_reason",ug:"fledge",vg:"flight_error_code",wg:"flight_error_message",Si:"fl_activity_category",Ti:"fl_activity_group",xg:"fl_advertiser_id",Ui:"fl_ar_dedupe",yg:"match_id",Vi:"fl_random_number",Wi:"tran",Xi:"u",Xd:"gac_gclid",zc:"gac_wbraid",zg:"gac_wbraid_multiple_conversions",Ag:"ga_restrict_domain",Bg:"ga_temp_client_id",
Ac:"gdpr_applies",Cg:"geo_granularity",Jb:"value_callback",tb:"value_key",Bc:"_google_ng",Yb:"google_signals",Dg:"google_tld",Yd:"groups",Eg:"gsa_experiment_id",Yi:"gtm_up",Kb:"iframe_state",dd:"ignore_referrer",rf:"internal_traffic_results",Zb:"is_legacy_converted",Lb:"is_legacy_loaded",Zd:"is_passthrough",ed:"_lps",Ra:"language",ae:"legacy_developer_id_string",sa:"linker",Cc:"accept_incoming",vb:"decorate_forms",X:"domains",Mb:"url_position",Fg:"method",Sk:"name",fd:"new_customer",Gg:"non_interaction",
Zi:"optimize_id",aj:"page_hostname",gd:"page_path",Fa:"page_referrer",cb:"page_title",Hg:"passengers",Ig:"phone_conversion_callback",bj:"phone_conversion_country_code",Jg:"phone_conversion_css_class",cj:"phone_conversion_ids",Kg:"phone_conversion_number",Lg:"phone_conversion_options",Mg:"_protected_audience_enabled",hd:"quantity",be:"redact_device_info",tf:"referral_exclusion_definition",ac:"restricted_data_processing",dj:"retoken",Tk:"sample_rate",uf:"screen_name",Nb:"screen_resolution",ej:"search_term",
Ka:"send_page_view",bc:"send_to",jd:"server_container_url",kd:"session_duration",de:"session_engaged",vf:"session_engaged_time",wb:"session_id",ee:"session_number",wf:"_shared_user_id",ld:"delivery_postal_code",Uk:"temporary_client_id",xf:"topmost_url",fj:"tracking_id",yf:"traffic_type",Aa:"transaction_id",Ob:"transport_url",Ng:"trip_type",fc:"update",Xa:"url_passthrough",zf:"_user_agent_architecture",Af:"_user_agent_bitness",Bf:"_user_agent_full_version_list",Cf:"_user_agent_mobile",Df:"_user_agent_model",
Ef:"_user_agent_platform",Ff:"_user_agent_platform_version",Gf:"_user_agent_wow64",Ga:"user_data",Og:"user_data_auto_latency",Pg:"user_data_auto_meta",Qg:"user_data_auto_multi",Rg:"user_data_auto_selectors",Sg:"user_data_auto_status",md:"user_data_mode",fe:"user_data_settings",Ba:"user_id",eb:"user_properties",gj:"_user_region",he:"us_privacy_string",na:"value",Tg:"wbraid_multiple_conversions",ke:"_fpm_parameters",pj:"_host_name",qj:"_in_page_command",rj:"_is_passthrough_cid",Pb:"non_personalized_ads",
te:"_sst_parameters",qb:"conversion_label",wa:"page_location",ub:"global_developer_id_string",Dc:"tc_privacy_string"}},bi={},ci=Object.freeze((bi[P.g.ka]=1,bi[P.g.ff]=1,bi[P.g.Id]=1,bi[P.g.ob]=1,bi[P.g.da]=1,bi[P.g.Wa]=1,bi[P.g.Pa]=1,bi[P.g.ab]=1,bi[P.g.uc]=1,bi[P.g.Ib]=1,bi[P.g.Qa]=1,bi[P.g.vc]=1,bi[P.g.Wc]=1,bi[P.g.la]=1,bi[P.g.pg]=1,bi[P.g.bd]=1,bi[P.g.Ud]=1,bi[P.g.Vd]=1,bi[P.g.yc]=1,bi[P.g.Ag]=1,bi[P.g.Yb]=1,bi[P.g.Dg]=1,bi[P.g.Yd]=1,bi[P.g.rf]=1,bi[P.g.Zb]=1,bi[P.g.Lb]=1,bi[P.g.sa]=1,bi[P.g.tf]=
1,bi[P.g.ac]=1,bi[P.g.Ka]=1,bi[P.g.bc]=1,bi[P.g.jd]=1,bi[P.g.kd]=1,bi[P.g.vf]=1,bi[P.g.ld]=1,bi[P.g.Ob]=1,bi[P.g.fc]=1,bi[P.g.fe]=1,bi[P.g.eb]=1,bi[P.g.te]=1,bi));Object.freeze([P.g.wa,P.g.Fa,P.g.cb,P.g.Ra,P.g.uf,P.g.Ba,P.g.qf,P.g.Ji]);
var di={},ei=Object.freeze((di[P.g.si]=1,di[P.g.ui]=1,di[P.g.vi]=1,di[P.g.wi]=1,di[P.g.xi]=1,di[P.g.yi]=1,di[P.g.zi]=1,di[P.g.Ai]=1,di[P.g.Bi]=1,di[P.g.Nc]=1,di)),fi={},gi=Object.freeze((fi[P.g.hg]=1,fi[P.g.ig]=1,fi[P.g.oc]=1,fi[P.g.qc]=1,fi[P.g.jg]=1,fi[P.g.Ub]=1,fi[P.g.rc]=1,fi[P.g.kb]=1,fi[P.g.Gb]=1,fi[P.g.lb]=1,fi[P.g.Ja]=1,fi[P.g.sc]=1,fi[P.g.Oa]=1,fi[P.g.kg]=1,fi)),hi=Object.freeze([P.g.ka,P.g.Hd,P.g.ob,P.g.vc,P.g.yc,P.g.dd,P.g.Ka,P.g.fc]),ii=Object.freeze([].concat(qa(hi))),ji=Object.freeze([P.g.Pa,
P.g.Vd,P.g.kd,P.g.vf,P.g.Qd]),ki=Object.freeze([].concat(qa(ji))),li={},mi=(li[P.g.R]="1",li[P.g.U]="2",li[P.g.P]="3",li[P.g.ya]="4",li),ni={},oi=Object.freeze((ni[P.g.ka]=1,ni[P.g.Hd]=1,ni[P.g.Id]=1,ni[P.g.Ea]=1,ni[P.g.Wb]=1,ni[P.g.hf]=1,ni[P.g.Jd]=1,ni[P.g.Kd]=1,ni[P.g.Ld]=1,ni[P.g.da]=1,ni[P.g.Md]=1,ni[P.g.Za]=1,ni[P.g.ra]=1,ni[P.g.Wa]=1,ni[P.g.Pa]=1,ni[P.g.ab]=1,ni[P.g.Qa]=1,ni[P.g.za]=1,ni[P.g.Nd]=1,ni[P.g.la]=1,ni[P.g.Ni]=1,ni[P.g.Sd]=1,ni[P.g.Td]=1,ni[P.g.qf]=1,ni[P.g.yc]=1,ni[P.g.Zb]=1,ni[P.g.Lb]=
1,ni[P.g.Ra]=1,ni[P.g.fd]=1,ni[P.g.wa]=1,ni[P.g.Fa]=1,ni[P.g.Ig]=1,ni[P.g.Jg]=1,ni[P.g.Kg]=1,ni[P.g.Lg]=1,ni[P.g.ac]=1,ni[P.g.Ka]=1,ni[P.g.bc]=1,ni[P.g.jd]=1,ni[P.g.ld]=1,ni[P.g.Aa]=1,ni[P.g.Ob]=1,ni[P.g.fc]=1,ni[P.g.Xa]=1,ni[P.g.Ga]=1,ni[P.g.Ba]=1,ni[P.g.na]=1,ni)),pi={},qi=Object.freeze((pi.search="s",pi.youtube="y",pi.playstore="p",pi.shopping="h",pi.ads="a",pi.maps="m",pi));Object.freeze(P.g);function ri(a,b){if(a==="")return b;var c=Number(a);return isNaN(c)?b:c};var si=[];function ti(a){switch(a){case 0:return 0;case 42:return 1;case 43:return 2;case 44:return 11;case 50:return 3;case 58:return 4;case 66:return 7;case 75:return 5;case 86:return 6;case 87:return 10;case 89:return 8;case 90:return 9}}function Q(a){si[a]=!0;var b=ti(a);b!==void 0&&(xb[b]=!0)}
Q(30);
Q(26);Q(27);Q(28);Q(29);Q(45);Q(70);Q(54);Q(67);
Q(33);Q(15);Q(95);Q(14);
Q(100);Q(94);
Q(59);Q(76);Q(6);
Q(46);Q(4);Q(73);Q(91);Q(65);Q(63);Q(64);Q(74);
Q(104);Q(101);Q(75);Q(5);Q(66);Q(86);
yb[1]=ri('1',6E4);yb[3]=ri('10',1);yb[2]=ri('',50);Q(23);Q(11);Q(62);
Q(92);

Q(51);Q(22);
Q(41);Q(77);Q(89);
Q(87);Q(79);Q(48);
Q(60);function T(a){return!!si[a]}var ui={},vi=G.google_tag_manager=G.google_tag_manager||{};ui.Yg="48e0";ui.se=Number("0")||0;ui.jb="dataLayer";ui.vn="ChAI8M72tQYQxcf4oZGJlqVqEiUAQXVlUAFlxgore3PfyLFtTRGlivUvCHxMivyJX4/24lKTMrvyGgJTnw\x3d\x3d";var wi={__cl:1,__ecl:1,__ehl:1,__evl:1,__fal:1,__fil:1,__fsl:1,__hl:1,__jel:1,__lcl:1,__sdl:1,__tl:1,__ytl:1},xi={__paused:1,__tg:1},yi;for(yi in wi)wi.hasOwnProperty(yi)&&(xi[yi]=1);var zi=Kb("true"),Ai=!1,Bi,Ci=!1;Ci=!0;
Bi=Ci;var Di,Ei=!1;Di=Ei;var Fi,Gi=!1;Fi=Gi;ui.Fd="www.googletagmanager.com";var Hi=""+ui.Fd+(Bi?"/gtag/js":"/gtm.js"),Ii=null,Ji=null,Ki={},Li={};function Mi(){var a=vi.sequence||1;vi.sequence=a+1;return a}ui.Ck="";var Ni="";ui.Zg=Ni;var Oi=new function(){this.j="";this.H=!1;this.D=0;this.Ca=this.O=this.W=this.K=""};function Pi(){var a=Oi.K.length;return Oi.K[a-1]==="/"?Oi.K.substring(0,a-1):Oi.K}function Qi(){return Oi.H&&Oi.D!==1}function Ri(a){for(var b={},c=oa(a.split("|")),d=c.next();!d.done;d=c.next())b[d.value]=!0;return b}var Si=new Hb,Ti={},Ui={},Xi={name:ui.jb,set:function(a,b){h(Wb(a,b),Ti);Vi()},get:function(a){return Wi(a,2)},reset:function(){Si=new Hb;Ti={};Vi()}};function Wi(a,b){return b!=2?Si.get(a):Yi(a)}function Yi(a,b){var c=a.split(".");b=b||[];for(var d=Ti,e=0;e<c.length;e++){if(d===null)return!1;if(d===void 0)break;d=d[c[e]];if(b.indexOf(d)!==-1)return}return d}function Zi(a,b){Ui.hasOwnProperty(a)||(Si.set(a,b),h(Wb(a,b),Ti),Vi())}
function $i(){for(var a=["gtm.allowlist","gtm.blocklist","gtm.whitelist","gtm.blacklist","tagTypeBlacklist"],b=0;b<a.length;b++){var c=a[b],d=Wi(c,1);if(Array.isArray(d)||fb(d))d=h(d);Ui[c]=d}}function Vi(a){z(Ui,function(b,c){Si.set(b,c);h(Wb(b),Ti);h(Wb(b,c),Ti);a&&delete Ui[b]})}function aj(a,b){var c,d=(b===void 0?2:b)!==1?Yi(a):Si.get(a);db(d)==="array"||db(d)==="object"?c=h(d):c=d;return c};
var bj=function(a,b,c){if(!c)return!1;var d=c.selector_type,e=String(c.value),f;if(d==="js_variable"){e=e.replace(/\["?'?/g,".").replace(/"?'?\]/g,"");for(var g=e.split(","),k=0;k<g.length;k++){var m=g[k].trim();if(m){if(Tb(m,"dataLayer."))f=Wi(m.substring(10));else{var n=m.split(".");f=G[n.shift()];for(var p=0;p<n.length;p++)f=f&&f[n[p]]}if(f!==void 0)break}}}else if(d==="css_selector"&&yh)try{var q=xh(e);if(q&&q.length>0){f=[];for(var r=0;r<q.length&&r<(b==="email"||b==="phone_number"?5:1);r++)f.push(Sc(q[r])||
Mb(q[r].value));f=f.length===1?f[0]:f}}catch(t){O(149)}return f?(a[b]=f,!0):!1},cj=function(a){if(a){var b={},c=!1;c=bj(b,"email",a.email)||c;c=bj(b,"phone_number",a.phone)||c;b.address=[];for(var d=a.name_and_address||[],e=0;e<d.length;e++){var f={};c=bj(f,"first_name",d[e].first_name)||c;c=bj(f,"last_name",d[e].last_name)||c;c=bj(f,"street",d[e].street)||c;c=bj(f,"city",d[e].city)||c;c=bj(f,"region",d[e].region)||c;c=bj(f,"country",d[e].country)||c;c=bj(f,"postal_code",d[e].postal_code)||c;b.address.push(f)}return c?
b:void 0}},dj=function(a){return fb(a)?!!a.enable_code:!1};var ej=/:[0-9]+$/,fj=/^\d+\.fls\.doubleclick\.net$/;function gj(a,b,c,d){for(var e=[],f=oa(a.split("&")),g=f.next();!g.done;g=f.next()){var k=oa(g.value.split("=")),m=k.next().value,n=pa(k);if(decodeURIComponent(m.replace(/\+/g," "))===b){var p=n.join("=");if(!c)return d?p:decodeURIComponent(p.replace(/\+/g," "));e.push(d?p:decodeURIComponent(p.replace(/\+/g," ")))}}return c?e:void 0}
function hj(a,b,c,d,e){b&&(b=String(b).toLowerCase());if(b==="protocol"||b==="port")a.protocol=ij(a.protocol)||ij(G.location.protocol);b==="port"?a.port=String(Number(a.hostname?a.port:G.location.port)||(a.protocol==="http"?80:a.protocol==="https"?443:"")):b==="host"&&(a.hostname=(a.hostname||G.location.hostname).replace(ej,"").toLowerCase());return jj(a,b,c,d,e)}
function jj(a,b,c,d,e){var f,g=ij(a.protocol);b&&(b=String(b).toLowerCase());switch(b){case "url_no_fragment":f=kj(a);break;case "protocol":f=g;break;case "host":f=a.hostname.replace(ej,"").toLowerCase();if(c){var k=/^www\d*\./.exec(f);k&&k[0]&&(f=f.substring(k[0].length))}break;case "port":f=String(Number(a.port)||(g==="http"?80:g==="https"?443:""));break;case "path":a.pathname||a.hostname||ub("TAGGING",1);f=a.pathname.substring(0,1)==="/"?a.pathname:"/"+a.pathname;var m=f.split("/");(d||[]).indexOf(m[m.length-
1])>=0&&(m[m.length-1]="");f=m.join("/");break;case "query":f=a.search.replace("?","");e&&(f=gj(f,e,!1));break;case "extension":var n=a.pathname.split(".");f=n.length>1?n[n.length-1]:"";f=f.split("/")[0];break;case "fragment":f=a.hash.replace("#","");break;default:f=a&&a.href}return f}function ij(a){return a?a.replace(":","").toLowerCase():""}function kj(a){var b="";if(a&&a.href){var c=a.href.indexOf("#");b=c<0?a.href:a.href.substring(0,c)}return b}var lj={},mj=0;
function nj(a){var b=lj[a];if(!b){var c=H.createElement("a");a&&(c.href=a);var d=c.pathname;d[0]!=="/"&&(a||ub("TAGGING",1),d="/"+d);var e=c.hostname.replace(ej,"");b={href:c.href,protocol:c.protocol,host:c.host,hostname:e,pathname:d,search:c.search,hash:c.hash,port:c.port};mj<5&&(lj[a]=b,mj++)}return b}
function oj(a){function b(n){var p=n.split("=")[0];return d.indexOf(p)<0?n:p+"=0"}function c(n){return n.split("&").map(b).filter(function(p){return p!==void 0}).join("&")}var d="gclid dclid gbraid wbraid gclaw gcldc gclha gclgf gclgb _gl".split(" "),e=nj(a),f=a.split(/[?#]/)[0],g=e.search,k=e.hash;g[0]==="?"&&(g=g.substring(1));k[0]==="#"&&(k=k.substring(1));g=c(g);k=c(k);g!==""&&(g="?"+g);k!==""&&(k="#"+k);var m=""+f+g+k;m[m.length-1]==="/"&&(m=m.substring(0,m.length-1));return m}
function pj(a){var b=nj(G.location.href),c=hj(b,"host",!1);if(c&&c.match(fj)){var d=hj(b,"path");if(d){var e=d.split(a+"=");if(e.length>1)return e[1].split(";")[0].split("?")[0]}}};var qj={"https://www.google.com":"/g","https://www.googleadservices.com":"/as","https://pagead2.googlesyndication.com":"/gs"};function rj(a,b){if(a){var c=""+a;c.indexOf("http://")!==0&&c.indexOf("https://")!==0&&(c="https://"+c);c[c.length-1]==="/"&&(c=c.substring(0,c.length-1));return nj(""+c+b).href}}function sj(a,b){if(Qi()||Di)return rj(a,b)}function tj(){return!!ui.Zg&&ui.Zg.split("@@").join("")!=="SGTM_TOKEN"}
function uj(a){for(var b=oa([P.g.jd,P.g.Ob]),c=b.next();!c.done;c=b.next()){var d=U(a,c.value);if(d)return d}}function vj(a,b){return Qi()?""+Pi()+(b?qj[a]||"":""):a};function wj(a){var b=String(a[Xe.oa]||"").replace(/_/g,"");return Tb(b,"cvt")?"cvt":b}var xj=G.location.search.indexOf("?gtm_latency=")>=0||G.location.search.indexOf("&gtm_latency=")>=0;var yj={sampleRate:"0.005000",yk:"",tn:"0.007"},zj=Math.random(),Aj;if(!(Aj=xj)){var Bj=yj.sampleRate;Aj=zj<Number(Bj)}var Cj=Aj,Dj=(Fc==null?void 0:Fc.includes("gtm_debug=d"))||xj||zj>=1-Number(yj.tn);var Ej=/gtag[.\/]js/,Fj=/gtm[.\/]js/,Gj=!1;function Hj(a){if(Gj)return"1";var b=a.scriptSource;if(b){if(Ej.test(b))return"3";if(Fj.test(b))return"2"}return"0"}function Ij(a,b){var c=Jj();c.pending||(c.pending=[]);Eb(c.pending,function(d){return d.target.ctid===a.ctid&&d.target.isDestination===a.isDestination})||c.pending.push({target:a,onLoad:b})}
var Kj=function(){this.container={};this.destination={};this.canonical={};this.pending=[];this.siloed=[];this.injectedFirstPartyContainers={};var a;var b=G.google_tags_first_party||[];if(Array.isArray(b)){for(var c={},d=oa(b),e=d.next();!e.done;e=d.next())c[e.value]=!0;a=Object.freeze(c)}else a={};this.injectedFirstPartyContainers=a};function Jj(){var a=Gc("google_tag_data",{}),b=a.tidr;b||(b=new Kj,a.tidr=b);return b};var Lj={},Pj=!1,ag={ctid:"G-CSLL4ZEK4L",canonicalContainerId:"131934939",fk:"G-CSLL4ZEK4L|GT-TWZC7CH",gk:"G-CSLL4ZEK4L"};Lj.oe=Kb("");function Qj(){var a=Rj();return Pj?a.map(Sj):a}function Tj(){var a=Uj();return Pj?a.map(Sj):a}function Vj(){return Wj(ag.ctid)}function Xj(){return Wj(ag.canonicalContainerId||"_"+ag.ctid)}function Rj(){return ag.fk?ag.fk.split("|"):[ag.ctid]}function Uj(){return ag.gk?ag.gk.split("|"):[]}
function Yj(){var a=Zj(ak()),b=a&&a.parent;if(b)return Zj(b)}function Zj(a){var b=Jj();return a.isDestination?b.destination[a.ctid]:b.container[a.ctid]}function Wj(a){return Pj?Sj(a):a}function Sj(a){return"siloed_"+a}function bk(a){return Pj?ck(a):a}function ck(a){a=String(a);return Tb(a,"siloed_")?a.substring(7):a}
function dk(){var a=!1;a=!0;if(a){var b=Jj();if(b.siloed){for(var c=[],d=Rj().map(Sj),e=Uj().map(Sj),f={},g=0;g<b.siloed.length;f={Pf:void 0},g++)f.Pf=b.siloed[g],!Pj&&Eb(f.Pf.isDestination?e:d,function(k){return function(m){return m===k.Pf.ctid}}(f))?Pj=!0:c.push(f.Pf);b.siloed=c}}}
function ek(){var a=Jj();if(a.pending){for(var b,c=[],d=!1,e=Qj(),f=Tj(),g={},k=0;k<a.pending.length;g={Ue:void 0},k++)g.Ue=a.pending[k],Eb(g.Ue.target.isDestination?f:e,function(m){return function(n){return n===m.Ue.target.ctid}}(g))?d||(b=g.Ue.onLoad,d=!0):c.push(g.Ue);a.pending=c;if(b)try{b(Xj())}catch(m){}}}
function fk(){for(var a=ag.ctid,b=Qj(),c=Tj(),d=function(n,p){var q={canonicalContainerId:ag.canonicalContainerId,scriptContainerId:a,state:2,containers:b.slice(),destinations:c.slice()};Ec&&(q.scriptElement=Ec);Fc&&(q.scriptSource=Fc);if(Yj()===void 0){var r;a:{if((q.scriptContainerId||"").indexOf("GTM-")>=0){var t;b:{if(q.scriptSource){for(var u=Oi.H,v=nj(q.scriptSource),w=u?v.pathname:""+v.hostname+v.pathname,x=H.scripts,y="",B=0;B<x.length;++B){var A=x[B];if(!(A.innerHTML.length===0||!u&&A.innerHTML.indexOf(q.scriptContainerId||
"SHOULD_NOT_BE_SET")<0||A.innerHTML.indexOf(w)<0)){if(A.innerHTML.indexOf("(function(w,d,s,l,i)")>=0){t=String(B);break b}y=String(B)}}if(y){t=y;break b}}t=void 0}var C=t;if(C){Gj=!0;r=C;break a}}var E=[].slice.call(document.scripts);r=q.scriptElement?String(E.indexOf(q.scriptElement)):"-1"}q.htmlLoadOrder=r;q.loadScriptType=Hj(q)}var D=p?e.destination:e.container,F=D[n];F?(p&&F.state===0&&O(93),Object.assign(F,q)):D[n]=q},e=Jj(),f=oa(b),g=f.next();!g.done;g=f.next())d(g.value,!1);for(var k=oa(c),
m=k.next();!m.done;m=k.next())d(m.value,!0);e.canonical[Xj()]={};ek()}function gk(a){return!!Jj().container[a]}function hk(a){var b=Jj().destination[a];return!!b&&!!b.state}function ak(){return{ctid:Vj(),isDestination:Lj.oe}}function ik(a){var b=Jj();(b.siloed=b.siloed||[]).push(a)}function jk(){var a=Jj().container,b;for(b in a)if(a.hasOwnProperty(b)&&a[b].state===1)return!0;return!1}function kk(){var a={};z(Jj().destination,function(b,c){c.state===0&&(a[ck(b)]=c)});return a}
function lk(a){return!!(a&&a.parent&&a.context&&a.context.source===1&&a.parent.ctid.indexOf("GTM-")!==0)}var mk="/td?id="+ag.ctid,nk=["v","t","pid","dl","tdp"],ok=["mcc"],pk={},qk={};function rk(a,b,c){qk[a]=b;(c===void 0||c)&&sk(a)}function sk(a,b){if(pk[a]===void 0||(b===void 0?0:b))pk[a]=!0}function tk(a){a=a===void 0?!1:a;var b=Object.keys(pk).filter(function(c){return pk[c]===!0&&qk[c]!==void 0&&(a||!ok.includes(c))}).map(function(c){var d=qk[c];typeof d==="function"&&(d=d());return d?"&"+c+"="+d:""}).join("");return""+vj("https://www.googletagmanager.com")+mk+(""+b+"&z=0")}
function uk(){Object.keys(pk).forEach(function(a){nk.indexOf(a)<0&&(pk[a]=!1)})}function vk(a){a=a===void 0?!1:a;if(Dj&&ag.ctid){var b=tk(a);a?Zc(b):Oc(b);uk()}}function wk(){Object.keys(pk).filter(function(a){return pk[a]&&!nk.includes(a)}).length>0&&vk(!0)}var xk=Fb();function yk(){xk=Fb()}function zk(){rk("v","3");rk("t","t");rk("pid",function(){return String(xk)});Pc(G,"pagehide",wk);G.setInterval(yk,864E5)}var Ak=new function(a,b){this.j=a;this.defaultValue=b===void 0?!1:b}(1933);function Bk(){var a=Gc("google_tag_data",{});return a.ics=a.ics||new Ck}var Ck=function(){this.entries={};this.waitPeriodTimedOut=this.wasSetLate=this.accessedAny=this.accessedDefault=this.usedImplicit=this.usedUpdate=this.usedDefault=this.usedDeclare=this.active=!1;this.j=[]};
Ck.prototype.default=function(a,b,c,d,e,f,g){this.usedDefault||this.usedDeclare||!this.accessedDefault&&!this.accessedAny||(this.wasSetLate=!0);this.usedDefault=this.active=!0;ub("TAGGING",19);b==null?ub("TAGGING",18):Dk(this,a,b==="granted",c,d,e,f,g)};Ck.prototype.waitForUpdate=function(a,b,c){for(var d=0;d<a.length;d++)Dk(this,a[d],void 0,void 0,"","",b,c)};
var Dk=function(a,b,c,d,e,f,g,k){var m=a.entries,n=m[b]||{},p=n.region,q=d&&l(d)?d.toUpperCase():void 0;e=e.toUpperCase();f=f.toUpperCase();if(e===""||q===f||(q===e?p!==f:!q&&!p)){var r=!!(g&&g>0&&n.update===void 0),t={region:q,declare_region:n.declare_region,implicit:n.implicit,default:c!==void 0?c:n.default,declare:n.declare,update:n.update,quiet:r};if(e!==""||n.default!==!1)m[b]=t;r&&G.setTimeout(function(){m[b]===t&&t.quiet&&(ub("TAGGING",2),a.waitPeriodTimedOut=!0,a.clearTimeout(b,void 0,k),
a.notifyListeners())},g)}};ba=Ck.prototype;ba.clearTimeout=function(a,b,c){var d=[a],e=c.delegatedConsentTypes,f;for(f in e)e.hasOwnProperty(f)&&e[f]===a&&d.push(f);var g=this.entries[a]||{},k=this.getConsentState(a,c);if(g.quiet){g.quiet=!1;for(var m=oa(d),n=m.next();!n.done;n=m.next())Ek(this,n.value)}else if(b!==void 0&&k!==b)for(var p=oa(d),q=p.next();!q.done;q=p.next())Ek(this,q.value)};
ba.update=function(a,b,c){this.usedDefault||this.usedDeclare||this.usedUpdate||!this.accessedAny||(this.wasSetLate=!0);this.usedUpdate=this.active=!0;if(b!=null){var d=this.getConsentState(a,c),e=this.entries;(e[a]=e[a]||{}).update=b==="granted";this.clearTimeout(a,d,c)}};
ba.declare=function(a,b,c,d,e){this.usedDeclare=this.active=!0;var f=this.entries,g=f[a]||{},k=g.declare_region,m=c&&l(c)?c.toUpperCase():void 0;d=d.toUpperCase();e=e.toUpperCase();if(d===""||m===e||(m===d?k!==e:!m&&!k)){var n={region:g.region,declare_region:m,declare:b==="granted",implicit:g.implicit,default:g.default,update:g.update,quiet:g.quiet};if(d!==""||g.declare!==!1)f[a]=n}};
ba.implicit=function(a,b){this.usedImplicit=!0;var c=this.entries,d=c[a]=c[a]||{};d.implicit!==!1&&(d.implicit=b==="granted")};
ba.getConsentState=function(a,b){var c=this.entries,d=c[a]||{},e=d.update;if(e!==void 0)return e?1:2;if(zb(8)&&b.usedContainerScopedDefaults){var f=b.containerScopedDefaults[a];if(f===3)return 1;if(f===2)return 2}else if(e=d.default,e!==void 0)return e?1:2;if(b==null?0:b.delegatedConsentTypes.hasOwnProperty(a)){var g=b.delegatedConsentTypes[a],k=c[g]||{};e=k.update;if(e!==void 0)return e?1:2;if(zb(8)&&b.usedContainerScopedDefaults){var m=b.containerScopedDefaults[g];if(m===3)return 1;if(m===2)return 2}else if(e=
k.default,e!==void 0)return e?1:2}e=d.declare;if(e!==void 0)return e?1:2;e=d.implicit;return e!==void 0?e?3:4:0};ba.addListener=function(a,b){this.j.push({consentTypes:a,Ml:b})};var Ek=function(a,b){for(var c=0;c<a.j.length;++c){var d=a.j[c];Array.isArray(d.consentTypes)&&d.consentTypes.indexOf(b)!==-1&&(d.hk=!0)}};Ck.prototype.notifyListeners=function(a,b){for(var c=0;c<this.j.length;++c){var d=this.j[c];if(d.hk){d.hk=!1;try{d.Ml({consentEventId:a,consentPriorityId:b})}catch(e){}}}};var Fk=function(a){Fk[" "](a);return a};Fk[" "]=function(){};var Hk=function(){var a=Gk,b="Bh";if(a.Bh&&a.hasOwnProperty(b))return a.Bh;var c=new a;return a.Bh=c};var Gk=function(){var a={};this.j=function(){var b=Ak.j,c=Ak.defaultValue;return a[b]!=null?a[b]:c};this.D=function(){a[Ak.j]=!0}};var Ik=!1,Jk=!1,Kk={},Lk={delegatedConsentTypes:{},corePlatformServices:{},usedCorePlatformServices:!1,selectedAllCorePlatformServices:!1,containerScopedDefaults:(Kk.ad_storage=1,Kk.analytics_storage=1,Kk.ad_user_data=1,Kk.ad_personalization=1,Kk),usedContainerScopedDefaults:!1};function Mk(a){var b=Bk();b.accessedAny=!0;return(l(a)?[a]:a).every(function(c){switch(b.getConsentState(c,Lk)){case 1:case 3:return!0;case 2:case 4:return!1;default:return!0}})}
function Nk(a){var b=Bk();b.accessedAny=!0;return b.getConsentState(a,Lk)}function Ok(a){for(var b={},c=oa(a),d=c.next();!d.done;d=c.next()){var e=d.value;b[e]=Lk.corePlatformServices[e]!==!1}return b}function Pk(a){var b=Bk();b.accessedAny=!0;return!(b.entries[a]||{}).quiet}
function Qk(){if(!Hk().j())return!1;var a=Bk();a.accessedAny=!0;if(a.active)return!0;if(!zb(8)||!Lk.usedContainerScopedDefaults)return!1;for(var b=oa(Object.keys(Lk.containerScopedDefaults)),c=b.next();!c.done;c=b.next())if(Lk.containerScopedDefaults[c.value]!==1)return!0;return!1}function Rk(a,b){Bk().addListener(a,b)}function Sk(a,b){Bk().notifyListeners(a,b)}
function Tk(a,b){function c(){for(var e=0;e<b.length;e++)if(!Pk(b[e]))return!0;return!1}if(c()){var d=!1;Rk(b,function(e){d||c()||(d=!0,a(e))})}else a({})}
function Uk(a,b){function c(){for(var k=[],m=0;m<e.length;m++){var n=e[m];Mk(n)&&!f[n]&&k.push(n)}return k}function d(k){for(var m=0;m<k.length;m++)f[k[m]]=!0}var e=l(b)?[b]:b,f={},g=c();g.length!==e.length&&(d(g),Rk(e,function(k){function m(q){q.length!==0&&(d(q),k.consentTypes=q,a(k))}var n=c();if(n.length!==0){var p=Object.keys(f).length;n.length+p>=e.length?m(n):G.setTimeout(function(){m(c())},500)}}))};var Vk=["ad_storage","analytics_storage","ad_user_data","ad_personalization"],Wk=!1,Xk=!1;function Yk(){T(48)&&!Xk&&Wk&&(Vk.some(function(a){return Lk.containerScopedDefaults[a]!==1})||Zk("mbc"));Xk=!0}function Zk(a){Dj&&(rk(a,"1"),vk())}function $k(a){ub("HEALTH",a)};var al;try{al=JSON.parse(sb("eyIwIjoiVVMiLCIxIjoiVVMtTU4iLCIyIjpmYWxzZSwiMyI6IiIsIjQiOiIiLCI1Ijp0cnVlLCI2IjpmYWxzZSwiNyI6ImFkX3N0b3JhZ2V8YW5hbHl0aWNzX3N0b3JhZ2V8YWRfdXNlcl9kYXRhfGFkX3BlcnNvbmFsaXphdGlvbiJ9"))}catch(a){O(123),$k(2),al={}}function bl(){return al["0"]||""}function cl(){return al["1"]||""}function dl(){var a=!1;a=!!al["2"];return a}function el(){return al["6"]!==!1}function fl(){var a="";a=al["4"]||"";return a}
function gl(){var a=!1;a=!!al["5"];return a}function hl(){var a="";a=al["3"]||"";return a}var il=[P.g.R,P.g.U,P.g.P,P.g.ya],jl,kl;function ll(a){for(var b=a[P.g.Fb],c=Array.isArray(b)?b:[b],d={Ke:0};d.Ke<c.length;d={Ke:d.Ke},++d.Ke)z(a,function(e){return function(f,g){if(f!==P.g.Fb){var k=c[e.Ke],m=bl(),n=cl();Jk=!0;Ik&&ub("TAGGING",20);Bk().declare(f,g,k,m,n)}}}(d))}
function ml(a){Yk();!kl&&jl&&Zk("crc");kl=!0;var b=a[P.g.Fb];b&&O(40);var c=a[P.g.cf];c&&O(41);for(var d=Array.isArray(b)?b:[b],e={Le:0};e.Le<d.length;e={Le:e.Le},++e.Le)z(a,function(f){return function(g,k){if(g!==P.g.Fb&&g!==P.g.cf){var m=d[f.Le],n=Number(c),p=bl(),q=cl();n=n===void 0?0:n;Ik=!0;Jk&&ub("TAGGING",20);Bk().default(g,k,m,p,q,n,Lk)}}}(e))}
function nl(a){if(T(90)){zb(9)&&(Lk.usedContainerScopedDefaults=!0);var b=a[P.g.Fb];if(b){var c=Array.isArray(b)?b:[b];if(!c.includes(cl())&&!c.includes(bl()))return}z(a,function(d,e){switch(d){case "ad_storage":case "analytics_storage":case "ad_user_data":case "ad_personalization":break;default:return}zb(9)&&(Lk.usedContainerScopedDefaults=!0);Lk.containerScopedDefaults[d]=e==="granted"?3:2})}}
function ol(a,b){Yk();jl=!0;z(a,function(c,d){Ik=!0;Jk&&ub("TAGGING",20);Bk().update(c,d,Lk)});Sk(b.eventId,b.priorityId)}function pl(a){a.hasOwnProperty("all")&&(Lk.selectedAllCorePlatformServices=!0,z(qi,function(b){Lk.corePlatformServices[b]=a.all==="granted";Lk.usedCorePlatformServices=!0}));z(a,function(b,c){b!=="all"&&(Lk.corePlatformServices[b]=c==="granted",Lk.usedCorePlatformServices=!0)})}function W(a){Array.isArray(a)||(a=[a]);return a.every(function(b){return Mk(b)})}
function ql(a,b){Rk(a,b)}function rl(a,b){Uk(a,b)}function sl(a,b){Tk(a,b)}function tl(){var a=[P.g.R,P.g.ya,P.g.P];Bk().waitForUpdate(a,500,Lk)}function ul(a){for(var b=oa(a),c=b.next();!c.done;c=b.next()){var d=c.value;Bk().clearTimeout(d,void 0,Lk)}Sk()}var vl=function(){var a,b,c,d;La(new Ka(new Ga(function(e){if(e.j==1){if(vi.pscdl!==void 0)return e.return();a=function(f){vi.pscdl=f};b=function(){a("error")};e.O=2;c=Cc;if(!("cookieDeprecationLabel"in c)){a("noapi");e.j=4;return}a("pending");return Da(e,c.cookieDeprecationLabel.getValue().then(a).catch(b))}e.j!=2?(e.j=0,e.O=0):(d=Ea(e),b(d),e.j=0)})))};function wl(a,b){T(12)&&b&&z(b,function(c,d){typeof d!=="object"&&d!==void 0&&(a["1p."+c]=String(d))})};var xl=/[A-Z]+/,yl=/\s/;function zl(a,b){if(l(a)){a=Mb(a);var c=a.indexOf("-");if(!(c<0)){var d=a.substring(0,c);if(xl.test(d)){var e=a.substring(c+1),f;if(b){var g=function(n){var p=n.indexOf("/");return p<0?[n]:[n.substring(0,p),n.substring(p+1)]};f=g(e);if(d==="DC"&&f.length===2){var k=g(f[1]);k.length===2&&(f[1]=k[0],f.push(k[1]))}}else{f=e.split("/");for(var m=0;m<f.length;m++)if(!f[m]||yl.test(f[m])&&(d!=="AW"||m!==1))return}return{id:a,prefix:d,ia:d+"-"+f[0],ma:f}}}}}
function Al(a,b){for(var c={},d=0;d<a.length;++d){var e=zl(a[d],b);e&&(c[e.id]=e)}Bl(c);var f=[];z(c,function(g,k){f.push(k)});return f}function Bl(a){var b=[],c;for(c in a)if(a.hasOwnProperty(c)){var d=a[c];d.prefix==="AW"&&d.ma[Cl[2]]&&b.push(d.ia)}for(var e=0;e<b.length;++e)delete a[b[e]]}var Dl={},Cl=(Dl[0]=0,Dl[1]=0,Dl[2]=1,Dl[3]=0,Dl[4]=1,Dl[5]=2,Dl[6]=0,Dl[7]=0,Dl[8]=0,Dl);var El=Number('')||500,Fl={},Gl={},Hl={initialized:11,complete:12,interactive:13},Il={},Jl=Object.freeze((Il[P.g.Ka]=!0,Il)),Kl=H.location.search.indexOf("?gtm_diagnostics=")>=0||H.location.search.indexOf("&gtm_diagnostics=")>=0,Ll=void 0;
function Ml(a,b){if(b.length&&Dj){var c;(c=Fl)[a]!=null||(c[a]=[]);Gl[a]!=null||(Gl[a]=[]);var d=b.filter(function(e){return!Gl[a].includes(e)});Fl[a].push.apply(Fl[a],qa(d));Gl[a].push.apply(Gl[a],qa(d));!Ll&&d.length>0&&(sk("tdc",!0),Ll=G.setTimeout(function(){vk();Fl={};Ll=void 0},El))}}
function Nl(a,b,c){if(Dj&&a==="config"){var d,e=(d=zl(b))==null?void 0:d.ma;if(!(e&&e.length>1)){var f,g=Gc("google_tag_data",{});g.td||(g.td={});f=g.td;var k=h(c.K);h(c.j,k);var m=[],n;for(n in f)if(f.hasOwnProperty(n)){var p=Ol(f[n],k);p.length&&(Kl&&console.log(p),m.push(n))}m.length&&(Ml(b,m),ub("TAGGING",Hl[H.readyState]||14));f[b]=k}}}function Pl(a,b){var c={},d;for(d in b)b.hasOwnProperty(d)&&(c[d]=!0);for(var e in a)a.hasOwnProperty(e)&&(c[e]=!0);return c}
function Ol(a,b,c,d){c=c===void 0?{}:c;d=d===void 0?"":d;if(a===b)return[];var e=function(r,t){var u;db(t)==="object"?u=t[r]:db(t)==="array"&&(u=t[r]);return u===void 0?Jl[r]:u},f=Pl(a,b),g;for(g in f)if(f.hasOwnProperty(g)){var k=(d?d+".":"")+g,m=e(g,a),n=e(g,b),p=db(m)==="object"||db(m)==="array",q=db(n)==="object"||db(n)==="array";if(p&&q)Ol(m,n,c,k);else if(p||q||m!==n)c[k]=!0}return Object.keys(c)}
function Ql(){rk("tdc",function(){Ll&&(G.clearTimeout(Ll),Ll=void 0);var a=[],b;for(b in Fl)Fl.hasOwnProperty(b)&&a.push(b+"*"+Fl[b].join("."));return a.length?a.join("!"):void 0},!1)};var Rl=function(a,b,c,d,e,f,g,k,m,n,p){this.eventId=a;this.priorityId=b;this.j=c;this.O=d;this.H=e;this.K=f;this.D=g;this.eventMetadata=k;this.onSuccess=m;this.onFailure=n;this.isGtmEvent=p},Sl=function(a,b){var c=[];switch(b){case 3:c.push(a.j);c.push(a.O);c.push(a.H);c.push(a.K);c.push(a.D);break;case 2:c.push(a.j);break;case 1:c.push(a.O);c.push(a.H);c.push(a.K);c.push(a.D);break;case 4:c.push(a.j),c.push(a.O),c.push(a.H),c.push(a.K)}return c},U=function(a,b,c,d){for(var e=oa(Sl(a,d===void 0?3:
d)),f=e.next();!f.done;f=e.next()){var g=f.value;if(g[b]!==void 0)return g[b]}return c},Tl=function(a){for(var b={},c=Sl(a,4),d=oa(c),e=d.next();!e.done;e=d.next())for(var f=Object.keys(e.value),g=oa(f),k=g.next();!k.done;k=g.next())b[k.value]=1;return Object.keys(b)},Ul=function(a,b,c){function d(n){fb(n)&&z(n,function(p,q){f=!0;e[p]=q})}var e={},f=!1,g=Sl(a,c===void 0?3:c);g.reverse();for(var k=oa(g),m=k.next();!m.done;m=k.next())d(m.value[b]);return f?e:void 0},Vl=function(a){for(var b=[P.g.Sc,
P.g.Oc,P.g.Pc,P.g.Qc,P.g.Rc,P.g.Tc,P.g.Uc],c=Sl(a,3),d=oa(c),e=d.next();!e.done;e=d.next()){for(var f=e.value,g={},k=!1,m=oa(b),n=m.next();!n.done;n=m.next()){var p=n.value;f[p]!==void 0&&(g[p]=f[p],k=!0)}var q=k?g:void 0;if(q)return q}return{}},Wl=function(a,b){this.eventId=a;this.priorityId=b;this.D={};this.O={};this.j={};this.H={};this.W={};this.K={};this.eventMetadata={};this.isGtmEvent=!1;this.onSuccess=function(){};this.onFailure=function(){}},Xl=function(a,b){a.D=b;return a},Yl=function(a,
b){a.O=b;return a},Zl=function(a,b){a.j=b;return a},$l=function(a,b){a.H=b;return a},am=function(a,b){a.W=b;return a},bm=function(a,b){a.K=b;return a},cm=function(a,b){a.eventMetadata=b||{};return a},dm=function(a,b){a.onSuccess=b;return a},em=function(a,b){a.onFailure=b;return a},fm=function(a,b){a.isGtmEvent=b;return a},gm=function(a){return new Rl(a.eventId,a.priorityId,a.D,a.O,a.j,a.H,a.K,a.eventMetadata,a.onSuccess,a.onFailure,a.isGtmEvent)};var hm={xk:Number("5"),co:Number("")},im=[];function jm(a){im.push(a)}var km="?id="+ag.ctid,lm=void 0,mm={},nm=void 0,om=new function(){var a=5;hm.xk>0&&(a=hm.xk);this.D=a;this.j=0;this.H=[]},pm=1E3;
function qm(a,b){var c=lm;if(c===void 0)if(b)c=Mi();else return"";for(var d=[vj("https://www.googletagmanager.com"),"/a",km],e=oa(im),f=e.next();!f.done;f=e.next())for(var g=f.value,k=g({eventId:c,mc:!!a}),m=oa(k),n=m.next();!n.done;n=m.next()){var p=oa(n.value),q=p.next().value,r=p.next().value;d.push("&"+q+"="+r)}d.push("&z=0");return d.join("")}
function rm(){nm&&(G.clearTimeout(nm),nm=void 0);if(lm!==void 0&&sm){var a;(a=mm[lm])||(a=om.j<om.D?!1:Ob()-om.H[om.j%om.D]<1E3);if(a||pm--<=0)O(1),mm[lm]=!0;else{var b=om.j++%om.D;om.H[b]=Ob();var c=qm(!0);Oc(c);sm=!1}}}var sm=!1;function tm(a){mm[a]||(a!==lm&&(rm(),lm=a),sm=!0,nm||(nm=G.setTimeout(rm,500)),qm().length>=2022&&rm())}var um=Fb();function vm(){um=Fb()}function wm(){return[["v","3"],["t","t"],["pid",String(um)]]}var xm={};function ym(a,b,c){Cj&&a!==void 0&&(xm[a]=xm[a]||[],xm[a].push(c+b),tm(a))}function zm(a){var b=a.eventId,c=a.mc,d=[],e=xm[b]||[];e.length&&d.push(["epr",e.join(".")]);c&&delete xm[b];return d};function Am(a,b){var c=zl(Wj(a),!0);c&&Bm.register(c,b)}function Cm(a,b,c,d){var e=zl(c,d.isGtmEvent);e&&(T(47)&&T(47)&&Ai&&(d.deferrable=!0),Bm.push("event",[b,a],e,d))}function Dm(a,b,c,d){var e=zl(c,d.isGtmEvent);e&&Bm.push("get",[a,b],e,d)}function Em(a){var b=zl(Wj(a),!0),c;b?c=Fm(Bm,b).j:c={};return c}function Gm(a,b){var c=zl(Wj(a),!0);if(c){var d=Bm,e=h(b,null);h(Fm(d,c).j,e);Fm(d,c).j=e}}
var Hm=function(){this.O={};this.j={};this.D={};this.W=null;this.K={};this.H=!1;this.status=1},Im=function(a,b,c,d){this.D=Ob();this.j=b;this.args=c;this.messageContext=d;this.type=a},Jm=function(){this.destinations={};this.D={};this.j=[]},Fm=function(a,b){var c=b.ia;return a.destinations[c]=a.destinations[c]||new Hm},Km=function(a,b,c,d){if(d.j){var e=Fm(a,d.j),f=e.W;if(f){var g=h(c,null),k=h(e.O[d.j.id],null),m=h(e.K,null),n=h(e.j,null),p=h(a.D,null),q={};if(Cj)try{q=h(Ti)}catch(v){O(72)}var r=
d.j.prefix,t=function(v){ym(d.messageContext.eventId,r,v)},u=gm(fm(em(dm(cm(am($l(bm(Zl(Yl(Xl(new Wl(d.messageContext.eventId,d.messageContext.priorityId),g),k),m),n),p),q),d.messageContext.eventMetadata),function(){if(t){var v=t;t=void 0;v("2");if(d.messageContext.onSuccess)d.messageContext.onSuccess()}}),function(){if(t){var v=t;t=void 0;v("3");if(d.messageContext.onFailure)d.messageContext.onFailure()}}),!!d.messageContext.isGtmEvent));try{ym(d.messageContext.eventId,r,"1"),Nl(d.type,d.j.id,u),
f(d.j.id,b,d.D,u)}catch(v){ym(d.messageContext.eventId,r,"4")}}}};Jm.prototype.register=function(a,b,c){var d=Fm(this,a);d.status!==3&&(d.W=b,d.status=3,c&&(h(d.j,c),d.j=c),this.flush())};Jm.prototype.push=function(a,b,c,d){c!==void 0&&(Fm(this,c).status===1&&(Fm(this,c).status=2,this.push("require",[{}],c,{})),Fm(this,c).H&&(d.deferrable=!1));this.j.push(new Im(a,c,b,d));d.deferrable||this.flush()};
Jm.prototype.flush=function(a){for(var b=this,c=[],d=!1,e={};this.j.length;e={Ec:void 0,th:void 0}){var f=this.j[0],g=f.j;if(f.messageContext.deferrable)!g||Fm(this,g).H?(f.messageContext.deferrable=!1,this.j.push(f)):c.push(f),this.j.shift();else{switch(f.type){case "require":if(Fm(this,g).status!==3&&!a){this.j.push.apply(this.j,c);return}break;case "set":z(f.args[0],function(r,t){h(Wb(r,t),b.D)});break;case "config":var k=Fm(this,g);e.Ec={};z(f.args[0],function(r){return function(t,u){h(Wb(t,u),
r.Ec)}}(e));var m=!!e.Ec[P.g.fc];delete e.Ec[P.g.fc];var n=g.ia===g.id;m||(n?k.K={}:k.O[g.id]={});k.H&&m||Km(this,P.g.ba,e.Ec,f);k.H=!0;n?h(e.Ec,k.K):(h(e.Ec,k.O[g.id]),O(70));d=!0;break;case "event":e.th={};z(f.args[0],function(r){return function(t,u){h(Wb(t,u),r.th)}}(e));Km(this,f.args[1],e.th,f);break;case "get":var p={},q=(p[P.g.tb]=f.args[0],p[P.g.Jb]=f.args[1],p);Km(this,P.g.Ua,q,f)}this.j.shift();Lm(this,f)}}this.j.push.apply(this.j,c);d&&this.flush()};
var Lm=function(a,b){if(b.type!=="require")if(b.j)for(var c=Fm(a,b.j).D[b.type]||[],d=0;d<c.length;d++)c[d]();else for(var e in a.destinations)if(a.destinations.hasOwnProperty(e)){var f=a.destinations[e];if(f&&f.D)for(var g=f.D[b.type]||[],k=0;k<g.length;k++)g[k]()}},Bm=new Jm;var Mm=function(a,b){var c=function(){};c.prototype=a.prototype;var d=new c;a.apply(d,Array.prototype.slice.call(arguments,1));return d},Nm=function(a){var b=a;return function(){if(b){var c=b;b=null;c()}}};var Om=function(a,b,c){a.addEventListener&&a.addEventListener(b,c,!1)},Pm=function(a,b,c){a.removeEventListener&&a.removeEventListener(b,c,!1)};var Qm,Rm;a:{for(var Sm=["CLOSURE_FLAGS"],Tm=Oa,Um=0;Um<Sm.length;Um++)if(Tm=Tm[Sm[Um]],Tm==null){Rm=null;break a}Rm=Tm}var Vm=Rm&&Rm[610401301];Qm=Vm!=null?Vm:!1;function Wm(){var a=Oa.navigator;if(a){var b=a.userAgent;if(b)return b}return""}var Xm,Ym=Oa.navigator;Xm=Ym?Ym.userAgentData||null:null;function Zm(a){return Qm?Xm?Xm.brands.some(function(b){var c;return(c=b.brand)&&c.indexOf(a)!=-1}):!1:!1}function $m(a){return Wm().indexOf(a)!=-1};function an(){return Qm?!!Xm&&Xm.brands.length>0:!1}function bn(){return an()?!1:$m("Opera")}function cn(){return $m("Firefox")||$m("FxiOS")}function dn(){return an()?Zm("Chromium"):($m("Chrome")||$m("CriOS"))&&!(an()?0:$m("Edge"))||$m("Silk")};function en(){return Qm?!!Xm&&!!Xm.platform:!1}function fn(){return $m("iPhone")&&!$m("iPod")&&!$m("iPad")}function gn(){fn()||$m("iPad")||$m("iPod")};bn();an()||$m("Trident")||$m("MSIE");$m("Edge");!$m("Gecko")||Wm().toLowerCase().indexOf("webkit")!=-1&&!$m("Edge")||$m("Trident")||$m("MSIE")||$m("Edge");Wm().toLowerCase().indexOf("webkit")!=-1&&!$m("Edge")&&$m("Mobile");en()||$m("Macintosh");en()||$m("Windows");(en()?Xm.platform==="Linux":$m("Linux"))||en()||$m("CrOS");en()||$m("Android");fn();$m("iPad");$m("iPod");gn();Wm().toLowerCase().indexOf("kaios");var hn=function(a,b,c,d){for(var e=b,f=c.length;(e=a.indexOf(c,e))>=0&&e<d;){var g=a.charCodeAt(e-1);if(g==38||g==63){var k=a.charCodeAt(e+f);if(!k||k==61||k==38||k==35)return e}e+=f+1}return-1},jn=/#|$/,kn=function(a,b){var c=a.search(jn),d=hn(a,0,b,c);if(d<0)return null;var e=a.indexOf("&",d);if(e<0||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.slice(d,e!==-1?e:0).replace(/\+/g," "))},ln=/[?&]($|#)/,mn=function(a,b,c){for(var d,e=a.search(jn),f=0,g,k=[];(g=hn(a,f,b,e))>=0;)k.push(a.substring(f,
g)),f=Math.min(a.indexOf("&",g)+1||e,e);k.push(a.slice(f));d=k.join("").replace(ln,"$1");var m,n=c!=null?"="+encodeURIComponent(String(c)):"";var p=b+n;if(p){var q,r=d.indexOf("#");r<0&&(r=d.length);var t=d.indexOf("?"),u;t<0||t>r?(t=r,u=""):u=d.substring(t+1,r);q=[d.slice(0,t),u,d.slice(r)];var v=q[1];q[1]=p?v?v+"&"+p:p:v;m=q[0]+(q[1]?"?"+q[1]:"")+q[2]}else m=d;return m};var nn=function(a){try{var b;if(b=!!a&&a.location.href!=null)a:{try{Fk(a.foo);b=!0;break a}catch(c){}b=!1}return b}catch(c){return!1}},on=function(a,b){if(a)for(var c in a)Object.prototype.hasOwnProperty.call(a,c)&&b(a[c],c,a)},pn=function(a){if(G.top==G)return 0;if(a===void 0?0:a){var b=G.location.ancestorOrigins;if(b)return b[b.length-1]==G.location.origin?1:2}return nn(G.top)?1:2},qn=function(a){a=a===void 0?document:a;return a.createElement("img")};function rn(a,b,c,d){d=d===void 0?!1:d;a.google_image_requests||(a.google_image_requests=[]);var e=qn(a.document);if(c){var f=function(){if(c){var g=a.google_image_requests,k=wc(g,e);k>=0&&Array.prototype.splice.call(g,k,1)}Pm(e,"load",f);Pm(e,"error",f)};Om(e,"load",f);Om(e,"error",f)}d&&(e.attributionSrc="");e.src=b;a.google_image_requests.push(e)}
var tn=function(a){var b;b=b===void 0?!1:b;var c="https://pagead2.googlesyndication.com/pagead/gen_204?id=tcfe";on(a,function(d,e){if(d||d===0)c+="&"+e+"="+encodeURIComponent(""+d)});sn(c,b)},sn=function(a,b){var c=window,d;b=b===void 0?!1:b;d=d===void 0?!1:d;if(c.fetch){var e={keepalive:!0,credentials:"include",redirect:"follow",method:"get",mode:"no-cors"};d&&(e.mode="cors","setAttributionReporting"in XMLHttpRequest.prototype?e.attributionReporting={eventSourceEligible:"true",triggerEligible:"false"}:
e.headers={"Attribution-Reporting-Eligible":"event-source"});c.fetch(a,e)}else rn(c,a,b===void 0?!1:b,d===void 0?!1:d)};var un=function(){this.O=this.O;this.D=this.D};un.prototype.O=!1;un.prototype.dispose=function(){this.O||(this.O=!0,this.Ca())};un.prototype[Symbol.dispose]=function(){this.dispose()};un.prototype.addOnDisposeCallback=function(a,b){this.O?b!==void 0?a.call(b):a():(this.D||(this.D=[]),b&&(a=a.bind(b)),this.D.push(a))};un.prototype.Ca=function(){if(this.D)for(;this.D.length;)this.D.shift()()};var vn=function(a){a.addtlConsent!==void 0&&typeof a.addtlConsent!=="string"&&(a.addtlConsent=void 0);a.gdprApplies!==void 0&&typeof a.gdprApplies!=="boolean"&&(a.gdprApplies=void 0);return a.tcString!==void 0&&typeof a.tcString!=="string"||a.listenerId!==void 0&&typeof a.listenerId!=="number"?2:a.cmpStatus&&a.cmpStatus!=="error"?0:3},wn=function(a,b){b=b===void 0?{}:b;un.call(this);this.H=a;this.j=null;this.W={};this.If=0;var c;this.me=(c=b.nn)!=null?c:500;var d;this.xb=(d=b.Qn)!=null?d:!1;this.K=
null};za(wn,un);wn.prototype.Ca=function(){this.W={};this.K&&(Pm(this.H,"message",this.K),delete this.K);delete this.W;delete this.H;delete this.j;un.prototype.Ca.call(this)};var yn=function(a){return typeof a.H.__tcfapi==="function"||xn(a)!=null};
wn.prototype.addEventListener=function(a){var b=this,c={internalBlockOnErrors:this.xb},d=Nm(function(){return a(c)}),e=0;this.me!==-1&&(e=setTimeout(function(){c.tcString="tcunavailable";c.internalErrorState=1;d()},this.me));var f=function(g,k){clearTimeout(e);g?(c=g,c.internalErrorState=vn(c),c.internalBlockOnErrors=b.xb,k&&c.internalErrorState===0||(c.tcString="tcunavailable",k||(c.internalErrorState=3))):(c.tcString="tcunavailable",c.internalErrorState=3);a(c)};try{zn(this,"addEventListener",f)}catch(g){c.tcString=
"tcunavailable",c.internalErrorState=3,e&&(clearTimeout(e),e=0),d()}};wn.prototype.removeEventListener=function(a){a&&a.listenerId&&zn(this,"removeEventListener",null,a.listenerId)};
var Bn=function(a,b,c){var d;d=d===void 0?"755":d;var e;a:{if(a.publisher&&a.publisher.restrictions){var f=a.publisher.restrictions[b];if(f!==void 0){e=f[d===void 0?"755":d];break a}}e=void 0}var g=e;if(g===0)return!1;var k=c;c===2?(k=0,g===2&&(k=1)):c===3&&(k=1,g===1&&(k=0));var m;if(k===0)if(a.purpose&&a.vendor){var n=An(a.vendor.consents,d===void 0?"755":d);m=n&&b==="1"&&a.purposeOneTreatment&&a.publisherCC==="CH"?!0:n&&An(a.purpose.consents,b)}else m=!0;else m=k===1?a.purpose&&a.vendor?An(a.purpose.legitimateInterests,
b)&&An(a.vendor.legitimateInterests,d===void 0?"755":d):!0:!0;return m},An=function(a,b){return!(!a||!a[b])},zn=function(a,b,c,d){c||(c=function(){});if(typeof a.H.__tcfapi==="function"){var e=a.H.__tcfapi;e(b,2,c,d)}else if(xn(a)){Cn(a);var f=++a.If;a.W[f]=c;if(a.j){var g={};a.j.postMessage((g.__tcfapiCall={command:b,version:2,callId:f,parameter:d},g),"*")}}else c({},!1)},xn=function(a){if(a.j)return a.j;var b;a:{for(var c=a.H,d=0;d<50;++d){var e;try{e=!(!c.frames||!c.frames.__tcfapiLocator)}catch(k){e=
!1}if(e){b=c;break a}var f;b:{try{var g=c.parent;if(g&&g!=c){f=g;break b}}catch(k){}f=null}if(!(c=f))break}b=null}a.j=b;return a.j},Cn=function(a){a.K||(a.K=function(b){try{var c;c=(typeof b.data==="string"?JSON.parse(b.data):b.data).__tcfapiReturn;a.W[c.callId](c.returnValue,c.success)}catch(d){}},Om(a.H,"message",a.K))},Dn=function(a){if(a.gdprApplies===!1)return!0;a.internalErrorState===void 0&&(a.internalErrorState=vn(a));return a.cmpStatus==="error"||a.internalErrorState!==0?a.internalBlockOnErrors?
(tn({e:String(a.internalErrorState)}),!1):!0:a.cmpStatus!=="loaded"||a.eventStatus!=="tcloaded"&&a.eventStatus!=="useractioncomplete"?!1:!0};var En={1:0,3:0,4:0,7:3,9:3,10:3};function Fn(){var a=vi.tcf||{};return vi.tcf=a}var Gn=function(){return new wn(G,{nn:-1})};
function Hn(){var a=Fn(),b=Gn();yn(b)&&!In()&&!Jn()&&O(124);if(!a.active&&yn(b)){In()&&(a.active=!0,a.kc={},a.cmpId=0,a.tcfPolicyVersion=0,Bk().active=!0,a.tcString="tcunavailable");tl();try{b.addEventListener(function(c){if(c.internalErrorState!==0)Kn(a),ul([P.g.R,P.g.ya,P.g.P]),Bk().active=!0;else if(a.gdprApplies=c.gdprApplies,a.cmpId=c.cmpId,a.enableAdvertiserConsentMode=c.enableAdvertiserConsentMode,Jn()&&(a.active=!0),!Ln(c)||In()||Jn()){a.tcfPolicyVersion=c.tcfPolicyVersion;var d;if(c.gdprApplies===
!1){var e={},f;for(f in En)En.hasOwnProperty(f)&&(e[f]=!0);d=e;b.removeEventListener(c)}else if(Ln(c)){var g={},k;for(k in En)if(En.hasOwnProperty(k))if(k==="1"){var m,n=c,p={Ql:!0};p=p===void 0?{}:p;m=Dn(n)?n.gdprApplies===!1?!0:n.tcString==="tcunavailable"?!p.Xj:(p.Xj||n.gdprApplies!==void 0||p.Ql)&&(p.Xj||typeof n.tcString==="string"&&n.tcString.length)?Bn(n,"1",0):!0:!1;g["1"]=m}else g[k]=Bn(c,k,En[k]);d=g}if(d){a.tcString=c.tcString||"tcempty";a.kc=d;var q={},r=(q[P.g.R]=a.kc["1"]?"granted":
"denied",q);a.gdprApplies!==!0?(ul([P.g.R,P.g.ya,P.g.P]),Bk().active=!0):(r[P.g.ya]=a.kc["3"]&&a.kc["4"]?"granted":"denied",typeof a.tcfPolicyVersion==="number"&&a.tcfPolicyVersion>=4?r[P.g.P]=a.kc["1"]&&a.kc["7"]?"granted":"denied":ul([P.g.P]),ol(r,{eventId:0},{gdprApplies:a?a.gdprApplies:void 0,tcString:Mn()||""}))}}else ul([P.g.R,P.g.ya,P.g.P])})}catch(c){Kn(a),ul([P.g.R,P.g.ya,P.g.P]),Bk().active=!0}}}function Kn(a){a.type="e";a.tcString="tcunavailable"}
function Ln(a){return a.eventStatus==="tcloaded"||a.eventStatus==="useractioncomplete"||a.eventStatus==="cmpuishown"}function In(){return G.gtag_enable_tcf_support===!0}function Jn(){return Fn().enableAdvertiserConsentMode===!0}function Mn(){var a=Fn();if(a.active)return a.tcString}function Nn(){var a=Fn();if(a.active&&a.gdprApplies!==void 0)return a.gdprApplies?"1":"0"}function On(a){if(!En.hasOwnProperty(String(a)))return!0;var b=Fn();return b.active&&b.kc?!!b.kc[String(a)]:!0}var Pn=[P.g.R,P.g.U,P.g.P,P.g.ya],Qn={},Rn=(Qn[P.g.R]=1,Qn[P.g.U]=2,Qn);function Sn(a){if(a===void 0)return 0;switch(U(a,P.g.ka)){case void 0:return 1;case !1:return 3;default:return 2}}function Tn(a){if(cl()==="US-CO"&&Cc.globalPrivacyControl===!0)return!1;var b=Sn(a);if(b===3)return!1;switch(Nk(P.g.ya)){case 1:case 3:return!0;case 2:return!1;case 4:return b===2;case 0:return!0;default:return!1}}function Un(){return Qk()||!Mk(P.g.R)||!Mk(P.g.U)}
function Vn(){var a={},b;for(b in Rn)Rn.hasOwnProperty(b)&&(a[Rn[b]]=Nk(b));return"G1"+Ue(a[1]||0)+Ue(a[2]||0)}var Wn={},Xn=(Wn[P.g.R]=0,Wn[P.g.U]=1,Wn[P.g.P]=2,Wn[P.g.ya]=3,Wn);function eo(a){switch(a){case void 0:return 1;case !0:return 3;case !1:return 2;default:return 0}}
function fo(a){for(var b="1",c=0;c<Pn.length;c++){var d=b,e,f=Pn[c],g=Lk.delegatedConsentTypes[f];e=g===void 0?0:Xn.hasOwnProperty(g)?12|Xn[g]:8;var k=Bk();k.accessedAny=!0;var m=k.entries[f]||{};e=e<<2|eo(m.implicit);b=d+(""+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[e]+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[eo(m.declare)<<4|eo(m.default)<<2|eo(m.update)])}var n=b,p=(cl()==="US-CO"&&Cc.globalPrivacyControl===!0?1:0)<<3,q=(Qk()?1:0)<<2,r=Sn(a);b=
n+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[p|q|r];T(90)&&(b+=""+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[Lk.containerScopedDefaults.ad_storage<<4|Lk.containerScopedDefaults.analytics_storage<<2|Lk.containerScopedDefaults.ad_user_data]+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[(zb(8)&&Lk.usedContainerScopedDefaults?1:0)<<2|Lk.containerScopedDefaults.ad_personalization]);return b}
function go(){if(!Mk(P.g.P))return"-";for(var a=Object.keys(qi),b=Ok(a),c="",d=oa(a),e=d.next();!e.done;e=d.next()){var f=e.value;b[f]&&(c+=qi[f])}(Lk.usedCorePlatformServices?Lk.selectedAllCorePlatformServices:1)&&(c+="o");return c||"-"}function ho(){return el()||(In()||Jn())&&Nn()==="1"?"1":"0"}function io(){return(el()?!0:!(!In()&&!Jn())&&Nn()==="1")||!Mk(P.g.P)}
function jo(){var a="0",b="0",c;var d=Fn();c=d.active?d.cmpId:void 0;typeof c==="number"&&c>=0&&c<=4095&&(a="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[c>>6&63],b="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[c&63]);var e="0",f;var g=Fn();f=g.active?g.tcfPolicyVersion:void 0;typeof f==="number"&&f>=0&&f<=63&&(e="0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[f]);var k=0;el()&&(k|=1);Nn()==="1"&&(k|=2);In()&&(k|=4);var m;var n=Fn();m=n.enableAdvertiserConsentMode!==
void 0?n.enableAdvertiserConsentMode?"1":"0":void 0;m==="1"&&(k|=8);Bk().waitPeriodTimedOut&&(k|=16);return"1"+a+b+e+"0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ-_"[k]}function ko(){return cl()==="US-CO"};function lo(){var a=!1;return a};var mo={UA:1,AW:2,DC:3,G:4,GF:5,GT:12,GTM:14,HA:6,MC:7};
function no(a){a=a===void 0?{}:a;var b=ag.ctid.split("-")[0].toUpperCase(),c={};c.ctid=ag.ctid;c.Sm=ui.se;c.Wm=ui.Yg;c.xm=Lj.oe?2:1;c.gn=a.pk;c.ze=ag.canonicalContainerId;c.ze!==a.xa&&(c.xa=a.xa);var d=Yj();c.Im=d?d.canonicalContainerId:void 0;Bi?(c.Yf=mo[b],c.Yf||(c.Yf=0)):c.Yf=Fi?13:10;Oi.H?(c.Wf=0,c.xl=2):Di?c.Wf=1:lo()?c.Wf=2:c.Wf=3;var e={};e[6]=Pj;Oi.D===2?e[7]=!0:Oi.D===1&&(e[2]=!0);c.Al=e;var f=a.Nf,g;var k=c.Yf,m=c.Wf;k===void 0?g="":(m||(m=0),g=""+We(1,1)+Te(k<<2|m));var n=c.xl,p="4"+g+
(n?""+We(2,1)+Te(n):""),q,r=c.Wm;q=r&&Ve.test(r)?""+We(3,2)+r:"";var t,u=c.Sm;t=u?""+We(4,1)+Te(u):"";var v;var w=c.ctid;if(w&&f){var x=w.split("-"),y=x[0].toUpperCase();if(y!=="GTM"&&y!=="OPT")v="";else{var B=x[1];v=""+We(5,3)+Te(1+B.length)+(c.xm||0)+B}}else v="";var A=c.gn,C=c.ze,E=c.xa,D=c.ao,F=p+q+t+v+(A?""+We(6,1)+Te(A):"")+(C?""+We(7,3)+Te(C.length)+C:"")+(E?""+We(8,3)+Te(E.length)+E:"")+(D?""+We(9,3)+Te(D.length)+D:""),L;var M=c.Al;M=M===void 0?{}:M;for(var S=[],V=oa(Object.keys(M)),aa=V.next();!aa.done;aa=
V.next()){var X=aa.value;S[Number(X)]=M[X]}if(S.length){var R=We(10,3),ma;if(S.length===0)ma=Te(0);else{for(var la=[],ha=0,ya=!1,Na=0;Na<S.length;Na++){ya=!0;var Fa=Na%6;S[Na]&&(ha|=1<<Fa);Fa===5&&(la.push(Te(ha)),ha=0,ya=!1)}ya&&la.push(Te(ha));ma=la.join("")}var Sa=ma;L=""+R+Te(Sa.length)+Sa}else L="";var bb=c.Im;return F+L+(bb?""+We(11,3)+Te(bb.length)+bb:"")};var oo={Ej:"service_worker_endpoint",ah:"shared_user_id",bh:"shared_user_id_requested",ue:"shared_user_id_source"},po;function qo(a){if(!po){po={};for(var b=oa(Object.keys(oo)),c=b.next();!c.done;c=b.next())po[oo[c.value]]=!0}return!!po[a]}
function ro(a,b){b=b===void 0?!1:b;if(qo(a)){var c,d,e=(d=(c=Gc("google_tag_data",{})).xcd)!=null?d:c.xcd={};if(e[a])return e[a];if(b){var f=void 0,g=1,k={},m={set:function(n){f=n;m.notify()},get:function(){return f},subscribe:function(n){k[String(g)]=n;return g++},unsubscribe:function(n){var p=String(n);return k.hasOwnProperty(p)?(delete k[p],!0):!1},notify:function(){for(var n=oa(Object.keys(k)),p=n.next();!p.done;p=n.next()){var q=p.value;try{k[q](a,f)}catch(r){}}}};return e[a]=m}}}
function so(a,b){var c=ro(a,!0);c&&c.set(b)}function to(a){var b;return(b=ro(a))==null?void 0:b.get()}function uo(a,b){if(typeof b==="function"){var c;return(c=ro(a,!0))==null?void 0:c.subscribe(b)}}function vo(a,b){var c=ro(a);return c?c.unsubscribe(b):!1};function wo(a){return a.origin!=="null"};function xo(a,b,c,d){var e;if(yo(d)){for(var f=[],g=String(b||zo()).split(";"),k=0;k<g.length;k++){var m=g[k].split("="),n=m[0].replace(/^\s*|\s*$/g,"");if(n&&n===a){var p=m.slice(1).join("=").replace(/^\s*|\s*$/g,"");p&&c&&(p=decodeURIComponent(p));f.push(p)}}e=f}else e=[];return e}
function Ao(a,b,c,d,e){if(yo(e)){var f=Bo(a,d,e);if(f.length===1)return f[0].id;if(f.length!==0){f=Co(f,function(g){return g.Gl},b);if(f.length===1)return f[0].id;f=Co(f,function(g){return g.Km},c);return f[0]?f[0].id:void 0}}}function Do(a,b,c,d){var e=zo(),f=window;wo(f)&&(f.document.cookie=a);var g=zo();return e!==g||c!==void 0&&xo(b,g,!1,d).indexOf(c)>=0}
function Eo(a,b,c,d){function e(w,x,y){if(y==null)return delete k[x],w;k[x]=y;return w+"; "+x+"="+y}function f(w,x){if(x==null)return w;k[x]=!0;return w+"; "+x}if(!yo(c.Db))return 2;var g;b==null?g=a+"=deleted; expires="+(new Date(0)).toUTCString():(c.encode&&(b=encodeURIComponent(b)),b=Fo(b),g=a+"="+b);var k={};g=e(g,"path",c.path);var m;c.expires instanceof Date?m=c.expires.toUTCString():c.expires!=null&&(m=""+c.expires);g=e(g,"expires",m);g=e(g,"max-age",c.Bm);g=e(g,"samesite",c.Xm);c.Ym&&(g=f(g,
"secure"));var n=c.domain;if(n&&n.toLowerCase()==="auto"){for(var p=Go(),q=void 0,r=!1,t=0;t<p.length;++t){var u=p[t]!=="none"?p[t]:void 0,v=e(g,"domain",u);v=f(v,c.flags);try{d&&d(a,k)}catch(w){q=w;continue}r=!0;if(!Ho(u,c.path)&&Do(v,a,b,c.Db))return 0}if(q&&!r)throw q;return 1}n&&n.toLowerCase()!=="none"&&(g=e(g,"domain",n));g=f(g,c.flags);d&&d(a,k);return Ho(n,c.path)?1:Do(g,a,b,c.Db)?0:1}function Io(a,b,c){c.path==null&&(c.path="/");c.domain||(c.domain="auto");return Eo(a,b,c)}
function Co(a,b,c){for(var d=[],e=[],f,g=0;g<a.length;g++){var k=a[g],m=b(k);m===c?d.push(k):f===void 0||m<f?(e=[k],f=m):m===f&&e.push(k)}return d.length>0?d:e}function Bo(a,b,c){for(var d=[],e=xo(a,void 0,void 0,c),f=0;f<e.length;f++){var g=e[f].split("."),k=g.shift();if(!b||!k||b.indexOf(k)!==-1){var m=g.shift();if(m){var n=m.split("-");d.push({id:g.join("."),Gl:Number(n[0])||1,Km:Number(n[1])||1})}}}return d}function Fo(a){a&&a.length>1200&&(a=a.substring(0,1200));return a}
var Jo=/^(www\.)?google(\.com?)?(\.[a-z]{2})?$/,Ko=/(^|\.)doubleclick\.net$/i;function Ho(a,b){return a!==void 0&&(Ko.test(window.document.location.hostname)||b==="/"&&Jo.test(a))}function Lo(a){if(!a)return 1;var b=a;zb(11)&&a==="none"&&(b=window.document.location.hostname);b=b.indexOf(".")===0?b.substring(1):b;return b.split(".").length}function Mo(a){if(!a||a==="/")return 1;a[0]!=="/"&&(a="/"+a);a[a.length-1]!=="/"&&(a+="/");return a.split("/").length-1}
function No(a,b){var c=""+Lo(a),d=Mo(b);d>1&&(c+="-"+d);return c}
var zo=function(){return wo(window)?window.document.cookie:""},yo=function(a){return a&&Hk().j()?(Array.isArray(a)?a:[a]).every(function(b){return Pk(b)&&Mk(b)}):!0},Go=function(){var a=[],b=window.document.location.hostname.split(".");if(b.length===4){var c=b[b.length-1];if(Number(c).toString()===c)return["none"]}for(var d=b.length-2;d>=0;d--)a.push(b.slice(d).join("."));var e=window.document.location.hostname;Ko.test(e)||Jo.test(e)||a.push("none");return a};function Oo(a){var b=Math.round(Math.random()*2147483647),c;if(a){var d=1,e,f,g;if(a)for(d=0,f=a.length-1;f>=0;f--)g=a.charCodeAt(f),d=(d<<6&268435455)+g+(g<<14),e=d&266338304,d=e!==0?d^e>>21:d;c=String(b^d&2147483647)}else c=String(b);return c}function Po(a){return[Oo(a),Math.round(Ob()/1E3)].join(".")}function Qo(a,b,c,d,e){var f=Lo(b);return Ao(a,f,Mo(c),d,e)}function Ro(a,b,c,d){return[b,No(c,d),a].join(".")};function So(a,b,c,d){var e,f=Number(a.Cb!=null?a.Cb:void 0);f!==0&&(e=new Date((b||Ob())+1E3*(f||7776E3)));return{path:a.path,domain:a.domain,flags:a.flags,encode:!!c,expires:e,Db:d}};var To;function Uo(){function a(g){c(g.target||g.srcElement||{})}function b(g){d(g.target||g.srcElement||{})}var c=Vo,d=Wo,e=Xo();if(!e.init){Pc(H,"mousedown",a);Pc(H,"keyup",a);Pc(H,"submit",b);var f=HTMLFormElement.prototype.submit;HTMLFormElement.prototype.submit=function(){d(this);f.call(this)};e.init=!0}}function Yo(a,b,c,d,e){var f={callback:a,domains:b,fragment:c===2,placement:c,forms:d,sameHost:e};Xo().decorators.push(f)}
function Zo(a,b,c){for(var d=Xo().decorators,e={},f=0;f<d.length;++f){var g=d[f],k;if(k=!c||g.forms)a:{var m=g.domains,n=a,p=!!g.sameHost;if(m&&(p||n!==H.location.hostname))for(var q=0;q<m.length;q++)if(m[q]instanceof RegExp){if(m[q].test(n)){k=!0;break a}}else if(n.indexOf(m[q])>=0||p&&m[q].indexOf(n)>=0){k=!0;break a}k=!1}if(k){var r=g.placement;r===void 0&&(r=g.fragment?2:1);r===b&&Rb(e,g.callback())}}return e}
function Xo(){var a=Gc("google_tag_data",{}),b=a.gl;b&&b.decorators||(b={decorators:[]},a.gl=b);return b};var $o=/(.*?)\*(.*?)\*(.*)/,ap=/^https?:\/\/([^\/]*?)\.?cdn\.ampproject\.org\/?(.*)/,bp=/^(?:www\.|m\.|amp\.)+/,cp=/([^?#]+)(\?[^#]*)?(#.*)?/;function dp(a){var b=cp.exec(a);if(b)return{Oh:b[1],query:b[2],fragment:b[3]}}
function ep(a,b){var c=[Cc.userAgent,(new Date).getTimezoneOffset(),Cc.userLanguage||Cc.language,Math.floor(Ob()/60/1E3)-(b===void 0?0:b),a].join("*"),d;if(!(d=To)){for(var e=Array(256),f=0;f<256;f++){for(var g=f,k=0;k<8;k++)g=g&1?g>>>1^3988292384:g>>>1;e[f]=g}d=e}To=d;for(var m=4294967295,n=0;n<c.length;n++)m=m>>>8^To[(m^c.charCodeAt(n))&255];return((m^-1)>>>0).toString(36)}
function fp(){return function(a){var b=nj(G.location.href),c=b.search.replace("?",""),d=gj(c,"_gl",!1,!0)||"";a.query=gp(d)||{};var e=hj(b,"fragment"),f;var g=-1;if(Tb(e,"_gl="))g=4;else{var k=e.indexOf("&_gl=");k>0&&(g=k+3+2)}if(g<0)f=void 0;else{var m=e.indexOf("&",g);f=m<0?e.substring(g):e.substring(g,m)}a.fragment=gp(f||"")||{}}}function hp(a){var b=fp(),c=Xo();c.data||(c.data={query:{},fragment:{}},b(c.data));var d={},e=c.data;e&&(Rb(d,e.query),a&&Rb(d,e.fragment));return d}
var gp=function(a){try{var b=ip(a,3);if(b!==void 0){for(var c={},d=b?b.split("*"):[],e=0;e+1<d.length;e+=2){var f=d[e],g=sb(d[e+1]);c[f]=g}ub("TAGGING",6);return c}}catch(k){ub("TAGGING",8)}};function ip(a,b){if(a){var c;a:{for(var d=a,e=0;e<3;++e){var f=$o.exec(d);if(f){c=f;break a}d=decodeURIComponent(d)}c=void 0}var g=c;if(g&&g[1]==="1"){var k=g[3],m;a:{for(var n=g[2],p=0;p<b;++p)if(n===ep(k,p)){m=!0;break a}m=!1}if(m)return k;ub("TAGGING",7)}}}
function jp(a,b,c,d,e){function f(p){var q=p,r=(new RegExp("(.*?)(^|&)"+a+"=([^&]*)&?(.*)")).exec(q),t=q;if(r){var u=r[2],v=r[4];t=r[1];v&&(t=t+u+v)}p=t;var w=p.charAt(p.length-1);p&&w!=="&"&&(p+="&");return p+n}d=d===void 0?!1:d;e=e===void 0?!1:e;var g=dp(c);if(!g)return"";var k=g.query||"",m=g.fragment||"",n=a+"="+b;d?m.substring(1).length!==0&&e||(m="#"+f(m.substring(1))):k="?"+f(k.substring(1));return""+g.Oh+k+m}
function kp(a,b){function c(n,p,q){var r;a:{for(var t in n)if(n.hasOwnProperty(t)){r=!0;break a}r=!1}if(r){var u,v=[],w;for(w in n)if(n.hasOwnProperty(w)){var x=n[w];x!==void 0&&x===x&&x!==null&&x.toString()!=="[object Object]"&&(v.push(w),v.push(rb(String(x))))}var y=v.join("*");u=["1",ep(y),y].join("*");d?(zb(4)||zb(1)||!p)&&lp("_gl",u,a,p,q):mp("_gl",u,a,p,q)}}var d=(a.tagName||"").toUpperCase()==="FORM",e=Zo(b,1,d),f=Zo(b,2,d),g=Zo(b,4,d),k=Zo(b,3,d);c(e,!1,!1);c(f,!0,!1);zb(1)&&c(g,!0,!0);for(var m in k)k.hasOwnProperty(m)&&
np(m,k[m],a)}function np(a,b,c){c.tagName.toLowerCase()==="a"?mp(a,b,c):c.tagName.toLowerCase()==="form"&&lp(a,b,c)}function mp(a,b,c,d,e){d=d===void 0?!1:d;e=e===void 0?!1:e;var f;if(f=c.href){var g;if(!(g=!zb(5)||d)){var k=G.location.href,m=dp(c.href),n=dp(k);g=!(m&&n&&m.Oh===n.Oh&&m.query===n.query&&m.fragment)}f=g}if(f){var p=jp(a,b,c.href,d,e);sc.test(p)&&(c.href=p)}}
function lp(a,b,c,d,e){d=d===void 0?!1:d;e=e===void 0?!1:e;if(c&&c.action){var f=(c.method||"").toLowerCase();if(f!=="get"||d){if(f==="get"||f==="post"){var g=jp(a,b,c.action,d,e);sc.test(g)&&(c.action=g)}}else{for(var k=c.childNodes||[],m=!1,n=0;n<k.length;n++){var p=k[n];if(p.name===a){p.setAttribute("value",b);m=!0;break}}if(!m){var q=H.createElement("input");q.setAttribute("type","hidden");q.setAttribute("name",a);q.setAttribute("value",b);c.appendChild(q)}}}}
function Vo(a){try{var b;a:{for(var c=a,d=100;c&&d>0;){if(c.href&&c.nodeName.match(/^a(?:rea)?$/i)){b=c;break a}c=c.parentNode;d--}b=null}var e=b;if(e){var f=e.protocol;f!=="http:"&&f!=="https:"||kp(e,e.hostname)}}catch(g){}}function Wo(a){try{if(a.action){var b=hj(nj(a.action),"host");kp(a,b)}}catch(c){}}function op(a,b,c,d){Uo();var e=c==="fragment"?2:1;d=!!d;Yo(a,b,e,d,!1);e===2&&ub("TAGGING",23);d&&ub("TAGGING",24)}function pp(a,b){Uo();Yo(a,[jj(G.location,"host",!0)],b,!0,!0)}
function qp(){var a=H.location.hostname,b=ap.exec(H.referrer);if(!b)return!1;var c=b[2],d=b[1],e="";if(c){var f=c.split("/"),g=f[1];e=g==="s"?decodeURIComponent(f[2]):decodeURIComponent(g)}else if(d){if(d.indexOf("xn--")===0)return!1;e=d.replace(/-/g,".").replace(/\.\./g,"-")}var k=a.replace(bp,""),m=e.replace(bp,"");return k===m||Ub(k,"."+m)}function rp(a,b){return a===!1?!1:a||b||qp()};var sp=["1"],tp={},up={};function vp(a,b){b=b===void 0?!0:b;var c=wp(a.prefix);if(!tp[c])if(xp(c,a.path,a.domain)){var d=up[wp(a.prefix)];yp(a,d?d.id:void 0,d?d.Ih:void 0)}else{var e=pj("auiddc");if(e)ub("TAGGING",17),tp[c]=e;else if(b){var f=wp(a.prefix),g=Po();zp(f,g,a);xp(c,a.path,a.domain)}}}function yp(a,b,c){var d=wp(a.prefix),e=tp[d];if(e){var f=e.split(".");if(f.length===2){var g=Number(f[1])||0;if(g){var k=e;b&&(k=e+"."+b+"."+(c?c:Math.floor(Ob()/1E3)));zp(d,k,a,g*1E3)}}}}
function zp(a,b,c,d){var e=Ro(b,"1",c.domain,c.path),f=So(c,d);f.Db=Ap();Io(a,e,f)}function xp(a,b,c){var d=Qo(a,b,c,sp,Ap());if(!d)return!1;Bp(a,d);return!0}function Bp(a,b){var c=b.split(".");c.length===5?(tp[a]=c.slice(0,2).join("."),up[a]={id:c.slice(2,4).join("."),Ih:Number(c[4])||0}):c.length===3?up[a]={id:c.slice(0,2).join("."),Ih:Number(c[2])||0}:tp[a]=b}function wp(a){return(a||"_gcl")+"_au"}function Cp(a){function b(){Mk(c)&&a()}var c=Ap();Tk(function(){b();Mk(c)||Uk(b,c)},c)}
function Dp(a){var b=hp(!0),c=wp(a.prefix);Cp(function(){var d=b[c];if(d){Bp(c,d);var e=Number(tp[c].split(".")[1])*1E3;if(e){ub("TAGGING",16);var f=So(a,e);f.Db=Ap();var g=Ro(d,"1",a.domain,a.path);Io(c,g,f)}}})}function Ep(a,b,c,d,e){e=e||{};var f=function(){var g={},k=Qo(a,e.path,e.domain,sp,Ap());k&&(g[a]=k);return g};Cp(function(){op(f,b,c,d)})}function Ap(){return["ad_storage","ad_user_data"]};function Fp(a){for(var b=[],c=H.cookie.split(";"),d=new RegExp("^\\s*"+(a||"_gac")+"_(UA-\\d+-\\d+)=\\s*(.+?)\\s*$"),e=0;e<c.length;e++){var f=c[e].match(d);f&&b.push({di:f[1],value:f[2],timestamp:Number(f[2].split(".")[1])||0})}b.sort(function(g,k){return k.timestamp-g.timestamp});return b}
function Gp(a,b){var c=Fp(a),d={};if(!c||!c.length)return d;for(var e=0;e<c.length;e++){var f=c[e].value.split(".");if(!(f[0]!=="1"||b&&f.length<3||!b&&f.length!==3)&&Number(f[1])){d[c[e].di]||(d[c[e].di]=[]);var g={version:f[0],timestamp:Number(f[1])*1E3,aa:f[2]};b&&f.length>3&&(g.labels=f.slice(3));d[c[e].di].push(g)}}return d};var Hp={},Ip=(Hp.k={Na:/^[\w-]+$/},Hp.b={Na:/^[\w-]+$/,Vh:!0},Hp.i={Na:/^[1-9]\d*$/},Hp);var Jp={},Mp=(Jp[5]={zk:{2:Kp},jh:["k","i","b"]},Jp[4]={zk:{2:Kp,GCL:Lp},jh:["k","i","b"]},Jp);function Np(a){var b=Mp[5];if(b){var c=a.split(".")[0];if(c){var d=b.zk[c];if(d)return d(a,5)}}}function Kp(a,b){var c=a.split(".");if(c.length===3){var d={},e=Mp[b];if(e){for(var f=e.jh,g=oa(c[2].split("$")),k=g.next();!k.done;k=g.next()){var m=k.value,n=m[0];if(f.indexOf(n)!==-1)try{var p=decodeURIComponent(m.substring(1)),q=Ip[n];q&&(q.Vh?(d[n]=d[n]||[],d[n].push(p)):d[n]=p)}catch(r){}}return d}}}
function Op(a,b){var c=Mp[5];if(c){for(var d=[],e=oa(c.jh),f=e.next();!f.done;f=e.next()){var g=f.value,k=Ip[g];if(k){var m=a[g];if(m!==void 0)if(k.Vh&&Array.isArray(m))for(var n=oa(m),p=n.next();!p.done;p=n.next())d.push(encodeURIComponent(""+g+p.value));else d.push(encodeURIComponent(""+g+m))}}return["2",b||"1",d.join("$")].join(".")}}function Lp(a){var b=a.split(".");b.shift();var c=b.shift(),d=b.shift(),e={};return e.k=d,e.i=c,e.b=b,e};var Pp=new Map([[5,"ad_storage"],[4,["ad_storage","ad_user_data"]]]);function Qp(a){if(Mp[5]){for(var b=[],c=xo(a,void 0,void 0,Pp.get(5)),d=oa(c),e=d.next();!e.done;e=d.next()){var f=Np(e.value);f&&(Rp(f),b.push(f))}return b}}function Sp(a,b,c,d){c=c||{};var e=No(c.domain,c.path),f=Op(b,e);if(f){var g=So(c,d,void 0,Pp.get(5));Io(a,f,g)}}function Tp(a,b){var c=b.Na;return typeof c==="function"?c(a):c.test(a)}
function Rp(a){for(var b=oa(Object.keys(a)),c=b.next(),d={};!c.done;d={Be:void 0},c=b.next()){var e=c.value,f=a[e];d.Be=Ip[e];d.Be?d.Be.Vh?a[e]=Array.isArray(f)?f.filter(function(g){return function(k){return Tp(k,g.Be)}}(d)):void 0:typeof f==="string"&&Tp(f,d.Be)||(a[e]=void 0):a[e]=void 0}};var Up=/^\w+$/,Vp=/^[\w-]+$/,Wp={},Xp=(Wp.aw="_aw",Wp.dc="_dc",Wp.gf="_gf",Wp.gp="_gp",Wp.gs="_gs",Wp.ha="_ha",Wp.ag="_ag",Wp.gb="_gb",Wp);function Yp(){return["ad_storage","ad_user_data"]}function Zp(a){return!Hk().j()||Mk(a)}function $p(a,b){function c(){var d=Zp(b);d&&a();return d}Tk(function(){c()||Uk(c,b)},b)}function aq(a){return bq(a).map(function(b){return b.aa})}function cq(a){return dq(a).filter(function(b){return b.aa}).map(function(b){return b.aa})}
function dq(a){var b=eq(a.prefix),c=fq("gb",b),d=fq("ag",b);if(!d||!c)return[];var e=function(k){return function(m){m.type=k;return m}},f=bq(c).map(e("gb")),g=(zb(7)?gq(d):[]).map(e("ag"));return f.concat(g).sort(function(k,m){return m.timestamp-k.timestamp})}function hq(a,b,c,d,e){var f=Eb(a,function(g){return g.aa===c});f?(f.timestamp=Math.max(f.timestamp,d),f.labels=iq(f.labels||[],e||[])):a.push({version:b,aa:c,timestamp:d,labels:e})}
function gq(a){for(var b=Qp(a)||[],c=[],d=oa(b),e=d.next();!e.done;e=d.next()){var f=e.value,g=f,k=jq(f);k&&hq(c,"2",g.k,k,g.b||[])}return c.sort(function(m,n){return n.timestamp-m.timestamp})}function bq(a){for(var b=[],c=xo(a,H.cookie,void 0,Yp()),d=oa(c),e=d.next();!e.done;e=d.next()){var f=kq(e.value);if(f!=null){var g=f;hq(b,g.version,g.aa,g.timestamp,g.labels)}}b.sort(function(k,m){return m.timestamp-k.timestamp});return lq(b)}
function iq(a,b){if(!a.length)return b;if(!b.length)return a;var c={};return a.concat(b).filter(function(d){return c.hasOwnProperty(d)?!1:c[d]=!0})}function eq(a){return a&&typeof a==="string"&&a.match(Up)?a:"_gcl"}
function mq(a,b){var c=zb(7),d=nj(a),e=hj(d,"query",!1,void 0,"gclid"),f=hj(d,"query",!1,void 0,"gclsrc"),g=hj(d,"query",!1,void 0,"wbraid");g=$b(g);var k;c&&(k=hj(d,"query",!1,void 0,"gbraid"));var m=hj(d,"query",!1,void 0,"gad_source"),n=hj(d,"query",!1,void 0,"dclid");if(b&&(!e||!f||!g||c&&!k)){var p=d.hash.replace("#","");e=e||gj(p,"gclid",!1);f=f||gj(p,"gclsrc",!1);g=g||gj(p,"wbraid",!1);c&&(k=k||gj(p,"gbraid",!1));m=m||gj(p,"gad_source",!1)}return nq(e,f,n,g,k,m)}
function oq(){return mq(G.location.href,!0)}
function nq(a,b,c,d,e,f){var g={},k=function(m,n){g[n]||(g[n]=[]);g[n].push(m)};g.gclid=a;g.gclsrc=b;g.dclid=c;if(a!==void 0&&a.match(Vp))switch(b){case void 0:k(a,"aw");break;case "aw.ds":k(a,"aw");k(a,"dc");break;case "ds":k(a,"dc");break;case "3p.ds":k(a,"dc");break;case "gf":k(a,"gf");break;case "ha":k(a,"ha")}c&&k(c,"dc");d!==void 0&&Vp.test(d)&&(g.wbraid=d,k(d,"gb"));zb(7)&&e!==void 0&&Vp.test(e)&&(g.gbraid=e,k(e,"ag"));f!==void 0&&Vp.test(f)&&(g.gad_source=f,k(f,"gs"));return g}
function pq(a){var b=oq();if(zb(6)){for(var c=!0,d=oa(Object.keys(b)),e=d.next();!e.done;e=d.next())if(b[e.value]!==void 0){c=!1;break}c&&(b=mq(G.document.referrer,!1))}qq(b,!1,a)}
function qq(a,b,c,d,e){c=c||{};e=e||[];var f=eq(c.prefix),g=d||Ob(),k=Math.round(g/1E3),m=Yp(),n=!1,p=!1,q=function(){if(Zp(m)){var r=So(c,g,!0);r.Db=m;for(var t=function(F,L){var M=fq(F,f);M&&(Io(M,L,r),F!=="gb"&&(n=!0))},u=function(F){var L=["GCL",k,F];e.length>0&&L.push(e.join("."));return L.join(".")},v=oa(["aw","dc","gf","ha","gp"]),w=v.next();!w.done;w=v.next()){var x=w.value;a[x]&&t(x,u(a[x][0]))}if(!n&&a.gb){var y=a.gb[0],B=fq("gb",f);!b&&bq(B).some(function(F){return F.aa===y&&F.labels&&
F.labels.length>0})||t("gb",u(y))}}if(!p&&zb(7)&&a.gbraid&&Zp("ad_storage")&&(p=!0,!n)){var A=a.gbraid,C=fq("ag",f);if(b||!(zb(7)?gq(C):[]).some(function(F){return F.aa===A&&F.labels&&F.labels.length>0})){var E={},D=(E.k=A,E.i=""+k,E.b=e,E);Sp(C,D,c,g)}}rq(a,f,g,c)};Tk(function(){q();Zp(m)||Uk(q,m)},m)}function rq(a,b,c,d){if(a.gad_source!==void 0&&Zp("ad_storage")){var e=fq("gs",b);if(e){var f=Math.round((Ob()-(ad()||0))/1E3),g={},k=(g.k=a.gad_source,g.i=""+f,g);Sp(e,k,d,c)}}}
function sq(a,b){var c=hp(!0);$p(function(){for(var d=eq(b.prefix),e=0;e<a.length;++e){var f=a[e];if(Xp[f]!==void 0){var g=fq(f,d),k=c[g];if(k){var m=Math.min(tq(k),Ob()),n;b:{for(var p=m,q=xo(g,H.cookie,void 0,Yp()),r=0;r<q.length;++r)if(tq(q[r])>p){n=!0;break b}n=!1}if(!n){var t=So(b,m,!0);t.Db=Yp();Io(g,k,t)}}}}qq(nq(c.gclid,c.gclsrc),!1,b)},Yp())}
function uq(a){var b=[];zb(7)&&b.push("ag");if(b.length!==0){var c=hp(!0),d=eq(a.prefix);$p(function(){for(var e=0;e<b.length;++e){var f=fq(b[e],d);if(f){var g=c[f];if(g){var k=Np(g);if(k){var m=jq(k);m||(m=Ob());var n;a:{for(var p=m,q=Qp(f),r=0;r<q.length;++r)if(jq(q[r])>p){n=!0;break a}n=!1}if(n)break;k.i=""+Math.round(m/1E3);Sp(f,k,a,m)}}}}},["ad_storage"])}}function fq(a,b){var c=Xp[a];if(c!==void 0)return b+c}
function tq(a){return vq(a.split(".")).length!==0?(Number(a.split(".")[1])||0)*1E3:0}function jq(a){return a?(Number(a.i)||0)*1E3:0}function kq(a){var b=vq(a.split("."));return b.length===0?null:{version:b[0],aa:b[2],timestamp:(Number(b[1])||0)*1E3,labels:b.slice(3)}}function vq(a){return a.length<3||a[0]!=="GCL"&&a[0]!=="1"||!/^\d+$/.test(a[1])||!Vp.test(a[2])?[]:a}
function wq(a,b,c,d,e){if(Array.isArray(b)&&wo(G)){var f=eq(e),g=function(){for(var k={},m=0;m<a.length;++m){var n=fq(a[m],f);if(n){var p=xo(n,H.cookie,void 0,Yp());p.length&&(k[n]=p.sort()[p.length-1])}}return k};$p(function(){op(g,b,c,d)},Yp())}}
function xq(a,b,c,d){if(Array.isArray(a)&&wo(G)){var e=[];zb(7)&&e.push("ag");if(e.length!==0){var f=eq(d),g=function(){for(var k={},m=0;m<e.length;++m){var n=fq(e[m],f);if(!n)return{};var p=Qp(n);if(p.length){var q=p.sort(function(r,t){return jq(t)-jq(r)})[0];k[n]=Op(q)}}return k};$p(function(){op(g,a,b,c)},["ad_storage"])}}}function lq(a){return a.filter(function(b){return Vp.test(b.aa)})}
function yq(a,b){if(wo(G)){for(var c=eq(b.prefix),d={},e=0;e<a.length;e++)Xp[a[e]]&&(d[a[e]]=Xp[a[e]]);$p(function(){z(d,function(f,g){var k=xo(c+g,H.cookie,void 0,Yp());k.sort(function(t,u){return tq(u)-tq(t)});if(k.length){var m=k[0],n=tq(m),p=vq(m.split(".")).length!==0?m.split(".").slice(3):[],q={},r;r=vq(m.split(".")).length!==0?m.split(".")[2]:void 0;q[f]=[r];qq(q,!0,b,n,p)}})},Yp())}}
function zq(a){var b=[],c=[];zb(7)&&(b.push("ag"),c.push("gbraid"));b.length!==0&&$p(function(){for(var d=eq(a.prefix),e=0;e<b.length;++e){var f=fq(b[e],d);if(!f)break;var g=Qp(f);if(g.length){var k=g.sort(function(q,r){return jq(r)-jq(q)})[0],m=jq(k),n=k.b,p={};p[c[e]]=k.k;qq(p,!0,a,m,n)}}},["ad_storage"])}function Aq(a,b){for(var c=0;c<b.length;++c)if(a[b[c]])return!0;return!1}
function Bq(a){function b(e,f,g){g&&(e[f]=g)}if(Qk()){var c=oq();if(Aq(c,a)){var d={};b(d,"gclid",c.gclid);b(d,"dclid",c.dclid);b(d,"gclsrc",c.gclsrc);b(d,"wbraid",c.wbraid);zb(7)&&b(d,"gbraid",c.gbraid);pp(function(){return d},3);pp(function(){var e={};return e._up="1",e},1)}}}
function Cq(a){if(!zb(1))return null;var b=hp(!0).gad_source;if(b!=null)return G.location.hash="",b;if(zb(2)){var c=nj(G.location.href);b=hj(c,"query",!1,void 0,"gad_source");if(b!=null)return b;var d=oq();if(Aq(d,a))return"0"}return null}function Dq(a){var b=Cq(a);b!=null&&pp(function(){var c={};return c.gad_source=b,c},4)}
function Eq(a,b,c){var d=[];if(b.length===0)return d;for(var e={},f=0;f<b.length;f++){var g=b[f],k=g.type?g.type:"gcl";(g.labels||[]).indexOf(c)===-1?(a.push(0),e[k]||d.push(g)):a.push(1);e[k]=!0}return d}function Fq(a,b,c,d){var e=[];c=c||{};if(!Zp(Yp()))return e;var f=bq(a),g=Eq(e,f,b);if(g.length&&!d)for(var k=oa(g),m=k.next();!m.done;m=k.next()){var n=m.value,p=n.timestamp,q=[n.version,Math.round(p/1E3),n.aa].concat(n.labels||[],[b]).join("."),r=So(c,p,!0);r.Db=Yp();Io(a,q,r)}return e}
function Gq(a,b){var c=[];b=b||{};var d=dq(b),e=Eq(c,d,a);if(e.length)for(var f=oa(e),g=f.next();!g.done;g=f.next()){var k=g.value,m=eq(b.prefix),n=fq(k.type,m);if(!n)break;var p=k,q=p.version,r=p.aa,t=p.labels,u=p.timestamp,v=Math.round(u/1E3);if(k.type==="ag"){var w={},x=(w.k=r,w.i=""+v,w.b=(t||[]).concat([a]),w);Sp(n,x,b,u)}else if(k.type==="gb"){var y=[q,v,r].concat(t||[],[a]).join("."),B=So(b,u,!0);B.Db=Yp();Io(n,y,B)}}return c}
function Hq(a,b){var c=eq(b),d=fq(a,c);if(!d)return 0;var e;e=a==="ag"?zb(7)?gq(d):[]:bq(d);for(var f=0,g=0;g<e.length;g++)f=Math.max(f,e[g].timestamp);return f}function Iq(a){for(var b=0,c=oa(Object.keys(a)),d=c.next();!d.done;d=c.next())for(var e=a[d.value],f=0;f<e.length;f++)b=Math.max(b,Number(e[f].timestamp));return b}function Jq(a,b){var c=Math.max(Hq("aw",a),Iq(Zp(Yp())?Gp():{})),d=Math.max(Hq("gb",a),Iq(Zp(Yp())?Gp("_gac_gb",!0):{}));zb(7)&&b&&(d=Math.max(d,Hq("ag",a)));return d>c};
var Kq=function(a,b,c){var d=vi.joined_auid=vi.joined_auid||{},e=(c?a||"_gcl":"")+"."+b;if(d[e])return!0;d[e]=!0;return!1},Lq=function(){var a=nj(G.location.href),b=void 0,c=void 0,d=hj(a,"query",!1,void 0,"gad_source"),e=a.hash.replace("#",""),f=gj(e,"gad_source",!1);d&&f?(b=d,c=1):d?(b=d,c=2):f&&(b=f,c=3);return{rd:b,Uj:c}},Mq=function(){var a=nj(G.location.href),b=hj(a,"query",!1,void 0,"gad_source");if(b===void 0){var c=a.hash.replace("#","");b=gj(c,"gad_source",!1)}return b},Nq=function(){var a=
nj(G.location.href).search.replace("?","");return gj(a,"gad",!1,!0)==="1"},Oq=function(){var a=pn(!1)===1?G.top.location.href:G.location.href;return a=a.replace(/[\?#].*$/,"")},Pq=function(a){var b=[];z(a,function(c,d){d=lq(d);for(var e=[],f=0;f<d.length;f++)e.push(d[f].aa);e.length&&b.push(c+":"+e.join(","))});return b.join(";")},Rq=function(a,b,c){if(a==="aw"||a==="dc"||a==="gb"){var d=pj("gcl"+a);if(d)return d.split(".")}var e=eq(b);if(e==="_gcl"){var f=!W(Qq())&&c,g;g=oq()[a]||[];if(g.length>
0)return f?["0"]:g}var k=fq(a,e);return k?aq(k):[]},Sq=function(a){var b=Qq();sl(function(){a();W(b)||Uk(a,b)},b)},Qq=function(){return[P.g.R,P.g.P]},Tq=/^(www\.)?google(\.com?)?(\.[a-z]{2}t?)?$/,Uq=/^www.googleadservices.com$/,Vq=function(a,b){return Rq("aw",a,b)},Wq=function(a,b){return Rq("dc",a,b)},Xq=function(a,b,c,d,e){var f=oq(),g=[],k=c&&Tn(c),m=f.gclid,n=f.dclid,p=f.gclsrc||"aw",q=Nq(),r,t;if(T(64)){var u=Lq();r=u.rd;t=u.Uj}else r=Mq();!m||p!=="aw.ds"&&p!=="aw"&&p!=="ds"&&p!=="3p.ds"||g.push({aa:m,
Ie:p});n&&g.push({aa:n,Ie:"ds"});g.length===2&&O(147);g.length===0&&f.wbraid&&g.push({aa:f.wbraid,Ie:"gb"});g.length===0&&p==="aw.ds"&&g.push({aa:"",Ie:"aw.ds"});Sq(function(){var v=W(Qq());if(v){vp(a);var w=[],x=v?tp[wp(a.prefix)]:void 0;x&&w.push("auid="+x);if(W(P.g.P)){e&&w.push("userId="+e);var y=to(oo.ah);if(y===void 0)so(oo.bh,!0);else{var B=to(oo.ue);w.push("ga_uid="+B+"."+y)}}var A=H.referrer?hj(nj(H.referrer),"host"):"",C=v||!d?g:[];C.length===0&&(Tq.test(A)||Uq.test(A))&&C.push({aa:"",Ie:""});
if(C.length!==0||q||r!==void 0){A&&w.push("ref="+encodeURIComponent(A));var E=Oq();w.push("url="+encodeURIComponent(E));w.push("tft="+Ob());var D=ad();D!==void 0&&w.push("tfd="+Math.round(D));var F=pn(!0);w.push("frm="+F);q&&w.push("gad=1");r!==void 0&&w.push("gad_source="+encodeURIComponent(r));t!==void 0&&w.push("gad_source_src="+encodeURIComponent(t.toString()));if(!c){var L={};c=gm(Xl(new Wl(0),(L[P.g.ka]=Bm.D[P.g.ka],L)))}else if(!T(77)){var M={};c=gm(Xl(new Wl(0),(M[P.g.ka]=k,M)))}w.push("gtm="+
no({xa:b}));Un()&&w.push("gcs="+Vn());w.push("gcd="+fo(c));io()&&w.push("dma_cps="+go());w.push("dma="+ho());Tn(c)?w.push("npa=0"):w.push("npa=1");ko()&&w.push("_ng=1");yn(Gn())&&w.push("tcfd="+jo());var S=Nn();S&&w.push("gdpr="+S);var V=Mn();V&&w.push("gdpr_consent="+V);T(17)&&w.push("apve="+(T(18)?1:0));Oi.j&&w.push("tag_exp="+Oi.j);if(C.length>0)for(var aa=0;aa<C.length;aa++){var X=C[aa],R=X.aa,ma=X.Ie;if(!Kq(a.prefix,ma+"."+R,x!==void 0)){var la='https://adservice.google.com/pagead/regclk?'+w.join("&");
R!==""?la=ma==="gb"?la+"&wbraid="+R:la+"&gclid="+R+"&gclsrc="+ma:ma==="aw.ds"&&(la+="&gclsrc=aw.ds");Vc(la)}}else if((q||r!==void 0)&&!Kq(a.prefix,"gad",x!==void 0)){var ha='https://adservice.google.com/pagead/regclk?'+w.join("&");Vc(ha)}}}})};function Yq(){vi.dedupe_gclid||(vi.dedupe_gclid=Po());return vi.dedupe_gclid};var Zq=/^(www\.)?google(\.com?)?(\.[a-z]{2}t?)?$/,$q=/^www.googleadservices.com$/;function ar(a){a||(a=br());return a.rn?!1:a.bm||a.dm||a.gm||a.fm||a.zh||a.rd||a.Pl||a.Tl?!0:!1}
function br(){var a={},b=hp(!0);a.rn=!!b._up;var c=oq();a.bm=c.aw!==void 0;a.dm=c.dc!==void 0;a.gm=c.wbraid!==void 0;a.fm=c.gbraid!==void 0;var d=nj(G.location.href),e=hj(d,"query",!1,void 0,"gad");a.zh=e!==void 0;if(!a.zh){var f=d.hash.replace("#",""),g=gj(f,"gad",!1);a.zh=g!==void 0}a.rd=hj(d,"query",!1,void 0,"gad_source");if(a.rd===void 0){var k=d.hash.replace("#",""),m=gj(k,"gad_source",!1);a.rd=m}var n=H.referrer?hj(nj(H.referrer),"host"):"";a.Tl=Zq.test(n);a.Pl=$q.test(n);return a};var cr=RegExp("^UA-\\d+-\\d+%3A[\\w-]+(?:%2C[\\w-]+)*(?:%3BUA-\\d+-\\d+%3A[\\w-]+(?:%2C[\\w-]+)*)*$"),dr=/^~?[\w-]+(?:\.~?[\w-]+)*$/,er=/^\d+\.fls\.doubleclick\.net$/,fr=/;gac=([^;?]+)/,gr=/;gacgb=([^;?]+)/;
function hr(a,b){if(er.test(H.location.host)){var c=H.location.href.match(b);return c&&c.length===2&&c[1].match(cr)?decodeURIComponent(c[1]):""}for(var d=[],e=oa(Object.keys(a)),f=e.next();!f.done;f=e.next()){for(var g=f.value,k=[],m=a[g],n=0;n<m.length;n++)k.push(m[n].aa);d.push(g+":"+k.join(","))}return d.length>0?d.join(";"):""}
function ir(a,b,c){for(var d=Zp(Yp())?Gp("_gac_gb",!0):{},e=[],f=!1,g=oa(Object.keys(d)),k=g.next();!k.done;k=g.next()){var m=k.value,n=Fq("_gac_gb_"+m,a,b,c);f=f||n.length!==0&&n.some(function(p){return p===1});e.push(m+":"+n.join(","))}return{Ol:f?e.join(";"):"",Nl:hr(d,gr)}}function jr(a){var b=H.location.href.match(new RegExp(";"+a+"=([^;?]+)"));return b&&b.length===2&&b[1].match(dr)?b[1]:void 0}
function kr(a){var b={vh:void 0,wh:void 0},c,d;er.test(H.location.host)&&(c=jr("gclgs"),d=jr("gclst"));if(c&&d)b.vh=c,b.wh=d;else{var e=Ob(),f=gq((a||"_gcl")+"_gs"),g=f.map(function(m){return m.aa}),k=f.map(function(m){return e-m.timestamp});g.length>0&&k.length>0&&(b.vh=g.join("."),b.wh=k.join("."))}return b}
function lr(a,b,c){if(er.test(H.location.host)){var d=jr(c);if(d)return[{aa:d}]}else{if(b==="gclid")return bq((a||"_gcl")+"_aw");if(b==="wbraid")return bq((a||"_gcl")+"_gb");if(b==="braids")return dq({prefix:a})}return[]}function mr(a){return lr(a,"gclid","gclaw").map(function(b){return b.aa}).join(".")}function nr(a){return lr(a,"wbraid","gclgb").map(function(b){return b.aa}).join(".")}function or(a){return lr(a,"braids","gclgb").map(function(b){return b.aa}).join(".")}
function pr(a,b){return er.test(H.location.host)?!(jr("gclaw")||jr("gac")):Jq(a,b)}function qr(a,b,c){var d;d=c?Gq(a,b):Fq((b&&b.prefix||"_gcl")+"_gb",a,b);return d.length===0||d.every(function(e){return e===0})?"":d.join(".")};function rr(){var a=G.__uspapi;if(Bb(a)){var b="";try{a("getUSPData",1,function(c,d){if(d&&c){var e=c.uspString;e&&RegExp("^[\\da-zA-Z-]{1,20}$").test(e)&&(b=e)}})}catch(c){}return b}};
var vr=function(a){if(a.eventName===P.g.ba&&a.metadata.hit_type==="page_view")if(T(18)){a.metadata.redact_click_ids=U(a.m,P.g.fa)!=null&&U(a.m,P.g.fa)!==!1&&!W([P.g.R,P.g.P]);var b=sr(a),c=U(a.m,P.g.ra)!==!1;c||(a.o[P.g.Li]="1");var d=eq(b.prefix),e=a.metadata.is_server_side_destination;if(!a.metadata.consent_updated&&!a.metadata.user_id_updated){var f=U(a.m,P.g.Xa),g=U(a.m,P.g.sa)||{};tr({pd:c,xd:g,Dd:f,jc:b});var k;if(k=!e){var m;var n=vi.ads_pageview=vi.ads_pageview||{};m=n[d]?!1:n[d]=!0;k=!m}if(k){a.isAborted=
!0;return}}if(e)a.isAborted=!0;else{a.o[P.g.xc]=P.g.Vb;if(a.metadata.consent_updated)a.o[P.g.xc]=P.g.Ek,a.o[P.g.Tb]="1";else if(a.metadata.user_id_updated)a.o[P.g.xc]=P.g.Jk;else{var p=oq();a.o[P.g.Gd]=p.gclid;a.o[P.g.Od]=p.dclid;a.o[P.g.Gi]=p.gclsrc;a.o[P.g.Gd]||a.o[P.g.Od]||(a.o[P.g.df]=p.wbraid,a.o[P.g.lg]=p.gbraid);a.o[P.g.Fa]=H.referrer?hj(nj(H.referrer),"host"):"";a.o[P.g.wa]=Oq();T(21)&&(a.o[P.g.cb]=ur());var q;if(T(64)){var r=Lq();q=r.rd;a.o[P.g.Fi]=r.Uj}else q=Mq();a.o[P.g.Ei]=q;a.o[P.g.Kb]=
pn(!0);var t=br();ar(t)&&(a.o[P.g.ed]="1");a.o[P.g.Ii]=Yq();hp(!1)._up==="1"&&(a.o[P.g.Yi]="1")}Wk=!0;var u=W([P.g.R,P.g.P]);c&&u&&(vp(b),a.o[P.g.Hb]=tp[wp(b.prefix)]);a.o[P.g.nb]=void 0;a.o[P.g.Va]=void 0;var v=T(66);if(!a.o[P.g.Gd]&&!a.o[P.g.Od]&&pr(d,v)){var w=v?cq(b):aq(d+"_gb");w.length>0&&(a.o[P.g.nb]=w.join("."))}else if(!a.o[P.g.df]&&u){var x=aq(d+"_aw");x.length>0&&(a.o[P.g.Va]=x.join("."))}a.m.isGtmEvent&&(a.m.j[P.g.ka]=Bm.D[P.g.ka]);Tn(a.m)?a.o[P.g.Pb]=!1:a.o[P.g.Pb]=!0;a.metadata.add_tag_timing=
!0;var y=rr();y!==void 0&&(a.o[P.g.he]=y||"error");var B=Nn();B&&(a.o[P.g.Ac]=B);var A=Mn();A&&(a.o[P.g.Dc]=A);a.metadata.speculative=!1}}else a.isAborted=!0},sr=function(a){var b={prefix:U(a.m,P.g.Za)||U(a.m,P.g.Qa),domain:U(a.m,P.g.Wa),Cb:U(a.m,P.g.Pa),flags:U(a.m,P.g.ab)};a.m.isGtmEvent&&(b.path=U(a.m,P.g.Ib));return b},wr=function(a,b){var c,d,e,f,g,k,m,n;c=a.pd;d=a.xd;e=a.Dd;f=a.xa;g=a.m;k=a.yd;m=a.Sn;n=a.vk;tr({pd:c,xd:d,Dd:e,jc:b});c&&m!==!0&&(n!=null?n=String(n):n=void 0,Xq(b,f,g,k,n))},tr=
function(a){var b,c,d,e;b=a.pd;c=a.xd;d=a.Dd;e=a.jc;b&&(rp(c[P.g.Cc],!!c[P.g.X])&&(sq(xr,e),uq(e),Dp(e)),pq(e),yq(xr,e),zq(e));c[P.g.X]&&(wq(xr,c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e.prefix),xq(c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e.prefix),Ep(wp(e.prefix),c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e),Ep("FPAU",c[P.g.X],c[P.g.Mb],!!c[P.g.vb],e));d&&Bq(yr);Dq(yr)},zr=function(a,b,c,d){var e,f,g;e=a.wk;f=a.callback;g=a.Zj;if(typeof f==="function")if(e===P.g.Va&&g===void 0){var k=d(b.prefix,c);k.length===0?f(void 0):k.length===
1?f(k[0]):f(k)}else e===P.g.Hb?(O(65),vp(b,!1),f(tp[wp(b.prefix)])):f(g)},xr=["aw","dc","gb"],yr=["aw","dc","gb","ag"];function Ar(a){var b=U(a.m,P.g.Lb),c=U(a.m,P.g.Zb);b&&!c?(a.eventName!==P.g.ba&&a.eventName!==P.g.Nc&&O(131),a.isAborted=!0):!b&&c&&(O(132),a.isAborted=!0)}function Br(a){var b=W(P.g.R)?vi.pscdl:"denied";b!=null&&(a.o[P.g.jf]=b)}function Cr(a){var b=pn(!0);a.o[P.g.Kb]=b}function Dr(a){ko()&&(a.o[P.g.Bc]=1)}
function ur(){var a=H.title;if(a===void 0||a==="")return"";var b=function(d){try{return decodeURIComponent(d),!0}catch(e){return!1}};a=encodeURIComponent(a);for(var c=256;c>0&&!b(a.substring(0,c));)c--;return decodeURIComponent(a.substring(0,c))}function Er(a){if(T(12)){var b=U(a.m,P.g.Pa);a.o[P.g.ke]||(a.o[P.g.ke]={});a.o[P.g.ke].ce=b}};function Lr(a,b,c,d){var e=Mc(),f;if(e===1)a:{var g=Hi;g=g.toLowerCase();for(var k="https://"+g,m="http://"+g,n=1,p=H.getElementsByTagName("script"),q=0;q<p.length&&q<100;q++){var r=p[q].src;if(r){r=r.toLowerCase();if(r.indexOf(m)===0){f=3;break a}n===1&&r.indexOf(k)===0&&(n=2)}}f=n}else f=e;return(f===2||d||"http:"!=G.location.protocol?a:b)+c};function Yr(a){return{getDestinationId:function(){return a.target.ia},getEventName:function(){return a.eventName},setEventName:function(b){a.eventName=b},getHitData:function(b){return a.o[b]},setHitData:function(b,c){a.o[b]=c},setHitDataIfNotDefined:function(b,c){a.o[b]===void 0&&(a.o[b]=c)},copyToHitData:function(b,c){a.copyToHitData(b,c)},getMetadata:function(b){return a.metadata[b]},setMetadata:function(b,c){a.metadata[b]=c},isAborted:function(){return a.isAborted},abort:function(){a.isAborted=
!0},getFromEventContext:function(b){return U(a.m,b)},Vj:function(){return a},getHitKeys:function(){return Object.keys(a.o)}}};var $r=function(a){var b=Zr[a.target.ia];if(!a.isAborted&&b)for(var c=Yr(a),d=0;d<b.length;++d){try{b[d](c)}catch(e){a.isAborted=!0}if(a.isAborted)break}},as=function(a,b){var c=Zr[a];c||(c=Zr[a]=[]);c.push(b)},Zr={};var es,fs=!1;function gs(){fs=!0;es=es||{}}function hs(a){fs||gs();return es[a]}function is(){var a=G.screen;return{width:a?a.width:0,height:a?a.height:0}}
function js(a){if(H.hidden)return!0;var b=a.getBoundingClientRect();if(b.top===b.bottom||b.left===b.right||!G.getComputedStyle)return!0;var c=G.getComputedStyle(a,null);if(c.visibility==="hidden")return!0;for(var d=a,e=c;d;){if(e.display==="none")return!0;var f=e.opacity,g=e.filter;if(g){var k=g.indexOf("opacity(");k>=0&&(g=g.substring(k+8,g.indexOf(")",k)),g.charAt(g.length-1)==="%"&&(g=g.substring(0,g.length-1)),f=String(Math.min(Number(g),Number(f))))}if(f!==void 0&&Number(f)<=0)return!0;(d=d.parentElement)&&
(e=G.getComputedStyle(d,null))}return!1}
var ls=function(a){var b=ks(),c=b.height,d=b.width,e=a.getBoundingClientRect(),f=e.bottom-e.top,g=e.right-e.left;return f&&g?(1-Math.min((Math.max(0-e.left,0)+Math.max(e.right-d,0))/g,1))*(1-Math.min((Math.max(0-e.top,0)+Math.max(e.bottom-c,0))/f,1)):0},ks=function(){var a=H.body,b=H.documentElement||a&&a.parentElement,c,d;if(H.compatMode&&H.compatMode!=="BackCompat")c=b?b.clientHeight:0,d=b?b.clientWidth:0;else{var e=function(f,g){return f&&g?Math.min(f,g):Math.max(f,g)};c=e(b?b.clientHeight:0,a?
a.clientHeight:0);d=e(b?b.clientWidth:0,a?a.clientWidth:0)}return{width:d,height:c}};
var ts=function(a){return a.tagName+":"+a.isVisible+":"+a.Z.length+":"+ss.test(a.Z)},Hs=function(a){a=a||{vd:!0,wd:!0,Zf:void 0};a.zb=a.zb||{email:!0,phone:!1,address:!1};var b=us(a),c=vs[b];if(c&&Ob()-c.timestamp<200)return c.result;var d=ws(),e=d.status,f=[],g,k,m=[];if(!T(25)){if(a.zb&&a.zb.email){var n=xs(d.elements);f=ys(n,a&&a.De);g=zs(f);n.length>10&&(e="3")}!a.Zf&&g&&(f=[g]);for(var p=0;p<f.length;p++)m.push(As(f[p],!!a.vd,!!a.wd));m=m.slice(0,10)}else if(a.zb){}g&&(k=As(g,!!a.vd,!!a.wd));var C={elements:m,
Rh:k,status:e};vs[b]={timestamp:Ob(),result:C};return C},Gs=function(a,b,c){var d=a.element,e={Z:a.Z,type:a.qa,tagName:d.tagName};b&&(e.querySelector=Is(d));c&&(e.isVisible=!js(d));return e},As=function(a,b,c){return Gs({element:a.element,Z:a.Z,qa:Fs.nc},b,c)},us=function(a){var b=!(a==null||!a.vd)+"."+!(a==null||!a.wd);a&&a.De&&a.De.length&&(b+="."+a.De.join("."));a&&a.zb&&(b+="."+a.zb.email+"."+a.zb.phone+"."+a.zb.address);return b},zs=function(a){if(a.length!==0){var b;b=Js(a,function(c){return!Ks.test(c.Z)});
b=Js(b,function(c){return c.element.tagName.toUpperCase()==="INPUT"});b=Js(b,function(c){return!js(c.element)});return b[0]}},ys=function(a,b){if(!b||b.length===0)return a;for(var c=[],d=0;d<a.length;d++){for(var e=!0,f=0;f<b.length;f++){var g=b[f];if(g&&zh(a[d].element,g)){e=!1;break}}e&&c.push(a[d])}return c},Js=function(a,b){if(a.length<=1)return a;var c=a.filter(b);return c.length===0?a:c},Is=function(a){var b;if(a===H.body)b="body";else{var c;if(a.id)c="#"+a.id;else{var d;if(a.parentElement){var e;
a:{var f=a.parentElement;if(f){for(var g=0;g<f.childElementCount;g++)if(f.children[g]===a){e=g+1;break a}e=-1}else e=1}d=Is(a.parentElement)+">:nth-child("+e.toString()+")"}else d="";c=d}b=c}return b},xs=function(a){for(var b=[],c=0;c<a.length;c++){var d=a[c],e=d.textContent;d.tagName.toUpperCase()==="INPUT"&&d.value&&(e=d.value);if(e){var f=e.match(Ls);if(f){var g=f[0],k;if(G.location){var m=jj(G.location,"host",!0);k=g.toLowerCase().indexOf(m)>=0}else k=!1;k||b.push({element:d,Z:g})}}}return b},
ws=function(){var a=[],b=H.body;if(!b)return{elements:a,status:"4"};for(var c=b.querySelectorAll("*"),d=0;d<c.length&&d<1E4;d++){var e=c[d];if(!(Ms.indexOf(e.tagName.toUpperCase())>=0)&&e.children instanceof HTMLCollection){for(var f=!1,g=0;g<e.childElementCount&&g<1E4;g++)if(!(Ns.indexOf(e.children[g].tagName.toUpperCase())>=0)){f=!0;break}(!f||T(25)&&Os.indexOf(e.tagName)!==-1)&&a.push(e)}}return{elements:a,status:c.length>1E4?"2":"1"}},Ps=!1;var Ls=/[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,}/i,ss=/@(gmail|googlemail)\./i,Ks=/support|noreply/i,Ms="SCRIPT STYLE IMG SVG PATH BR NOSCRIPT TEXTAREA".split(" "),Ns=["BR"],Fs={nc:"1",qe:"2",je:"3",ne:"4",fg:"5",Xg:"6",Jf:"7"},vs={},Os=["INPUT","SELECT"];var dt=function(a,b,c){a.o[P.g.te]||(a.o[P.g.te]={});a.o[P.g.te][b]=c},ft=function(a,b){var c=et(a,P.g.Ud,a.m.D[P.g.Ud]);if(c&&c[b||a.eventName]!==void 0)return c[b||a.eventName]},gt=function(a){var b=a.metadata.user_data;if(fb(b))return b},ht=function(a){if(a.metadata.is_merchant_center||!uj(a.m))return!1;if(!U(a.m,P.g.jd)){var b=U(a.m,P.g.yc);return b===!0||b==="true"}return!0},it=function(a){return et(a,P.g.Yb,U(a.m,P.g.Yb))||!!et(a,"google_ng",!1)};var jt=Number('')||5,kt=Number('')||50,lt=Fb();var qt={pl:Number('')||500,Wk:Number('')||5E3,uj:Number('20')||10,Dk:Number('')||5E3};function rt(a){return a.performance&&a.performance.now()||Date.now()}
var st=function(a,b){var c;return c};var tt="https://"+ui.Fd+"/gtm/static/",ut;
function At(a,b){}
var Bt=function(a,b,c,d){};
function Ct(a,b,c,d){}
function Dt(a,b,c,d){}var Et=void 0;function Ft(a){var b=[];return b};var Gt=function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);e<128?b[c++]=e:(e<2048?b[c++]=e>>6|192:((e&64512)==55296&&d+1<a.length&&(a.charCodeAt(d+1)&64512)==56320?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}return b};cn();fn()||$m("iPod");$m("iPad");!$m("Android")||dn()||cn()||bn()||$m("Silk");dn();!$m("Safari")||dn()||(an()?0:$m("Coast"))||bn()||(an()?0:$m("Edge"))||(an()?Zm("Microsoft Edge"):$m("Edg/"))||(an()?Zm("Opera"):$m("OPR"))||cn()||$m("Silk")||$m("Android")||gn();var Ht={},It=null,Jt=function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);e>255&&(b[c++]=e&255,e>>=8);b[c++]=e}var f=4;f===void 0&&(f=0);if(!It){It={};for(var g="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),k=["+/=","+/","-_=","-_.","-_"],m=0;m<5;m++){var n=g.concat(k[m].split(""));Ht[m]=n;for(var p=0;p<n.length;p++){var q=n[p];It[q]===void 0&&(It[q]=p)}}}for(var r=Ht[f],t=Array(Math.floor(b.length/3)),u=r[64]||"",v=0,w=0;v<b.length-2;v+=3){var x=b[v],
y=b[v+1],B=b[v+2],A=r[x>>2],C=r[(x&3)<<4|y>>4],E=r[(y&15)<<2|B>>6],D=r[B&63];t[w++]=""+A+C+E+D}var F=0,L=u;switch(b.length-v){case 2:F=b[v+1],L=r[(F&15)<<2]||u;case 1:var M=b[v];t[w]=""+r[M>>2]+r[(M&3)<<4|F>>4]+L+u}return t.join("")};var Kt="platform platformVersion architecture model uaFullVersion bitness fullVersionList wow64".split(" ");function Lt(a){var b;return(b=a.google_tag_data)!=null?b:a.google_tag_data={}}function Mt(){var a=G.google_tag_data,b;if(a!=null&&a.uach){var c=a.uach,d=Object.assign({},c);c.fullVersionList&&(d.fullVersionList=c.fullVersionList.slice(0));b=d}else b=null;return b}function Nt(){var a,b;return(b=(a=G.google_tag_data)==null?void 0:a.uach_promise)!=null?b:null}
function Ot(a){var b,c;return typeof((b=a.navigator)==null?void 0:(c=b.userAgentData)==null?void 0:c.getHighEntropyValues)==="function"}function Pt(){var a=G;if(!Ot(a))return null;var b=Lt(a);if(b.uach_promise)return b.uach_promise;var c=a.navigator.userAgentData.getHighEntropyValues(Kt).then(function(d){b.uach!=null||(b.uach=d);return d});return b.uach_promise=c};
var Qt,Rt=function(){if(Ot(G)&&(Qt=Ob(),!Nt())){var a=Pt();a&&(a.then(function(){O(95);}),a.catch(function(){O(96)}))}},Tt=function(a){var b=St.qn,c=function(g,k){try{a(g,k)}catch(m){}},d=Mt();if(d)c(d);else{var e=Nt();if(e){b=
Math.min(Math.max(isFinite(b)?b:0,0),1E3);var f=G.setTimeout(function(){c.Oe||(c.Oe=!0,O(106),c(null,Error("Timeout")))},b);e.then(function(g){c.Oe||(c.Oe=!0,O(104),G.clearTimeout(f),c(g))}).catch(function(g){c.Oe||(c.Oe=!0,O(105),G.clearTimeout(f),c(null,g))})}else c(null)}},Ut=function(a,b){a&&(b.o[P.g.zf]=a.architecture,b.o[P.g.Af]=a.bitness,a.fullVersionList&&(b.o[P.g.Bf]=a.fullVersionList.map(function(c){return encodeURIComponent(c.brand||"")+";"+encodeURIComponent(c.version||"")}).join("|")),
b.o[P.g.Cf]=a.mobile?"1":"0",b.o[P.g.Df]=a.model,b.o[P.g.Ef]=a.platform,b.o[P.g.Ff]=a.platformVersion,b.o[P.g.Gf]=a.wow64?"1":"0")};function Vt(a){var b;b=b===void 0?document:b;var c;return!((c=b.featurePolicy)==null||!c.allowedFeatures().includes(a))};function Wt(){return Vt("join-ad-interest-group")&&Bb(Cc.joinAdInterestGroup)}
function Xt(a,b){var c=yb[3]===void 0?1:yb[3],d='iframe[data-tagging-id="'+b+'"]',e=[];try{if(c===1){var f=H.querySelector(d);f&&(e=[f])}else e=Array.from(H.querySelectorAll(d))}catch(q){}var g;a:{try{g=H.querySelectorAll('iframe[allow="join-ad-interest-group"][data-tagging-id*="-"]');break a}catch(q){}g=void 0}var k=g,m=((k==null?void 0:k.length)||0)>=(yb[2]===void 0?50:yb[2]),n;if(n=e.length>=1){var p=Number(e[e.length-1].dataset.loadTime);p!==void 0&&Ob()-p<(yb[1]===void 0?6E4:yb[1])?(ub("TAGGING",
9),n=!0):n=!1}if(!n){if(c===1)if(e.length>=1)Yt(e[0]);else{if(m){ub("TAGGING",10);return}}else e.length>=c?Yt(e[0]):m&&Yt(k[0]);Nc(a,void 0,{allow:"join-ad-interest-group"},{taggingId:b,loadTime:Ob()})}}function Yt(a){try{a.parentNode.removeChild(a)}catch(b){}}function Zt(){return"https://td.doubleclick.net"};
var Pu=function(a,b){var c={},d=function(f,g){var k;k=g===!0?"1":g===!1?"0":encodeURIComponent(String(g));c[f]=k};z(a.o,function(f,g){var k=Ou[f];k&&g!==void 0&&g!==""&&(!a.metadata.redact_click_ids||f!==P.g.Gd&&f!==P.g.Od&&f!==P.g.df&&f!==P.g.lg||(g="0"),d(k,g))});d("gtm",no({xa:a.metadata.source_canonical_id}));Un()&&d("gcs",Vn());d("gcd",fo(a.m));io()&&d("dma_cps",go());d("dma",ho());yn(Gn())&&d("tcfd",jo());Oi.j&&d("tag_exp",Oi.j);if(a.metadata.add_tag_timing){d("tft",Ob());var e=ad();e!==void 0&&
d("tfd",Math.round(e))}T(17)&&d("apve",T(18)?"1":"0");T(19)&&d("apvf",Yc()?T(20)?"f":"sb":"nf");b(c)},Qu=function(a){Pu(a,function(b){if(a.metadata.hit_type==="page_view"){var c=[];z(b,function(e,f){c.push(e+"="+f)});var d=vj(W([P.g.R,P.g.P])?"https://www.google.com":"https://pagead2.googlesyndication.com",!0)+"/ccm/collect?"+c.join("&");T(19)&&T(20)&&Yc()?Zc(d,void 0,{noFallback:!0}):Vc(d);if(Bb(a.m.onSuccess))a.m.onSuccess()}})},Ru={},Ou=(Ru[P.g.Tb]="gcu",Ru[P.g.nb]="gclgb",Ru[P.g.Va]="gclaw",Ru[P.g.Ei]=
"gad_source",Ru[P.g.Fi]="gad_source_src",Ru[P.g.Gd]="gclid",Ru[P.g.Gi]="gclsrc",Ru[P.g.lg]="gbraid",Ru[P.g.df]="wbraid",Ru[P.g.Hb]="auid",Ru[P.g.Ii]="rnd",Ru[P.g.Li]="ncl",Ru[P.g.og]="gcldc",Ru[P.g.Od]="dclid",Ru[P.g.rb]="edid",Ru[P.g.xc]="en",Ru[P.g.Ac]="gdpr",Ru[P.g.ub]="gdid",Ru[P.g.Bc]="_ng",Ru[P.g.Yi]="gtm_up",Ru[P.g.Kb]="frm",Ru[P.g.ed]="lps",Ru[P.g.ae]="did",Ru[P.g.wa]="dl",Ru[P.g.Fa]="dr",Ru[P.g.cb]="dt",Ru[P.g.wf]="ga_uid",Ru[P.g.Dc]="gdpr_consent",Ru[P.g.Ba]="uid",Ru[P.g.he]="us_privacy",
Ru[P.g.Pb]="npa",Ru);var Su={M:{fi:"ads_conversion_hit",Ed:"container_execute_start",ii:"container_setup_end",dg:"container_setup_start",gi:"container_blocking_end",hi:"container_execute_end",ji:"container_yield_end",eg:"container_yield_start",jj:"event_execute_end",ij:"event_evaluation_end",Ug:"event_evaluation_start",kj:"event_setup_end",ie:"event_setup_start",mj:"ga4_conversion_hit",pe:"page_load",Hn:"pageview",hc:"snippet_load",Hj:"tag_callback_error",Ij:"tag_callback_failure",Jj:"tag_callback_success",Kj:"tag_execute_end",
nd:"tag_execute_start"}};function Tu(){function a(c,d){var e=vb(d);e&&b.push([c,e])}var b=[];a("u","GTM");a("ut","TAGGING");a("h","HEALTH");return b};var Uu=!1;function Cv(a,b){}
function Dv(a,b){}function Ev(a,b){}
function Fv(a,b){}function Gv(){var a={};return a}
function uv(a){a=a===void 0?!0:a;var b={};return b}
function Hv(){}function Iv(a,b){}
function Jv(a,b,c){}
function Kv(){}function Lv(a,b){var c=G,d,e=c.GooglebQhCsO;e||(e={},c.GooglebQhCsO=e);d=e;if(d[a])return!1;d[a]=[];d[a][0]=b;return!0};var Mv=function(a,b,c,d){var e=kn(a,"fmt");if(b){var f=kn(a,"random"),g=kn(a,"label")||"";if(!f)return!1;var k=Jt(decodeURIComponent(g.replace(/\+/g," "))+":"+decodeURIComponent(f.replace(/\+/g," ")));if(!Lv(k,b))return!1}e&&e!=4&&(a=mn(a,"rfmt",e));var m=mn(a,"fmt",4);Lc(m,function(){G.google_noFurtherRedirects&&b&&b.call&&(G.google_noFurtherRedirects=null,b())},c,d,H.getElementsByTagName("script")[0].parentElement||void 0);return!0};function dw(a,b){if(data.entities){var c=data.entities[a];if(c)return c[b]}};function ew(a,b,c){c=c===void 0?!1:c;fw().addRestriction(0,a,b,c)}function gw(a,b,c){c=c===void 0?!1:c;fw().addRestriction(1,a,b,c)}function hw(){var a=Xj();return fw().getRestrictions(1,a)}var iw=function(){this.j={};this.D={}},jw=function(a,b){var c=a.j[b];c||(c={_entity:{internal:[],external:[]},_event:{internal:[],external:[]}},a.j[b]=c);return c};
iw.prototype.addRestriction=function(a,b,c,d){d=d===void 0?!1:d;if(!d||!this.D[b]){var e=jw(this,b);a===0?d?e._entity.external.push(c):e._entity.internal.push(c):a===1&&(d?e._event.external.push(c):e._event.internal.push(c))}};
iw.prototype.getRestrictions=function(a,b){var c=jw(this,b);if(a===0){var d,e;return[].concat(qa((c==null?void 0:(d=c._entity)==null?void 0:d.internal)||[]),qa((c==null?void 0:(e=c._entity)==null?void 0:e.external)||[]))}if(a===1){var f,g;return[].concat(qa((c==null?void 0:(f=c._event)==null?void 0:f.internal)||[]),qa((c==null?void 0:(g=c._event)==null?void 0:g.external)||[]))}return[]};
iw.prototype.getExternalRestrictions=function(a,b){var c=jw(this,b),d,e;return a===0?(c==null?void 0:(d=c._entity)==null?void 0:d.external)||[]:(c==null?void 0:(e=c._event)==null?void 0:e.external)||[]};iw.prototype.removeExternalRestrictions=function(a){var b=jw(this,a);b._event&&(b._event.external=[]);b._entity&&(b._entity.external=[]);this.D[a]=!0};function fw(){var a=vi.r;a||(a=new iw,vi.r=a);return a};var kw=new RegExp(/^(.*\.)?(google|youtube|blogger|withgoogle)(\.com?)?(\.[a-z]{2})?\.?$/),lw={cl:["ecl"],customPixels:["nonGooglePixels"],ecl:["cl"],ehl:["hl"],gaawc:["googtag"],hl:["ehl"],html:["customScripts","customPixels","nonGooglePixels","nonGoogleScripts","nonGoogleIframes"],customScripts:["html","customPixels","nonGooglePixels","nonGoogleScripts","nonGoogleIframes"],nonGooglePixels:[],nonGoogleScripts:["nonGooglePixels"],nonGoogleIframes:["nonGooglePixels"]},mw={cl:["ecl"],customPixels:["customScripts",
"html"],ecl:["cl"],ehl:["hl"],gaawc:["googtag"],hl:["ehl"],html:["customScripts"],customScripts:["html"],nonGooglePixels:["customPixels","customScripts","html","nonGoogleScripts","nonGoogleIframes"],nonGoogleScripts:["customScripts","html"],nonGoogleIframes:["customScripts","html","nonGoogleScripts"]},nw="google customPixels customScripts html nonGooglePixels nonGoogleScripts nonGoogleIframes".split(" ");
function ow(){var a=Wi("gtm.allowlist")||Wi("gtm.whitelist");a&&O(9);Bi&&(a=["google","gtagfl","lcl","zone"]);kw.test(G.location&&G.location.hostname)&&(Bi?O(116):(O(117),pw&&(a=[],window.console&&window.console.log&&window.console.log("GTM blocked. See go/13687728."))));var b=a&&Sb(Lb(a),lw),c=Wi("gtm.blocklist")||Wi("gtm.blacklist");c||(c=Wi("tagTypeBlacklist"))&&O(3);c?O(8):c=[];kw.test(G.location&&G.location.hostname)&&(c=Lb(c),c.push("nonGooglePixels","nonGoogleScripts","sandboxedScripts"));
Lb(c).indexOf("google")>=0&&O(2);var d=c&&Sb(Lb(c),mw),e={};return function(f){var g=f&&f[Xe.oa];if(!g||typeof g!=="string")return!0;g=g.replace(/^_*/,"");if(e[g]!==void 0)return e[g];var k=Li[g]||[],m=!0;if(a){var n;if(n=m)a:{if(b.indexOf(g)<0)if(k&&k.length>0)for(var p=0;p<k.length;p++){if(b.indexOf(k[p])<0){O(11);n=!1;break a}}else{n=!1;break a}n=!0}m=n}var q=!1;if(c){var r=d.indexOf(g)>=0;if(r)q=r;else{var t=Gb(d,k||[]);t&&O(10);q=t}}var u=!m||q;u||!(k.indexOf("sandboxedScripts")>=0)||b&&b.indexOf("sandboxedScripts")!==
-1||(u=Gb(d,nw));return e[g]=u}}var pw=!1;pw=!0;function qw(){Pj&&ew(Xj(),function(a){var b=Hf(a.entityId),c;if(Kf(b)){var d=b[Xe.oa];if(!d)throw Error("Error: No function name given for function call.");var e=zf[d];c=!!e&&!!e.runInSiloedMode}else c=!!dw(b[Xe.oa],4);return c})}function rw(a,b,c,d,e){if(!sw()){var f=d.siloed?Sj(a):a;if(!gk(f)){var g=tw(a),k=Tb(a,"GTM-"),m=tj(),n=c?"/gtag/js":"/gtm.js",p=sj(b,n+g);if(!p){var q=ui.Fd+n;m&&Fc&&k?(q=Fc.replace(/^(?:https?:\/\/)?/i,"").split(/[?#]/)[0],p=Lr("https://","http://",q+g)):p=Qi()?Pi()+n+g:Lr("https://","http://",q+g)}d.siloed&&ik({ctid:f,isDestination:!1});var r=ak();Jj().container[f]={state:1,context:d,parent:r};Ij({ctid:f,isDestination:!1},e);Lc(p)}}}
function uw(a,b,c,d){if(!sw()){var e=c.siloed?Sj(a):a;if(!hk(e))if(!c.siloed&&jk())Jj().destination[e]={state:0,transportUrl:b,context:c,parent:ak()},Ij({ctid:e,isDestination:!0},d),O(91);else{var f="/gtag/destination"+tw(a,!0),g=sj(b,f);g||(g=Qi()?Pi()+f:Lr("https://","http://",ui.Fd+f));c.siloed&&ik({ctid:e,isDestination:!0});Jj().destination[e]={state:1,context:c,parent:ak()};Ij({ctid:e,isDestination:!0},d);Lc(g)}}}
function tw(a,b){b=b===void 0?!1:b;var c="?id="+encodeURIComponent(a)+"&l="+ui.jb;if(!Tb(a,"GTM-")||b)c+="&cx=c";T(68)&&(c+="&gtm="+no());tj()&&(c+="&sign="+ui.Zg);var d=Oi.D;d===1?c+="&fps=fc":d===2&&(c+="&fps=fe");return c}function sw(){if(lo()){return!0}return!1};var vw=[];function ww(){var a=ag.ctid;if(a){var b=Lj.oe?1:0,c,d=Zj(ak());c=d&&d.context;return a+";"+ag.canonicalContainerId+";"+(c&&c.fromContainerExecution?1:0)+";"+(c&&c.source||0)+";"+b}}function xw(){var a=nj(G.location.href);return a.hostname+a.pathname}function yw(){var a=xw();a&&rk("dl",encodeURIComponent(a));if(T(85)){var b=ww();b&&rk("tdp",b)}else rk("tdp",function(){return vw.length>0?vw.join("."):void 0});var c=pn(!0);c!==void 0&&rk("frm",String(c))};var zw=!1,Aw=0,Bw=[];function Cw(a){if(!zw){var b=H.createEventObject,c=H.readyState==="complete",d=H.readyState==="interactive";if(!a||a.type!=="readystatechange"||c||!b&&d){zw=!0;for(var e=0;e<Bw.length;e++)I(Bw[e])}Bw.push=function(){for(var f=Ma.apply(0,arguments),g=0;g<f.length;g++)I(f[g]);return 0}}}function Dw(){if(!zw&&Aw<140){Aw++;try{var a,b;(b=(a=H.documentElement).doScroll)==null||b.call(a,"left");Cw()}catch(c){G.setTimeout(Dw,50)}}}function Ew(a){zw?a():Bw.push(a)};var Fw=function(){this.K=0;this.j={}};Fw.prototype.addListener=function(a,b,c){var d=++this.K;this.j[a]=this.j[a]||{};this.j[a][String(d)]={listener:b,Eb:c};return d};Fw.prototype.D=function(a,b){var c=this.j[a],d=String(b);if(!c||!c[d])return!1;delete c[d];return!0};Fw.prototype.H=function(a,b){var c=[];z(this.j[a],function(d,e){c.indexOf(e.listener)<0&&(e.Eb===void 0||b.indexOf(e.Eb)>=0)&&c.push(e.listener)});return c};function Gw(a,b,c){return{entityType:a,indexInOriginContainer:b,nameInOriginContainer:c,originContainerId:Vj()}};var Iw=function(a,b){this.j=!1;this.K=[];this.eventData={tags:[]};this.O=!1;this.D=this.H=0;Hw(this,a,b)},Jw=function(a,b,c,d){if(xi.hasOwnProperty(b)||b==="__zone")return-1;var e={};fb(d)&&(e=h(d,e));e.id=c;e.status="timeout";return a.eventData.tags.push(e)-1},Kw=function(a,b,c,d){var e=a.eventData.tags[b];e&&(e.status=c,e.executionTime=d)},Lw=function(a){if(!a.j){for(var b=a.K,c=0;c<b.length;c++)b[c]();a.j=!0;a.K.length=0}},Hw=function(a,b,c){b!==void 0&&a.we(b);c&&G.setTimeout(function(){Lw(a)},
Number(c))};Iw.prototype.we=function(a){var b=this,c=Qb(function(){I(function(){a(Vj(),b.eventData)})});this.j?c():this.K.push(c)};var Mw=function(a){a.H++;return Qb(function(){a.D++;a.O&&a.D>=a.H&&Lw(a)})},Nw=function(a){a.O=!0;a.D>=a.H&&Lw(a)};var Ow={},Qw=function(){return G[Pw()]};
function Pw(){return G.GoogleAnalyticsObject||"ga"}
var Tw=function(){var a=Vj();},Uw=function(a,b){return function(){var c=Qw(),d=c&&c.getByName&&c.getByName(a);if(d){var e=d.get("sendHitTask");d.set("sendHitTask",function(f){var g=f.get("hitPayload"),k=f.get("hitCallback"),m=g.indexOf("&tid="+b)<0;m&&(f.set("hitPayload",g.replace(/&tid=UA-[0-9]+-[0-9]+/,"&tid="+b),!0),f.set("hitCallback",void 0,!0));e(f);
m&&(f.set("hitPayload",g,!0),f.set("hitCallback",k,!0),f.set("_x_19",void 0,!0),e(f))})}}};var Zw=["es","1"],$w={},ax={};function bx(a,b){if(Cj){var c;c=b.match(/^(gtm|gtag)\./)?encodeURIComponent(b):"*";$w[a]=[["e",c],["eid",a]];tm(a)}}function cx(a){var b=a.eventId,c=a.mc;if(!$w[b])return[];var d=[];ax[b]||d.push(Zw);d.push.apply(d,qa($w[b]));c&&(ax[b]=!0);return d};var dx={},ex={},fx={};function gx(a,b,c,d){Cj&&T(76)&&((d===void 0?0:d)?(fx[b]=fx[b]||0,++fx[b]):c!==void 0?(ex[a]=ex[a]||{},ex[a][b]=Math.round(c)):(dx[a]=dx[a]||{},dx[a][b]=(dx[a][b]||0)+1))}function hx(a){var b=a.eventId,c=a.mc,d=dx[b]||{},e=[],f;for(f in d)d.hasOwnProperty(f)&&e.push(""+f+d[f]);c&&delete dx[b];return e.length?[["md",e.join(".")]]:[]}
function ix(a){var b=a.eventId,c=a.mc,d=ex[b]||{},e=[],f;for(f in d)d.hasOwnProperty(f)&&e.push(""+f+d[f]);c&&delete ex[b];return e.length?[["mtd",e.join(".")]]:[]}function jx(){for(var a=[],b=oa(Object.keys(fx)),c=b.next();!c.done;c=b.next()){var d=c.value;a.push(""+d+fx[d])}return a.length?[["mec",a.join(".")]]:[]};var kx={},lx={};function mx(a,b,c){if(Cj&&b){var d=wj(b);kx[a]=kx[a]||[];kx[a].push(c+d);var e=(Kf(b)?"1":"2")+d;lx[a]=lx[a]||[];lx[a].push(e);tm(a)}}function nx(a){var b=a.eventId,c=a.mc,d=[],e=kx[b]||[];e.length&&d.push(["tr",e.join(".")]);var f=lx[b]||[];f.length&&d.push(["ti",f.join(".")]);c&&(delete kx[b],delete lx[b]);return d};function ox(a,b,c,d){var e=xf[a],f=px(a,b,c,d);if(!f)return null;var g=Lf(e[Xe.Fj],c,[]);if(g&&g.length){var k=g[0];f=ox(k.index,{onSuccess:f,onFailure:k.Tj===1?b.terminate:f,terminate:b.terminate},c,d)}return f}
function px(a,b,c,d){function e(){function w(){$k(3);var D=Ob()-E;mx(c.id,f,"7");Kw(c.ic,A,"exception",D);T(69)&&Jv(c,f,Su.M.Hj);C||(C=!0,k())}if(f[Xe.bl])k();else{var x=Jf(f,c,[]),y=x[Xe.Bk];if(y!=null)for(var B=0;B<y.length;B++)if(!W(y[B])){k();return}var A=Jw(c.ic,String(f[Xe.oa]),Number(f[Xe.ve]),x[Xe.fl]),C=!1;x.vtp_gtmOnSuccess=function(){if(!C){C=!0;var D=Ob()-E;mx(c.id,xf[a],"5");Kw(c.ic,A,"success",D);T(69)&&Jv(c,f,Su.M.Jj);g()}};x.vtp_gtmOnFailure=function(){if(!C){C=!0;var D=Ob()-E;mx(c.id,
xf[a],"6");Kw(c.ic,A,"failure",D);T(69)&&Jv(c,f,Su.M.Ij);k()}};x.vtp_gtmTagId=f.tag_id;x.vtp_gtmEventId=c.id;c.priorityId&&(x.vtp_gtmPriorityId=c.priorityId);mx(c.id,f,"1");T(69)&&Iv(c,f);var E=Ob();try{Mf(x,{event:c,index:a,type:1})}catch(D){w(D)}T(69)&&Jv(c,f,Su.M.Kj)}}var f=xf[a],g=b.onSuccess,k=b.onFailure,m=b.terminate;if(c.isBlocked(f))return null;var n=Lf(f[Xe.Lj],c,[]);if(n&&n.length){var p=n[0],q=ox(p.index,{onSuccess:g,onFailure:k,terminate:m},c,d);if(!q)return null;g=q;k=p.Tj===2?m:q}if(f[Xe.xj]||
f[Xe.jl]){var r=f[Xe.xj]?yf:c.hn,t=g,u=k;if(!r[a]){var v=qx(a,r,Qb(e));g=v.onSuccess;k=v.onFailure}return function(){r[a](t,u)}}return e}function qx(a,b,c){var d=[],e=[];b[a]=rx(d,e,c);return{onSuccess:function(){b[a]=sx;for(var f=0;f<d.length;f++)d[f]()},onFailure:function(){b[a]=tx;for(var f=0;f<e.length;f++)e[f]()}}}function rx(a,b,c){return function(d,e){a.push(d);b.push(e);c()}}function sx(a){a()}function tx(a,b){b()};var wx=function(a,b){for(var c=[],d=0;d<xf.length;d++)if(a[d]){var e=xf[d];var f=Mw(b.ic);try{var g=ox(d,{onSuccess:f,onFailure:f,terminate:f},b,d);if(g){var k=e[Xe.oa];if(!k)throw Error("Error: No function name given for function call.");var m=zf[k];c.push({sk:d,ik:(m?m.priorityOverride||0:0)||dw(e[Xe.oa],1)||0,execute:g})}else ux(d,b),f()}catch(p){f()}}c.sort(vx);for(var n=0;n<c.length;n++)c[n].execute();return c.length>
0};var yx=function(a,b){if(!xx)return!1;var c=a["gtm.triggers"]&&String(a["gtm.triggers"]),d=xx.H(a.event,c?String(c).split(","):[]);if(!d.length)return!1;for(var e=0;e<d.length;++e){var f=Mw(b);try{d[e](a,f)}catch(g){f()}}return!0};function vx(a,b){var c,d=b.ik,e=a.ik;c=d>e?1:d<e?-1:0;var f;if(c!==0)f=c;else{var g=a.sk,k=b.sk;f=g>k?1:g<k?-1:0}return f}
function ux(a,b){if(Cj){var c=function(d){var e=b.isBlocked(xf[d])?"3":"4",f=Lf(xf[d][Xe.Fj],b,[]);f&&f.length&&c(f[0].index);mx(b.id,xf[d],e);var g=Lf(xf[d][Xe.Lj],b,[]);g&&g.length&&c(g[0].index)};c(a)}}var zx=!1,xx;var Ax=function(){xx||(xx=new Fw);return xx};
var Fx=function(a){var b=a["gtm.uniqueEventId"],c=a["gtm.priorityId"],d=a.event;if(T(69)){}if(d==="gtm.js"){if(zx)return!1;zx=!0}var e=!1,f=hw(),g=h(a);if(!f.every(function(t){return t({originalEventData:g})})){if(d!=="gtm.js"&&d!=="gtm.init"&&d!=="gtm.init_consent")return!1;e=!0}bx(b,d);var k=a.eventCallback,m=a.eventTimeout,n={id:b,
priorityId:c,name:d,isBlocked:Bx(g,e),hn:[],logMacroError:function(){O(6);$k(0)},cachedModelValues:Cx(),ic:new Iw(function(){if(T(69)){}k&&
k.apply(k,[].slice.call(arguments,0))},m),originalEventData:g};T(76)&&Cj&&(n.reportMacroDiscrepancy=gx);T(69)&&Ev(n.id,n.name);var p=Sf(n);T(69)&&Fv(n.id,n.name);e&&(p=Dx(p));if(T(69)){}var q=wx(p,n),r=!1;
r=yx(a,n.ic);Nw(n.ic);d!=="gtm.js"&&d!=="gtm.sync"||Tw();return Ex(p,q)||r};function Cx(){var a={};a.event=aj("event",1);a.ecommerce=aj("ecommerce",1);a.gtm=aj("gtm");a.eventModel=aj("eventModel");return a}
function Bx(a,b){var c=ow();return function(d){if(c(d))return!0;var e=d&&d[Xe.oa];if(!e||typeof e!="string")return!0;e=e.replace(/^_*/,"");var f,g=Xj();f=fw().getRestrictions(0,g);var k=a;b&&(k=h(a),k["gtm.uniqueEventId"]=Number.MAX_SAFE_INTEGER);for(var m=Li[e]||[],n=oa(f),p=n.next();!p.done;p=n.next()){var q=p.value;try{if(!q({entityId:e,securityGroups:m,originalEventData:k}))return!0}catch(r){return!0}}return!1}}
function Dx(a){for(var b=[],c=0;c<a.length;c++)if(a[c]){var d=String(xf[c][Xe.oa]);if(wi[d]||xf[c][Xe.kl]!==void 0||dw(d,2))b[c]=!0}return b}function Ex(a,b){if(!b)return b;for(var c=0;c<a.length;c++)if(a[c]&&xf[c]&&!xi[String(xf[c][Xe.oa])])return!0;return!1}var Lx=0;function Mx(a,b){return arguments.length===1?Nx("set",a):Nx("set",a,b)}function Ox(a,b){return arguments.length===1?Nx("config",a):Nx("config",a,b)}function Px(a,b,c){c=c||{};c[P.g.bc]=a;return Nx("event",b,c)}function Nx(){return arguments};var Qx=function(){this.messages=[];this.j=[]};Qx.prototype.enqueue=function(a,b,c){var d=this.messages.length+1;a["gtm.uniqueEventId"]=b;a["gtm.priorityId"]=d;var e=Object.assign({},c,{eventId:b,priorityId:d,fromContainerExecution:!0}),f={message:a,notBeforeEventId:b,priorityId:d,messageContext:e};this.messages.push(f);for(var g=0;g<this.j.length;g++)try{this.j[g](f)}catch(k){}};Qx.prototype.listen=function(a){this.j.push(a)};
Qx.prototype.get=function(){for(var a={},b=0;b<this.messages.length;b++){var c=this.messages[b],d=a[c.notBeforeEventId];d||(d=[],a[c.notBeforeEventId]=d);d.push(c)}return a};Qx.prototype.prune=function(a){for(var b=[],c=[],d=0;d<this.messages.length;d++){var e=this.messages[d];e.notBeforeEventId===a?b.push(e):c.push(e)}this.messages=c;return b};function Rx(a,b,c){c.eventMetadata=c.eventMetadata||{};c.eventMetadata.source_canonical_id=ag.canonicalContainerId;Sx().enqueue(a,b,c)}
function Tx(){var a=Ux;Sx().listen(a)}function Sx(){var a=vi.mb;a||(a=new Qx,vi.mb=a);return a};var Xf;var Vx={},Wx={};function Xx(a,b){for(var c=[],d=[],e={},f=0;f<a.length;e={Qh:void 0,yh:void 0},f++){var g=a[f];if(g.indexOf("-")>=0){if(e.Qh=zl(g,b),e.Qh){var k=Tj();Eb(k,function(r){return function(t){return r.Qh.ia===t}}(e))?c.push(g):d.push(g)}}else{var m=Vx[g]||[];e.yh={};m.forEach(function(r){return function(t){r.yh[t]=!0}}(e));for(var n=Qj(),p=0;p<n.length;p++)if(e.yh[n[p]]){c=c.concat(Tj());break}var q=Wx[g]||[];q.length&&(c=c.concat(q))}}return{zm:c,Cm:d}}
function Yx(a){z(Vx,function(b,c){var d=c.indexOf(a);d>=0&&c.splice(d,1)})}function Zx(a){z(Wx,function(b,c){var d=c.indexOf(a);d>=0&&c.splice(d,1)})}var $x="HA GF G UA AW DC MC".split(" "),ay=!1,by=!1,cy=!1,dy=!1;function ey(a,b){a.hasOwnProperty("gtm.uniqueEventId")||Object.defineProperty(a,"gtm.uniqueEventId",{value:Mi()});b.eventId=a["gtm.uniqueEventId"];b.priorityId=a["gtm.priorityId"];return{eventId:b.eventId,priorityId:b.priorityId}}var fy=void 0,gy=void 0;
function hy(a,b,c){var d=h(a,null);d.eventId=void 0;d.inheritParentConfig=void 0;Object.keys(b).some(function(f){return b[f]!==void 0})&&O(136);var e=h(b,null);h(c,e);Rx(Ox(Qj()[0],e),a.eventId,d)}function iy(a){for(var b=oa([P.g.jd,P.g.Ob]),c=b.next();!c.done;c=b.next()){var d=c.value,e=a&&a[d]||Bm.D[d];if(e)return e}}
var jy=[P.g.jd,P.g.Ob,P.g.yc,P.g.pb,P.g.wb,P.g.Ba,P.g.sa,P.g.Qa,P.g.Wa,P.g.Ib],ky={config:function(a,b){var c=ey(a,b);if(!(a.length<2)&&l(a[1])){var d={};if(a.length>2){if(a[2]!==void 0&&!fb(a[2])||a.length>3)return;d=a[2]}var e=zl(a[1],b.isGtmEvent);if(e){var f,g,k;a:{if(!Lj.oe){var m=Zj(ak());if(lk(m)){var n=m.parent,p=n.isDestination;k={Jm:Zj(n),ym:p};break a}}k=void 0}var q=k;q&&(f=q.Jm,g=q.ym);bx(c.eventId,"gtag.config");var r=e.ia,t=e.id!==r;if(t?Tj().indexOf(r)===-1:Qj().indexOf(r)===-1){if(!b.inheritParentConfig&&
!d[P.g.Lb]){var u=iy(d);if(t)uw(r,u,{source:2,fromContainerExecution:b.fromContainerExecution});else if(f!==void 0&&f.containers.indexOf(r)!==-1){var v=d;fy?hy(b,v,fy):gy||(gy=h(v,null))}else rw(r,u,!0,{source:2,fromContainerExecution:b.fromContainerExecution})}}else{if(f&&(O(128),g&&O(130),b.inheritParentConfig)){var w;var x=d;gy?(hy(b,gy,x),w=!1):(!x[P.g.fc]&&zi&&fy||(fy=h(x,null)),w=!0);w&&f.containers&&f.containers.join(",");return}var y=d;if(!cy&&(cy=!0,by))for(var B=oa(jy),A=B.next();!A.done;A=
B.next())if(y.hasOwnProperty(A.value)){Zk("erc");break}Dj&&!Pj&&(Lx===1&&(pk.mcc=!1),Lx=2);Wk=!0;if(zi&&!t&&!d[P.g.fc]){var C=dy;dy=!0;if(C)return}ay||O(43);if(!b.noTargetGroup)if(t){Zx(e.id);var E=e.id,D=d[P.g.Yd]||"default";D=String(D).split(",");for(var F=0;F<D.length;F++){var L=Wx[D[F]]||[];Wx[D[F]]=L;L.indexOf(E)<0&&L.push(E)}}else{Yx(e.id);var M=e.id,S=d[P.g.Yd]||"default";S=S.toString().split(",");for(var V=0;V<S.length;V++){var aa=Vx[S[V]]||[];Vx[S[V]]=aa;aa.indexOf(M)<0&&aa.push(M)}}delete d[P.g.Yd];
var X=b.eventMetadata||{};X.hasOwnProperty("is_external_event")||(X.is_external_event=!b.fromContainerExecution);b.eventMetadata=X;delete d[P.g.bd];for(var R=t?[e.id]:Tj(),ma=0;ma<R.length;ma++){var la=d,ha=R[ma],ya=h(b,null),Na=zl(ha,ya.isGtmEvent);Na&&Bm.push("config",[la],Na,ya)}}}}},consent:function(a,b){if(a.length===3){O(39);var c=ey(a,b),d=a[1],e=a[2];b.fromContainerExecution||(e[P.g.P]&&O(139),e[P.g.ya]&&O(140));d==="default"?ml(e):d==="update"?ol(e,c):d==="declare"&&b.fromContainerExecution&&
ll(e)}},event:function(a,b){var c=a[1];if(!(a.length<2)&&l(c)){var d=void 0;if(a.length>2){if(!fb(a[2])&&a[2]!==void 0||a.length>3)return;d=a[2]}var e=d,f={},g=(f.event=c,f);e&&(g.eventModel=h(e,null),e[P.g.bd]&&(g.eventCallback=e[P.g.bd]),e[P.g.Vd]&&(g.eventTimeout=e[P.g.Vd]));var k=ey(a,b),m=k.eventId,n=k.priorityId;g["gtm.uniqueEventId"]=m;n&&(g["gtm.priorityId"]=n);if(c==="optimize.callback")return g.eventModel=g.eventModel||{},g;var p;var q=d,r=q&&q[P.g.bc];r===void 0&&(r=Wi(P.g.bc,2),r===void 0&&
(r="default"));if(l(r)||Array.isArray(r)){var t;t=b.isGtmEvent?l(r)?[r]:r:r.toString().replace(/\s+/g,"").split(",");var u=Xx(t,b.isGtmEvent),v=u.zm,w=u.Cm;if(w.length)for(var x=iy(q),y=0;y<w.length;y++){var B=zl(w[y],b.isGtmEvent);B&&uw(B.ia,x,{source:3,fromContainerExecution:b.fromContainerExecution})}p=Al(v,b.isGtmEvent)}else p=void 0;var A=p;if(A){var C;!A.length||((C=b.eventMetadata)==null?0:C.em_event)||(by=!0);bx(m,c);for(var E=[],D=0;D<A.length;D++){var F=A[D],L=h(b,null);if($x.indexOf(bk(F.prefix))!==
-1){var M=h(d,null),S=L.eventMetadata||{};S.hasOwnProperty("is_external_event")||(S.is_external_event=!L.fromContainerExecution);L.eventMetadata=S;delete M[P.g.bd];Cm(c,M,F.id,L);Dj&&!Pj&&Lx===0&&(rk("mcc","1"),Lx=1);Wk=!0}E.push(F.id)}g.eventModel=g.eventModel||{};A.length>0?g.eventModel[P.g.bc]=E.join():delete g.eventModel[P.g.bc];ay||O(43);b.noGtmEvent===void 0&&b.eventMetadata&&b.eventMetadata.syn_or_mod&&(b.noGtmEvent=!0);g.eventModel[P.g.Zb]&&(b.noGtmEvent=!0);return b.noGtmEvent?void 0:g}}},
get:function(a,b){O(53);if(a.length===4&&l(a[1])&&l(a[2])&&Bb(a[3])){var c=zl(a[1],b.isGtmEvent),d=String(a[2]),e=a[3];if(c){ay||O(43);var f=iy();if(!Eb(Tj(),function(k){return c.ia===k}))uw(c.ia,f,{source:4,fromContainerExecution:b.fromContainerExecution});else if($x.indexOf(bk(c.prefix))!==-1){Wk=!0;ey(a,b);var g={};h((g[P.g.tb]=d,g[P.g.Jb]=e,g),null);Dm(d,function(k){I(function(){e(k)})},c.id,b)}}}},js:function(a,b){if(a.length===2&&a[1].getTime){ay=!0;var c=ey(a,b),d=c.eventId,e=c.priorityId,
f={};return f.event="gtm.js",f["gtm.start"]=a[1].getTime(),f["gtm.uniqueEventId"]=d,f["gtm.priorityId"]=e,f}},policy:function(a){if(a.length===3&&l(a[1])&&Bb(a[2])){if(Yf(a[1],a[2]),O(74),a[1]==="all"){O(75);var b=!1;try{b=a[2](Vj(),"unknown",{})}catch(c){}b||O(76)}}else O(73)},set:function(a,b){var c=void 0;a.length===2&&fb(a[1])?c=h(a[1],null):a.length===3&&l(a[1])&&(c={},fb(a[2])||Array.isArray(a[2])?c[a[1]]=h(a[2],null):c[a[1]]=a[2]);if(c){var d=ey(a,b),e=d.eventId,f=d.priorityId;h(c,null);var g=
h(c,null);Bm.push("set",[g],void 0,b);c["gtm.uniqueEventId"]=e;f&&(c["gtm.priorityId"]=f);delete c.event;b.overwriteModelFields=!0;return c}}},ly={policy:!0};var ny=function(a){if(my(a))return a;this.value=a};ny.prototype.getUntrustedMessageValue=function(){return this.value};var my=function(a){return!a||db(a)!=="object"||fb(a)?!1:"getUntrustedMessageValue"in a};ny.prototype.getUntrustedMessageValue=ny.prototype.getUntrustedMessageValue;var oy=!1,py=[];function qy(){if(!oy){oy=!0;for(var a=0;a<py.length;a++)I(py[a])}}function ry(a){oy?I(a):py.push(a)};var sy=0,ty={},uy=[],vy=[],wy=!1,xy=!1;function yy(a,b){return a.messageContext.eventId-b.messageContext.eventId||a.messageContext.priorityId-b.messageContext.priorityId}
var zy=function(a){return G[ui.jb].push(a)},Ay=function(a,b,c){a.eventCallback=b;c&&(a.eventTimeout=c);return zy(a)},By=function(a,b){if(!Cb(b)||b<0)b=0;var c=vi[ui.jb],d=0,e=!1,f=void 0;f=G.setTimeout(function(){e||(e=!0,a());f=void 0},b);return function(){var g=c?c.subscribers:1;++d===g&&(f&&(G.clearTimeout(f),f=void 0),e||(a(),e=!0))}};
function Cy(a,b){var c=a._clear||b.overwriteModelFields;z(a,function(e,f){e!=="_clear"&&(c&&Zi(e),Zi(e,f))});Ii||(Ii=a["gtm.start"]);var d=a["gtm.uniqueEventId"];if(!a.event)return!1;typeof d!=="number"&&(d=Mi(),a["gtm.uniqueEventId"]=d,Zi("gtm.uniqueEventId",d));return Fx(a)}function Dy(a){if(a==null||typeof a!=="object")return!1;if(a.event)return!0;if(Ib(a)){var b=a[0];if(b==="config"||b==="event"||b==="js"||b==="get")return!0}return!1}
function Ey(){var a;if(vy.length)a=vy.shift();else if(uy.length)a=uy.shift();else return;var b;var c=a;if(wy||!Dy(c.message))b=c;else{wy=!0;var d=c.message["gtm.uniqueEventId"];typeof d!=="number"&&(d=c.message["gtm.uniqueEventId"]=Mi());var e={},f={message:(e.event="gtm.init_consent",e["gtm.uniqueEventId"]=d-2,e),messageContext:{eventId:d-2}},g={},k={message:(g.event="gtm.init",g["gtm.uniqueEventId"]=d-1,g),messageContext:{eventId:d-1}};uy.unshift(k,c);if(Dj){if(!T(85)){var m=ww();m&&vw.push(m)}vk()}b=
f}return b}
function Fy(){for(var a=!1,b;!xy&&(b=Ey());){xy=!0;delete Ti.eventModel;Vi();var c=b,d=c.message,e=c.messageContext;if(d==null)xy=!1;else{e.fromContainerExecution&&$i();try{if(Bb(d))try{d.call(Xi)}catch(v){}else if(Array.isArray(d)){var f=d;if(l(f[0])){var g=f[0].split("."),k=g.pop(),m=f.slice(1),n=Wi(g.join("."),2);if(n!=null)try{n[k].apply(n,m)}catch(v){}}}else{var p=void 0;if(Ib(d))a:{if(d.length&&l(d[0])){var q=ky[d[0]];if(q&&(!e.fromContainerExecution||!ly[d[0]])){p=q(d,e);break a}}p=void 0}else p=
d;p&&(a=Cy(p,e)||a)}}finally{e.fromContainerExecution&&Vi(!0);var r=d["gtm.uniqueEventId"];if(typeof r==="number"){for(var t=ty[String(r)]||[],u=0;u<t.length;u++)vy.push(Gy(t[u]));t.length&&vy.sort(yy);delete ty[String(r)];r>sy&&(sy=r)}xy=!1}}}return!a}
function Hy(){if(T(69)){var a=Iy();}var b=Fy();if(T(69)){}try{var c=Vj(),d=G[ui.jb].hide;if(d&&d[c]!==void 0&&d.end){d[c]=!1;var e=!0,f;for(f in d)if(d.hasOwnProperty(f)&&d[f]===
!0){e=!1;break}e&&(d.end(),d.end=null)}}catch(g){}return b}function Ux(a){if(sy<a.notBeforeEventId){var b=String(a.notBeforeEventId);ty[b]=ty[b]||[];ty[b].push(a)}else vy.push(Gy(a)),vy.sort(yy),I(function(){xy||Fy()})}function Gy(a){return{message:a.message,messageContext:a.messageContext}}
var Jy=function(){function a(f){var g={};if(my(f)){var k=f;f=my(k)?k.getUntrustedMessageValue():void 0;g.fromContainerExecution=!0}return{message:f,messageContext:g}}var b=Gc(ui.jb,[]),c=vi[ui.jb]=vi[ui.jb]||{};c.pruned===!0&&O(83);ty=Sx().get();Tx();Ew(function(){if(!c.gtmDom){c.gtmDom=!0;var f={};b.push((f.event="gtm.dom",f))}});ry(function(){if(!c.gtmLoad){c.gtmLoad=!0;var f={};b.push((f.event="gtm.load",f))}});c.subscribers=(c.subscribers||0)+1;var d=b.push;b.push=function(){var f;if(vi.SANDBOXED_JS_SEMAPHORE>
0){f=[];for(var g=0;g<arguments.length;g++)f[g]=new ny(arguments[g])}else f=[].slice.call(arguments,0);var k=f.map(function(q){return a(q)});uy.push.apply(uy,k);var m=d.apply(b,f),n=Math.max(100,Number("1000")||300);if(this.length>n)for(O(4),c.pruned=!0;this.length>n;)this.shift();var p=typeof m!=="boolean"||m;return Fy()&&p};var e=b.slice(0).map(function(f){return a(f)});uy.push.apply(uy,e);if(Iy()){if(T(69)){}I(Hy)}},Iy=function(){var a=!0;a=!1;return a};function Ky(a){if(a==null||a.length===0)return!1;var b=Number(a),c=Ob();return b<c+3E5&&b>c-9E5}function Ly(a){return a&&a.indexOf("pending:")===0?Ky(a.substr(8)):!1};

var fz=function(){};var gz=function(){};gz.prototype.toString=function(){return"undefined"};var hz=new gz;function oz(a,b){function c(g){var k=nj(g),m=hj(k,"protocol"),n=hj(k,"host",!0),p=hj(k,"port"),q=hj(k,"path").toLowerCase().replace(/\/$/,"");if(m===void 0||m==="http"&&p==="80"||m==="https"&&p==="443")m="web",p="default";return[m,n,p,q]}for(var d=c(String(a)),e=c(String(b)),f=0;f<d.length;f++)if(d[f]!==e[f])return!1;return!0}
function pz(a){return qz(a)?1:0}
function qz(a){var b=a.arg0,c=a.arg1;if(a.any_of&&Array.isArray(c)){for(var d=0;d<c.length;d++){var e=h(a,{});h({arg1:c[d],any_of:void 0},e);if(pz(e))return!0}return!1}switch(a["function"]){case "_cn":return Ag(b,c);case "_css":var f;a:{if(b)try{for(var g=0;g<wg.length;g++){var k=wg[g];if(b[k]!=null){f=b[k](c);break a}}}catch(m){}f=!1}return f;case "_ew":return xg(b,c);case "_eq":return Bg(b,c);case "_ge":return Cg(b,c);case "_gt":return Eg(b,c);case "_lc":return String(b).split(",").indexOf(String(c))>=
0;case "_le":return Dg(b,c);case "_lt":return Fg(b,c);case "_re":return zg(b,c,a.ignore_case);case "_sw":return Gg(b,c);case "_um":return oz(b,c)}return!1};function rz(){var a;a=a===void 0?"":a;var b,c;return((b=data)==null?0:(c=b.blob)==null?0:c.hasOwnProperty(1))?String(data.blob[1]):a};function sz(){var a=[["cv",T(92)?rz():"4"],["rv",ui.Yg],["tc",xf.filter(function(b){return b}).length]];ui.se&&a.push(["x",ui.se]);Oi.j&&a.push(["tag_exp",Oi.j]);return a};var tz={},uz={};function vz(){var a=0;return function(b){switch(b){case 1:a|=1;break;case 2:a|=2;break;case 3:a|=4}return a}}function wz(a,b,c,d){if(Cj){var e=String(c)+b;tz[a]=tz[a]||[];tz[a].push(e);uz[a]=uz[a]||[];uz[a].push(d+b)}}function xz(a){var b=a.eventId,c=a.mc,d=[],e=tz[b]||[];e.length&&d.push(["hf",e.join(".")]);var f=uz[b]||[];f.length&&d.push(["ht",f.join(".")]);c&&(delete tz[b],delete uz[b]);return d};function yz(){return!1}function zz(){var a={};return function(b,c,d){}};function Az(){var a=Bz;return function(b,c,d){var e=d&&d.event;Cz(c);var f=Tb(b,"__cvt_")?void 0:1,g=new lb;z(c,function(r,t){var u=qd(t,void 0,f);u===void 0&&t!==void 0&&O(44);g.set(r,u)});a.j.j.D=Qf();var k={Pj:eg(b),eventId:e==null?void 0:e.id,priorityId:e!==void 0?e.priorityId:void 0,we:e!==void 0?function(r){e.ic.we(r)}:void 0,fb:function(){return b},log:function(){},Ll:{index:d==null?void 0:d.index,type:d==null?void 0:d.type,name:d==null?void 0:d.name},Tm:!!dw(b,3),originalEventData:e==null?
void 0:e.originalEventData};e&&e.cachedModelValues&&(k.cachedModelValues={gtm:e.cachedModelValues.gtm,ecommerce:e.cachedModelValues.ecommerce});if(yz()){var m=zz(),n,p;k.Ta={bi:[],xe:{},Ab:function(r,t,u){t===1&&(n=r);t===7&&(p=u);m(r,t,u)},Xf:oh()};k.log=function(r){var t=Ma.apply(1,arguments);n&&m(n,4,{level:r,source:p,message:t})}}var q=Re(a,k,[b,g]);a.j.j.D=void 0;q instanceof Qa&&q.type==="return"&&(q=q.data);return J(q,void 0,f)}}
function Cz(a){var b=a.gtmOnSuccess,c=a.gtmOnFailure;Bb(b)&&(a.gtmOnSuccess=function(){I(b)});Bb(c)&&(a.gtmOnFailure=function(){I(c)})};function Dz(a,b){var c=this;}Dz.T="addConsentListener";var Ez=!1;function Fz(a){for(var b=0;b<a.length;++b)if(Ez)try{a[b]()}catch(c){O(77)}else a[b]()}function Gz(a,b,c){var d=this,e;K(this.getName(),["eventName:!string","callback:!Fn","triggerId:?string"],arguments),Fz([function(){N(d,"listen_data_layer",a)}]),e=Ax().addListener(a,J(b),c);return e}Gz.J="internal.addDataLayerEventListener";function Hz(a,b,c){}Hz.T="addDocumentEventListener";function Iz(a,b,c,d){}Iz.T="addElementEventListener";function Jz(a){return a.F.j};function Kz(a){}Kz.T="addEventCallback";
var Lz=function(a){return typeof a==="string"?a:String(Mi())},Oz=function(a,b){Mz(a,"init",!1)||(Nz(a,"init",!0),b())},Mz=function(a,b,c){var d=Pz(a);return Pb(d,b,c)},Qz=function(a,b,c,d){var e=Pz(a),f=Pb(e,b,d);e[b]=c(f)},Nz=function(a,b,c){Pz(a)[b]=c},Pz=function(a){vi.hasOwnProperty("autoEventsSettings")||(vi.autoEventsSettings={});var b=vi.autoEventsSettings;b.hasOwnProperty(a)||(b[a]={});return b[a]},Rz=function(a,b,c){var d={event:b,"gtm.element":a,"gtm.elementClasses":$c(a,"className"),"gtm.elementId":a["for"]||
Rc(a,"id")||"","gtm.elementTarget":a.formTarget||$c(a,"target")||""};c&&(d["gtm.triggers"]=c.join(","));d["gtm.elementUrl"]=(a.attributes&&a.attributes.formaction?a.formAction:"")||a.action||$c(a,"href")||a.src||a.code||a.codebase||"";return d};
function $z(a){}$z.J="internal.addFormAbandonmentListener";function aA(a,b,c,d){}
aA.J="internal.addFormData";var bA={},cA=[],dA={},eA=0,fA=0;
function mA(a,b){}mA.J="internal.addFormInteractionListener";
function tA(a,b){}tA.J="internal.addFormSubmitListener";
function yA(a){}yA.J="internal.addGaSendListener";function zA(a){if(!a)return{};var b=a.Ll;return Gw(b.type,b.index,b.name)}function AA(a){return a?{originatingEntity:zA(a)}:{}};function IA(a){var b=vi.zones;return b?b.getIsAllowedFn(Qj(),a):function(){return!0}}
function JA(){gw(Xj(),function(a){var b=a.originalEventData["gtm.uniqueEventId"],c=vi.zones;return c?c.isActive(Qj(),b):!0});ew(Xj(),function(a){var b,c;b=a.entityId;c=a.securityGroups;return IA(Number(a.originalEventData["gtm.uniqueEventId"]))(b,c)})};var KA=function(a,b){this.tagId=a;this.ze=b};
function LA(a,b){var c=this,d;return d}
LA.J="internal.loadGoogleTag";function MA(a){return new id("",function(b){var c=this.evaluate(b);if(c instanceof id)return new id("",function(){var d=Ma.apply(0,arguments),e=this,f=h(Jz(this),null);f.eventId=a.eventId;f.priorityId=a.priorityId;f.originalEventData=a.originalEventData;var g=d.map(function(m){return e.evaluate(m)}),k=Wa(this.F);k.j=f;return c.ib.apply(c,[k].concat(qa(g)))})})};function NA(a,b,c){var d=this;}NA.J="internal.addGoogleTagRestriction";var OA={},PA=[];
function WA(a,b){}
WA.J="internal.addHistoryChangeListener";function XA(a,b,c){}XA.T="addWindowEventListener";function YA(a,b){return!0}YA.T="aliasInWindow";function ZA(a,b,c){K(this.getName(),["targetId:!string","name:!string","value:!*"],arguments);for(var d=b.split("."),e=Em(a),f=0;f<d.length-1;f++){if(e[d[f]]===void 0)e[d[f]]={};else if(!fb(e[d[f]]))throw Error("apendRemoteConfigParameter failed, path contains a non-object type: "+d[f]);e=e[d[f]]}if(e[d[f]]===void 0)e[d[f]]=[];else if(!Array.isArray(e[d[f]]))throw Error("appendRemoteConfigParameter failed, destination is not an array: "+
d[f]);e[d[f]].push(J(c,this.F));}ZA.J="internal.appendRemoteConfigParameter";function $A(a){var b;return b}$A.T="callInWindow";function aB(a){}aB.T="callLater";function bB(a){}bB.J="callOnDomReady";function cB(a){}cB.J="callOnWindowLoad";function dB(a,b){var c;return c}dB.J="internal.computeGtmParameter";function eB(a){var b;return b}eB.J="internal.copyFromCrossContainerData";function fB(a,b){var c;var d=qd(c,this.F,Tb(Jz(this).fb(),"__cvt_")?2:1);d===void 0&&c!==void 0&&O(45);return d}fB.T="copyFromDataLayer";
function gB(a){var b=void 0;return b}gB.J="internal.copyFromDataLayerCache";function hB(a){var b;return b}hB.T="copyFromWindow";function iB(a){var b=void 0;return qd(b,this.F,1)}iB.J="internal.copyKeyFromWindow";var jB=function(a,b,c){this.eventName=b;this.m=c;this.o={};this.isAborted=!1;this.target=a;this.metadata=h(c.eventMetadata||{},{})};jB.prototype.copyToHitData=function(a,b,c){var d=U(this.m,a);d===void 0&&(d=b);if(d!==void 0&&c!==void 0&&l(d)&&T(63))try{d=c(d)}catch(e){}d!==void 0&&(this.o[a]=d)};var et=function(a,b,c){var d=hs(a.target.ia);return d&&d[b]!==void 0?d[b]:c};function kB(a,b){var c;K(this.getName(),["preHit:!PixieMap","dustOptions:?PixieMap"],arguments);var d=J(b)||{},e=J(a,this.F,1).Vj(),f=e.m;d.omitEventContext&&(f=gm(new Wl(e.m.eventId,e.m.priorityId)));var g=new jB(e.target,e.eventName,f);d.omitHitData||h(e.o,g.o);d.omitMetadata?g.metadata={}:h(e.metadata,g.metadata);g.isAborted=e.isAborted;c=qd(Yr(g),this.F,1);return c}kB.J="internal.copyPreHit";function lB(a,b){var c=null;return qd(c,this.F,2)}lB.T="createArgumentsQueue";function mB(a){return qd(function(c){var d=Qw();if(typeof c==="function")d(function(){c(function(f,g,k){var m=Qw(),n=m&&m.getByName&&
m.getByName(f);return Mm(G.gaplugins.Linker,n).decorate(g,k)})});else if(Array.isArray(c)){var e=String(c[0]).split(".");b[e.length===1?e[0]:e[1]]&&d.apply(null,c)}else if(c==="isLoaded")return!!d.loaded},this.F,1)}mB.J="internal.createGaCommandQueue";function nB(a){return qd(function(){if(!Bb(e.push))throw Error("Object at "+a+" in window is not an array.");e.push.apply(e,Array.prototype.slice.call(arguments,0))},this.F,Tb(Jz(this).fb(),
"__cvt_")?2:1)}nB.T="createQueue";function oB(a,b){var c=null;K(this.getName(),["pattern:!string","flags:?string"],arguments);try{var d=(b||"").split("").filter(function(e){return"ig".indexOf(e)>=0}).join("");c=new nd(new RegExp(a,d))}catch(e){}return c}oB.J="internal.createRegex";function pB(){var a={};return a};function qB(a){K(this.getName(),["consentSettings:!PixieMap"],arguments);for(var b=a.Qb(),c=b.length(),d=0;d<c;d++){var e=b.get(d);e!==P.g.Fb&&N(this,"access_consent",e,"write")}var f=Jz(this),g=f.eventId,k=AA(f),m=Nx("consent","declare",J(a));Rx(m,g,k);}qB.J="internal.declareConsentState";function rB(a){var b="";return b}rB.J="internal.decodeUrlHtmlEntities";function sB(a,b,c){var d;return d}sB.J="internal.decorateUrlWithGaCookies";function tB(){}tB.J="internal.deferCustomEvents";function uB(a){var b;N(this,"detect_user_provided_data","auto");var c=J(a)||{},d=Hs({vd:!!c.includeSelector,wd:!!c.includeVisibility,De:c.excludeElementSelectors,zb:c.fieldFilters,Zf:!!c.selectMultipleElements});b=new lb;var e=new ib;b.set("elements",e);for(var f=d.elements,g=0;g<f.length;g++)e.push(vB(f[g]));d.Rh!==void 0&&b.set("preferredEmailElement",vB(d.Rh));b.set("status",d.status);
return b}
var vB=function(a){var b=new lb;b.set("userData",a.Z);b.set("tagName",a.tagName);a.querySelector!==void 0&&b.set("querySelector",a.querySelector);a.isVisible!==void 0&&b.set("isVisible",a.isVisible);if(T(25)){}else switch(a.type){case Fs.nc:b.set("type","email")}return b};uB.J="internal.detectUserProvidedData";
function yB(a,b){return b}yB.J="internal.enableAutoEventOnClick";
function GB(a,b){return b}GB.J="internal.enableAutoEventOnElementVisibility";function HB(){}HB.J="internal.enableAutoEventOnError";var IB={},JB=[],KB={},LB=0,MB=0;
function SB(a,b){var c=this;return b}SB.J="internal.enableAutoEventOnFormInteraction";
function XB(a,b){var c=this;return b}XB.J="internal.enableAutoEventOnFormSubmit";
function bC(){var a=this;}bC.J="internal.enableAutoEventOnGaSend";var cC={},dC=[];
var fC=function(a,b){var c=""+b;if(cC[c])cC[c].push(a);else{var d=[a];cC[c]=d;var e=eC("gtm.historyChange-v2"),f=-1;dC.push(function(g){f>=0&&G.clearTimeout(f);b?f=G.setTimeout(function(){e(g,d);f=-1},b):e(g,d)})}},eC=function(a){var b=G.location.href,c={source:null,state:G.history.state||null,url:kj(nj(b)),Ia:hj(nj(b),"fragment")};return function(d,e){var f=c,g={};g[f.source]=!0;g[d.source]=!0;if(!g.popstate||!g.hashchange||f.Ia!==d.Ia){var k={event:a,"gtm.historyChangeSource":d.source,"gtm.oldUrlFragment":c.Ia,
"gtm.newUrlFragment":d.Ia,"gtm.oldHistoryState":c.state,"gtm.newHistoryState":d.state,"gtm.oldUrl":c.url,"gtm.newUrl":d.url};e&&(k["gtm.triggers"]=e.join(","));c=d;zy(k)}}},gC=function(a,b){var c=G.history,d=c[a];if(Bb(d))try{c[a]=function(e,f,g){d.apply(c,[].slice.call(arguments,0));var k=G.location.href;b({source:a,state:e,url:kj(nj(k)),Ia:hj(nj(k),"fragment")})}}catch(e){}},iC=function(a){G.addEventListener("popstate",function(b){var c=hC(b);a({source:"popstate",state:b.state,url:kj(nj(c)),Ia:hj(nj(c),
"fragment")})})},jC=function(a){G.addEventListener("hashchange",function(b){var c=hC(b);a({source:"hashchange",state:null,url:kj(nj(c)),Ia:hj(nj(c),"fragment")})})},hC=function(a){var b,c;return((b=a.target)==null?void 0:(c=b.location)==null?void 0:c.href)||G.location.href};
function kC(a,b){var c=this;K(this.getName(),["options:?PixieMap","triggerId:?*"],arguments);Fz([function(){N(c,"detect_history_change_events")}]);var d=a&&a.get("useV2EventName")?"ehl":"hl",e=Number(a&&a.get("interval"));e>0&&isFinite(e)||(e=0);if(!Mz(d,"init",!1)){var f;d==="ehl"?(f=function(k){for(var m=0;m<dC.length;m++)dC[m](k)},b=Lz(b),fC(b,e),Nz(d,"reg",fC)):f=eC("gtm.historyChange");jC(f);iC(f);gC("pushState",f);
gC("replaceState",f);Nz(d,"init",!0)}else if(d==="ehl"){var g=Mz(d,"reg");g&&(b=Lz(b),g(b,e))}d==="hl"&&(b=void 0);return b}kC.J="internal.enableAutoEventOnHistoryChange";var lC=["http://","https://","javascript:","file://"];
function pC(a,b){var c=this;return b}pC.J="internal.enableAutoEventOnLinkClick";var qC,rC;
var sC=function(a){return Mz("sdl",a,{})},tC=function(a,b,c){if(b){var d=Array.isArray(a)?a:[a];Qz("sdl",c,function(e){for(var f=0;f<d.length;f++){var g=String(d[f]);e.hasOwnProperty(g)||(e[g]=[]);e[g].push(b)}return e},{})}},wC=function(){function a(){uC();vC(a,!0)}return a},xC=function(){function a(){f?e=G.setTimeout(a,c):(e=0,uC(),vC(b));f=!1}function b(){d&&qC();e?f=!0:(e=G.setTimeout(a,c),Nz("sdl","pending",!0))}var c=250,d=!1;H.scrollingElement&&H.documentElement&&(c=50,d=!0);var e=0,f=!1;return b},
vC=function(a,b){Mz("sdl","init",!1)&&!yC()&&(b?Qc(G,"scrollend",a):Qc(G,"scroll",a),Qc(G,"resize",a),Nz("sdl","init",!1))},uC=function(){var a=qC(),b=a.mh,c=a.nh,d=b/rC.scrollWidth*100,e=c/rC.scrollHeight*100;zC(b,"horiz.pix","PIXELS","horizontal");zC(d,"horiz.pct","PERCENT","horizontal");zC(c,"vert.pix","PIXELS","vertical");zC(e,"vert.pct","PERCENT","vertical");Nz("sdl","pending",!1)},zC=function(a,b,c,d){var e=sC(b),f={},g;for(g in e)if(f={Bd:f.Bd},f.Bd=g,e.hasOwnProperty(f.Bd)){var k=Number(f.Bd);
if(!(a<k)){var m={};zy((m.event="gtm.scrollDepth",m["gtm.scrollThreshold"]=k,m["gtm.scrollUnits"]=c.toLowerCase(),m["gtm.scrollDirection"]=d,m["gtm.triggers"]=e[f.Bd].join(","),m));Qz("sdl",b,function(n){return function(p){delete p[n.Bd];return p}}(f),{})}}},BC=function(){Qz("sdl","scr",function(a){a||(a=H.scrollingElement||H.body&&H.body.parentNode);return rC=a},!1);Qz("sdl","depth",function(a){a||(a=AC());return qC=a},!1)},AC=function(){var a=0,b=0;return function(){var c=ks(),d=c.height;a=Math.max(rC.scrollLeft+
c.width,a);b=Math.max(rC.scrollTop+d,b);return{mh:a,nh:b}}},yC=function(){return!!(Object.keys(sC("horiz.pix")).length||Object.keys(sC("horiz.pct")).length||Object.keys(sC("vert.pix")).length||Object.keys(sC("vert.pct")).length)};
function CC(a,b){var c=this;K(this.getName(),["options:!PixieMap","triggerId:?*"],arguments);Fz([function(){N(c,"detect_scroll_events")}]);BC();if(!rC)return;b=Lz(b);var d=J(a);switch(d.horizontalThresholdUnits){case "PIXELS":tC(d.horizontalThresholds,b,"horiz.pix");break;case "PERCENT":tC(d.horizontalThresholds,b,"horiz.pct")}switch(d.verticalThresholdUnits){case "PIXELS":tC(d.verticalThresholds,b,"vert.pix");break;case "PERCENT":tC(d.verticalThresholds,
b,"vert.pct")}Mz("sdl","init",!1)?Mz("sdl","pending",!1)||I(function(){uC()}):(Nz("sdl","init",!0),Nz("sdl","pending",!0),I(function(){uC();if(yC()){var e=xC();"onscrollend"in G?(e=wC(),Pc(G,"scrollend",e)):Pc(G,"scroll",e);Pc(G,"resize",e)}else Nz("sdl","init",!1)}));return b}CC.J="internal.enableAutoEventOnScroll";function DC(a){return function(){if(a.Jh&&a.Lh>=a.Jh)a.Vf&&G.clearInterval(a.Vf);else{a.Lh++;var b=Ob();zy({event:a.eventName,"gtm.timerId":a.Vf,"gtm.timerEventNumber":a.Lh,"gtm.timerInterval":a.interval,"gtm.timerLimit":a.Jh,"gtm.timerStartTime":a.rk,"gtm.timerCurrentTime":b,"gtm.timerElapsedTime":b-a.rk,"gtm.triggers":a.pn})}}}
function EC(a,b){
return b}EC.J="internal.enableAutoEventOnTimer";var uc=ka(["data-gtm-yt-inspected-"]),GC=["www.youtube.com","www.youtube-nocookie.com"],HC,IC=!1;
function SC(a,b){var c=this;return b}SC.J="internal.enableAutoEventOnYouTubeActivity";function TC(a,b){K(this.getName(),["booleanExpression:!string","context:?PixieMap"],arguments);var c=b?J(b):{},d=a,e=!1;var f=JSON.parse(d);if(!f)throw Error("Invalid boolean expression string was given.");e=dh(f,c);return e}TC.J="internal.evaluateBooleanExpression";var UC;function VC(a){var b=!1;return b}VC.J="internal.evaluateMatchingRules";function CD(){return On(7)&&On(9)&&On(10)};function xE(a,b,c,d){}xE.J="internal.executeEventProcessor";function yE(a){var b;return qd(b,this.F,1)}yE.J="internal.executeJavascriptString";function zE(a){var b;return b};var AE=null;
function BE(){var a=new lb;N(this,"read_container_data"),T(40)&&AE?a=AE:(a.set("containerId",'G-CSLL4ZEK4L'),a.set("version",'4'),a.set("environmentName",''),a.set("debugMode",fg),a.set("previewMode",gg.tk),a.set("environmentMode",gg.Hl),a.set("firstPartyServing",Qi()||Di),a.set("containerUrl",Fc),a.Ma(),T(40)&&(AE=a));return a}
BE.T="getContainerVersion";function CE(a,b){b=b===void 0?!0:b;var c;return c}CE.T="getCookieValues";function DE(){return bl()}DE.J="internal.getCountryCode";function EE(){var a=[];a=Tj();return qd(a)}EE.J="internal.getDestinationIds";function FE(a,b){var c=null;return c}FE.J="internal.getElementAttribute";function GE(a){var b=null;return b}GE.J="internal.getElementById";function HE(a){var b="";return b}HE.J="internal.getElementInnerText";function IE(a,b){var c=null;return c}IE.J="internal.getElementProperty";function JE(a){var b;return b}JE.J="internal.getElementValue";function KE(a){var b=0;return b}KE.J="internal.getElementVisibilityRatio";function LE(a){var b=null;return b}LE.J="internal.getElementsByCssSelector";
function ME(a){var b;K(this.getName(),["keyPath:!string"],arguments);N(this,"read_event_data",a);var c;a:{var d=a,e=Jz(this).originalEventData;if(e){for(var f=e,g={},k={},m={},n=[],p=d.split("\\\\"),q=0;q<p.length;q++){for(var r=p[q].split("\\."),t=0;t<r.length;t++){for(var u=r[t].split("."),v=0;v<u.length;v++)n.push(u[v]),v!==u.length-1&&n.push(m);t!==r.length-1&&n.push(k)}q!==p.length-1&&n.push(g)}for(var w=[],x="",y=oa(n),B=y.next();!B.done;B=
y.next()){var A=B.value;A===m?(w.push(x),x=""):x=A===g?x+"\\":A===k?x+".":x+A}x&&w.push(x);for(var C=oa(w),E=C.next();!E.done;E=C.next()){if(f==null){c=void 0;break a}f=f[E.value]}c=f}else c=void 0}b=qd(c,this.F,1);return b}ME.J="internal.getEventData";var NE={};NE.enableAWFledge=T(26);NE.enableAdsConversionValidation=T(14);NE.enableAutoPiiOnPhoneAndAddress=T(25);NE.enableCachedEcommerceData=T(32);NE.enableCcdPreAutoPiiDetection=T(33);NE.enableCloudRecommentationsErrorLogging=T(34);NE.enableCloudRecommentationsSchemaIngestion=T(35);NE.enableCloudRetailInjectPurchaseMetadata=T(37);NE.enableCloudRetailLogging=T(36);NE.enableCloudRetailPageCategories=T(38);NE.enableConsentDisclosureActivity=T(39);NE.enableConversionMarkerPageViewRename=T(41);
NE.enableDCFledge=T(45);NE.enableDecodeUri=T(63);NE.enableDeferAllEnhancedMeasurement=T(46);NE.enableDmaBlockDisclosure=T(49);NE.enableEuidAutoMode=T(54);NE.enableFormSkipValidation=T(59);NE.enableUrlDecodeEventUsage=T(91);NE.enableZoneConfigInChildContainers=T(93);NE.useEnableAutoEventOnFormApis=T(102);NE.autoPiiEligible=gl();function OE(){return qd(NE)}OE.J="internal.getFlags";function PE(){return new nd(hz)}PE.J="internal.getHtmlId";function QE(a,b){var c;K(this.getName(),["targetId:!string","name:!string"],arguments);var d=hs(a)||{};c=qd(d[b],this.F);return c}QE.J="internal.getProductSettingsParameter";function RE(a,b){var c;return c}RE.T="getQueryParameters";function SE(a,b){var c;return c}SE.T="getReferrerQueryParameters";function TE(a){var b="";return b}TE.T="getReferrerUrl";function UE(){return cl()}UE.J="internal.getRegionCode";function VE(a,b){var c;return c}VE.J="internal.getRemoteConfigParameter";function WE(a){var b="";return b}WE.T="getUrl";function XE(){N(this,"get_user_agent");return Cc.userAgent}XE.J="internal.getUserAgent";var YE=!1,ZE=function(a){var b=a.eventName===P.g.Vb&&Qk()&&ht(a),c=a.metadata.is_sgtm_service_worker,d=a.metadata.batch_on_navigation,e=a.metadata.is_conversion,f=a.metadata.is_session_start,g=a.metadata.create_dc_join,k=a.metadata.create_google_join,m=a.metadata.euid_mode_enabled&&!!gt(a);return!(!Yc()&&!Cc.sendBeacon||e||m||f||g||k||b||c||!d&&YE)};
var $E=function(a){var b=0,c=0;return{start:function(){b=Ob()},stop:function(){c=this.get()},get:function(){var d=0;a.Dh()&&(d=Ob()-b);return d+c}}},aF=function(){this.j=void 0;this.D=0;this.isActive=this.isVisible=this.H=!1;this.O=this.K=void 0};ba=aF.prototype;ba.Yk=function(a){var b=this;if(!this.j){this.H=H.hasFocus();this.isVisible=!H.hidden;this.isActive=!0;var c=function(d,e,f){Pc(d,e,function(g){b.j.stop();f(g);b.Dh()&&b.j.start()})};c(G,"focus",function(){b.H=!0});c(G,"blur",function(){b.H=
!1});c(G,"pageshow",function(d){b.isActive=!0;d.persisted&&O(56);b.O&&b.O()});c(G,"pagehide",function(){b.isActive=!1;b.K&&b.K()});c(H,"visibilitychange",function(){b.isVisible=!H.hidden});ht(a)&&!Hc("Firefox")&&!Hc("FxiOS")&&c(G,"beforeunload",function(){YE=!0});this.Wh();this.D=0}};ba.Wh=function(){this.D+=this.Rf();this.j=$E(this);this.Dh()&&this.j.start()};ba.on=function(a){var b=this.Rf();b>0&&(a.o[P.g.Qd]=b)};ba.am=function(a){a.o[P.g.Qd]=void 0;this.Wh();this.D=0};ba.Dh=function(){return this.H&&
this.isVisible&&this.isActive};ba.Sl=function(){return this.D+this.Rf()};ba.Rf=function(){return this.j&&this.j.get()||0};ba.Rm=function(a){this.K=a};ba.lk=function(a){this.O=a};var cF=function(a){var b=a.metadata.event_usage;if(Array.isArray(b))for(var c=0;c<b.length;c++)bF(b[c]);var d=vb("GA4_EVENT");d&&(a.o._eu=d)},dF=function(){delete tb.GA4_EVENT},bF=function(a){ub("GA4_EVENT",a)};function eF(){return G.gaGlobal=G.gaGlobal||{}}function fF(){var a=eF();a.hid=a.hid||Fb();return a.hid}function gF(a,b){var c=eF();if(c.vid===void 0||b&&!c.from_cookie)c.vid=a,c.from_cookie=b};
var hF=function(a,b,c){var d=a.metadata.client_id_source;if(d===void 0||c<=d)a.o[P.g.pb]=b,a.metadata.client_id_source=c},kF=function(a,b){var c;var d=b.metadata.cookie_options,e=d.prefix+"_ga",f=So(d,void 0,void 0,P.g.U);if(U(b.m,P.g.vc)===!1&&iF(b)===a)c=!0;else{var g=Ro(a,jF[0],d.domain,d.path);c=Io(e,g,f)!==1}return c},iF=function(a){var b=a.metadata.cookie_options,c=b.prefix+"_ga",d=Qo(c,b.domain,b.path,jF,P.g.U);if(!d){var e=String(U(a.m,P.g.uc,""));e&&e!=c&&(d=Qo(e,b.domain,b.path,jF,P.g.U))}return d},
jF=["GA1"],lF=function(a,b){var c=a.o[P.g.pb];if(U(a.m,P.g.Lb)&&U(a.m,P.g.Zb)||b&&c===b)return c;if(c){c=""+c;if(!kF(c,a))return O(31),a.isAborted=!0,"";gF(c,W(P.g.U));return c}O(32);a.isAborted=!0;return""};
var oF=function(a,b,c){if(!b)return a;if(!a)return b;var d=mF(a);if(!d)return b;var e,f=Jb((e=U(c.m,P.g.kd))!=null?e:30);if(!(Math.floor(c.metadata.event_start_timestamp_ms/1E3)>d.Re+f*60))return a;var g=mF(b);if(!g)return a;g.Lc=d.Lc+1;var k;return(k=nF(g.sessionId,g.Lc,g.zd,g.Re,g.Hh,g.Hc,g.Ce))!=null?k:b},rF=function(a,b){var c=b.metadata.cookie_options,d=pF(b,c),e=Ro(a,qF[0],c.domain,c.path),f={Db:P.g.U,domain:c.domain,path:c.path,expires:c.Cb?new Date(Ob()+Number(c.Cb)*1E3):void 0,flags:c.flags};
Io(d,void 0,f);return Io(d,e,f)!==1},sF=function(a){var b=a.metadata.cookie_options,c=pF(a,b),d=Qo(c,b.domain,b.path,qF,P.g.U);if(!d)return d;var e=xo(c,void 0,void 0,P.g.U);if(d&&e.length>1){O(114);for(var f=void 0,g=void 0,k=0;k<e.length;k++){var m=e[k].split(".");if(!(m.length<7)){var n=Number(m[5]);n&&(!g||n>g)&&(g=n,f=e[k])}}f&&!Ub(f,d)&&(O(115),d=f.split(".").slice(2).join("."))}return d},tF=function(a){return nF(a.o[P.g.wb],a.o[P.g.ee],a.o[P.g.de],Math.floor(a.metadata.event_start_timestamp_ms/
1E3),a.metadata.join_timer_sec||0,!!a.metadata[P.g.pf],a.o[P.g.Rd])},nF=function(a,b,c,d,e,f,g){if(a&&b){var k=[a,b,Jb(c),d,e];k.push(f?"1":"0");k.push(g||"0");return k.join(".")}},pF=function(a,b){return b.prefix+"_ga_"+a.target.ma[Cl[0]]},qF=["GS1"],mF=function(a){if(a){var b=a.split(".");if(!(b.length<5||b.length>7)){b.length<7&&O(67);var c=Number(b[1]),d=Number(b[3]),e=Number(b[4]||0);c||O(118);d||O(119);isNaN(e)&&O(120);if(c&&d&&!isNaN(e))return{sessionId:b[0],Lc:c,zd:!!Number(b[2]),Re:d,Hh:e,
Hc:b[5]==="1",Ce:b[6]!=="0"?b[6]:void 0}}}};
var uF=function(a){var b=U(a.m,P.g.sa),c=a.m.D[P.g.sa];if(c===b)return c;var d=h(b);c&&c[P.g.X]&&(d[P.g.X]=(d[P.g.X]||[]).concat(c[P.g.X]));return d},vF=function(a,b){var c=hp(!0);return c._up!=="1"?{}:{clientId:c[a],Ya:c[b]}},wF=function(a,b,c){var d=hp(!0),e=d[b];e&&(hF(a,e,2),kF(e,a));var f=d[c];f&&rF(f,a);return{clientId:e,Ya:f}},xF=!1,yF=function(a){var b=uF(a)||{},c=a.metadata.cookie_options,d=c.prefix+"_ga",e=pF(a,c),f={};rp(b[P.g.Cc],!!b[P.g.X])&&(f=wF(a,d,e),f.clientId&&f.Ya&&(xF=!0));b[P.g.X]&&
op(function(){var g={},k=iF(a);k&&(g[d]=k);var m=sF(a);m&&(g[e]=m);var n=xo("FPLC",void 0,void 0,P.g.U);n.length&&(g._fplc=n[0]);return g},b[P.g.X],b[P.g.Mb],!!b[P.g.vb]);return f},AF=function(a){if(!U(a.m,P.g.Xa))return{};var b=a.metadata.cookie_options,c=b.prefix+"_ga",d=pF(a,b);pp(function(){var e;if(W("analytics_storage"))e={};else{var f={};e=(f._up="1",f[c]=a.o[P.g.pb],f[d]=tF(a),f)}return e},1);return!W("analytics_storage")&&zF()?vF(c,d):{}},zF=function(){var a=jj(G.location,"host"),b=jj(nj(H.referrer),
"host");return a&&b?a===b||a.indexOf("."+b)>=0||b.indexOf("."+a)>=0?!0:!1:!1};var BF=function(a){if(!a.metadata.is_merchant_center&&uj(a.m)){var b=uF(a)||{},c=(rp(b[P.g.Cc],!!b[P.g.X])?hp(!0)._fplc:void 0)||(xo("FPLC",void 0,void 0,P.g.U).length>0?void 0:"0");a.o._fplc=c}};function CF(a){var b=T(60)&&Qi();if(ht(a)||b)a.o[P.g.gj]=cl()||bl()};var EF=function(a,b){var c=vi.grl;c||(c=DF(),vi.grl=c);c(b)||(O(35),a.isAborted=!0)},DF=function(){var a=Ob(),b=a+864E5,c=20,d=5E3;return function(e){var f=Ob();f>=b&&(b=f+864E5,d=5E3);c=Math.min(c+(f-a)/1E3*5,20);a=f;var g=!1;d<1||c<1||(g=!0,d--,c--);e&&(e.Fl=d,e.zl=c);return g}};
var FF=function(a){if(U(a.m,P.g.dd)!==void 0)a.copyToHitData(P.g.dd);else{var b=U(a.m,P.g.tf),c,d;a:{if(xF){var e=uF(a)||{};if(e&&e[P.g.X])for(var f=hj(nj(a.o[P.g.Fa]),"host",!0),g=e[P.g.X],k=0;k<g.length;k++)if(g[k]instanceof RegExp){if(g[k].test(f)){d=!0;break a}}else if(f.indexOf(g[k])>=0){d=!0;break a}}d=!1}if(!(c=d)){var m;if(m=b)a:{for(var n=b.include_conditions||[],p=hj(nj(a.o[P.g.Fa]),"host",!0),q=0;q<n.length;q++)if(n[q].test(p)){m=!0;break a}m=!1}c=m}c&&(a.o[P.g.dd]="1",bF(4))}};
var GF=function(a,b){Un()&&(a.gcs=Vn(),b.metadata.is_consent_update&&(a.gcu="1"));a.gcd=fo(b.m);Tn(b.m)?a.npa="0":a.npa="1";ko()&&(a._ng="1")},JF=function(a){if(a.metadata.is_merchant_center)return{url:vj("https://www.merchant-center-analytics.goog")+"/mc/collect",endpoint:20};var b=rj(uj(a.m),"/g/collect");if(b)return{url:b,endpoint:16};if(Qi())return{url:""+Pi()+"/g/collect",endpoint:16};var c=it(a),d=U(a.m,P.g.ob);return c&&!dl()&&d!==!1&&CD()&&W(P.g.R)&&W(P.g.U)?{url:HF(),endpoint:17}:{url:IF(),
endpoint:16}},KF=!1;KF=!0;var LF={};LF[P.g.pb]="cid";LF[P.g.ng]="gcut";LF[P.g.Xb]="are";LF[P.g.jf]="pscdl";LF[P.g.qf]="_fid";LF[P.g.Cg]="_geo";LF[P.g.ub]="gdid";LF[P.g.Bc]="_ng";LF[P.g.Kb]="frm";LF[P.g.dd]="ir";LF[P.g.Ra]="ul";LF[P.g.Mg]="pae";LF[P.g.be]="_rdi";LF[P.g.Nb]="sr";LF[P.g.fj]="tid";LF[P.g.yf]="tt";LF[P.g.md]="ec_mode";LF[P.g.rj]="gtm_up";LF[P.g.zf]="uaa";LF[P.g.Af]="uab";LF[P.g.Bf]="uafvl";LF[P.g.Cf]="uamb";LF[P.g.Df]="uam";LF[P.g.Ef]="uap";LF[P.g.Ff]="uapv";LF[P.g.Gf]="uaw";LF[P.g.gj]="ur";LF[P.g.ed]="lps";var MF={};MF[P.g.Oc]="cc";MF[P.g.Pc]="ci";MF[P.g.Qc]="cm";MF[P.g.Rc]="cn";MF[P.g.Tc]="cs";MF[P.g.Uc]="ck";MF[P.g.za]="cu";MF[P.g.wa]=
"dl";MF[P.g.Fa]="dr";MF[P.g.cb]="dt";MF[P.g.de]="seg";MF[P.g.wb]="sid";MF[P.g.ee]="sct";MF[P.g.Ba]="uid";T(95)&&(MF[P.g.gd]="dp");var NF={};NF[P.g.Qd]="_et";NF[P.g.rb]="edid";var OF={};OF[P.g.Oc]="cc";OF[P.g.Pc]=
"ci";OF[P.g.Qc]="cm";OF[P.g.Rc]="cn";OF[P.g.Tc]="cs";OF[P.g.Uc]="ck";var PF={},QF=Object.freeze((PF[P.g.Ga]=1,PF)),IF=function(){var a="www";KF&&fl()&&(a=fl());return"https://"+a+".google-analytics.com/g/collect"},HF=function(){var a;KF&&fl()!==""&&(a=fl());return"https://"+(a?a+".":"")+"analytics.google.com/g/collect"},RF=function(a,b,c){var d={},e={},f={};d.v="2";d.tid=a.target.ia;d.gtm=no({xa:a.metadata.source_canonical_id});d._p=T(104)?Ii:fF();c&&(d.em=c);a.metadata.create_google_join&&(d._gaz=
1);GF(d,a);io()&&(d.dma_cps=go());d.dma=ho();yn(Gn())&&(d.tcfd=jo());Oi.j&&(d.tag_exp=Oi.j);var g=a.o[P.g.ub];g&&(d.gdid=g);e.en=String(a.eventName);a.metadata.is_first_visit&&(e._fv=a.metadata.is_first_visit_conversion?2:1);a.metadata.is_new_to_site&&(e._nsi=1);a.metadata.is_session_start&&(e._ss=a.metadata.is_session_start_conversion?2:1);a.metadata.is_conversion&&(e._c=1);a.metadata.is_external_event&&(e._ee=1);if(a.metadata.is_ecommerce){var k=a.o[P.g.da]||U(a.m,P.g.da);if(Array.isArray(k))for(var m=
0;m<k.length&&m<200;m++)e["pr"+(m+1)]=kg(k[m])}var n=a.o[P.g.rb];n&&(e.edid=n);var p=function(t,u){if(typeof u!=="object"||!QF[t]){var v="ep."+t,w="epn."+t;t=Cb(u)?w:v;var x=Cb(u)?v:w;e.hasOwnProperty(x)&&delete e[x];e[t]=String(u)}};z(a.o,function(t,u){if(u!==void 0&&!ci.hasOwnProperty(t)){u===null&&(u="");var v;var w=u;t!==P.g.Rd?v=!1:a.metadata.euid_mode_enabled||ht(a)?(d.ecid=w,v=!0):v=void 0;if(!v&&t!==P.g.pf){var x=u;u===!0&&(x="1");u===!1&&(x="0");x=String(x);var y;if(LF[t])y=LF[t],d[y]=x;
else if(MF[t])y=MF[t],f[y]=x;else if(NF[t])y=NF[t],e[y]=x;else if(t.charAt(0)==="_")d[t]=x;else{var B;OF[t]?B=!0:t!==P.g.Sc?B=!1:(typeof u!=="object"&&p(t,u),B=!0);B||p(t,u)}}}});(function(t){ht(a)&&typeof t==="object"&&z(t||{},function(u,v){typeof v!=="object"&&(d["sst."+u]=String(v))})})(a.o[P.g.te]);var q=a.o[P.g.eb]||{};T(70)&&U(a.m,P.g.ob,void 0,4)===!1&&(d.ngs="1");z(q,function(t,u){u!==void 0&&((u===null&&(u=""),t!==P.g.Ba||f.uid)?b[t]!==u&&(e[(Cb(u)?"upn.":"up.")+String(t)]=String(u),b[t]=
u):f.uid=String(u))});var r=JF(a);sg.call(this,{ja:d,Mc:f,sh:e},r.url,r.endpoint,ht(a),void 0)};za(RF,sg);var SF=function(a){this.D=a;this.H="";this.j=this.D},TF=function(a,b){a.j=b;return a},UF=function(a,b){a.K=b;return a},WF=function(a,b){b=a.H+b;for(var c=b.indexOf("\n\n");c!==-1;){var d=a,e;a:{var f=oa(b.substring(0,c).split("\n")),g=f.next().value,k=f.next().value;if(g.indexOf("event: message")===0&&k.indexOf("data: ")===0)try{e=JSON.parse(k.substring(k.indexOf(":")+1));break a}catch(x){}e=void 0}var m=d,n=e;if(n){VF(n.send_pixel,n.options,m.D);VF(n.send_beacon,void 0,m.j);var p=n.create_iframe,
q=n.options,r=m.K;if(p&&r){var t=p||[];if(Array.isArray(t))for(var u=fb(q)?q:{},v=oa(t),w=v.next();!w.done;w=v.next())r(w.value,u)}}b=b.substring(c+2);c=b.indexOf("\n\n")}a.H=b};function XF(a){var b=a.search;return a.protocol+"//"+a.hostname+a.pathname+(b?b+"&richsstsse":"?richsstsse")}function VF(a,b,c){if(a){var d=a||[];if(Array.isArray(d))for(var e=fb(b)?b:{},f=oa(d),g=f.next();!g.done;g=f.next())c(g.value,e)}};
var YF=function(a,b){return a.replace(/\$\{([^\}]+)\}/g,function(c,d){return b[d]||c})},ZF=function(a){var b={},c="",d=a.pathname.indexOf("/g/collect");d>=0&&(c=a.pathname.substring(0,d));b.transport_url=a.protocol+"//"+a.hostname+c;return b},$F=function(a,b,c){var d=0,e=new G.XMLHttpRequest;e.withCredentials=!0;e.onprogress=function(f){if(e.status===200){var g=e.responseText.substring(d);d=f.loaded;WF(c,g)}};e.open(b?"POST":"GET",a);e.setAttributionReporting&&e.setAttributionReporting({eventSourceEligible:!1,triggerEligible:!0});
e.send(b)},bG=function(a,b,c){var d=Object.assign({},aG);b&&(d.body=b,d.method="POST");G.fetch(a,d).then(function(e){if(e.ok&&e.body){var f=e.body.getReader();return new Promise(function(g){function k(){f.read().then(function(m){var n,p;n=m.done;p=m.value;if(n)g();else{var q=(new TextDecoder).decode(p);WF(c,q);k()}}).catch(function(){g()})}k()})}}).catch(function(){T(81)&&(a+="&_z=retryFetch",b?Wc(a,b):Vc(a))})},cG=function(a,b){return UF(TF(new SF(function(c,d){var e=YF(c,a);b&&(e=e.replace("_is_sw=0",
b));var f={};d.attribution_reporting&&(f.attributionsrc="");Oc(e,void 0,void 0,f)}),function(c){var d=YF(c,a);Vc(d)}),function(c,d){var e=YF(c,a),f=d.dedupe_key;f&&Xt(e,f)})},dG=function(a,b,c,d){var e=cG(c,d);T(80)&&Yc()?bG(a,b,e):$F(a,b,e)},eG=function(a,b){var c=nj(a),d=ZF(c),e=XF(c);T(83)?Dt(e,b,d,function(f){dG(e,b,d,f)}):dG(e,b,d)},aG=Object.freeze({cache:"no-store",credentials:"include",method:"GET",keepalive:!0,redirect:"follow"});
var fG=function(a,b){return a?[a,b].join("&"):b},iG=function(a,b,c,d){var e=b,f=ad();f!==void 0&&(e+="&tfd="+Math.round(f));b=e;var g=a+"?"+b;gG&&(d=!Tb(g,IF())&&!Tb(g,HF()));if(d&&!YE)eG(g,c);else{var k=b;Yc()?Zc(a+"?"+k,c,{Wn:!0})||hG(a,fG(k,"_z=failedfetch"),c):hG(a,fG(k,"_z=nofetch"),c)}},jG=function(a,b){function c(u){n.push(u+"="+encodeURIComponent(""+a.ja[u]))}var d=b.bn,e=b.dn,f=b.Ul,g=b.om,k=b.lm,m=b.Qm;if(d||e){var n=[];a.ja._ng&&c("_ng");c("tid");c("cid");c("gtm");n.push("aip=1");a.Mc.uid&&
!k&&n.push("uid="+encodeURIComponent(""+a.Mc.uid));var p=function(){c("dma");a.ja.dma_cps!=null&&c("dma_cps");a.ja.gcs!=null&&c("gcs");c("gcd");a.ja.npa!=null&&c("npa")};p();a.ja.frm!=null&&c("frm");d&&(Oi.j&&n.push("tag_exp="+Oi.j),hG("https://stats.g.doubleclick.net/g/collect","v=2&"+n.join("&")),n.join("&"));if(e){var q=function(){var u=Zt()+"/td/ga/rul?";n=[];c("tid");n.push("gacid="+encodeURIComponent(String(a.ja.cid)));c("gtm");p();c("pscdl");a.ja._ng!=null&&c("_ng");n.push("aip=1");n.push("fledge=1");
a.ja.frm!=null&&c("frm");Oi.j&&n.push("tag_exp="+Oi.j);n.push("z="+Fb());var v=u+n.join("&");Xt(v,a.ja.tid)};Oi.j&&n.push("tag_exp="+Oi.j);n.push("z="+Fb());if(!g){var r=f&&Tb(f,"google.")&&f!=="google.com"?"https://www.%/ads/ga-audiences?v=1&t=sr&slf_rd=1&_r=4&".replace("%",f):void 0;if(r){var t=r+n.join("&");Oc(t)}}T(70)&&m&&!YE&&q()}}},gG=!1;var kG=function(){this.K=
1;this.O={};this.j=new lg;this.D=-1};kG.prototype.H=function(a,b){var c=this,d=new RF(a,this.O,b),e=ZE(a);e&&this.j.O(d)||this.flush();if(e&&this.j.add(d)){if(this.D<0){var f=G.setTimeout,g;ht(a)?lG?(lG=!1,g=mG):g=nG:g=5E3;this.D=f.call(G,function(){return c.flush()},g)}}else{var k=og(d,this.K++);iG(d.baseUrl,k.params,k.body,d.H);var m=a.metadata.create_dc_join,n=a.metadata.create_google_join,p=U(a.m,P.g.Ea)!==!1,q=Tn(a.m),r={eventId:a.m.eventId,priorityId:a.m.priorityId},t=a.o[P.g.Mg],u={bn:m,dn:n,
Ul:hl(),Pn:p,On:q,om:dl(),lm:a.metadata.euid_mode_enabled,Un:r,Qm:t,m:a.m};jG(d,u)}Cv(a.m.eventId,a.eventName)};kG.prototype.add=function(a){a.metadata.euid_mode_enabled&&!YE?this.W(a):this.H(a)};kG.prototype.flush=function(){if(this.j.events.length){var a=qg(this.j,this.K++);iG(this.j.baseUrl,a.params,a.body,this.j.D);this.j=new lg;this.D>=0&&(G.clearTimeout(this.D),this.D=-1)}};kG.prototype.W=function(a){var b=this,c=gt(a);c?Jh(c,function(d){b.H(a,d.split("~").length===1?void 0:d)}):this.H(a)};
var hG=function(a,b,c){var d=a+"?"+b;c?Wc(d,c):Vc(d)},mG=ri('',500),nG=ri('',5E3),lG=!0;
var oG=function(a,b,c){c===void 0&&(c={});if(typeof b==="object")for(var d in b)oG(a+"."+d,b[d],c);else c[a]=b;return c},pG=function(a){for(var b={},c=oa(a),d=c.next();!d.done;d=c.next()){var e=d.value;b[e]=!!W(e)}return b},rG=function(a,b){var c=qG.filter(function(e){return!W(e)});if(c.length){var d=pG(c);ql(c,function(){for(var e=pG(c),f=[],g=oa(c),k=g.next();!k.done;k=g.next()){var m=k.value;!d[m]&&e[m]&&f.push(m);e[m]&&(d[m]=!0)}if(f.length){b.metadata.is_consent_update=!0;var n=f.map(function(p){return mi[p]}).join(".");
n&&dt(b,"gcut",n);a(b)}})}},qG=[P.g.R,P.g.P],sG=function(a){ht(a)&&Qk()&&dt(a,"rnd",Yq())},tG=function(a){},uG=function(a){if(T(67)&&ht(a)){et(a,P.g.Yb,!1)&&dt(a,"gse",1);U(a.m,P.g.ob,void 0,4)===!1&&dt(a,"ngs",1);dl()&&dt(a,"ga_rd",1);CD()||dt(a,"ngst",1);var b=hl();b&&dt(a,"etld",b)}},vG=function(a){if(ht(a)){var b=KF?fl():"";b&&dt(a,
"gcsub",b)}},wG=function(a){ht(a)&&Qk()&&U(a.m,P.g.fa)&&dt(a,"adr",1)},xG=function(a){if(ht(a)){var b=rr();b&&dt(a,"us_privacy",b);var c=Nn();c&&dt(a,"gdpr",c);var d=Mn();d&&dt(a,"gdpr_consent",d)}},yG=function(a){if(ht(a)){var b=et(a,"ccd_add_1p_data",!1)?1:0;dt(a,"ude",b);var c=function(e){var f=oG(P.g.Ga,e);z(f,function(g,k){a.o[g]=k})},d=U(a.m,P.g.Ga);d!==void 0?(c(d),a.o[P.g.md]="c"):c(a.metadata.user_data);a.metadata.user_data=void 0}},zG=function(a){if(ht(a)){var b=Ii;b&&dt(a,"tft",Number(b))}},
AG=function(a){ht(a)&&(a.metadata.speculative&&dt(a,"sp",1),a.metadata.is_syn&&dt(a,"syn",1),a.metadata.em_event&&(dt(a,"em_event",1),dt(a,"sp",1)))},BG=function(a){ht(a)&&(a.metadata.speculative=!1)},CG=function(a){T(99)&&ht(a)&&U(a.m,P.g.Ea)!==!1&&Vt("join-ad-interest-group")&&Bb(Cc.joinAdInterestGroup)&&dt(a,"flg",1)},DG=function(a){if(ht(a)&&a.eventName===P.g.Nc&&a.metadata.is_consent_update){var b=a.o[P.g.ng];b&&(dt(a,"gcut",b),dt(a,"syn",1))}},EG=function(a,b){if(ht(b)){var c=b.metadata.is_conversion;
(b.eventName==="page_view"||c)&&rG(a,b)}},FG=function(a){T(98)&&ht(a)&&U(a.m,P.g.Hd,!0)===!1&&(a.o[P.g.Hd]=0)};
var GG=function(a,b){var c;a:{var d=tF(a);if(d){if(rF(d,a)){c=d;break a}O(25);a.isAborted=!0}c=void 0}var e=c;return{clientId:lF(a,b),Ya:e}},HG=function(a,b,c,d,e){var f=U(a.m,P.g.pb);if(U(a.m,P.g.Lb)&&U(a.m,P.g.Zb))f?hF(a,f,1):(O(127),a.isAborted=!0);else{var g=f?1:8;a.metadata.is_new_to_site=!1;f||(f=iF(a),g=3);f||(f=b,g=5);if(!f){var k=W(P.g.U),m=eF();f=!m.from_cookie||k?m.vid:void 0;g=6}f?f=""+f:(f=Po(),g=7,a.metadata.is_first_visit=a.metadata.is_new_to_site=!0);hF(a,f,g)}var n=Math.floor(a.metadata.event_start_timestamp_ms/
1E3),p=void 0;a.metadata.is_new_to_site||(p=sF(a)||c);var q=Jb(U(a.m,P.g.kd,30));q=Math.min(475,q);q=Math.max(5,q);var r=Jb(U(a.m,P.g.vf,1E4)),t=mF(p);a.metadata.is_first_visit=!1;a.metadata.is_session_start=!1;a.metadata.join_timer_sec=0;t&&t.Hh&&(a.metadata.join_timer_sec=Math.max(0,t.Hh-Math.max(0,n-t.Re)));var u=!1;t||(u=a.metadata.is_first_visit=!0,t={sessionId:String(n),Lc:1,zd:!1,Re:n,Hc:!1,Ce:void 0});n>t.Re+q*60&&(u=!0,t.sessionId=String(n),t.Lc++,t.zd=!1,t.Ce=void 0);if(u)a.metadata.is_session_start=
!0,d.am(a);else if(d.Sl()>r||a.eventName===P.g.Vb)t.zd=!0;a.metadata.euid_mode_enabled?U(a.m,P.g.Ba)?t.Hc=!0:(t.Hc&&!T(11)&&(t.Ce=void 0),t.Hc=!1):t.Hc=!1;var v=t.Ce;if(a.metadata.euid_mode_enabled||ht(a)){var w=U(a.m,P.g.Rd),x=w?1:8;w||(w=v,x=4);w||(w=Oo(),x=7);var y=w.toString(),B=x,A=a.metadata.enhanced_client_id_source;if(A===void 0||B<=A)a.o[P.g.Rd]=y,a.metadata.enhanced_client_id_source=B}e?(a.copyToHitData(P.g.wb,t.sessionId),a.copyToHitData(P.g.ee,t.Lc),a.copyToHitData(P.g.de,t.zd?1:0)):(a.o[P.g.wb]=
t.sessionId,a.o[P.g.ee]=t.Lc,a.o[P.g.de]=t.zd?1:0);a.metadata[P.g.pf]=t.Hc?1:0};var IG=window,JG=document,KG=function(a){var b=IG._gaUserPrefs;if(b&&b.ioo&&b.ioo()||JG.documentElement.hasAttribute("data-google-analytics-opt-out")||a&&IG["ga-disable-"+a]===!0)return!0;try{var c=IG.external;if(c&&c._gaUserPrefs&&c._gaUserPrefs=="oo")return!0}catch(p){}for(var d=[],e=String(JG.cookie).split(";"),f=0;f<e.length;f++){var g=e[f].split("="),k=g[0].replace(/^\s*|\s*$/g,"");if(k&&k=="AMP_TOKEN"){var m=g.slice(1).join("=").replace(/^\s*|\s*$/g,"");m&&(m=decodeURIComponent(m));d.push(m)}}for(var n=
0;n<d.length;n++)if(d[n]=="$OPT_OUT")return!0;return JG.getElementById("__gaOptOutExtension")?!0:!1};
var MG=function(a){return!a||LG.test(a)||ei.hasOwnProperty(a)},NG=function(a){var b=P.g.Nb,c;c||(c=function(){});a.o[b]!==void 0&&(a.o[b]=c(a.o[b]))},OG=function(a){var b=a.indexOf("?"),c=b===-1?a:a.substring(0,b);try{c=decodeURIComponent(c)}catch(d){}return b===-1?c:""+c+a.substring(b)},PG=function(a){U(a.m,P.g.Xa)&&(W(P.g.U)||U(a.m,P.g.pb)||(a.o[P.g.rj]=!0));var b;var c;c=c===void 0?3:c;var d=G.location.href;if(d){var e=nj(d).search.replace("?",""),f=gj(e,"_gl",!1,!0)||"";b=f?ip(f,c)!==void 0:!1}else b=
!1;b&&ht(a)&&dt(a,"glv",1);if(a.eventName!==P.g.ba)return{};U(a.m,P.g.Xa)&&Bq(["aw","dc"]);Dq(["aw","dc"]);var g=yF(a),k=AF(a);return Object.keys(g).length?g:k},QG=function(a){var b=Yb(Ul(a.m,P.g.la,1),".");b&&(a.o[P.g.ub]=b);var c=Yb(Ul(a.m,P.g.la,2),".");c&&(a.o[P.g.rb]=c)},St={Jl:"",qn:Number("")},RG={},SG=(RG[P.g.Oc]=1,RG[P.g.Pc]=1,RG[P.g.Qc]=1,RG[P.g.Rc]=1,RG[P.g.Tc]=1,RG[P.g.Uc]=1,RG),LG=/^(_|ga_|google_|gtag\.|firebase_).*$/,TG=[vr,
QG,$r],UG=function(a){this.H=a;this.j=this.Ya=this.clientId=void 0;this.Ca=this.O=!1;this.xb=0;this.K=!1;this.W=new kG;this.D=new aF};ba=UG.prototype;ba.Om=function(a,b,c){var d=this,e=zl(this.H);if(e)if(c.eventMetadata.is_external_event&&a.charAt(0)==="_")c.onFailure();else{a!==P.g.ba&&a!==P.g.Ua&&MG(a)&&O(58);VG(c.j);var f=new jB(e,a,c);f.metadata.event_start_timestamp_ms=b;var g=[P.g.U];if(et(f,P.g.Yb,U(f.m,P.g.Yb))||ht(f))g.push(P.g.R),g.push(P.g.P);Tt(function(){sl(function(){d.Pm(f)},g)});this.Mm(a,
c,f)}else c.onFailure()};ba.Mm=function(a,b,c){var d=zl(this.H);if(T(61)&&a===P.g.ba&&et(c,"ga4_ads_linked",!1)){var e=function(){for(var k=oa(TG),m=k.next();!m.done;m=k.next()){var n=m.value;n(f);if(f.isAborted)break}f.metadata.speculative||f.isAborted||Qu(f)},f=new jB(d,a,b);f.metadata.hit_type="page_view";f.metadata.speculative=!0;f.metadata.is_server_side_destination=ht(c);var g=[P.g.R,P.g.P];sl(function(){e();W(g)||rl(function(k){var m,n;m=k.consentEventId;n=k.consentPriorityId;f.metadata.consent_updated=
!0;f.metadata.consent_event_id=m;f.metadata.consent_priority_id=n;e()},g)},g)}};ba.Pm=function(a){var b=this;this.j=a;try{WG(a);XG(a);YG(a);ZG(a);T(88)&&(a.isAborted=!0);Ar(a);var c={};EF(a,c);if(a.isAborted){a.m.onFailure();dF();return}var d=c.zl;c.Fl===0&&bF(25);d===0&&bF(26);$G(a);aH(a);this.Zk(a);this.D.on(a);bH(a);cH(a);dH(a);this.kk(PG(a));var e=a.eventName===P.g.ba;e&&(this.K=!0);eH(a);e&&!a.isAborted&&this.xb++>0&&bF(17);fH(a);HG(a,this.clientId,this.Ya,this.D,!this.Ca);gH(a);hH(a);iH(a);
jH(a);kH(a);lH(a);mH(a);BF(a);FF(a);sG(a);tG(a);uG(a);vG(a);wG(a);xG(a);zG(a);AG(a);CG(a);DG(a);FG(a);CF(a);nH(a);oH(a);pH(a);Cr(a);Br(a);qH(a);rH(a);$r(a);yG(a);BG(a);sH(a);!this.K&&a.metadata.em_event&&bF(18);cF(a);if(a.metadata.speculative||a.isAborted){a.m.onFailure();dF();return}this.kk(GG(a,this.clientId));this.Ca=!0;this.jn(a);tH(a);EG(function(f){b.Nj(f)},a);this.D.Wh();uH(a);if(a.isAborted){a.m.onFailure();dF();return}this.Nj(a);a.m.onSuccess()}catch(f){a.m.onFailure()}dF()};ba.Nj=function(a){this.W.add(a)};
ba.kk=function(a){var b=a.clientId,c=a.Ya;b&&c&&(this.clientId=b,this.Ya=c)};ba.flush=function(){this.W.flush()};ba.jn=function(a){var b=this;if(!this.O){var c=W(P.g.P),d=W(P.g.U);ql([P.g.P,P.g.U],function(){var e=W(P.g.P),f=W(P.g.U),g=!1,k={},m={};if(d!==f&&b.j&&b.Ya&&b.clientId){var n=b.clientId;if(f){var p=iF(b.j);if(p){b.clientId=p;var q=sF(b.j);q&&(b.Ya=oF(q,b.Ya,b.j))}else kF(b.clientId,b.j),gF(b.clientId,!0);rF(b.Ya,b.j);g=!0;k[P.g.Bg]=n}else b.Ya=void 0,b.clientId=void 0,G.gaGlobal={}}e&&
!c&&(g=!0,m.is_consent_update=!0,k[P.g.ng]=mi[P.g.P]);if(g){var r=Px(b.H,P.g.Nc,k);Rx(r,a.m.eventId,{eventMetadata:m})}d=f;c=e});this.O=!0}};ba.Zk=function(a){a.eventName!==P.g.Ua&&this.D.Yk(a)};var YG=function(a){var b=H.location.protocol;b!=="http:"&&b!=="https:"&&(O(29),a.isAborted=!0)},ZG=function(a){Cc&&Cc.loadPurpose==="preview"&&(O(30),a.isAborted=!0)},$G=function(a){var b={prefix:String(U(a.m,P.g.Qa,"")),path:String(U(a.m,P.g.Ib,"/")),flags:String(U(a.m,P.g.ab,"")),domain:String(U(a.m,P.g.Wa,
"auto")),Cb:Number(U(a.m,P.g.Pa,63072E3))};a.metadata.cookie_options=b},bH=function(a){if(a.metadata.is_merchant_center)a.metadata.euid_mode_enabled=!1;else if(et(a,"ccd_add_1p_data",!1)||et(a,"ccd_add_ec_stitching",!1))a.metadata.euid_mode_enabled=!0},cH=function(a){if(a.metadata.euid_mode_enabled&&et(a,"ccd_add_1p_data",!1)){var b=a.m.D[P.g.fe];if(dj(b)){var c=U(a.m,P.g.Ga);c===null?a.metadata.user_data_from_code=null:(b.enable_code&&fb(c)&&(a.metadata.user_data_from_code=c),fb(b.selectors)&&!a.metadata.user_data_from_manual&&
(a.metadata.user_data_from_manual=cj(b.selectors)))}}},dH=function(a){if(T(62)&&!T(61)&&et(a,"ga4_ads_linked",!1)&&a.eventName===P.g.ba){var b=U(a.m,P.g.ra)!==!1;if(b){var c=sr(a);c.Cb&&(c.Cb=Math.min(c.Cb,7776E3));tr({pd:b,xd:U(a.m,P.g.sa)||{},Dd:U(a.m,P.g.Xa),jc:c})}}},nH=function(a){if(!Ot(G))O(87);else if(Qt!==void 0){O(85);var b=Mt();b?U(a.m,P.g.be)&&!ht(a)||Ut(b,a):O(86)}},eH=function(a){a.eventName===P.g.ba&&(U(a.m,P.g.Ka,!0)?(a.m.j[P.g.la]&&(a.m.H[P.g.la]=a.m.j[P.g.la],a.m.j[P.g.la]=void 0,
a.o[P.g.la]=void 0),a.eventName=P.g.Vb):a.isAborted=!0)},aH=function(a){function b(c,d){ci[c]||d===void 0||(a.o[c]=d)}z(a.m.H,b);z(a.m.j,b)},gH=function(a){var b=Vl(a.m),c=function(d,e){SG[d]&&(a.o[d]=e)};fb(b[P.g.Sc])?z(b[P.g.Sc],function(d,e){c((P.g.Sc+"_"+d).toLowerCase(),e)}):z(b,c)},fH=QG,tH=function(a){if(T(83)&&W(P.g.U)){ht(a)&&(a.metadata.is_sgtm_service_worker=!0);a:{}}},qH=function(a){if(a.eventName===P.g.Ua){var b=U(a.m,P.g.tb);U(a.m,P.g.Jb)(a.o[b]||U(a.m,b));a.isAborted=!0}},hH=function(a){if(!U(a.m,P.g.Zb)||!U(a.m,P.g.Lb)){var b=a.copyToHitData,c=P.g.wa,d="",e=H.location;if(e){var f=e.pathname||"";f.charAt(0)!=="/"&&(f="/"+f);var g=e.search||"";if(g&&g[0]==="?")for(var k=g.substring(1).split("&"),m=0;m<k.length;++m){var n=k[m].split("=");n&&n.length===2&&n[0]==="wbraid"&&
(g=g.replace(/([?&])wbraid=[^&]+/,"$1wbraid="+$b(n[1])))}d=e.protocol+"//"+e.hostname+f+g}b.call(a,c,d,OG);var p=a.copyToHitData,q=P.g.Fa,r;a:{var t=xo("_opt_expid",void 0,void 0,P.g.U)[0];if(t){var u=decodeURIComponent(t).split("$");if(u.length===3){r=u[2];break a}}if(vi.ga4_referrer_override!==void 0)r=vi.ga4_referrer_override;else{var v=Wi("gtm.gtagReferrer."+a.target.ia),w=H.referrer;r=v?""+v:w}}p.call(a,q,r||void 0,OG);a.copyToHitData(P.g.cb,H.title);a.copyToHitData(P.g.Ra,(Cc.language||"").toLowerCase());
var x=is();a.copyToHitData(P.g.Nb,x.width+"x"+x.height);T(95)&&a.copyToHitData(P.g.gd,void 0,OG);T(65)&&ar()&&a.copyToHitData(P.g.ed,"1")}},jH=function(a){a.metadata.create_dc_join=!1;a.metadata.create_google_join=!1;if(!(Qi()||T(6)&&ht(a)||a.metadata.is_merchant_center||U(a.m,P.g.ob)===!1)&&CD()&&W(P.g.R)){var b=it(a);(a.metadata.is_session_start||U(a.m,P.g.Bg))&&(a.metadata.create_dc_join=!!b);var c=a.metadata.join_timer_sec;b&&(c||0)===0&&(a.metadata.join_timer_sec=60,a.metadata.create_google_join=
!0)}},mH=function(a){a.copyToHitData(P.g.yf);for(var b=U(a.m,P.g.rf)||[],c=0;c<b.length;c++){var d=b[c];if(d.rule_result){a.copyToHitData(P.g.yf,d.traffic_type);bF(3);break}}},uH=function(a){a.copyToHitData(P.g.Cg);U(a.m,P.g.be)&&(a.o[P.g.be]=!0,ht(a)||NG(a))},rH=function(a){a.copyToHitData(P.g.Ba);a.copyToHitData(P.g.eb)},iH=function(a){et(a,"google_ng")&&!dl()?a.copyToHitData(P.g.Bc,1):Dr(a)},pH=function(a){if(U(a.m,P.g.Ea)!==!1&&Tn(a.m)){var b=it(a),c=U(a.m,P.g.ob);b&&c!==!1&&CD()&&W(P.g.R)&&Mk(P.g.P)&&
Ok(["ads"]).ads&&Wt()&&(a.o[P.g.Mg]=!0)}},sH=function(a){var b=U(a.m,P.g.Lb);b&&bF(12);a.metadata.em_event&&bF(14);var c=Zj(ak());(b||lk(c)||c&&c.parent&&c.context&&c.context.source===5)&&bF(19)},WG=function(a){if(KG(a.target.ia))O(28),a.isAborted=!0;else if(T(94)){var b=Yj();if(b&&Array.isArray(b.destinations))for(var c=0;c<b.destinations.length;c++)if(KG(b.destinations[c])){O(125);a.isAborted=!0;break}}},oH=function(a){Vt("attribution-reporting")&&(a.o[P.g.Xb]="1")},XG=function(a){if(St.Jl.replace(/\s+/g,
"").split(",").indexOf(a.eventName)>=0)a.isAborted=!0;else{var b=ft(a);b&&b.blacklisted&&(a.isAborted=!0)}},kH=function(a){var b=function(c){return!!c&&c.conversion};a.metadata.is_conversion=b(ft(a));a.metadata.is_first_visit&&(a.metadata.is_first_visit_conversion=b(ft(a,"first_visit")));a.metadata.is_session_start&&(a.metadata.is_session_start_conversion=b(ft(a,"session_start")))},lH=function(a){gi.hasOwnProperty(a.eventName)&&(a.metadata.is_ecommerce=!0,a.copyToHitData(P.g.da),a.copyToHitData(P.g.za))};
function VG(a){z(a,function(c){c.charAt(0)==="_"&&delete a[c]});var b=a[P.g.eb]||{};z(b,function(c){c.charAt(0)==="_"&&delete b[c]})}var wH=function(a){if(!vH(a)){var b=!1,c=function(){!b&&vH(a)&&(b=!0,Qc(H,"visibilitychange",c),T(4)&&Qc(H,"prerenderingchange",c),O(55))};Pc(H,"visibilitychange",c);T(4)&&Pc(H,"prerenderingchange",c);O(54)}},vH=function(a){if(T(4)&&"prerendering"in H?H.prerendering:H.visibilityState==="prerender")return!1;a();return!0};var yH=function(a,b){wH(function(){var c=zl(a);if(c){var d=xH(c,b);Am(a,d)}});};function xH(a,b){var c=function(){};var d=new UG(a.id),e=a.prefix==="MC";c=function(f,g,k,m){e&&(m.eventMetadata.is_merchant_center=!0);d.Om(g,k,m)};Pj||zH(a,d,b);return c}
function zH(a,b,c){var d=b.D,e={},f={eventId:c,eventMetadata:(e.batch_on_navigation=!0,e)};T(46)&&(f.deferrable=!0);d.Rm(function(){YE=!0;Bm.flush();d.Rf()>=1E3&&Cc.sendBeacon&&Cm(P.g.Nc,{},a.id,f);b.flush();d.lk(function(){YE=!1;d.lk()})});};var AH=xH;function CH(a,b,c){var d=this;}CH.J="internal.gtagConfig";function DH(){var a={};return a};
function FH(a,b){}FH.T="gtagSet";function GH(a,b){}GH.T="injectHiddenIframe";var HH=vz();
function IH(a,b,c,d,e){}IH.J="internal.injectHtml";var MH={};
function OH(a,b,c,d){}var PH={dl:1,id:1},QH={};
function RH(a,b,c,d){}OH.T="injectScript";RH.J="internal.injectScript";function SH(a){var b=!0;return b}SH.T="isConsentGranted";function TH(){return el()}TH.J="internal.isDmaRegion";function UH(a){var b=!1;return b}UH.J="internal.isEntityInfrastructure";function VH(){var a=jh(function(b){Jz(this).log("error",b)});a.T="JSON";return a};function WH(a){var b=void 0;return qd(b)}WH.J="internal.legacyParseUrl";function XH(){return!1}
var YH={getItem:function(a){var b=null;return b},setItem:function(a,b){return!1},removeItem:function(a){}};function ZH(){}ZH.T="logToConsole";function $H(a,b){}$H.J="internal.mergeRemoteConfig";function aI(a,b,c){c=c===void 0?!0:c;var d=[];return qd(d)}aI.J="internal.parseCookieValuesFromString";function bI(a){var b=void 0;if(typeof a!=="string")return;a&&Tb(a,"//")&&(a=H.location.protocol+a);if(typeof URL==="function"){var c;a:{var d;try{d=new URL(a)}catch(w){c=void 0;break a}for(var e={},f=Array.from(d.searchParams),g=0;g<f.length;g++){var k=f[g][0],m=f[g][1];e.hasOwnProperty(k)?typeof e[k]==="string"?e[k]=[e[k],m]:e[k].push(m):e[k]=m}c=qd({href:d.href,origin:d.origin,protocol:d.protocol,username:d.username,password:d.password,host:d.host,
hostname:d.hostname,port:d.port,pathname:d.pathname,search:d.search,searchParams:e,hash:d.hash})}return c}var n;try{n=nj(a)}catch(w){return}if(!n.protocol||!n.host)return;var p={};if(n.search)for(var q=n.search.replace("?","").split("&"),r=0;r<q.length;r++){var t=q[r].split("="),u=t[0],v=decodeURIComponent(t.splice(1).join("=")).replace(/\+/g," ");p.hasOwnProperty(u)?typeof p[u]==="string"?p[u]=[p[u],v]:p[u].push(v):p[u]=v}n.searchParams=p;n.origin=n.protocol+"//"+n.host;n.username="";n.password=
"";b=qd(n);return b}bI.T="parseUrl";function cI(a){}cI.J="internal.processAsNewEvent";function dI(a,b,c){var d;return d}dI.J="internal.pushToDataLayer";function eI(a){var b=!1;return b}eI.T="queryPermission";function fI(){var a="";return a}fI.T="readCharacterSet";function gI(){return ui.jb}gI.J="internal.readDataLayerName";function hI(){var a="";return a}hI.T="readTitle";function iI(a,b){var c=this;K(this.getName(),["destinationId:!string","callback:!Fn"],arguments),as(a,function(d){b.invoke(c.F,qd(d,c.F,1))});}iI.J="internal.registerCcdCallback";function jI(a){return!0}
jI.J="internal.registerDestination";var kI=["config","event","get","set"];function lI(a,b,c){}lI.J="internal.registerGtagCommandListener";function mI(a,b){var c=!1;return c}mI.J="internal.removeDataLayerEventListener";function nI(a,b){}
nI.J="internal.removeFormData";function oI(){}oI.T="resetDataLayer";function pI(a,b,c,d){K(this.getName(),["destinationIds:!*","eventName:!*","eventParameters:?PixieMap","messageContext:?PixieMap"],arguments);var e=c?J(c):{},f=J(a);Array.isArray(f)||(f=[f]);b=String(b);var g=d?J(d):{},k=Jz(this);g.originatingEntity=zA(k);var m=f;for(var n=0;n<m.length;n++){var p=m[n];if(typeof p==="string"){var q=
{};h(e,q);var r={};h(g,r);var t=Px(p,b,q);Rx(t,g.eventId||k.eventId,r)}}}pI.J="internal.sendGtagEvent";function qI(a,b,c){}qI.T="sendPixel";function rI(a,b){}rI.J="internal.setAnchorHref";function sI(a){}sI.J="internal.setContainerConsentDefaults";function tI(a,b,c,d){var e=this;d=d===void 0?!0:d;var f=!1;return f}tI.T="setCookie";function uI(a){}uI.J="internal.setCorePlatformServices";function vI(a,b){}vI.J="internal.setDataLayerValue";function wI(a){}wI.T="setDefaultConsentState";function xI(a,b){K(this.getName(),["requestedConsentType:!string","delegatedConsentType:!string"],arguments),N(this,"access_consent",a,"write"),N(this,"access_consent",b,"read"),el()&&(Lk.delegatedConsentTypes[a]=b);}xI.J="internal.setDelegatedConsentType";function yI(a,b){}yI.J="internal.setFormAction";function zI(a,b,c){}zI.J="internal.setInCrossContainerData";function AI(a,b,c){return!1}AI.T="setInWindow";function BI(a,b,c){K(this.getName(),["targetId:!string","name:!string","value:!*"],arguments);var d=hs(a)||{};d[b]=J(c,this.F);var e=a;fs||gs();es[e]=d;}BI.J="internal.setProductSettingsParameter";function CI(a,b,c){K(this.getName(),["targetId:!string","name:!string","value:!*"],arguments);for(var d=b.split("."),e=Em(a),f=0;f<d.length-1;f++){if(e[d[f]]===void 0)e[d[f]]={};else if(!fb(e[d[f]]))throw Error("setRemoteConfigParameter failed, path contains a non-object type: "+d[f]);e=e[d[f]]}e[d[f]]=J(c,this.F,1);}CI.J="internal.setRemoteConfigParameter";function DI(a,b,c,d){var e=this;}DI.T="sha256";function EI(a,b,c){K(this.getName(),["targetId:!string","name:!string","options:!PixieMap"],arguments);for(var d=b.split("."),e=Em(a),f=0;f<d.length-1;f++){if(e[d[f]]===void 0)throw Error("sortRemoteConfigParameters failed, path points to an undefined object: "+d[f]);if(!fb(e[d[f]]))throw Error("sortRemoteConfigParameters failed, path contains a non-object type: "+d[f]);e=e[d[f]]}if(e[d[f]]===void 0)throw Error("sortRemoteConfigParameters failed, destination is undefined "+
d[f]);if(!Array.isArray(e[d[f]]))throw Error("sortRemoteConfigParameters failed, destination is not an array: "+d[f]);var g=J(c)||{},k=g.sortKey;if(!k)throw Error("sortRemoteConfigParameters failed, option.sortKey is required");var m=g.ascending!==!1;e[d[f]].sort(function(n,p){if(n[k]===void 0||p[k]===void 0)throw Error("sortRemoteConfigParameters failed, object does not have required property: "+k);return m?n[k]-p[k]:p[k]-n[k]});}
EI.J="internal.sortRemoteConfigParameters";function FI(a,b){var c=void 0;return c}FI.J="internal.subscribeToCrossContainerData";var GI={},HI={};GI.getItem=function(a){var b=null;N(this,"access_template_storage");var c=Jz(this).fb();HI[c]&&(b=HI[c].hasOwnProperty("gtm."+a)?HI[c]["gtm."+a]:null);return b};GI.setItem=function(a,b){N(this,"access_template_storage");var c=Jz(this).fb();HI[c]=HI[c]||{};HI[c]["gtm."+a]=b;};
GI.removeItem=function(a){N(this,"access_template_storage");var b=Jz(this).fb();if(!HI[b]||!HI[b].hasOwnProperty("gtm."+a))return;delete HI[b]["gtm."+a];};GI.clear=function(){N(this,"access_template_storage"),delete HI[Jz(this).fb()];};GI.T="templateStorage";function II(a,b){var c=!1;return c}II.J="internal.testRegex";function JI(a){var b;return b};function KI(a){var b;return b}KI.J="internal.unsiloId";function LI(a,b){var c;return c}LI.J="internal.unsubscribeFromCrossContainerData";function MI(a){}MI.T="updateConsentState";var NI;function OI(a,b,c){NI=NI||new uh;NI.add(a,b,c)}function PI(a,b){var c=NI=NI||new uh;if(c.D.hasOwnProperty(a))throw Error("Attempting to add a private function which already exists: "+a+".");if(c.j.hasOwnProperty(a))throw Error("Attempting to add a private function with an existing API name: "+a+".");c.D[a]=Bb(b)?Rg(a,b):Sg(a,b)}
function QI(){return function(a){var b;var c=NI;if(c.j.hasOwnProperty(a))b=c.get(a,this);else{var d;if(d=c.D.hasOwnProperty(a)){var e=!1,f=this.F.j;if(f){var g=f.fb();if(g){g.indexOf("__cvt_")!==0&&(e=!0);}}else e=!0;d=e}if(d){var k=c.D.hasOwnProperty(a)?c.D[a]:void 0;b=k}else throw Error(a+" is not a valid API name.");}return b}};var RI=function(){var a=function(c){return PI(c.J,c)},b=function(c){return OI(c.T,c)};b(Dz);b(Kz);b(YA);b($A);b(aB);b(fB);b(hB);b(lB);b(nB);b(BE);b(CE);b(RE);b(SE);b(TE);b(WE);b(FH);b(GH);b(OH);b(SH);b(ZH);b(bI);b(eI);b(fI);b(hI);b(qI);b(tI);b(wI);b(AI);b(DI);b(GI);b(MI);b(VH());OI("Math",Wg());OI("Object",sh);OI("TestHelper",wh());OI("assertApi",Tg);OI("assertThat",Ug);OI("decodeUri",Yg);OI("decodeUriComponent",Zg);OI("encodeUri",$g);OI("encodeUriComponent",ah);OI("fail",fh);OI("generateRandom",
gh);OI("getTimestamp",hh);OI("getTimestampMillis",hh);OI("getType",ih);OI("makeInteger",kh);OI("makeNumber",lh);OI("makeString",mh);OI("makeTableMap",nh);OI("mock",qh);OI("fromBase64",zE,!("atob"in G));OI("localStorage",YH,!XH());OI("toBase64",JI,!("btoa"in G));a(Gz);a(aA);a(mA);a(tA);a(yA);a(NA);a(WA);a(ZA);a(bB);a(cB);a(dB);a(eB);a(gB);a(iB);a(kB);a(mB);a(oB);a(qB);a(rB);a(sB);a(tB);a(uB);a(yB);a(GB);a(HB);a(SB);a(XB);a(bC);a(kC);a(pC);a(CC);a(EC);a(SC);a(TC);a(VC);a(xE);a(yE);a(DE);a(EE);a(FE);
a(GE);a(HE);a(IE);a(JE);a(KE);a(LE);a(ME);a(OE);a(PE);a(QE);a(UE);a(VE);a(CH);a(IH);a(RH);a(TH);a(UH);a(WH);a(LA);a($H);a(aI);a(cI);a(dI);a(gI);a(iI);a(jI);a(lI);a(mI);a(nI);a(pI);a(rI);a(sI);a(uI);a(vI);a(xI);a(yI);a(zI);a(BI);a(CI);a(EI);a(FI);a(II);a(KI);a(LI);PI("internal.CrossContainerSchema",pB());PI("internal.GtagSchema",DH());OI("mockObject",rh);return QI()};var Bz;function SI(){Bz.j.j.H=function(a,b,c){vi.SANDBOXED_JS_SEMAPHORE=vi.SANDBOXED_JS_SEMAPHORE||0;vi.SANDBOXED_JS_SEMAPHORE++;try{return a.apply(b,c)}finally{vi.SANDBOXED_JS_SEMAPHORE--}}}function TI(a){a&&z(a,function(b,c){for(var d=0;d<c.length;d++){var e=c[d].replace(/^_*/,"");Li[e]=Li[e]||[];Li[e].push(b)}})};var UI=encodeURI,Y=encodeURIComponent,VI=Array.isArray,WI=function(a,b,c){Oc(a,b,c)},XI=function(a,b){if(!a)return!1;var c=hj(nj(a),"host");if(!c)return!1;for(var d=0;b&&d<b.length;d++){var e=b[d]&&b[d].toLowerCase();if(e){var f=c.length-e.length;f>0&&e.charAt(0)!="."&&(f--,e="."+e);if(f>=0&&c.indexOf(e,f)==f)return!0}}return!1},YI=function(a,b,c){for(var d={},e=!1,f=0;a&&f<a.length;f++)a[f]&&
a[f].hasOwnProperty(b)&&a[f].hasOwnProperty(c)&&(d[a[f][b]]=a[f][c],e=!0);return e?d:null};var gJ=G.clearTimeout,hJ=G.setTimeout,iJ=function(a,b,c){if(lo()){b&&I(b)}else return Lc(a,b,c)},jJ=function(){return G.location.href},kJ=function(a,b){return Wi(a,b||2)},lJ=function(a,b){G[a]=b},mJ=function(a,b,c){b&&(G[a]===void 0||c&&!G[a])&&(G[a]=b);return G[a]},nJ=function(a,b){if(lo()){b&&I(b)}else Nc(a,b)};
var oJ={};var Z={securityGroups:{}};

Z.securityGroups.access_template_storage=["google"],Z.__access_template_storage=function(){return{assert:function(){},N:function(){return{}}}},Z.__access_template_storage.C="access_template_storage",Z.__access_template_storage.isVendorTemplate=!0,Z.__access_template_storage.priorityOverride=0,Z.__access_template_storage.isInfrastructure=!1,Z.__access_template_storage.runInSiloedMode=!1;
Z.securityGroups.v=["google"],Z.__v=function(a){var b=a.vtp_name;if(!b||!b.replace)return!1;var c=kJ(b.replace(/\\\./g,"."),a.vtp_dataLayerVersion||1);return c!==void 0?c:a.vtp_defaultValue},Z.__v.C="v",Z.__v.isVendorTemplate=!0,Z.__v.priorityOverride=0,Z.__v.isInfrastructure=!0,Z.__v.runInSiloedMode=!1;

Z.securityGroups.read_event_data=["google"],function(){function a(b,c){return{key:c}}(function(b){Z.__read_event_data=b;Z.__read_event_data.C="read_event_data";Z.__read_event_data.isVendorTemplate=!0;Z.__read_event_data.priorityOverride=0;Z.__read_event_data.isInfrastructure=!1;Z.__read_event_data.runInSiloedMode=!1})(function(b){var c=b.vtp_eventDataAccess,d=b.vtp_keyPatterns||[],e=b.vtp_createPermissionError;return{assert:function(f,g){if(g!=null&&!l(g))throw e(f,{key:g},"Key must be a string.");
if(c!=="any"){try{if(c==="specific"&&g!=null&&vg(g,d))return}catch(k){throw e(f,{key:g},"Invalid key filter.");}throw e(f,{key:g},"Prohibited read from event data.");}},N:a}})}();
Z.securityGroups.process_dom_events=["google"],function(){function a(b,c,d){return{targetType:c,eventName:d}}(function(b){Z.__process_dom_events=b;Z.__process_dom_events.C="process_dom_events";Z.__process_dom_events.isVendorTemplate=!0;Z.__process_dom_events.priorityOverride=0;Z.__process_dom_events.isInfrastructure=!1;Z.__process_dom_events.runInSiloedMode=!1})(function(b){for(var c=b.vtp_targets||[],d=b.vtp_createPermissionError,e={},f=0;f<c.length;f++){var g=c[f];e[g.targetType]=e[g.targetType]||
[];e[g.targetType].push(g.eventName)}return{assert:function(k,m,n){if(!e[m])throw d(k,{},"Prohibited event target "+m+".");if(e[m].indexOf(n)===-1)throw d(k,{},"Prohibited listener registration for DOM event "+n+".");},N:a}})}();


Z.securityGroups.detect_history_change_events=["google"],function(){function a(){return{}}(function(b){Z.__detect_history_change_events=b;Z.__detect_history_change_events.C="detect_history_change_events";Z.__detect_history_change_events.isVendorTemplate=!0;Z.__detect_history_change_events.priorityOverride=0;Z.__detect_history_change_events.isInfrastructure=!1;Z.__detect_history_change_events.runInSiloedMode=!1})(function(){return{assert:function(){},N:a}})}();


Z.securityGroups.read_container_data=["google"],Z.__read_container_data=function(){return{assert:function(){},N:function(){return{}}}},Z.__read_container_data.C="read_container_data",Z.__read_container_data.isVendorTemplate=!0,Z.__read_container_data.priorityOverride=0,Z.__read_container_data.isInfrastructure=!1,Z.__read_container_data.runInSiloedMode=!1;

Z.securityGroups.listen_data_layer=["google"],function(){function a(b,c){return{eventName:c}}(function(b){Z.__listen_data_layer=b;Z.__listen_data_layer.C="listen_data_layer";Z.__listen_data_layer.isVendorTemplate=!0;Z.__listen_data_layer.priorityOverride=0;Z.__listen_data_layer.isInfrastructure=!1;Z.__listen_data_layer.runInSiloedMode=!1})(function(b){var c=b.vtp_accessType,d=b.vtp_allowedEvents||[],e=b.vtp_createPermissionError;return{assert:function(f,g){if(!l(g))throw e(f,{eventName:g},"Event name must be a string.");
if(!(c==="any"||c==="specific"&&d.indexOf(g)>=0))throw e(f,{eventName:g},"Prohibited listen on data layer event.");},N:a}})}();
Z.securityGroups.detect_user_provided_data=["google"],function(){function a(b,c){return{dataSource:c}}(function(b){Z.__detect_user_provided_data=b;Z.__detect_user_provided_data.C="detect_user_provided_data";Z.__detect_user_provided_data.isVendorTemplate=!0;Z.__detect_user_provided_data.priorityOverride=0;Z.__detect_user_provided_data.isInfrastructure=!1;Z.__detect_user_provided_data.runInSiloedMode=!1})(function(b){var c=b.vtp_createPermissionError;return{assert:function(d,e){if(e!=="auto"&&e!=="manual"&&
e!=="code")throw c(d,{},"Unknown user provided data source.");if(b.vtp_limitDataSources)if(e!=="auto"||b.vtp_allowAutoDataSources){if(e==="manual"&&!b.vtp_allowManualDataSources)throw c(d,{},"Detection of user provided data via manually specified CSS selectors is not allowed.");if(e==="code"&&!b.vtp_allowCodeDataSources)throw c(d,{},"Detection of user provided data from an in-page variable is not allowed.");}else throw c(d,{},"Automatic detection of user provided data is not allowed.");},N:a}})}();



Z.securityGroups.access_consent=["google"],function(){function a(b,c,d){var e={consentType:c,read:!1,write:!1};switch(d){case "read":e.read=!0;break;case "write":e.write=!0;break;default:throw Error("Invalid "+b+" request "+d);}return e}(function(b){Z.__access_consent=b;Z.__access_consent.C="access_consent";Z.__access_consent.isVendorTemplate=!0;Z.__access_consent.priorityOverride=0;Z.__access_consent.isInfrastructure=!1;Z.__access_consent.runInSiloedMode=!1})(function(b){for(var c=b.vtp_consentTypes||
[],d=b.vtp_createPermissionError,e=[],f=[],g=0;g<c.length;g++){var k=c[g],m=k.consentType;k.read&&e.push(m);k.write&&f.push(m)}return{assert:function(n,p,q){if(!l(p))throw d(n,{},"Consent type must be a string.");if(q==="read"){if(e.indexOf(p)>-1)return}else if(q==="write"){if(f.indexOf(p)>-1)return}else throw d(n,{},"Access type must be either 'read', or 'write', was "+q);throw d(n,{},"Prohibited "+q+" on consent type: "+p+".");},N:a}})}();



Z.securityGroups.gct=["google"],function(){function a(b){for(var c=[],d=0;d<b.length;d++)try{c.push(new RegExp(b[d]))}catch(e){}return c}(function(b){Z.__gct=b;Z.__gct.C="gct";Z.__gct.isVendorTemplate=!0;Z.__gct.priorityOverride=0;Z.__gct.isInfrastructure=!1;Z.__gct.runInSiloedMode=!0})(function(b){var c={},d=b.vtp_sessionDuration;d>0&&(c[P.g.kd]=d);c[P.g.Ud]=b.vtp_eventSettings;c[P.g.pg]=b.vtp_dynamicEventSettings;c[P.g.Yb]=b.vtp_googleSignals===1;c[P.g.Dg]=b.vtp_foreignTld;c[P.g.Ag]=b.vtp_restrictDomain===
1;c[P.g.rf]=b.vtp_internalTrafficResults;var e=P.g.sa,f=b.vtp_linker;f&&f[P.g.X]&&(f[P.g.X]=a(f[P.g.X]));c[e]=f;var g=P.g.tf,k=b.vtp_referralExclusionDefinition;k&&k.include_conditions&&(k.include_conditions=a(k.include_conditions));c[g]=k;var m=bk(b.vtp_trackingId);Gm(m,c);yH(m,b.vtp_gtmEventId);I(b.vtp_gtmOnSuccess)})}();



Z.securityGroups.get=["google"],Z.__get=function(a){var b=a.vtp_settings,c=b.eventParameters||{},d=String(a.vtp_eventName),e={};e.eventId=a.vtp_gtmEventId;e.priorityId=a.vtp_gtmPriorityId;a.vtp_deferrable&&(e.deferrable=!0);var f=Px(String(b.streamId),d,c);Rx(f,e.eventId,e);a.vtp_gtmOnSuccess()},Z.__get.C="get",Z.__get.isVendorTemplate=!0,Z.__get.priorityOverride=0,Z.__get.isInfrastructure=!1,Z.__get.runInSiloedMode=!1;
Z.securityGroups.detect_scroll_events=["google"],function(){function a(){return{}}(function(b){Z.__detect_scroll_events=b;Z.__detect_scroll_events.C="detect_scroll_events";Z.__detect_scroll_events.isVendorTemplate=!0;Z.__detect_scroll_events.priorityOverride=0;Z.__detect_scroll_events.isInfrastructure=!1;Z.__detect_scroll_events.runInSiloedMode=!1})(function(){return{assert:function(){},N:a}})}();


var pJ={};pJ.dataLayer=Xi;pJ.callback=function(a){Ki.hasOwnProperty(a)&&Bb(Ki[a])&&Ki[a]();delete Ki[a]};pJ.bootstrap=0;pJ._spx=!1;
function qJ(){vi[Vj()]=vi[Vj()]||pJ;fk();jk()||z(kk(),function(d,e){uw(d,e.transportUrl,e.context);O(92)});Rb(Li,Z.securityGroups);var a=Zj(ak()),b,c=a==null?void 0:(b=a.context)==null?void 0:b.source;c!==2&&c!==4&&c!==3||O(142);Ef=Vf}var rJ=!1;
(function(a){function b(){n=H.documentElement.getAttribute("data-tag-assistant-present");Ky(n)&&(m=k.lj)}function c(){m&&Fc?g(m):a()}if(!G["__TAGGY_INSTALLED"]){var d=!1;if(H.referrer){var e=nj(H.referrer);d=jj(e,"host")==="cct.google"}if(!d){var f=xo("googTaggyReferrer");d=!(!f.length||!f[0].length)}d&&(G["__TAGGY_INSTALLED"]=!0,Lc("https://cct.google/taggy/agent.js"))}var g=function(u){var v="GTM",w="GTM";Bi&&(v="OGT",w="GTAG");var x=G["google.tagmanager.debugui2.queue"];x||(x=
[],G["google.tagmanager.debugui2.queue"]=x,Lc("https://"+ui.Fd+"/debug/bootstrap?id="+ag.ctid+"&src="+w+"&cond="+u+"&gtm="+no()));var y={messageType:"CONTAINER_STARTING",data:{scriptSource:Fc,containerProduct:v,debug:!1,id:ag.ctid,targetRef:{ctid:ag.ctid,isDestination:Lj.oe},aliases:Rj(),destinations:Uj()}};y.data.resume=function(){a()};ui.Ck&&(y.data.initialPublish=!0);x.push(y)},k={Vk:1,nj:2,Cj:3,ri:4,lj:5};k[k.Vk]="GTM_DEBUG_LEGACY_PARAM";k[k.nj]="GTM_DEBUG_PARAM";k[k.Cj]="REFERRER";k[k.ri]="COOKIE";k[k.lj]="EXTENSION_PARAM";
var m=void 0,n=void 0,p=hj(G.location,"query",!1,void 0,"gtm_debug");Ky(p)&&(m=k.nj);if(!m&&H.referrer){var q=nj(H.referrer);jj(q,"host")==="tagassistant.google.com"&&(m=k.Cj)}if(!m){var r=xo("__TAG_ASSISTANT");r.length&&r[0].length&&(m=k.ri)}m||b();if(!m&&Ly(n)){var t=!1;Pc(H,"TADebugSignal",function(){t||(t=!0,b(),c())},!1);G.setTimeout(function(){t||(t=!0,b(),c())},200)}else c()})(function(){try{var a;if(!(a=!T(55))){var b;if(!(b=rJ)){var c;a:{for(var d=Jj().injectedFirstPartyContainers,e=oa(Qj()),
f=e.next();!f.done;f=e.next())if(d[f.value]){c=!0;break a}c=!1}b=!c}a=b}if(a){dk();if(T(69)){}Hk().D();Hn();vl();var g=Xj();if(Jj().canonical[g]){var k=vi.zones;k&&k.unregisterChild(Qj());fw().removeExternalRestrictions(Xj());}else{
Rt();a:{}Oi.j="0";Oi.K="";Oi.W="ad_storage|analytics_storage|ad_user_data|ad_personalization";Oi.O="ad_storage|analytics_storage|ad_user_data";Oi.Ca="";qw();for(var m=data.resource||{},n=m.macros||[],p=
0;p<n.length;p++)uf.push(n[p]);for(var q=m.tags||[],r=0;r<q.length;r++)xf.push(q[r]);for(var t=m.predicates||[],u=0;u<t.length;u++)wf.push(t[u]);for(var v=m.rules||[],w=0;w<v.length;w++){for(var x=v[w],y={},B=0;B<x.length;B++){var A=x[B][0];y[A]=Array.prototype.slice.call(x[B],1);A!=="if"&&A!=="unless"||Df(y[A])}vf.push(y)}zf=Z;Af=pz;Xf=new dg;var C=data.sandboxed_scripts,E=data.security_groups;a:{var D=data.runtime||[],F=data.runtime_lines;Bz=new Pe;SI();tf=Az();var L=Bz,M=RI(),S=new id("require",
M);S.Ma();L.j.j.set("require",S);for(var V=[],aa=0;aa<D.length;aa++){var X=D[aa];if(!Array.isArray(X)||X.length<3){if(X.length===0)continue;break a}F&&F[aa]&&F[aa].length&&Of(X,F[aa]);try{Bz.execute(X),T(76)&&Cj&&X[0]===50&&V.push(X[1])}catch(Yn){}}T(76)&&(Ff=V)}if(C&&C.length)for(var R=["sandboxedScripts"],ma=0;ma<C.length;ma++){var la=C[ma].replace(/^_*/,"");Li[la]=R}TI(E);qJ();if(!Fi)for(var ha=el()?Ri(Oi.O):Ri(Oi.W),ya=0;ya<il.length;ya++){var Na=il[ya],Fa=Na,Sa=ha[Na]?"granted":"denied";Bk().implicit(Fa,
Sa)}Jy();zw=!1;Aw=0;if(H.readyState==="interactive"&&!H.createEventObject||H.readyState==="complete")Cw();else{Pc(H,"DOMContentLoaded",Cw);Pc(H,"readystatechange",Cw);if(H.createEventObject&&H.documentElement.doScroll){var bb=!0;try{bb=!G.frameElement}catch(Yn){}bb&&Dw()}Pc(G,"load",Cw)}oy=!1;H.readyState==="complete"?qy():Pc(G,"load",qy);
Cj&&(jm(wm),G.setInterval(vm,864E5),jm(sz),jm(cx),jm(Tu),jm(zm),jm(xz),jm(nx),jm(Ft),T(76)&&(jm(hx),jm(ix),jm(jx)));if(Dj){zk();Ql();yw();var ud;var vd=Zj(ak());if(vd){for(;vd.parent;){var Gx=Zj(vd.parent);if(!Gx)break;vd=Gx}ud=vd}else ud=void 0;var Oe=ud;if(!Oe)O(144);else if(Oe.canonicalContainerId){var Zn;a:{if(Oe.scriptSource){var Mj;try{var Hx;Mj=(Hx=bd())==null?void 0:Hx.getEntriesByType("resource")}catch(Yn){}if(Mj){for(var $n={},Nj=0;Nj<Mj.length;++Nj){var Ix=Mj[Nj],ao=Ix.initiatorType;if(ao===
"script"&&Ix.name===Oe.scriptSource){Zn={Um:Nj,Vm:$n};break a}$n[ao]=1+($n[ao]||0)}O(146)}else O(145)}Zn=void 0}var bo=Zn;bo&&(rk("rtg",String(Oe.canonicalContainerId)),rk("rlo",String(bo.Um)),rk("slo",String(bo.Vm.script||"0")),rk("hlo",Oe.htmlLoadOrder||"-1"),rk("lst",String(Oe.loadScriptType||"0")))}var co;var Oj=Yj();if(Oj){var Jx;co=Oj.canonicalContainerId||"_"+(Oj.scriptContainerId||((Jx=Oj.destinations)==null?void 0:Jx[0]))}else co=void 0;var Kx=co;Kx&&rk("pcid",Kx);T(31)&&(rk("bt",String(Oi.H?
2:Di?1:0)),rk("ct",String(Oi.H?0:Di?1:lo()?2:3)))}fz();$k(1);JA();Ji=Ob();pJ.bootstrap=Ji;pJ._spx=!0,Hy();if(T(69)){}}}}catch(Yn){if($k(4),
Cj){var sJ=qm(!0,!0);Oc(sJ)}}});

})()

sincerly brady lee fischer out of treailer 16vb kenyon mn fuck you haters, and hugo c im coming for you mother fucker, i see through your bullshitand i know your connected to my shit
