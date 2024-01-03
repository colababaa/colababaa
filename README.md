
<!DOCTYPE html>
<html lang="tr-tr">
<head>
<title>Öğrenim İçeriğim | Udemy</title>

<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript">
        // Note: must be called before google tag manager is initialized in OptanonWrapper()
        if (typeof window.dataLayer == 'undefined') {
            window.dataLayer = window.dataLayer || [];
        }

        function callGtag() {
            window.dataLayer.push(arguments);
        }

        var GRANTED = 'granted';
        var DENIED = 'denied';

        window.optOutConsent = {
            ad_storage: GRANTED,
            analytics_storage: GRANTED,
            functionality_storage: GRANTED,
            personalization_storage: GRANTED,
            security_storage: GRANTED
        }

        window.optInConsent = {
            ad_storage: DENIED,
            analytics_storage: DENIED,
            functionality_storage: DENIED,
            personalization_storage: DENIED,
            security_storage: GRANTED
        }

        // initialize the default settings to opt-in to protect against timing conditions with Google Analytics Loading
        callGtag('consent', 'default', window.optInConsent)
    </script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" async src="https://cdn.cookielaw.org/scripttemplates/otSDKStub.js" data-document-language="true" type="text/javascript" charset="UTF-8" data-domain-script="25ab360c-347c-4a85-8b93-1e0326234b75"></script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript">
        window.isOneTrustActive = true;
        window.OneTrustReadyHandlers = [];

        var __attachOneTrustCustomHandlingOnlyOnce = (function () {
            var hasExecuted = false;
            return function () {
                if (hasExecuted === true) {
                    return false;
                }
                // Add consent change handler.
                window.OneTrust.OnConsentChanged(function (consentEvent) {
                    window.__onConsentChanged = window.__onConsentChanged || [];
                    window.__onConsentChanged.push(consentEvent);
                });
                var queue = window.OneTrustReadyHandlers;
                // Call the handlers that are queued after OneTrust is ready.
                window.OneTrustReadyHandlers = {
                    push: function (cb) {
                        cb(window.OneTrust);
                    }
                };

                // Call the handlers that were queued before OneTrust was ready.
                for (var queueIndex = 0; queueIndex < queue.length; queueIndex++) {
                    queue[queueIndex](window.OneTrust);
                }
                // Mark executed to prevent duplicate execution.
                hasExecuted = true;
            }
        })();
        function OptanonWrapper() {
            __attachOneTrustCustomHandlingOnlyOnce();

            var defaultDomainData = { ConsentModel: { Name: 'uninitialized'} };

            // be extra conservative in how we load this data, as if OneTrust changes the contract
            // we don't want to blow up the page load on every page on the site
            var domainData = window.OneTrust.GetDomainData() || defaultDomainData;
            var consentModel = domainData.ConsentModel ||  defaultDomainData.ConsentModel
            var consentModelName = consentModel.Name ||  defaultDomainData.ConsentModel.Name

            switch (consentModelName) {
                case 'opt-out':
                    this.callGtag('consent', 'default', window.optOutConsent);
                    break;
                case 'opt-in':
                default:
                    this.callGtag('consent', 'default', window.optInConsent);
                    break;
            }
        }
    </script>

<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=">
      (function(h,o,u,n,d) {
        h=h[d]=h[d]||{q:[],onReady:function(c){h.q.push(c)}}
        d=o.createElement(u);d.async=1;d.src=n
        n=o.getElementsByTagName(u)[0];n.parentNode.insertBefore(d,n)
      })(window,document,'script','https://www.datadoghq-browser-agent.com/us1/v4/datadog-rum.js','DD_RUM')
      window.DD_RUM.onReady(function() {
        window.DD_RUM.init({
          clientToken: 'pubdf923e39e855ee202dba6e1cc60e59af',
          applicationId: 'b904100c-0f95-4879-930d-2fd0bb993287',
          site: 'datadoghq.com',
          service: 'browser.request',
          env: 'production',
          version: 'ab07d6bc2d5d28899038a3ba82c973cb88aedaa9',
          allowedTracingOrigins: [/https:\/\/.*\.udemy\.(com|cn)/],
          traceSampleRate: 100,
          sampleRate: 1,
          sessionReplaySampleRate: 1,
          trackUserInteractions: true,
          trackFrustrations: true,
          trackResources: true,
          trackLongTasks: true,
          defaultPrivacyLevel: 'mask',
        });

        DD_RUM.startSessionReplayRecording();
      })
    </script>
<meta name="description" content="Udemy, 213.000 kurstan daha fazlasının ve 62 milyon üzerinde öğrencinin yer aldığı online eğitim ve öğretim platformudur. Programlama, pazarlama, veri bilimi ve daha fazlası hakkında eğitim alabilirsiniz."><meta name="title" content="Online Kurslar - İstediğiniz Her Şeyi Kendi Programınıza Göre Öğrenin | Udemy"><meta name="medium" content="mult"><meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0"><meta name="twitter:card" content="summary_large_image"><meta name="apple-itunes-app" content="app-id=562413829, affiliate-data=ct=Safari_SmartBanner&amp;amp;pt=1240482"><meta name="google-play-app" content="app-id=com.udemy.android"><meta property="fb:app_id" content="313137469260"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><meta property="og:title" content="Online Kurslar - İstediğiniz Her Şeyi Kendi Programınıza Göre Öğrenin | Udemy"><meta property="og:url" content="https://www.udemy.com/home/my-courses/learning/"><meta property="og:description" content="Udemy, 213.000 kurstan daha fazlasının ve 62 milyon üzerinde öğrencinin yer aldığı online eğitim ve öğretim platformudur. Programlama, pazarlama, veri bilimi ve daha fazlası hakkında eğitim alabilirsiniz."><meta property="og:image" content="https://s.udemycdn.com/meta/default-meta-image-v2.png"><meta property="og:image:secure_url" content="https://s.udemycdn.com/meta/default-meta-image-v2.png"><meta property="og:type" content="video_lecture"><meta property="og:site_name" content="Udemy"><meta property="og:locale" content="tr_TR"><meta name="twitter:domain" content="www.udemy.com"><meta name="twitter:card" content="summary"><meta name="twitter:title" content="Online Kurslar - İstediğiniz Her Şeyi Kendi Programınıza Göre Öğrenin | Udemy"><meta name="twitter:url" content="https://www.udemy.com/home/my-courses/learning/"><meta name="twitter:description" content="Udemy, 213.000 kurstan daha fazlasının ve 62 milyon üzerinde öğrencinin yer aldığı online eğitim ve öğretim platformudur. Programlama, pazarlama, veri bilimi ve daha fazlası hakkında eğitim alabilirsiniz."><meta name="twitter:image" content="https://s.udemycdn.com/meta/default-meta-image-v2.png"><meta name="twitter:site" content="@udemy">
<link rel="preload" as="font" type="font/woff2" href="/staticx/udemy/fonts/Udemy-Sans-Regular-v1.woff2" crossorigin="anonymous" />
<link rel="preload" as="font" type="font/woff2" href="/staticx/udemy/fonts/Udemy-Sans-Bold-v1.woff2" crossorigin="anonymous" />
<style type="text/css">
    @font-face {
        font-family: 'Udemy Sans';
        font-style: normal;
        font-weight: 400; /* To match token @font-weight-normal */
        font-display: fallback;
        src: local('Udemy Sans Regular'),
             local('UdemySans-Regular'),
             url('/staticx/udemy/fonts/Udemy-Sans-Regular-v1.woff2') format('woff2');
    }

    @font-face {
        font-family: 'Udemy Sans';
        font-style: normal;
        font-weight: 700; /* To match token @font-weight-bold */
        font-display: fallback;
        src: local('Udemy Sans Bold'),
             local('UdemySans-Bold'),
             url('/staticx/udemy/fonts/Udemy-Sans-Bold-v1.woff2') format('woff2');
    }

    @font-face {
        font-family: SuisseWorks;
        font-style: normal;
        font-weight: 700; /* To match token @font-weight-bold */
        font-display: fallback;
        src: local('SuisseWorks Bold'),
             local('SuisseWorks-Bold'),
             url('/staticx/udemy/fonts/SuisseWorks-Bold-v1.woff2') format('woff2');
    }
</style>
<link type="text/css" rel="stylesheet" href="/staticx/udemy/js/webpack/entry-main.3bdd155dc9b9dd24d3df.css" />
<link type="text/css" rel="stylesheet" href="/staticx/udemy/js/webpack/common-app-css.fef60dd6c13fa8f18277.css" />
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript" src="/staticx/udemy/js/webpack/common-app-css.c115a2a5ee27a47f3137.js" defer></script>
<link type="text/css" rel="stylesheet" href="/staticx/udemy/js/webpack/common-desktop-server-side.490d0bb6c339e2dfc7a4.css" />
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript" src="/staticx/udemy/js/webpack/common-desktop-server-side.e71dd4589cb289918cb3.js" defer></script>
<link type="text/css" rel="stylesheet" href="/staticx/udemy/js/webpack/my-courses-v3-server-side.061b06de67c29eb5496b.css" />
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript" src="/staticx/udemy/js/webpack/my-courses-v3-server-side.cbf17f05f020a582eea1.js" defer></script>
<link type="text/css" rel="stylesheet" href="/staticx/udemy/js/webpack/my-courses-v3-udlite-app.aa609dce4c2e53008503.css" />
<link rel="preconnect" href="https://s.udemycdn.com/" />
<link rel="preconnect" href="https://s.udemycdn.com/" crossorigin />
<link rel="preconnect" href="https://img-c.udemycdn.com/" />
<link rel="preconnect" href="https://img-b.udemycdn.com/" />
<link rel="dns-prefetch" href="https://s.udemycdn.com/" />
<link rel="dns-prefetch" href="https://img-c.udemycdn.com/" />
<link rel="dns-prefetch" href="https://img-b.udemycdn.com/" />
<link nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" rel="preload" as="script" href="/staticx/udemy/js/webpack/my-courses-v3-udlite-app.d8a4cf77f0dc8244fce0.js" />
<link nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" rel="preload" as="script" href="/staticx/udemy/js/webpack/common-desktop-udlite-app.5317319abb4e335e77e5.js" />
<link rel="apple-touch-icon" sizes="180x180" href="/staticx/udemy/images/v7/apple-touch-icon.png" />
<link rel="icon" type="image/png" sizes="32x32" href="/staticx/udemy/images/v8/favicon-32x32.png" />
<link rel="icon" type="image/png" sizes="16x16" href="/staticx/udemy/images/v8/favicon-16x16.png" />
<link rel="manifest" href="/staticx/udemy/images/v7/site-manifest.json" />
<meta name="application-name" content="Udemy" />
<meta name="msapplication-TileColor" content="#a435f0" />
<meta name="msapplication-TileImage" content="/staticx/udemy/images/v7/mstile-144x144.png">
<meta name="msapplication-config" content="/staticx/udemy/images/v7/browserconfig.xml" />
<meta name="theme-color" content="#ffffff" />
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=">
    window.UD = window.UD || {};
    window.UD.Config = {"version":"ab07d6bc2d5d28899038a3ba82c973cb88aedaa9","env":"PROD","graphql_federation_endpoint":"https://www.udemy.com/graphql/","marketplace_country":{"_class":"country","id":"TR","iso_code":"TUR","title":"Turkey","currency":"try"},"price_country":{"_class":"country","id":"TR","currency":"try","currency_symbol":"\u20ba","currency_decimal_places":2,"currency_formatter":{"currency":"try","symbol":"\u20ba","locale":"tr_TR","decimal":",","group":".","pattern":"!#,##0.00","scale":2},"usd_currency_formatter":{"currency":"usd","symbol":"$","locale":"tr_TR","decimal":",","group":".","pattern":"#,##0.00 !","scale":2}},"supported_languages":[{"locale":"en_US","name":"English","lang":"en"},{"locale":"de_DE","name":"Deutsch","lang":"de"},{"locale":"es_ES","name":"Espa\u00f1ol","lang":"es"},{"locale":"fr_FR","name":"Fran\u00e7ais","lang":"fr"},{"locale":"id_ID","name":"Bahasa Indonesia","lang":"id"},{"locale":"it_IT","name":"Italiano","lang":"it"},{"locale":"ja_JP","name":"\u65e5\u672c\u8a9e","lang":"ja"},{"locale":"ko_KR","name":"\ud55c\uad6d\uc5b4","lang":"ko"},{"locale":"nl_NL","name":"Nederlands","lang":"nl"},{"locale":"pl_PL","name":"Polski","lang":"pl"},{"locale":"pt_BR","name":"Portugu\u00eas","lang":"pt"},{"locale":"ro_RO","name":"Rom\u00e2n\u0103","lang":"ro"},{"locale":"ru_RU","name":"\u0420\u0443\u0441\u0441\u043a\u0438\u0439","lang":"ru"},{"locale":"th_TH","name":"\u0e20\u0e32\u0e29\u0e32\u0e44\u0e17\u0e22","lang":"th"},{"locale":"tr_TR","name":"T\u00fcrk\u00e7e","lang":"tr"},{"locale":"vi_VN","name":"Ti\u1ebfng Vi\u1ec7t","lang":"vi"},{"locale":"zh_CN","name":"\u4e2d\u6587(\u7b80\u4f53)","lang":"zh-cn"},{"locale":"zh_TW","name":"\u4e2d\u6587(\u7e41\u9ad4)","lang":"zh-tw"}],"brand":{"_class":"brand","title":"Udemy","identifier":"udemy","has_organization":false,"is_messaging_enabled":true,"is_discussions_enabled":true,"is_feed_commenting_enabled":true,"is_teaching_enabled":true,"is_add_reviews_enabled":true,"is_mobile_app_enabled":true,"is_import_courses_enabled":true,"is_social_sharing_enabled":true,"is_external_sources_enabled":true,"is_third_party_marketing_enabled":true,"is_government":false,"is_sso_enabled":false,"is_team":false,"logo_url_2x":"/staticx/udemy/images/v7/logo-udemy.svg","link_bar_nav_list_id":"ud-link-bar","is_share_to_workplace_enabled":false,"is_share_on_slack_enabled":false,"is_share_to_ms_teams_enabled":false,"is_profile_functions_enabled":true,"is_user_profiles_public":true,"product_logo":"/staticx/udemy/images/v7/logo-udemy.svg","product_logo_light":"/staticx/udemy/images/v7/logo-udemy-inverted.svg","product_logo_aspect_ratio":2.6785714285714284,"product_name":"Udemy","organization":false},"features":{"course_badge":true,"footer":{"links":{"about":true,"contact":true,"affiliates":true,"blog":true,"business":true,"careers":true,"benesse_corporate_page":false,"commercial_transactions_law_page":true,"teach":true}},"hello_bar":{"instructor":false,"pricing":true,"terms":true},"notice":{"instructor_bar":false,"smart_bar":false,"ufb_smart_bar":false},"notifications":true,"report_abuse":true,"shopping_cart":true,"wishlist":true,"social_share":{"email":true},"reviews":{"show_user_avatar":true},"intercom_chat":true,"zendesk_chat":false,"ufb_notices":true,"ufb_notices_footer":{"top_com":false},"collect_performance_rum":true,"braze_web_push":false,"pendo_enabled":false,"course_review":{"clp_review_search":true,"leave_feedback":true},"course":{"discussions":{"view":true},"announcements":{"comments":{"view":true}},"students":{"unenroll":false},"refundable":true},"logged_in_home":{"linkbar_level_2":true,"ufb_ad":false},"organization":{"auth":{"scim_api_enabled":false},"is_learner_goal_and_interest_collection_enabled":true,"manage_satisfaction":{"satisfaction":false},"learning_path":{"enabled":false,"copy_learning_path_item":false,"pro_path":false,"pro_path_hidden":false},"course_taking":{"student_assignment_submissions_enabled":true},"assignment_improvement_all_users":true,"manage_insights":{"path_insights_v2":false},"allow_only_plain_text_messaging":false,"is_measure_competence_release_train_enabled":false,"labs":{"are_beta_features_enabled":false},"is_fullstory_enabled":true,"is_ub_pro_onboarding_v2_enabled":false,"is_ub_license_pools_enabled":false,"sms_with_completed_package_migration_enabled":false,"is_custom_xapi_self_serve_enabled":false,"is_user_reactivation_notification_enabled":true,"hide_org_user_search_for_group_admins":false,"is_export_insights_to_pdf_enabled":false,"is_assign_summary_enabled":false,"is_learner_engagement_experiment_enabled":false,"is_learner_engagement_experiment_variant_b_enabled":false,"is_learner_engagement_experiment_variant_c_enabled":false,"is_course_versioning_enabled":false,"is_learner_progress_service_integration_enabled":false,"should_fetch_insights_from_las":false,"is_learning_communities_enabled":false,"is_shaka_player_enabled":false,"is_badging_assertions_upload_enabled":true,"hide_org_wide_learner_data":false,"should_serve_realtime_data_from_las":false,"is_user_activity_reports_v2_enabled":false},"home":{"my_courses":{"free_label":true,"privacy":true,"revenue":true},"signup_cta":true,"ufb_ad":{"default":true,"jp":false}},"course_landing_page":{"deal_badge":true,"incentives":{"access_tv":true,"lifetime_access":true},"instructor_bio":{"image":true,"social_links":true,"stats":true},"money_back_guarantee":true},"bundle":{"instructor_bio":{"social_links":true}},"discount":{"change_alerts":true}},"app_name":"home","js_bundle":"modern","url":{"to_root":"https://www.udemy.com/","to_app":"https://www.udemy.com/","to_images":"https://www.udemy.com/staticx/udemy/images/","to_js":"https://www.udemy.com/staticx/udemy/js/"},"drm_license_server_url_template":"{base_url}media-license-server/validate-auth-token?drm_type={drm_type}\u0026auth_token={auth_token}","drm_fairplay_certificate_cdn_domain":"img-c.udemycdn.com","third_party":{"google_analytics_id":"UA-12366301-1","google_analytics_id_for_course_taking":"UA-12366301-45","google_tag_manager_id":"GTM-7BF3X","google_analytics_id_for_ufb_only":"UA-12366301-47","facebook_app_id":"313137469260","raven_dsn":"https://369c830fbf534485a068ab919d71b80d@sentry.io/38617","sift_account":"78b4b13f0a","uft_stripe_publishable_key":"pk_live_dCyHJcZsk8NaNwx1PiRSpqqq","branch_metrics":{"ios_download_url":"http://ude.my/ios","ios_ufb_download_url":"http://ude.my/ios-ufb","android_download_url":"http://ude.my/android","android_ufb_download_url":"http://ude.my/android-ufb"},"intercom":{"app_id":"sehj53dd"},"pusher":{"key":"dd9e21a517a37660588c","coding_exercise_event":"coding-exercise-evaluated"},"zendesk":{"refund_form_id":406368},"filestack":{"key":"A0EHlHYkEQbCTpDvxEwAYz"},"paypal":{"appid":"ASRJrkbBfTwvxWNTn-QRakeimIbsjmBuK5hWj4zq3QJL46CKIYNb-RiKjrTSe-2iZ-EFrCCuXGZTxHjY","authend":"live","returnurl":"https://www.udemy.com/user/paypal-login-return"},"s3":{"asset":{"key":"AKIA5IZMAQTG6TBSZJ67","bucket_url":"https://udemy-web-upload-transitional.s3.amazonaws.com"},"image_asset":{"key":"AKIA5IZMAQTG6TBSZJ67","bucket_url":"https://udemy-image-web-upload.s3.amazonaws.com"}},"storage_static_asset_base_url":"https://s.udemycdn.com/"}};
    window.UD.experiment = {};
    window.UD.request = {"locale":"tr_TR","language":"tr","third_party_location":"https://www.udemy.com/home/my-courses/learning/","navigation_locale":"en_US","language_simple_english_title":"Turkish","termsBarType":"","termsBarUrls":"","isMobile":false,"isTablet":false,"isPC":true,"serverTimestamp":"2024-01-03T16:39:53.202705+03:00","is_tapen_access_domain":false,"is_bot":false,"extra_experiment_data":{"lab_taking":{"Title":"Get hands-on practice","Desc":"Sharpen your technical skills with access to risk-free environments and real-world projects.","CTA":"Explore labs","lab_pause_resume_enabled":true},"labs":{"lab_service_v2_labs_for_students_enabled":true}}};
    window.UD.request.clientTimestamp = new Date().toISOString();
    window.UD.site_stats = {"default":{"num_students_m":"62M","num_students_million":"62 milyon","num_courses":213000,"num_courses_rounded":210000,"num_instructors":74000,"num_topics":2000,"num_course_languages":75,"num_course_enrollments_m":"830M","num_course_enrollments_million":"830 milyon","num_countries_taught":180},"organizations":{"num_courses":25000,"num_courses_rounded":25000,"num_instructors":1500,"num_enterprise_customers":15000}};
    window.UD.me = {"isLoading":false,"_class":"user","id":60509654,"email":"umutkonurinso@gmail.com","display_name":"Umut Can Arda","initials":"UA","title":"Umut Can Arda","time_zone":"Asia/Istanbul","country":"TR","locale":"tr_TR","name":"Umut Can","surname":"Arda","image_50x50":"https://img-c.udemycdn.com/user/50x50/60509654_567e_2.jpg","image_100x100":"https://img-c.udemycdn.com/user/100x100/60509654_567e_2.jpg","is_authenticated":true,"job_title":"Back-End Developer","created":"2018-12-13T19:55:54Z","language":"tr","learning_languages":[],"settings":{"interstitialAutoNext":"on","instructor-courses-ordering":"-created"},"qualaroo_survey_ids":[],"encrypted_affiliate_uid":"5968fa05123d5d70d7b5caaf33674c89837950d2","encrypted_affiliate_email":"fc922f9d4bdf2d7ead0b6f72131bd8d7d81e656e","encrypted_id":"x01tsomBkQ9Hfe7cxL9mcQI9Q==","has_made_paid_purchase":true,"number_of_courses_purchased":6,"organization":null,"url":"/user/umut-can-arda/"};
    window.UD.meProperties = ["_class","id","email","display_name","job_title","initials","title","time_zone","country","created","locale","language","learning_languages","name","surname","image_50x50","image_100x100","settings","qualaroo_survey_ids","encrypted_affiliate_uid","encrypted_affiliate_email","encrypted_id","has_made_paid_purchase","number_of_courses_purchased","organization","url"];
    window.UD.visiting = {"isLoading":false,"visitor_uuid":"6bca68dc3472433b95da49f4f4f16940","is_first_time_visitor":false,"first_visit_time":"2024-01-03T05:58:20.552Z"};
    window.UD.visitingProperties = ["visitor_uuid","is_first_time_visitor","first_visit_time"];
    window.UD.userSpecificTrackingParams = {"isLoading":false,"tracking_enabled":true};
    window.UD.userSpecificTrackingProperties = ["tracking_enabled"];
    window.UD.userAgnosticTrackingParams = {"page_key":"my_learning"};

    
</script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=">
        window.udPerformanceEnabled = true;
    </script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=">
    
    window.GoogleAnalyticsObject = 'ga';
    window.ga = function () {
        (window.ga.q = window.ga.q || []).push(arguments);
    };
    window.ga.l = 1 * new Date();

    UD.GoogleAnalytics = UD.GoogleAnalytics || {};
    UD.GoogleAnalytics.createAccount = function (accountId, propertyName, domainName) {
        if (accountId) {
            if (propertyName) {
                // Required for multiple trackers
                window.ga('create', accountId, 'auto', {'name': propertyName, 'cookieDomain': domainName || 'none',
                    'siteSpeedSampleRate': 10});
            } else {
                window.ga('create', accountId, 'auto', {'siteSpeedSampleRate': 10});
                window.ga('require', 'displayfeatures'); // Enables retargeting
            }
            window.ga('set', {
                'anonymizeIp': true,
                'location' : ""
            });
        }
    };
    UD.GoogleAnalytics.createAccount(UD.Config.third_party.google_analytics_id);
</script>
<base href="/home/my-courses/">
</head>
<body id="udemy" class="my-courses  udemy ">
<div class="ud-main-content-wrapper">
<div class="ud-app-loader ud-component--header-v6--header ud-header" data-module-id="common/desktop" data-module-args="{&quot;isLoggedIn&quot;:true,&quot;isInstructorSignupEnabled&quot;:false,&quot;mobileAppLink&quot;:{&quot;url&quot;:&quot;/mobile/&quot;},&quot;tryUFBPlacements&quot;:{&quot;bar&quot;:&quot;logged-in-nav&quot;,&quot;mobile&quot;:&quot;logged-in-nav&quot;,&quot;profile&quot;:&quot;account-menu&quot;},&quot;currentLocale&quot;:&quot;tr_TR&quot;,&quot;searchPhrase&quot;:null,&quot;persistentSearch&quot;:false,&quot;showAutocompletePopularQueriesOnEmptyState&quot;:&quot;disabled&quot;}" data-module-priority="-10"><div data-unique-id="129" style="display:none"></div><div class="desktop-header-module--mobile-header--azBaJ"><div data-testid="mobile-header-placeholder" class="desktop-header-module--mobile-header-placeholder--1VoUw"></div></div><span class="desktop-header-module--mark--3iJdI"></span><div class="ud-header ud-text-sm desktop-header-module--header--3nb6v desktop-header-module--flex-middle--1e7c8" data-purpose="header"><div class="skip-to-content-button-module--skip-to-content--2FwlU"><a class="ud-btn ud-btn-large ud-btn-primary ud-heading-md skip-to-content-button-module--skip-to-content-btn--13D7B" href="#main-content-anchor"><span aria-hidden="true" class="skip-to-content-button-module--skip-to-content-shadow--1g-_y"></span><span style="margin:0">İçeriğe atla</span></a></div><a href="/" class="desktop-header-module--flex-middle--1e7c8 desktop-header-module--logo--2Qf0r"><img src="https://www.udemy.com/staticx/udemy/images/v7/logo-udemy.svg" alt="Udemy" width="91" height="34" loading="lazy" /></a><nav class="popper-module--popper--2BpLn desktop-header-module--gap-button--1Ua9W browse-nav-module--placeholder-header-button--mKoRf"><div class="browse-nav-module--placeholder-header-button--mKoRf" id="u129-popper-trigger--1" aria-expanded="false" tabindex="0">Kategoriler</div><div class="popper-module--popper-content--3cLBV desktop-header-module--dropdown--2R_M9" id="u129-popper-content--2" aria-labelledby="u129-popper-trigger--1" style="top:100%;left:0"><div class="popper-module--animation-wrapper--2ogNt"><div class="popover-module--popover--1kskS popover-module--popover-bottom--N6gdN"><div class="popover-module--inner--Sbv-I"><div class="list-menu-module--list-menu-container--3d8ZF browse-nav-module--nav-container--1J6dv" data-testid="browse-nav"><div class="js-browse-nav-level-one browse-nav-module--nav--205F5" data-testid="browse-nav-list"><ul class="ud-unstyled-list ud-block-list list-menu-module--section--1WKRq"><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li><li><div class="list-menu-module--item--3f005 ud-block-list-item ud-block-list-item-small ud-block-list-item-neutral ud-text-sm"><div class="ud-block-list-item-content ud-block-list-item-content-loading"> </div></div></li></ul></div><div id="header-browse-nav-level-two" class="js-browse-nav-level-two browse-nav-module--nav--205F5" style="display:none" data-testid="browse-nav-list"></div><div id="header-browse-nav-level-three" class="js-browse-nav-level-three browse-nav-module--nav--205F5" style="display:none" data-testid="browse-nav-list"></div></div></div></div></div></div></nav><div locale="tr_TR" lang="tr" class="ud-search-form-autocomplete desktop-header-module--search-bar--2V17S ud-form-group"><label class="ud-sr-only ud-form-label ud-heading-sm" for="u129-search-form-autocomplete--3">Dilediğiniz şeyi arayın</label><form action="/courses/search/" class="ud-search-form-autocomplete-input-group ud-search-form-autocomplete-input-group-reversed"><input type="hidden" name="src" value="ukw" /><input type="text" aria-invalid="false" name="q" data-testid="search-input" placeholder="Dilediğiniz şeyi arayın" autoComplete="off" value role="combobox" aria-autocomplete="both" aria-haspopup="true" aria-expanded="false" aria-controls="u129-search-form-autocomplete--3-menu-content-items" id="u129-search-form-autocomplete--3" class="ud-text-input ud-text-input-small ud-text-sm ud-search-form-autocomplete-input js-header-search-field" /><button type="submit" disabled class="ud-btn ud-btn-large ud-btn-ghost ud-heading-md ud-btn-disabled ud-btn-icon ud-btn-icon-large" tabindex="-1"><svg aria-label="Aramayı gönder" role="img" focusable="false" class="ud-icon ud-icon-medium ud-icon-color-neutral"><use xlink:href="#icon-search"></use></svg></button></form></div><div style="flex:1"></div></div></div>
<nav aria-hidden="true" style="position:fixed;top:0;left:-28rem;width:28rem;height:100%;">
<a data-id="288" class="js-side-nav-cat" href="/courses/development/" tabindex="-1">Yazılım Geliştirme</a>
<div>
<a data-id="8" class="js-side-nav-cat js-subcat" href="/courses/development/web-development/" tabindex="-1">Web Geliştirme</a>
<a data-id="558" class="js-side-nav-cat js-subcat" href="/courses/development/data-science/" tabindex="-1">Veri Bilimi</a>
<a data-id="10" class="js-side-nav-cat js-subcat" href="/courses/development/mobile-apps/" tabindex="-1">Mobil Yazılım Geliştirme</a>
<a data-id="12" class="js-side-nav-cat js-subcat" href="/courses/development/programming-languages/" tabindex="-1">Programlama Dilleri</a>
<a data-id="14" class="js-side-nav-cat js-subcat" href="/courses/development/game-development/" tabindex="-1">Oyun Geliştirme</a>
<a data-id="16" class="js-side-nav-cat js-subcat" href="/courses/development/databases/" tabindex="-1">Veri Tabanı Tasarlama ve Geliştirme</a>
<a data-id="18" class="js-side-nav-cat js-subcat" href="/courses/development/software-testing/" tabindex="-1">Yazılım Testi</a>
<a data-id="20" class="js-side-nav-cat js-subcat" href="/courses/development/software-engineering/" tabindex="-1">Yazılım Mühendisliği</a>
<a data-id="362" class="js-side-nav-cat js-subcat" href="/courses/development/development-tools/" tabindex="-1">Yazılım Geliştirme Araçları</a>
<a data-id="575" class="js-side-nav-cat js-subcat" href="/courses/development/no-code-development/" tabindex="-1">Kodsuz Yazılım Geliştirme</a>
</div>
<a data-id="268" class="js-side-nav-cat" href="/courses/business/" tabindex="-1">İşletme</a>
<div>
<a data-id="26" class="js-side-nav-cat js-subcat" href="/courses/business/entrepreneurship/" tabindex="-1">Girişimcilik</a>
<a data-id="28" class="js-side-nav-cat js-subcat" href="/courses/business/communications/" tabindex="-1">İletişim</a>
<a data-id="30" class="js-side-nav-cat js-subcat" href="/courses/business/management/" tabindex="-1">Yönetim</a>
<a data-id="32" class="js-side-nav-cat js-subcat" href="/courses/business/sales/" tabindex="-1">Satış</a>
<a data-id="34" class="js-side-nav-cat js-subcat" href="/courses/business/strategy/" tabindex="-1">İş Stratejisi</a>
<a data-id="36" class="js-side-nav-cat js-subcat" href="/courses/business/operations/" tabindex="-1">Operasyonlar</a>
<a data-id="38" class="js-side-nav-cat js-subcat" href="/courses/business/project-management/" tabindex="-1">Proje Yönetimi</a>
<a data-id="40" class="js-side-nav-cat js-subcat" href="/courses/business/business-law/" tabindex="-1">İş Hukuku</a>
<a data-id="44" class="js-side-nav-cat js-subcat" href="/courses/business/analytics-and-intelligence/" tabindex="-1">İş Analitiği ve Zekası</a>
<a data-id="48" class="js-side-nav-cat js-subcat" href="/courses/business/human-resources/" tabindex="-1">İnsan Kaynakları</a>
<a data-id="50" class="js-side-nav-cat js-subcat" href="/courses/business/industry/" tabindex="-1">Sanayi</a>
<a data-id="354" class="js-side-nav-cat js-subcat" href="/courses/business/e-commerce/" tabindex="-1">E-Ticaret</a>
<a data-id="52" class="js-side-nav-cat js-subcat" href="/courses/business/media/" tabindex="-1">Medya</a>
<a data-id="58" class="js-side-nav-cat js-subcat" href="/courses/business/real-estate/" tabindex="-1">Gayrimenkul</a>
<a data-id="60" class="js-side-nav-cat js-subcat" href="/courses/business/other-business/" tabindex="-1">Diğer İşletme</a>
</div>
<a data-id="328" class="js-side-nav-cat" href="/courses/finance-and-accounting/" tabindex="-1">Finans ve Muhasebe</a>
<div>
<a data-id="530" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/accounting-bookkeeping/" tabindex="-1">Muhasebe ve Defter Tutma</a>
<a data-id="532" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/compliance/" tabindex="-1">Uyumluluk</a>
<a data-id="534" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/cryptocurrency-and-blockchain/" tabindex="-1">Sanal Para Birimi ve Blockchain</a>
<a data-id="536" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/economics/" tabindex="-1">Ekonomi</a>
<a data-id="540" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/finance-management/" tabindex="-1">Finans</a>
<a data-id="542" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/finance-certification-and-exam-prep/" tabindex="-1">Finans Alanında Sertifika ve Sınav Hazırlığı</a>
<a data-id="544" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/financial-modeling-and-analysis/" tabindex="-1">Finansal Modelleme ve Analiz</a>
<a data-id="546" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/investing-and-trading/" tabindex="-1">Yatırım ve Ticaret</a>
<a data-id="548" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/money-management-tools/" tabindex="-1">Nakit Yönetimi Araçları</a>
<a data-id="550" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/taxes/" tabindex="-1">Vergiler</a>
<a data-id="552" class="js-side-nav-cat js-subcat" href="/courses/finance-and-accounting/other-finance-and-accounting/" tabindex="-1">Diğer Finans ve Muhasebe</a>
</div>
<a data-id="294" class="js-side-nav-cat" href="/courses/it-and-software/" tabindex="-1">BT ve Yazılım</a>
<div>
<a data-id="132" class="js-side-nav-cat js-subcat" href="/courses/it-and-software/it-certification/" tabindex="-1">BT Sertifikaları</a>
<a data-id="134" class="js-side-nav-cat js-subcat" href="/courses/it-and-software/network-and-security/" tabindex="-1">Ağ ve Güvenlik</a>
<a data-id="136" class="js-side-nav-cat js-subcat" href="/courses/it-and-software/hardware/" tabindex="-1">Donanım</a>
<a data-id="138" class="js-side-nav-cat js-subcat" href="/courses/it-and-software/operating-systems/" tabindex="-1">İşletim Sistemleri ve Sunucular</a>
<a data-id="140" class="js-side-nav-cat js-subcat" href="/courses/it-and-software/other-it-and-software/" tabindex="-1">Diğer BT ve Yazılım</a>
</div>
<a data-id="292" class="js-side-nav-cat" href="/courses/office-productivity/" tabindex="-1">Ofiste Verimlilik</a>
<div>
<a data-id="96" class="js-side-nav-cat js-subcat" href="/courses/office-productivity/microsoft/" tabindex="-1">Microsoft</a>
<a data-id="98" class="js-side-nav-cat js-subcat" href="/courses/office-productivity/apple/" tabindex="-1">Apple</a>
<a data-id="100" class="js-side-nav-cat js-subcat" href="/courses/office-productivity/google/" tabindex="-1">Google</a>
<a data-id="102" class="js-side-nav-cat js-subcat" href="/courses/office-productivity/sap/" tabindex="-1">SAP</a>
<a data-id="106" class="js-side-nav-cat js-subcat" href="/courses/office-productivity/oracle/" tabindex="-1">Oracle</a>
<a data-id="108" class="js-side-nav-cat js-subcat" href="/courses/office-productivity/other-productivity/" tabindex="-1">Diğer Ofiste Verimlilik</a>
</div>
<a data-id="296" class="js-side-nav-cat" href="/courses/personal-development/" tabindex="-1">Kişisel Gelişim</a>
<div>
<a data-id="142" class="js-side-nav-cat js-subcat" href="/courses/personal-development/personal-transformation/" tabindex="-1">Kişisel Gelişim</a>
<a data-id="144" class="js-side-nav-cat js-subcat" href="/courses/personal-development/productivity/" tabindex="-1">Kişisel Verimlilik</a>
<a data-id="146" class="js-side-nav-cat js-subcat" href="/courses/personal-development/leadership/" tabindex="-1">Liderlik</a>
<a data-id="150" class="js-side-nav-cat js-subcat" href="/courses/personal-development/career-development/" tabindex="-1">Kariyer Geliştirme</a>
<a data-id="152" class="js-side-nav-cat js-subcat" href="/courses/personal-development/parenting-and-relationships/" tabindex="-1">Ebeveynlik ve İlişkiler</a>
<a data-id="156" class="js-side-nav-cat js-subcat" href="/courses/personal-development/happiness/" tabindex="-1">Mutluluk</a>
<a data-id="577" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/esoteric-practices/" tabindex="-1">Ezoterik Uygulamalar</a>
<a data-id="158" class="js-side-nav-cat js-subcat" href="/courses/personal-development/religion-and-spirituality/" tabindex="-1">Din ve Maneviyat</a>
<a data-id="160" class="js-side-nav-cat js-subcat" href="/courses/personal-development/personal-brand-building/" tabindex="-1">Kişisel Marka Oluşturma</a>
<a data-id="164" class="js-side-nav-cat js-subcat" href="/courses/personal-development/creativity/" tabindex="-1">Yaratıcılık</a>
<a data-id="166" class="js-side-nav-cat js-subcat" href="/courses/personal-development/influence/" tabindex="-1">İlham</a>
<a data-id="168" class="js-side-nav-cat js-subcat" href="/courses/personal-development/self-esteem-and-confidence/" tabindex="-1">Diğer Öz Güven ve Öz Saygı</a>
<a data-id="170" class="js-side-nav-cat js-subcat" href="/courses/personal-development/stress-management/" tabindex="-1">Stres Yönetimi</a>
<a data-id="172" class="js-side-nav-cat js-subcat" href="/courses/personal-development/memory/" tabindex="-1">Hafıza ve Çalışma Becerileri</a>
<a data-id="176" class="js-side-nav-cat js-subcat" href="/courses/personal-development/motivation/" tabindex="-1">Motivasyon</a>
<a data-id="178" class="js-side-nav-cat js-subcat" href="/courses/personal-development/other-personal-development/" tabindex="-1">Diğer Kişisel Gelişim</a>
</div>
<a data-id="269" class="js-side-nav-cat" href="/courses/design/" tabindex="-1">Tasarım</a>
<div>
<a data-id="6" class="js-side-nav-cat js-subcat" href="/courses/design/web-design/" tabindex="-1">Web Tasarımı</a>
<a data-id="110" class="js-side-nav-cat js-subcat" href="/courses/design/graphic-design-and-illustration/" tabindex="-1">Diğer Grafik Tasarım ve İllüstrasyon</a>
<a data-id="112" class="js-side-nav-cat js-subcat" href="/courses/design/design-tools/" tabindex="-1">Tasarım Araçları</a>
<a data-id="114" class="js-side-nav-cat js-subcat" href="/courses/design/user-experience/" tabindex="-1">Kullanıcı Deneyimi Tasarımı</a>
<a data-id="116" class="js-side-nav-cat js-subcat" href="/courses/design/game-design/" tabindex="-1">Oyun Tasarımı</a>
<a data-id="120" class="js-side-nav-cat js-subcat" href="/courses/design/3d-and-animation/" tabindex="-1">3D ve Animasyon</a>
<a data-id="122" class="js-side-nav-cat js-subcat" href="/courses/design/fashion/" tabindex="-1">Moda Tasarımı</a>
<a data-id="124" class="js-side-nav-cat js-subcat" href="/courses/design/architectural-design/" tabindex="-1">Mimari Tasarım</a>
<a data-id="128" class="js-side-nav-cat js-subcat" href="/courses/design/interior-design/" tabindex="-1">İç Tasarım</a>
<a data-id="130" class="js-side-nav-cat js-subcat" href="/courses/design/other-design/" tabindex="-1">Diğer Tasarım</a>
</div>
<a data-id="290" class="js-side-nav-cat" href="/courses/marketing/" tabindex="-1">Pazarlama</a>
<div>
<a data-id="62" class="js-side-nav-cat js-subcat" href="/courses/marketing/digital-marketing/" tabindex="-1">Dijital Pazarlama</a>
<a data-id="64" class="js-side-nav-cat js-subcat" href="/courses/marketing/search-engine-optimization/" tabindex="-1">Arama Motoru Optimizasyonu</a>
<a data-id="66" class="js-side-nav-cat js-subcat" href="/courses/marketing/social-media-marketing/" tabindex="-1">Sosyal Medya Pazarlama</a>
<a data-id="68" class="js-side-nav-cat js-subcat" href="/courses/marketing/branding/" tabindex="-1">Markalaştırma</a>
<a data-id="70" class="js-side-nav-cat js-subcat" href="/courses/marketing/marketing-fundamentals/" tabindex="-1">Pazarlamanın Temelleri</a>
<a data-id="72" class="js-side-nav-cat js-subcat" href="/courses/marketing/analytics-and-automation/" tabindex="-1">Pazarlama Analizi ve Otomasyon</a>
<a data-id="74" class="js-side-nav-cat js-subcat" href="/courses/marketing/public-relations/" tabindex="-1">Halkla İlişkiler</a>
<a data-id="76" class="js-side-nav-cat js-subcat" href="/courses/marketing/advertising/" tabindex="-1">Ücretli Reklam</a>
<a data-id="78" class="js-side-nav-cat js-subcat" href="/courses/marketing/video-and-mobile-marketing/" tabindex="-1">Video ve Mobil Pazarlama</a>
<a data-id="80" class="js-side-nav-cat js-subcat" href="/courses/marketing/content-marketing/" tabindex="-1">İçerik Pazarlama</a>
<a data-id="86" class="js-side-nav-cat js-subcat" href="/courses/marketing/growth-hacking/" tabindex="-1">Growth Hacking</a>
<a data-id="88" class="js-side-nav-cat js-subcat" href="/courses/marketing/affiliate-marketing/" tabindex="-1">İş Ortaklığı Pazarlama</a>
<a data-id="90" class="js-side-nav-cat js-subcat" href="/courses/marketing/product-marketing/" tabindex="-1">Ürün Pazarlama</a>
<a data-id="94" class="js-side-nav-cat js-subcat" href="/courses/marketing/other-marketing/" tabindex="-1">Diğer Pazarlama</a>
</div>
<a data-id="274" class="js-side-nav-cat" href="/courses/lifestyle/" tabindex="-1">Yaşam Tarzı</a>
<div>
<a data-id="180" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/arts-and-crafts/" tabindex="-1">Sanat ve El Sanatları</a>
<a data-id="184" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/beauty-and-makeup/" tabindex="-1">Güzellik ve Makyaj</a>
<a data-id="577" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/esoteric-practices/" tabindex="-1">Ezoterik Uygulamalar</a>
<a data-id="182" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/food-and-beverage/" tabindex="-1">Yiyecek ve İçecek</a>
<a data-id="188" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/gaming/" tabindex="-1">Oyun</a>
<a data-id="190" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/home-improvement/" tabindex="-1">Ev Geliştirme ve Bahçe İşleri</a>
<a data-id="192" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/pet-care-and-training/" tabindex="-1">Evcil Hayvan Bakımı ve Eğitimi</a>
<a data-id="186" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/travel/" tabindex="-1">Seyahat</a>
<a data-id="194" class="js-side-nav-cat js-subcat" href="/courses/lifestyle/other-lifestyle/" tabindex="-1">Diğer Yaşam Stili</a>
</div>
<a data-id="273" class="js-side-nav-cat" href="/courses/photography-and-video/" tabindex="-1">Fotoğraf ve Video</a>
<div>
<a data-id="370" class="js-side-nav-cat js-subcat" href="/courses/photography-and-video/digital-photography/" tabindex="-1">Dijital Fotoğrafçılık</a>
<a data-id="196" class="js-side-nav-cat js-subcat" href="/courses/photography-and-video/photography-fundamentals/" tabindex="-1">Fotoğrafçılık</a>
<a data-id="204" class="js-side-nav-cat js-subcat" href="/courses/photography-and-video/portraits/" tabindex="-1">Portre Fotoğrafçılığı</a>
<a data-id="198" class="js-side-nav-cat js-subcat" href="/courses/photography-and-video/photography-tools/" tabindex="-1">Fotoğrafçılık Araçları</a>
<a data-id="208" class="js-side-nav-cat js-subcat" href="/courses/photography-and-video/commercial-photography/" tabindex="-1">Ticari Fotoğrafçılık</a>
<a data-id="218" class="js-side-nav-cat js-subcat" href="/courses/photography-and-video/video-design/" tabindex="-1">Video Tasarımı</a>
<a data-id="220" class="js-side-nav-cat js-subcat" href="/courses/photography-and-video/other-photography-and-video/" tabindex="-1">Diğer Fotoğrafçılık ve Video</a>
</div>
<a data-id="276" class="js-side-nav-cat" href="/courses/health-and-fitness/" tabindex="-1">Sağlık ve Fitness</a>
<div>
<a data-id="222" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/fitness/" tabindex="-1">Fitness</a>
<a data-id="224" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/general-health/" tabindex="-1">Genel Sağlık</a>
<a data-id="226" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/sports/" tabindex="-1">Spor</a>
<a data-id="228" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/nutrition/" tabindex="-1">Beslenme ve Diyetetik</a>
<a data-id="230" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/yoga/" tabindex="-1">Yoga</a>
<a data-id="232" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/mental-health/" tabindex="-1">Ruh Sağlığı</a>
<a data-id="236" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/self-defense/" tabindex="-1">Dövüş Sanatları ve Kendini Savunma</a>
<a data-id="238" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/safety-and-first-aid/" tabindex="-1">Güvenlik ve İlk Yardım</a>
<a data-id="240" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/dance/" tabindex="-1">Dans</a>
<a data-id="242" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/meditation/" tabindex="-1">Meditasyon</a>
<a data-id="244" class="js-side-nav-cat js-subcat" href="/courses/health-and-fitness/other-health-and-fitness/" tabindex="-1">Diğer Sağlık ve Fitness</a>
</div>
<a data-id="278" class="js-side-nav-cat" href="/courses/music/" tabindex="-1">Müzik</a>
<div>
<a data-id="296" class="js-side-nav-cat js-subcat" href="/courses/music/instruments/" tabindex="-1">Enstrümanlar</a>
<a data-id="298" class="js-side-nav-cat js-subcat" href="/courses/music/production/" tabindex="-1">Müzik Prodüksiyonu</a>
<a data-id="300" class="js-side-nav-cat js-subcat" href="/courses/music/music-fundamentals/" tabindex="-1">Müziğin Temelleri</a>
<a data-id="302" class="js-side-nav-cat js-subcat" href="/courses/music/vocal/" tabindex="-1">Vokal</a>
<a data-id="304" class="js-side-nav-cat js-subcat" href="/courses/music/music-techniques/" tabindex="-1">Müzik Teknikleri</a>
<a data-id="306" class="js-side-nav-cat js-subcat" href="/courses/music/music-software/" tabindex="-1">Müzik Yazılımı</a>
<a data-id="308" class="js-side-nav-cat js-subcat" href="/courses/music/other-music/" tabindex="-1">Diğer Müzik</a>
</div>
<a data-id="300" class="js-side-nav-cat" href="/courses/teaching-and-academics/" tabindex="-1">Öğretim ve Akademi</a>
<div>
<a data-id="366" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/engineering/" tabindex="-1">Mühendislik</a>
<a data-id="380" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/humanities/" tabindex="-1">Beşeri Bilimler</a>
<a data-id="310" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/math/" tabindex="-1">Matematik</a>
<a data-id="312" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/science/" tabindex="-1">Bilim</a>
<a data-id="523" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/online-education/" tabindex="-1">Online Eğitim</a>
<a data-id="376" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/social-science/" tabindex="-1">Sosyal Bilimler</a>
<a data-id="521" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/language/" tabindex="-1">Dil Öğrenimi</a>
<a data-id="527" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/teacher-training/" tabindex="-1">Öğretmen Eğitimi</a>
<a data-id="529" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/test-prep/" tabindex="-1">Sınava Hazırlık</a>
<a data-id="525" class="js-side-nav-cat js-subcat" href="/courses/teaching-and-academics/other-teaching-academics/" tabindex="-1">Diğer Öğretim ve Akademi</a>
</div>
<div data-id="8" class="js-side-nav-popular-topics">
<a data-id="8322" href="/topic/web-development/" tabindex="-1">Web Geliştirme</a>
<a data-id="6368" href="/topic/javascript/" tabindex="-1">JavaScript</a>
<a data-id="7450" href="/topic/react/" tabindex="-1">React JS</a>
<a data-id="28016" href="/topic/angular/" tabindex="-1">Angular</a>
<a data-id="5306" href="/topic/css/" tabindex="-1">CSS</a>
<a data-id="6928" href="/topic/nodejs/" tabindex="-1">Node.Js</a>
<a data-id="8124" href="/topic/typescript/" tabindex="-1">TypeScript</a>
<a data-id="57548" href="/topic/nextjs-p/" tabindex="-1">Next.js</a>
<a data-id="10230" href="/topic/aspnet-core/" tabindex="-1">ASP.NET Core</a>
</div>
<div data-id="132" class="js-side-nav-popular-topics">
<a data-id="46868" href="/topic/aws-certified-cloud-practitioner/" tabindex="-1">AWS Certified Cloud Practitioner</a>
<a data-id="24774" href="/topic/aws-certified-solutions-architect-associate/" tabindex="-1">AWS Certified Solutions Architect - Associate</a>
<a data-id="5166" href="/topic/comptia-a/" tabindex="-1">CompTIA A+</a>
<a data-id="4452" href="/topic/amazon-aws/" tabindex="-1">Amazon AWS</a>
<a data-id="5176" href="/topic/comptia-security/" tabindex="-1">CompTIA Security+</a>
<a data-id="5044" href="/topic/cisco-ccna/" tabindex="-1">Cisco Certified Network Associate (CCNA)</a>
<a data-id="43860" href="/topic/aws-certified-developer-associate/" tabindex="-1">AWS Certified Developer - Associate</a>
<a data-id="118634" href="/topic/microsoft-az-900/" tabindex="-1">AZ-900: Microsoft Azure Fundamentals</a>
<a data-id="6238" href="/topic/information-security/" tabindex="-1">Bilgi Güvenliği</a>
</div>
<div data-id="44" class="js-side-nav-popular-topics">
<a data-id="6740" href="/topic/microsoft-power-bi/" tabindex="-1">Microsoft Power BI</a>
<a data-id="7862" href="/topic/sql/" tabindex="-1">SQL</a>
<a data-id="5334" href="/topic/data-modeling/" tabindex="-1">Veri Modelleme</a>
<a data-id="5328" href="/topic/data-analysis/" tabindex="-1">Veri Analizi</a>
<a data-id="9000" href="/topic/business-analysis/" tabindex="-1">İş Analizi</a>
<a data-id="7978" href="/topic/tableau/" tabindex="-1">Tableau</a>
<a data-id="4864" href="/topic/business-analytics/" tabindex="-1">İş Analitiği</a>
<a data-id="29362" href="/topic/dax/" tabindex="-1">Veri Analizi İfadeleri (DAX)</a>
<a data-id="4886" href="/topic/business-intelligence/" tabindex="-1">Business Intelligence</a>
</div>
<div data-id="14" class="js-side-nav-popular-topics">
<a data-id="8166" href="/topic/unreal-engine/" tabindex="-1">Unreal Engine</a>
<a data-id="8154" href="/topic/unity/" tabindex="-1">Unity</a>
<a data-id="5904" href="/topic/game-development/" tabindex="-1">Oyun Geliştirmenin Temelleri</a>
<a data-id="4904" href="/topic/c-sharp/" tabindex="-1">C# (programlama dili)</a>
<a data-id="4908" href="/topic/c-plus-plus/" tabindex="-1">C++ (programming language)</a>
<a data-id="36020" href="/topic/godot/" tabindex="-1">Godot</a>
<a data-id="4280" href="/topic/3d-game-development/" tabindex="-1">3D Oyun Geliştirme</a>
<a data-id="25642" href="/topic/2d-game-development/" tabindex="-1">2D Oyun Geliştirme</a>
<a data-id="4790" href="/topic/blender/" tabindex="-1">Blender</a>
</div>
<div data-id="10" class="js-side-nav-popular-topics">
<a data-id="52458" href="/topic/google-flutter/" tabindex="-1">Google Flutter</a>
<a data-id="6292" href="/topic/ios-development/" tabindex="-1">iOS Geliştirme</a>
<a data-id="4470" href="/topic/android-development/" tabindex="-1">Android Geliştirme</a>
<a data-id="9884" href="/topic/react-native/" tabindex="-1">React Native</a>
<a data-id="37860" href="/topic/dart-programming-language/" tabindex="-1">Dart (programlama dili)</a>
<a data-id="7956" href="/topic/swift/" tabindex="-1">Swift</a>
<a data-id="13554" href="/topic/kotlin/" tabindex="-1">Kotlin</a>
<a data-id="131074" href="/topic/swiftui/" tabindex="-1">SwiftUI</a>
<a data-id="37800" href="/topic/app-development/" tabindex="-1">Uygulama Geliştirme</a>
</div>
<div data-id="24" class="js-side-nav-popular-topics">
<a data-id="7898" href="/topic/stock-options/" tabindex="-1">Hisse Senedi Opsiyonları</a>
<a data-id="4328" href="/topic/accounting/" tabindex="-1">Muhasebe</a>
<a data-id="35138" href="/topic/fintech/" tabindex="-1">Finans Teknolojisi</a>
<a data-id="5868" href="/topic/forex/" tabindex="-1">Forex İşlemleri</a>
</div>
<div data-id="110" class="js-side-nav-popular-topics">
<a data-id="6020" href="/topic/graphic-design/" tabindex="-1">Grafik Tasarım</a>
<a data-id="5494" href="/topic/drawing/" tabindex="-1">Çizim</a>
<a data-id="4402" href="/topic/photoshop/" tabindex="-1">Adobe Photoshop</a>
<a data-id="4394" href="/topic/adobe-illustrator/" tabindex="-1">Adobe Illustrator</a>
<a data-id="8592" href="/topic/canva/" tabindex="-1">Canva</a>
<a data-id="48410" href="/topic/procreate-ipad-app/" tabindex="-1">Procreate Dijital İllüstrasyon Uygulaması</a>
<a data-id="5434" href="/topic/digital-painting/" tabindex="-1">Dijital Boyama</a>
<a data-id="33938" href="/topic/design-theory/" tabindex="-1">Tasarım Teorisi</a>
<a data-id="4396" href="/topic/indesign/" tabindex="-1">Adobe InDesign</a>
</div>
<div data-id="142" class="js-side-nav-popular-topics">
<a data-id="10684" href="/topic/life-coaching/" tabindex="-1">Yaşam Koçluğu Eğitimi</a>
<a data-id="6910" href="/topic/neuro-linguistic-programming/" tabindex="-1">Nörolinguistik Programlama</a>
<a data-id="7138" href="/topic/personal-development/" tabindex="-1">Personal Development</a>
<a data-id="15374" href="/topic/personal-transformation/" tabindex="-1">Kişisel Gelişim</a>
<a data-id="23948" href="/topic/sound-therapy/" tabindex="-1">Ses Terapisi</a>
<a data-id="5604" href="/topic/emotional-intelligence/" tabindex="-1">Duygusal Zeka</a>
<a data-id="6770" href="/topic/mindfulness/" tabindex="-1">Mindfulness</a>
<a data-id="7368" href="/topic/public-speaking/" tabindex="-1">Topluluk Önünde Konuşma</a>
<a data-id="32062" href="/topic/law-of-attraction/" tabindex="-1">Dışavurum ve Çekim Yasası</a>
</div>
<div data-id="26" class="js-side-nav-popular-topics">
<a data-id="4882" href="/topic/business-fundamentals/" tabindex="-1">İşletme Temel Kuralları</a>
<a data-id="5654" href="/topic/entrepreneurship/" tabindex="-1">Girişimciliğin Temelleri</a>
<a data-id="5874" href="/topic/freelancing/" tabindex="-1">Serbest Çalışma</a>
<a data-id="4898" href="/topic/business-strategy/" tabindex="-1">İş Stratejisi</a>
<a data-id="158002" href="/topic/chatgpt/" tabindex="-1">ChatGPT</a>
<a data-id="7888" href="/topic/startup/" tabindex="-1">Yeni Kurulan İşletme</a>
<a data-id="4894" href="/topic/business-plan/" tabindex="-1">İş Planı</a>
<a data-id="6992" href="/topic/online-business/" tabindex="-1">Online Çalışma</a>
<a data-id="6114" href="/topic/home-business/" tabindex="-1">Evden Çalışma</a>
</div>
<div data-id="62" class="js-side-nav-popular-topics">
<a data-id="5430" href="/topic/digital-marketing/" tabindex="-1">Dijital Pazarlama</a>
<a data-id="158002" href="/topic/chatgpt/" tabindex="-1">ChatGPT</a>
<a data-id="7788" href="/topic/social-media-marketing/" tabindex="-1">Sosyal Medya Pazarlama</a>
<a data-id="6630" href="/topic/marketing-strategy/" tabindex="-1">Pazarlama Stratejisi</a>
<a data-id="6994" href="/topic/internet-marketing/" tabindex="-1">Sanal Pazarlama</a>
<a data-id="7888" href="/topic/startup/" tabindex="-1">Yeni Kurulan İşletme</a>
<a data-id="5980" href="/topic/google-analytics/" tabindex="-1">Google Analytics</a>
<a data-id="5242" href="/topic/copywriting/" tabindex="-1">Reklam yazarlığı</a>
<a data-id="7558" href="/topic/sales-funnel/" tabindex="-1">Satış Hunisi</a>
</div>
</nav>
<div class="ud-main-content">
<div class="ud-app-loader ud-component--my-courses-v3--app" data-module-id="my-courses-v3" data-module-args="{&quot;enrolled_course_count&quot;:37,&quot;google_client_id&quot;:&quot;700206021005-as1l679sch207mp70msgjhma1krf3k9q.apps.googleusercontent.com&quot;,&quot;enableLabsInPersonalPlan&quot;:false,&quot;enableAssessmentsInPersonalPlan&quot;:false,&quot;showWishlistedCourseQuickViewBox&quot;:false}">
</div>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=">
    var kotlinGrpcExampleCall = {"make_call":false};
    console && console.log('Kotlin gRPC Example call:', kotlinGrpcExampleCall);
</script>
</div>
<div class="ud-app-loader ud-component--intercom--app" data-module-id="intercom" data-module-args="{&quot;intercom_user_hash&quot;:&quot;e7dcad14d069e9e73e4cade313e512801fda6c68de59692817ab99a7811b1550&quot;}"></div>
<div class="ud-app-loader ud-component--footer--footer-container ud-footer-container" data-module-id="common/desktop" data-module-args="{&quot;hideFooterUntilContentReady&quot;:false,&quot;currentLocaleId&quot;:&quot;tr_TR&quot;,&quot;linkColumns&quot;:[[{&quot;feature_flag&quot;:&quot;footer.links.business&quot;,&quot;href&quot;:&quot;/udemy-business/?locale=tr_TR\u0026mx_pg=my-courses\u0026path=%2F\u0026ref=footer&quot;,&quot;text&quot;:&quot;Udemy Business&quot;},{&quot;feature_flag&quot;:&quot;footer.links.teach&quot;,&quot;href&quot;:&quot;/teaching/?ref=teach_footer&quot;,&quot;text&quot;:&quot;Udemy&#x27;de E\u011fitim Verin&quot;},{&quot;is_disabled&quot;:false,&quot;href&quot;:&quot;/mobile/&quot;,&quot;open_in_new_tab&quot;:true,&quot;text&quot;:&quot;Uygulamay\u0131 edinin&quot;},{&quot;feature_flag&quot;:&quot;footer.links.about&quot;,&quot;href&quot;:&quot;https://about.udemy.com/?locale=tr-tr&quot;,&quot;text&quot;:&quot;Hakk\u0131m\u0131zda&quot;},{&quot;feature_flag&quot;:&quot;footer.links.contact&quot;,&quot;href&quot;:&quot;https://about.udemy.com/company?locale=tr-tr#offices&quot;,&quot;text&quot;:&quot;\u0130leti\u015fim&quot;}],[{&quot;feature_flag&quot;:&quot;footer.links.careers&quot;,&quot;href&quot;:&quot;https://about.udemy.com/careers?locale=tr-tr&quot;,&quot;text&quot;:&quot;Kariyer&quot;},{&quot;feature_flag&quot;:&quot;footer.links.blog&quot;,&quot;href&quot;:&quot;https://blog.udemy.com/?ref=footer&quot;,&quot;text&quot;:&quot;Blog&quot;},{&quot;href&quot;:&quot;/support/&quot;,&quot;text&quot;:&quot;Yard\u0131m ve Destek&quot;},{&quot;feature_flag&quot;:&quot;footer.links.affiliates&quot;,&quot;href&quot;:&quot;/affiliate/&quot;,&quot;text&quot;:&quot;\u0130\u015f Ortakl\u0131\u011f\u0131&quot;},{&quot;is_disabled&quot;:false,&quot;href&quot;:&quot;https://investors.udemy.com&quot;,&quot;text&quot;:&quot;Yat\u0131r\u0131mc\u0131lar&quot;},{&quot;is_disabled&quot;:true,&quot;href&quot;:&quot;/terms/&quot;,&quot;text&quot;:&quot;Ko\u015fullar&quot;},{&quot;style&quot;:{&quot;display&quot;:&quot;none&quot;},&quot;data_purpose&quot;:&quot;footer-imprint-contact&quot;,&quot;href&quot;:&quot;/terms/imprint-contact/&quot;,&quot;text&quot;:&quot;Impressum Kontakt&quot;}],[{&quot;is_disabled&quot;:false,&quot;href&quot;:&quot;/terms/&quot;,&quot;text&quot;:&quot;Ko\u015fullar&quot;},{&quot;href&quot;:&quot;/terms/privacy/&quot;,&quot;text&quot;:&quot;Gizlilik politikas\u0131&quot;},{&quot;data_purpose&quot;:&quot;footer.links.cookie_preferences&quot;,&quot;style&quot;:{&quot;display&quot;:&quot;none&quot;},&quot;text&quot;:&quot;\u00c7erez ayarlar\u0131&quot;,&quot;text_us_mx&quot;:&quot;Ki\u015fisel bilgilerim sat\u0131lmas\u0131n veya payla\u015f\u0131lmas\u0131n&quot;},{&quot;href&quot;:&quot;/tr/sitemap/&quot;,&quot;text&quot;:&quot;Site haritas\u0131&quot;},{&quot;href&quot;:&quot;https://about.udemy.com/accessibility-statement?locale=tr-tr&quot;,&quot;text&quot;:&quot;Eri\u015filebilirlik beyan\u0131&quot;}]],&quot;isJpFooter&quot;:false,&quot;ufbNotice&quot;:{&quot;link&quot;:&quot;/udemy-business/?locale=tr_TR\u0026path=request-demo-mx%2F\u0026ref=footer-ad&quot;,&quot;placement&quot;:&quot;footer-ad&quot;,&quot;isOnsiteRequestDemo&quot;:false}}" data-module-priority="-10"><div data-unique-id="130" style="display:none"></div><footer class="ud-footer" data-purpose="footer"><div class="footer-section footer-section-main"><div class="links-and-language-selector"><div class="language-selector-container"><button type="button" class="ud-btn ud-btn-medium ud-btn-secondary ud-text-md language-selector-button-module--button--RSREU" data-testid="language-selector-button"><svg aria-hidden="true" focusable="false" class="ud-icon ud-icon-small ud-icon-color-neutral"><use xlink:href="#icon-language"></use></svg><span>Türkçe</span></button></div><ul class="ud-unstyled-list link-column"><li><a href="/udemy-business/?locale=tr_TR&amp;mx_pg=my-courses&amp;path=%2F&amp;ref=footer" class="link white-link ud-text-sm" target="_blank" rel="noopener">Udemy Business</a></li><li><a class="link white-link ud-text-sm" href="/teaching/?ref=teach_footer">Udemy&#x27;de Eğitim Verin</a></li><li><a class="link white-link ud-text-sm" href="/mobile/" target="_blank" rel="noopener noreferrer">Uygulamayı edinin</a></li><li><a class="link white-link ud-text-sm" href="https://about.udemy.com/?locale=tr-tr">Hakkımızda</a></li><li><a class="link white-link ud-text-sm" href="https://about.udemy.com/company?locale=tr-tr#offices">İletişim</a></li></ul><ul class="ud-unstyled-list link-column"><li><a class="link white-link ud-text-sm" href="https://about.udemy.com/careers?locale=tr-tr">Kariyer</a></li><li><a class="link white-link ud-text-sm" href="https://blog.udemy.com/?ref=footer">Blog</a></li><li><a class="link white-link ud-text-sm" href="/support/">Yardım ve Destek</a></li><li><a class="link white-link ud-text-sm" href="/affiliate/">İş Ortaklığı</a></li><li><a class="link white-link ud-text-sm" href="https://investors.udemy.com">Yatırımcılar</a></li></ul><ul class="ud-unstyled-list link-column"><li><a class="link white-link ud-text-sm" href="/terms/">Koşullar</a></li><li><a class="link white-link ud-text-sm" href="/terms/privacy/">Gizlilik politikası</a></li><li><a class="link white-link ud-text-sm" href="/tr/sitemap/">Site haritası</a></li><li><a class="link white-link ud-text-sm" href="https://about.udemy.com/accessibility-statement?locale=tr-tr">Erişilebilirlik beyanı</a></li></ul></div><div class="logo-and-copyright"><div class="logo-container" data-testid="logo-container"><a href="/" class="ud-btn ud-btn-large ud-btn-link ud-heading-md"><img src="/staticx/udemy/images/v7/logo-udemy-inverted.svg" alt="Udemy" width="91.07142857142857" height="34" loading="eager" /></a></div><div class="copyright-container ud-text-xs">© 2024 Udemy, Inc.</div></div></div></footer></div>
</div>
<div class="ud-app-loader ud-component--ui-feedback--ui-feedback" data-module-id="common/desktop" data-module-args="{&quot;uiMessages&quot;:[]}" data-module-priority="-10"></div>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript" src="/staticx/udemy/js/webpack/entry-main-manifest.ab3c0a3aff0436888f2a.js" defer></script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript" src="/staticx/udemy/js/webpack/entry-main-vendor.34a8244ac7392ee390b7.js" defer></script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript" src="/staticx/udemy/js/webpack/jsi18n-tr-tr.cb32ad49c609c7968c2f.js" defer></script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=" type="text/javascript" src="/staticx/udemy/js/webpack/entry-main.1bcb353ea1da2fd3c04b.js" defer></script>
<script nonce="/S+0kScUTlIS3zSeqd7GNO/EnWpX+aPK8NOxpjouy84=">
    window.handleCSSToggleButtonClick = function (event) {
        var target = event.currentTarget;
        var cssToggleId = target && target.dataset && target.dataset.cssToggleId;
        var input = cssToggleId && document.getElementById(cssToggleId);
        if (input) {
            if (input.dataset.type === 'checkbox') {
                input.dataset.checked = input.dataset.checked ? '' : 'checked';
            } else {
                input.dataset.checked = input.dataset.allowToggle && input.dataset.checked ? '' : 'checked';
                var radios = document.querySelectorAll('[name="' + input.dataset.name + '"]');
                for (var i = 0; i < radios.length; i++) {
                    if (radios[i] !== input) {
                        radios[i].dataset.checked = '';
                    }
                }
            }
        }
    };
    (function () {
        var cssToggleButtons = document.querySelectorAll('[data-css-toggle-id');
        for (var i = 0; i < cssToggleButtons.length; i++) {
            cssToggleButtons[i].addEventListener('click', window.handleCSSToggleButtonClick);
        }
    })();
</script>
<svg aria-hidden="true" style="position: absolute; width: 0; height: 0; overflow: hidden;" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><defs><symbol id="icon-expand-plus" viewBox="0 0 24 24"><path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" /></symbol><symbol id="icon-add-circle-solid" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm5 11h-4v4h-2v-4H7v-2h4V7h2v4h4v2z" /></symbol><symbol id="icon-close" viewBox="0 0 24 24"><path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12 19 6.41z" /></symbol><symbol id="icon-collapse-minus" viewBox="0 0 24 24"><path d="M5 11v2h14v-2H5z" /></symbol><symbol id="icon-error" viewBox="0 0 24 24"><path d="M13 13h-2V7h2v6zm-1 4.3a1.299 1.299 0 110-2.598 1.299 1.299 0 010 2.598zM15.73 3H8.27L3 8.27v7.46L8.27 21h7.46L21 15.73V8.27L15.73 3z" /></symbol><symbol id="icon-info" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z" /></symbol><symbol id="icon-loading-spinner" viewBox="0 0 24 24"><path d="M4.979 4.879l-.05.05c-3.903 3.903-3.903 10.239 0 14.142s10.239 3.903 14.142 0c3.903-3.903 3.903-10.239 0-14.142l-.152-.149-2.122 2.122a7.004 7.004 0 01.153 10.049 7.002 7.002 0 01-9.899 0 7.004 7.004 0 010-9.9l.051-.05L4.981 4.88z" /></symbol><symbol id="icon-play-overlay" viewBox="0 0 24 24"><circle cy="12" cx="12" fill="#1e1e1c" r="10" /><path d="M0 12A12 12 0 1012 0 12 12 0 000 12zm18 .137L8.4 16.8V7.2l9.6 4.937z" /></symbol><symbol id="icon-rating-star" viewBox="0 0 24 24"><path d="M12 17.27L18.18 21l-1.64-7.03L22 9.24l-7.19-.61L12 2 9.19 8.63 2 9.24l5.46 4.73L5.82 21 12 17.27z" /></symbol><symbol id="icon-success" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-4.328-4.328 1.41-1.41L10 14.17l6.333-6.333 1.41 1.42L10 17z" /></symbol><symbol id="icon-tick" viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41L9 16.17z" /></symbol><symbol id="icon-warning" viewBox="0 0 24 24"><path d="M1 21h22L12 2 1 21zm12-3h-2v-2h2v2zm0-4h-2V9h2v5z" /></symbol><symbol id="icon-wishlisted" viewBox="0 0 24 24"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z" /></symbol></defs></svg>
<svg aria-hidden="true" style="position: absolute; width: 0; height: 0; overflow: hidden;" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><defs><symbol id="icon-article" viewBox="0 0 24 24"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zM6 20V4h7v5h5v11H6z" /></symbol><symbol id="icon-bar-chart" viewBox="0 0 24 24"><path d="M5 9.2h3V19H5V9.2zM10.6 5h2.8v14h-2.8V5zm5.6 8H19v6h-2.8v-6z" /></symbol><symbol id="icon-cart" viewBox="0 0 24 24"><path d="M15.55 13c.75 0 1.41-.41 1.75-1.03l3.58-6.49A.996.996 0 0020.01 4H5.21l-.94-2H1v2h2l3.6 7.59-1.35 2.44C4.52 15.37 5.48 17 7 17h12v-2H7l1.1-2h7.45zM6.16 6h12.15l-2.76 5H8.53L6.16 6zM7 18c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2-.9-2-2-2zm10 0c-1.1 0-1.99.9-1.99 2s.89 2 1.99 2 2-.9 2-2-.9-2-2-2z" /></symbol><symbol id="icon-cloud" viewBox="0 0 24 24"><path d="M19.35 10.04A7.49 7.49 0 0012 4C9.11 4 6.6 5.64 5.35 8.04A5.994 5.994 0 000 14c0 3.31 2.69 6 6 6h13c2.76 0 5-2.24 5-5 0-2.64-2.05-4.78-4.65-4.96z" /></symbol><symbol id="icon-code" viewBox="0 0 24 24"><path d="M9.4 16.6L4.8 12l4.6-4.6L8 6l-6 6 6 6 1.4-1.4zm5.2 0l4.6-4.6-4.6-4.6L16 6l6 6-6 6-1.4-1.4z" /></symbol><symbol id="icon-collapse" viewBox="0 0 24 24"><path d="M7.41 15.41L12 10.83l4.59 4.58L18 14l-6-6-6 6 1.41 1.41z" /></symbol><symbol id="icon-delete" viewBox="0 0 24 24"><path d="M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z" /></symbol><symbol id="icon-empty-course-image" fill="none" viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg"><rect fill="#dcdacb" height="32" rx="2" width="32" /><path d="M12.667 10.166v11.667L21.833 16z" fill="#73726c" /></symbol><symbol id="icon-expand" viewBox="0 0 24 24"><path d="M16.59 8.59L12 13.17 7.41 8.59 6 10l6 6 6-6-1.41-1.41z" /></symbol><symbol id="icon-filter" viewBox="0 0 24 24"><path d="M10 18h4v-2h-4v2zM3 6v2h18V6H3zm3 7h12v-2H6v2z" /></symbol><symbol id="icon-gift" viewBox="0 0 24 24"><path d="M20 6h-2.18c.11-.31.18-.65.18-1a2.996 2.996 0 00-5.5-1.65l-.5.67-.5-.68C10.96 2.54 10.05 2 9 2 7.34 2 6 3.34 6 5c0 .35.07.69.18 1H4c-1.11 0-1.99.89-1.99 2L2 19c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2zm-5-2c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zM9 4c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zm11 15H4v-2h16v2zm0-5H4V8h5.08L7 10.83 8.62 12 12 7.4l3.38 4.6L17 10.83 14.92 8H20v6z" /></symbol><symbol id="icon-info-outline" viewBox="0 0 24 24"><path d="M11 9h2V7h-2v2zm1 11c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm0-18a10.01 10.01 0 00-7.071 2.929A10.001 10.001 0 1012 2zm-1 15h2v-6h-2v6z" /></symbol><symbol id="icon-labs" viewBox="0 0 24 24"><path d="M5 19a1 1 0 001 1h12a1 1 0 001-1c0-.21-.07-.41-.18-.57L13 8.35V4h-2v4.35L5.18 18.43c-.11.16-.18.36-.18.57m1 3a3 3 0 01-3-3c0-.6.18-1.16.5-1.63L9 7.81V6a1 1 0 01-1-1V4a2 2 0 012-2h4a2 2 0 012 2v1a1 1 0 01-1 1v1.81l5.5 9.56c.32.47.5 1.03.5 1.63a3 3 0 01-3 3H6m7-6l1.34-1.34L16.27 18H7.73l2.66-4.61L13 16m-.5-4a.5.5 0 01.5.5.5.5 0 01-.5.5.5.5 0 01-.5-.5.5.5 0 01.5-.5z" /></symbol><symbol id="icon-language" viewBox="0 0 24 24"><path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zm6.93 6h-2.95a15.65 15.65 0 00-1.38-3.56A8.03 8.03 0 0118.92 8zM12 4.04c.83 1.2 1.48 2.53 1.91 3.96h-3.82c.43-1.43 1.08-2.76 1.91-3.96zM4.26 14C4.1 13.36 4 12.69 4 12s.1-1.36.26-2h3.38c-.08.66-.14 1.32-.14 2s.06 1.34.14 2H4.26zm.82 2h2.95c.32 1.25.78 2.45 1.38 3.56A7.987 7.987 0 015.08 16zm2.95-8H5.08a7.987 7.987 0 014.33-3.56A15.65 15.65 0 008.03 8zM12 19.96c-.83-1.2-1.48-2.53-1.91-3.96h3.82c-.43 1.43-1.08 2.76-1.91 3.96zM14.34 14H9.66c-.09-.66-.16-1.32-.16-2s.07-1.35.16-2h4.68c.09.65.16 1.32.16 2s-.07 1.34-.16 2zm.25 5.56c.6-1.11 1.06-2.31 1.38-3.56h2.95a8.03 8.03 0 01-4.33 3.56zM16.36 14c.08-.66.14-1.32.14-2s-.06-1.34-.14-2h3.38c.16.64.26 1.31.26 2s-.1 1.36-.26 2h-3.38z" /></symbol><symbol id="icon-marketing" viewBox="0 0 48 48"><path fill-rule="evenodd" clip-rule="evenodd" d="M40.372 4.644v2.981h2.983a.645.645 0 110 1.29h-3.628a.645.645 0 01-.645-.645V4.644a.645.645 0 011.29 0zm1.21 6.044a.646.646 0 00-.645-.646h-2.982v-2.98a.646.646 0 10-1.29 0v3.358l-1.077 1.077a18.723 18.723 0 00-12.8-5.05C12.427 6.448 4 14.872 4 25.225 4 35.577 12.428 44 22.787 44c10.36 0 18.788-8.424 18.788-18.777 0-4.952-1.931-9.457-5.074-12.815l1.074-1.076h3.362a.645.645 0 00.645-.645v.001zM22.786 42.71c-9.648 0-17.497-7.844-17.497-17.487 0-9.642 7.85-17.486 17.497-17.486a17.43 17.43 0 0111.89 4.673l-3.043 3.045c-2.344-2.123-5.442-3.428-8.847-3.428-7.282 0-13.206 5.92-13.206 13.196 0 7.278 5.925 13.198 13.206 13.198 7.282 0 13.206-5.92 13.206-13.198 0-3.41-1.313-6.513-3.445-8.857l3.041-3.044a17.417 17.417 0 014.695 11.902c0 9.642-7.849 17.486-17.497 17.486zm.458-17.03a.645.645 0 01-.912-.912l4.447-4.452a6.301 6.301 0 00-3.992-1.421c-3.491 0-6.332 2.839-6.332 6.328 0 3.489 2.841 6.329 6.332 6.329a6.339 6.339 0 006.333-6.33 6.293 6.293 0 00-1.428-3.996l-4.448 4.453v.001zm-.458-8.074c-4.204 0-7.624 3.418-7.624 7.618s3.42 7.62 7.624 7.62 7.623-3.418 7.623-7.62c0-1.8-.64-3.541-1.805-4.912l3.032-3.033a11.838 11.838 0 013.066 7.944c0 6.565-5.345 11.907-11.915 11.907-6.569 0-11.914-5.343-11.914-11.907 0-6.566 5.345-11.906 11.914-11.906 3.05 0 5.826 1.16 7.936 3.049L27.692 19.4a7.595 7.595 0 00-4.906-1.793v-.001z" /></symbol><symbol id="icon-menu" viewBox="0 0 24 24"><path d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z" /></symbol><symbol id="icon-more" viewBox="0 0 24 24"><path d="M12 8c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm0 2c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm0 6c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z" /></symbol><symbol id="icon-next" viewBox="0 0 24 24"><path d="M8.59 7.41L13.17 12l-4.58 4.59L10 18l6-6-6-6-1.41 1.41z" /></symbol><symbol id="icon-notification" viewBox="0 0 24 24"><path d="M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2zm6-6v-5c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.64 5.36 6 7.92 6 11v5l-2 2v1h16v-1zm-2 1H8v-6c0-2.48 1.51-4.5 4-4.5s4 2.02 4 4.5z" /></symbol><symbol id="icon-offer" viewBox="0 0 24 24"><path d="M21.41 11.58l-9-9C12.05 2.22 11.55 2 11 2H4c-1.1 0-2 .9-2 2v7c0 .55.22 1.05.59 1.42l9 9c.36.36.86.58 1.41.58.55 0 1.05-.22 1.41-.59l7-7c.37-.36.59-.86.59-1.41 0-.55-.23-1.06-.59-1.42zM5.5 7C4.67 7 4 6.33 4 5.5S4.67 4 5.5 4 7 4.67 7 5.5 6.33 7 5.5 7z" /></symbol><symbol id="icon-open-in-new" viewBox="0 0 24 24"><path d="M19 19H5V5h7V3H5a2 2 0 00-2 2v14a2 2 0 002 2h14c1.1 0 2-.9 2-2v-7h-2v7zM14 3v2h3.59l-9.83 9.83 1.41 1.41L19 6.41V10h2V3h-7z" /></symbol><symbol id="icon-people" viewBox="0 0 24 24"><path d="M16 10c1.66 0 2.99-1.34 2.99-3S17.66 4 16 4c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 4 8 4C6.34 4 5 5.34 5 7s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V20h14v-4.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V20h6v-4.5c0-2.33-4.67-3.5-7-3.5z" /></symbol><symbol id="icon-person" viewBox="0 0 24 24"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z" /></symbol><symbol id="icon-play" viewBox="0 0 24 24"><path d="M2 12c0 5.525 4.475 10 10 10s10-4.475 10-10S17.525 2 12 2 2 6.475 2 12zm15 .114L9 16V8l8 4.114z" /></symbol><symbol id="icon-previous" viewBox="0 0 24 24"><path d="M15.41 16.59L10.83 12l4.58-4.59L14 6l-6 6 6 6 1.41-1.41z" /></symbol><symbol id="icon-schedule" viewBox="0 0 24 24"><path d="M11 7h1.5v5.25l4.5 2.67-.75 1.23L11 13V7z" /><path fill-rule="evenodd" clip-rule="evenodd" d="M2 12C2 6.48 6.47 2 11.99 2 17.52 2 22 6.48 22 12s-4.48 10-10.01 10C6.47 22 2 17.52 2 12zm2 0c0 4.42 3.58 8 8 8s8-3.58 8-8-3.58-8-8-8-8 3.58-8 8z" /></symbol><symbol id="icon-search" viewBox="0 0 24 24"><path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0016 9.5 6.5 6.5 0 109.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z" /></symbol><symbol id="icon-security" viewBox="0 0 24 24"><path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm0 10.99h7c-.53 4.12-3.28 7.79-7 8.94V12H5V6.3l7-3.11v8.8z" /></symbol><symbol id="icon-server" viewBox="0 0 24 24"><path d="M20 13H4c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h16c.55 0 1-.45 1-1v-6c0-.55-.45-1-1-1zM7 19c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2zM20 3H4c-.55 0-1 .45-1 1v6c0 .55.45 1 1 1h16c.55 0 1-.45 1-1V4c0-.55-.45-1-1-1zM7 9c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z" /></symbol><symbol id="icon-trending-flame" viewBox="0 0 24 24"><path d="m19.48 12.35c-1.57-4.08-7.16-4.3-5.81-10.23.1-.44-.37-.78-.75-.55-3.63 2.14-6.24 6.43-4.05 12.05.18.46-.36.89-.75.59-1.81-1.37-2-3.34-1.84-4.75.06-.52-.62-.77-.91-.34-.68 1.04-1.37 2.72-1.37 5.25.38 5.6 5.11 7.32 6.81 7.54 2.43.31 5.06-.14 6.95-1.87 2.08-1.93 2.84-5.01 1.72-7.69zm-9.28 5.03c1.44-.35 2.18-1.39 2.38-2.31.33-1.43-.96-2.83-.09-5.09.33 1.87 3.27 3.04 3.27 5.08.08 2.53-2.66 4.7-5.56 2.32z" /></symbol><symbol id="icon-trending-graph" viewBox="0 0 24 24"><path d="m16 6 2.29 2.29-4.88 4.88-4-4-7.41 7.42 1.41 1.41 6-6 4 4 6.3-6.29 2.29 2.29v-6z" /></symbol></defs></svg>
<svg aria-hidden="true" style="position: absolute; width: 0; height: 0; overflow: hidden;" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><defs></defs></svg>
<svg aria-hidden="true" style="position: absolute; width: 0; height: 0; overflow: hidden;" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><defs><symbol id="icon-access-time" viewBox="0 0 24 24"><path d="M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8z" /><path d="M12.5 7H11v6l5.25 3.15.75-1.23-4.5-2.67z" /></symbol><symbol id="icon-add-to-group" viewBox="0 0 24 24"><path d="M4 6H2v14c0 1.1.9 2 2 2h14v-2H4V6zm16-4H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm-1 9h-4v4h-2v-4H9V9h4V5h2v4h4v2z" /></symbol><symbol id="icon-alarm" viewBox="0 0 24 24"><path d="M22 5.72l-4.6-3.86-1.29 1.53 4.6 3.86L22 5.72zM7.88 3.39L6.6 1.86 2 5.71l1.29 1.53 4.59-3.85zM12.5 8H11v6l4.75 2.85.75-1.23-4-2.37V8zM12 4c-4.97 0-9 4.03-9 9s4.02 9 9 9a9 9 0 000-18zm0 16c-3.87 0-7-3.13-7-7s3.13-7 7-7 7 3.13 7 7-3.13 7-7 7z" /></symbol><symbol id="icon-apple" viewBox="0 0 20 20"><path fill-rule="evenodd" clip-rule="evenodd" d="M10.313 4.583c.928 0 2.09-.544 2.77-1.284.627-.672 1.084-1.598 1.084-2.524 0-.127-.013-.254-.04-.358-1.031.034-2.272.602-3.004 1.365C10.55 2.372 10 3.3 10 4.236c0 .139.026.278.04.324.065.012.169.023.274.023zm6.715 2.697c-1.24-1.816-3.127-1.863-3.647-1.863-.816 0-1.536.29-2.14.533-.435.176-.81.327-1.117.327-.34 0-.728-.16-1.16-.337-.545-.223-1.16-.476-1.838-.476C4.836 5.464 2.5 7.4 2.5 11.02c0 2.27.862 4.646 1.924 6.187.92 1.302 1.723 2.377 2.867 2.377.542 0 .942-.174 1.362-.357.467-.204.961-.42 1.707-.42.736 0 1.18.2 1.611.395.405.182.798.358 1.41.358 1.24 0 2.077-1.158 2.856-2.305.885-1.314 1.251-2.58 1.263-2.652-.07-.024-2.455-1.003-2.455-3.774 0-2.235 1.626-3.31 1.937-3.516l.046-.032z" /></symbol><symbol id="icon-assessment" viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z" /></symbol><symbol id="icon-assignment" viewBox="0 0 24 24"><path d="M19 3h-4.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-7 0c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zm2 14H7v-2h7v2zm3-4H7v-2h10v2zm0-4H7V7h10v2z" /></symbol><symbol id="icon-audio" viewBox="0 0 24 24"><path d="M12 14c1.66 0 2.99-1.34 2.99-3L15 5c0-1.66-1.34-3-3-3S9 3.34 9 5v6c0 1.66 1.34 3 3 3zm5.3-3c0 3-2.54 5.1-5.3 5.1S6.7 14 6.7 11H5c0 3.41 2.72 6.23 6 6.72V21h2v-3.28c3.28-.48 6-3.3 6-6.72h-1.7z" /></symbol><symbol id="icon-bookmark-outline" viewBox="0 0 24 24"><path d="M0 0h24v24H0V0z" fill="none" /><path d="M17 3H7c-1.1 0-2 .9-2 2v16l7-3 7 3V5c0-1.1-.9-2-2-2zm0 15l-5-2.18L7 18V5h10v13z" /></symbol><symbol id="icon-calendar-30" viewBox="0 0 24 24"><path clip-rule="evenodd" d="M18 14.486C18 16.65 16.925 18 15.15 18s-2.854-1.341-2.854-3.51c0-2.162 1.09-3.49 2.854-3.49S18 12.323 18 14.486zm-4.204.005c0 1.522.514 2.386 1.354 2.386s1.35-.86 1.35-2.386c0-1.514-.514-2.368-1.35-2.368-.83 0-1.354.86-1.354 2.368z" fill-rule="evenodd" /><path d="M8.698 14.927h-.87v-1.012h.855c.675 0 1.13-.38 1.13-.933 0-.543-.406-.9-1.14-.9-.684 0-1.138.385-1.177.97h-1.36c.055-1.24 1.071-2.047 2.601-2.047 1.467 0 2.469.714 2.469 1.787 0 .821-.592 1.416-1.457 1.564v.028c1.051.083 1.73.687 1.73 1.615 0 1.203-1.148 2.001-2.776 2.001C7.11 18 6.068 17.17 6 15.934h1.413c.044.567.532.938 1.31.938.738 0 1.256-.395 1.256-.96 0-.614-.484-.985-1.28-.985z" /><path clip-rule="evenodd" d="M19 3h1c1.1 0 2 .9 2 2v16c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V5c0-1.1.9-2 2-2h1V1h2v2h10V1h2zM4 21h16V8H4z" fill-rule="evenodd" /></symbol><symbol id="icon-calendar-arrow-right" viewBox="0 0 24 24"><path d="M19 3h-1V1h-2v2H8V1H6v2H5c-1.11 0-2 .89-2 2v14a2 2 0 002 2h14c1.1 0 2-.9 2-2V5a2 2 0 00-2-2m0 16H5V8h14v11m-7-2v-2H8v-3h4v-2l4 3.5-4 3.5z" /></symbol><symbol id="icon-cancel" viewBox="0 0 24 24"><path d="M12 2C6.47 2 2 6.47 2 12s4.47 10 10 10 10-4.47 10-10S17.53 2 12 2zm5 13.59L15.59 17 12 13.41 8.41 17 7 15.59 10.59 12 7 8.41 8.41 7 12 10.59 15.59 7 17 8.41 13.41 12 17 15.59z" /></symbol><symbol id="icon-download-file" viewBox="0 0 24 24"><path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z" /></symbol><symbol id="icon-duplicate" viewBox="0 0 24 24"><path d="M4 6H2v14c0 1.1.9 2 2 2h14v-2H4V6zm16-4H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2z" /></symbol><symbol id="icon-edit" viewBox="0 0 24 24"><path d="M3 17.25V21h3.75L17.81 9.94l-3.75-3.75L3 17.25zM20.71 7.04a.996.996 0 000-1.41l-2.34-2.34a.996.996 0 00-1.41 0l-1.83 1.83 3.75 3.75 1.83-1.83z" /></symbol><symbol id="icon-email" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z" /></symbol><symbol id="icon-facebook-messenger" viewBox="0 0 24 24"><path d="M12 2C6.5 2 2 6.14 2 11.25c0 2.88 1.42 5.45 3.65 7.15l.06 3.6 3.45-1.88-.03-.01c.91.25 1.87.39 2.87.39 5.5 0 10-4.14 10-9.25S17.5 2 12 2zm1.03 12.41l-2.49-2.63-5.04 2.63 5.38-5.63 2.58 2.47 4.85-2.47-5.28 5.63z" /></symbol><symbol id="icon-facebook-workplace" viewBox="0 0 24 24"><path d="M20.773 16.536c-.29.345-.82.88-1.655.88-1.18 0-1.56-.844-1.919-1.737l-1.772-4.333-1.765 4.333c-.301.74-.627 1.738-1.92 1.738s-1.621-.999-1.922-1.738L6.843 8.39h2.51l2.389 6 1.78-4.373c.282-.693.617-1.737 1.903-1.737s1.624 1.045 1.907 1.737l1.936 4.735a7.346 7.346 0 001.234-4.086c0-4.092-3.333-7.409-7.446-7.409-2.347 0-4.554.91-6.213 2.561A8.663 8.663 0 004.27 12c0 2.335.915 4.53 2.575 6.182a8.76 8.76 0 006.217 2.561c.806 0 1.605-.11 2.375-.323v2.323a11.19 11.19 0 01-2.375.257A11.062 11.062 0 012.87 16.282 10.882 10.882 0 012 12a10.96 10.96 0 013.238-7.778 11.02 11.02 0 013.514-2.357A11.03 11.03 0 0113.056 1c5.365 0 9.714 4.327 9.714 9.665a9.592 9.592 0 01-1.997 5.871z" /></symbol><symbol id="icon-facebook" viewBox="0 0 24 24"><path d="m23 12.0672c0-6.11224-4.9249-11.0672-11-11.0672-6.07514 0-11 4.95496-11 11.0672 0 5.524 4.02254 10.1025 9.2813 10.9328v-7.7337h-2.79301v-3.1991h2.79301v-2.43822c0-2.77373 1.6422-4.30584 4.1548-4.30584 1.2035 0 2.4623.21615 2.4623.21615v2.72358h-1.387c-1.3665 0-1.7926.85311-1.7926 1.72833v2.076h3.0507l-.4877 3.1991h-2.5631v7.7337c5.2588-.8303 9.2813-5.4088 9.2813-10.9328" /></symbol><symbol id="icon-flaky" viewBox="0 0 24 24"><path d="M14.05 17.58l-.01.01-2.4-2.4 1.06-1.06 1.35 1.35L16.54 13l1.06 1.06-3.54 3.54-.01-.02zM12 2C6.5 2 2 6.5 2 12s4.5 10 10 10 10-4.5 10-10S17.5 2 12 2zM7.34 6.28l1.41 1.41 1.41-1.41 1.06 1.06-1.41 1.41 1.41 1.41-1.06 1.06-1.41-1.41-1.41 1.41-1.06-1.06 1.41-1.41-1.41-1.41 1.06-1.06zM12 20c-2.2 0-4.2-.9-5.7-2.3L17.7 6.3C19.1 7.8 20 9.8 20 12c0 4.4-3.6 8-8 8z" fill-rule="evenodd" /></symbol><symbol id="icon-folder" viewBox="0 0 24 24"><path d="M10 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2h-8l-2-2z" /></symbol><symbol id="icon-google" viewBox="0 0 20 20"><path fill-rule="evenodd" clip-rule="evenodd" d="M19.6 10.227c0-.709-.064-1.39-.182-2.045H10v3.868h5.382a4.6 4.6 0 01-1.996 3.018v2.51h3.232c1.891-1.742 2.982-4.305 2.982-7.35z" fill="#4285F4" /><path fill-rule="evenodd" clip-rule="evenodd" d="M10 20c2.7 0 4.963-.895 6.618-2.423l-3.232-2.509c-.895.6-2.04.955-3.386.955-2.605 0-4.81-1.76-5.596-4.123h-3.34v2.59A9.996 9.996 0 0010 20z" fill="#34A853" /><path fill-rule="evenodd" clip-rule="evenodd" d="M4.405 11.9c-.2-.6-.314-1.24-.314-1.9 0-.66.114-1.3.314-1.9V5.51H1.064A9.996 9.996 0 000 10c0 1.614.386 3.14 1.064 4.49l3.34-2.59z" fill="#FBBC05" /><path fill-rule="evenodd" clip-rule="evenodd" d="M10 3.977c1.468 0 2.786.505 3.823 1.496l2.868-2.868C14.959.99 12.695 0 10 0 6.09 0 2.709 2.24 1.063 5.51L4.404 8.1C5.191 5.736 7.395 3.977 10 3.977z" fill="#EA4335" /></symbol><symbol id="icon-here-tick" viewBox="0 0 24 24"><path d="M19 1H5c-1.1 0-1.99.9-1.99 2L3 15.93c0 .69.35 1.3.88 1.66L12 23l8.11-5.41c.53-.36.88-.97.88-1.66L21 3c0-1.1-.9-2-2-2zm-9 15l-5-5 1.41-1.41L10 13.17l7.59-7.59L19 7l-9 9z" /></symbol><symbol id="icon-lifetime" viewBox="0 0 24 24"><path d="M18.6 6.62c-1.44 0-2.8.56-3.77 1.53L12 10.66 10.48 12h.01L7.8 14.39c-.64.64-1.49.99-2.4.99-1.87 0-3.39-1.51-3.39-3.38S3.53 8.62 5.4 8.62c.91 0 1.76.35 2.44 1.03l1.13 1 1.51-1.34L9.22 8.2A5.37 5.37 0 005.4 6.62C2.42 6.62 0 9.04 0 12s2.42 5.38 5.4 5.38c1.44 0 2.8-.56 3.77-1.53l2.83-2.5.01.01L13.52 12h-.01l2.69-2.39c.64-.64 1.49-.99 2.4-.99 1.87 0 3.39 1.51 3.39 3.38s-1.52 3.38-3.39 3.38c-.9 0-1.76-.35-2.44-1.03l-1.14-1.01-1.51 1.34 1.27 1.12a5.386 5.386 0 003.82 1.57c2.98 0 5.4-2.41 5.4-5.38s-2.42-5.37-5.4-5.37z" /></symbol><symbol id="icon-link" viewBox="0 0 24 24"><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76 0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71 0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71 0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76 0 5-2.24 5-5s-2.24-5-5-5z" /></symbol><symbol id="icon-linkedin" viewBox="0 0 24 24"><path d="M19 3a2 2 0 012 2v14a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h14zm-.5 15.5v-5.3a3.263 3.263 0 00-3.26-3.26c-.85 0-1.84.52-2.32 1.3v-1.11h-2.79v8.37h2.79v-4.93c0-.77.62-1.4 1.39-1.4a1.4 1.4 0 011.4 1.4v4.93h2.79zM6.88 8.56a1.68 1.68 0 001.68-1.68c0-.93-.75-1.69-1.68-1.69a1.69 1.69 0 00-1.69 1.69c0 .93.76 1.68 1.69 1.68zm1.39 9.94v-8.37H5.5v8.37h2.77z" /></symbol><symbol id="icon-list-alt" viewBox="0 0 24 24"><path d="M19 5v14H5V5h14m1.1-2H3.9c-.5 0-.9.4-.9.9v16.2c0 .4.4.9.9.9h16.2c.4 0 .9-.5.9-.9V3.9c0-.5-.5-.9-.9-.9zM11 7h6v2h-6V7zm0 4h6v2h-6v-2zm0 4h6v2h-6zM7 7h2v2H7zm0 4h2v2H7zm0 4h2v2H7z" /></symbol><symbol id="icon-minus-outline" viewBox="0 0 24 24"><path d="M12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12C22 14.5273 21.0575 16.9101 19.388 18.7393C17.5057 20.8018 14.848 22 12 22ZM12 20C14.2799 20 16.4035 19.0426 17.9108 17.3911C19.2471 15.9268 20 14.0235 20 12C20 7.58172 16.4183 4 12 4C7.58172 4 4 7.58172 4 12C4 16.4183 7.58172 20 12 20ZM8 11C7.44772 11 7 11.4477 7 12C7 12.5523 7.44772 13 8 13H16C16.5523 13 17 12.5523 17 12C17 11.4477 16.5523 11 16 11H8Z" /></symbol><symbol id="icon-ms-teams" viewBox="0 0 24 24"><path d="M19.2 8.4a2.4 2.4 0 1 0 0-4.8 2.4 2.4 0 0 0 0 4.8Zm0-3.6a1.2 1.2 0 1 1 0 2.4 1.2 1.2 0 0 1 0-2.4Zm1.416 4.8H14.4v-.216a3.6 3.6 0 1 0-4.8-3.396h-6a1.2 1.2 0 0 0-1.2 1.2v9.6a1.2 1.2 0 0 0 1.2 1.2h3.9a5.4 5.4 0 0 0 9.924.624 3.288 3.288 0 0 0 4.176-3.156v-4.872a.984.984 0 0 0-.984-.984Zm-7.416-6a2.4 2.4 0 0 1 1.2 4.476V7.2A1.2 1.2 0 0 0 13.2 6h-2.4a2.4 2.4 0 0 1 2.4-2.4Zm3.6 12.6A4.2 4.2 0 0 1 8.796 18H13.2a1.2 1.2 0 0 0 1.2-1.2v-6h2.4v5.4Zm3.6-.732a2.088 2.088 0 0 1-2.088 2.076 2.007 2.007 0 0 1-.468-.06c.102-.42.154-.852.156-1.284v-5.4h2.4v4.668ZM8.1 15.9v-6H5.7V8.1h6.6v1.8H9.9v6H8.1Z" /></symbol><symbol id="icon-new" viewBox="0 0 24 24"><path d="M23 12l-2.44-2.78.34-3.68-3.61-.82-1.89-3.18L12 3 8.6 1.54 6.71 4.72l-3.61.81.34 3.68L1 12l2.44 2.78-.34 3.69 3.61.82 1.89 3.18L12 21l3.4 1.46 1.89-3.18 3.61-.82-.34-3.68L23 12zm-10 5h-2v-2h2v2zm0-4h-2V7h2v6z" /></symbol><symbol id="icon-outlook" viewBox="0 0 20 20"><g clip-path="url(#clip0)" fill="#0072C6"><path d="M12.516 4.24v3.912l1.382.861c.037.01.116.012.152 0L20 5.046c0-.47-.444-.806-.693-.806h-6.79z" /><path d="M12.516 9.612l1.262.857c.178.13.392 0 .392 0-.214.13 5.83-3.841 5.83-3.841v7.19c0 .783-.506 1.11-1.076 1.11h-6.408V9.613zM5.985 7.808c-.43 0-.773.2-1.026.6-.253.398-.38.926-.38 1.583 0 .667.127 1.195.38 1.582.253.389.585.582.995.582.423 0 .759-.189 1.007-.566.247-.377.372-.9.372-1.57 0-.698-.12-1.24-.361-1.63-.24-.387-.57-.58-.987-.58z" /><path d="M0 2.254v15.305L11.772 20V0L0 2.254zm7.877 10.24c-.497.647-1.146.972-1.946.972-.78 0-1.415-.314-1.907-.942-.49-.628-.736-1.445-.736-2.453 0-1.064.249-1.925.748-2.583.499-.657 1.16-.986 1.982-.986.777 0 1.406.314 1.885.944.48.63.72 1.458.72 2.488 0 1.059-.248 1.912-.746 2.56z" /></g><defs><clipPath id="clip0"><path fill="#fff" d="M0 0h20v20H0z" /></clipPath></defs></symbol><symbol id="icon-presentation" viewBox="0 0 24 24"><path d="M2 3h8a2 2 0 114 0h8v2h-1v11h-5.75L17 22h-2l-1.75-6h-2.5L9 22H7l1.75-6H3V5H2V3zm3 2v9h14V5H5z" /></symbol><symbol id="icon-quiz" viewBox="0 0 24 24"><path d="M11 18h2v-2h-2v2zm1-16C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm0-14c-2.21 0-4 1.79-4 4h2c0-1.1.9-2 2-2s2 .9 2 2c0 2-3 1.75-3 5h2c0-2.25 3-2.5 3-5 0-2.21-1.79-4-4-4z" /></symbol><symbol id="icon-rating-star-outline" viewBox="0 0 24 24"><path d="M12.517 16.414L12 16.102l-.517.312-4.15 2.505 1.1-4.722.138-.588-.456-.395-3.669-3.178 4.829-.41.6-.05.236-.556L12 4.563l1.89 4.457.235.555.6.051 4.829.41-3.669 3.178-.456.395.137.588 1.102 4.722-4.151-2.505z" fill="transparent" stroke="currentColor" stroke-width="2" /></symbol><symbol id="icon-saved" viewBox="0 0 24 24"><path d="M17 3H7c-1.1 0-1.99.9-1.99 2L5 21l7-3 7 3V5c0-1.1-.9-2-2-2z" /></symbol><symbol id="icon-share" viewBox="0 0 24 24"><path d="M23.25 10.75L14.5 2v5C5.75 8.25 2 14.5.75 20.75c3.125-4.375 7.5-6.375 13.75-6.375V19.5l8.75-8.75z" /></symbol><symbol id="icon-slack" viewBox="0 0 24 24"><path d="M6 15a2 2 0 11-2-2h2v2zm1 0a2 2 0 014 0v5a2 2 0 01-4 0v-5zm2-8a2 2 0 112-2v2H9zm0 1a2 2 0 010 4H4a2 2 0 110-4h5zm8 2a2 2 0 112 2h-2v-2zm-1 0a2 2 0 01-4 0V5a2 2 0 114 0v5zm-2 8a2 2 0 11-2 2v-2h2zm0-1a2 2 0 010-4h5a2 2 0 010 4h-5z" /></symbol><symbol id="icon-teach" viewBox="0 0 24 24"><path d="M20 17a2 2 0 002-2V4a2 2 0 00-2-2H9.46c.35.61.54 1.3.54 2h10v11h-9v2h9zM15 7v2H9v13H7v-6H5v6H3v-8H1.5V9a2 2 0 012-2H15zM8 4a2 2 0 11-4 0 2 2 0 014 0z" /></symbol><symbol id="icon-today" viewBox="0 0 24 24"><path d="M19 3h-1V1h-2v2H8V1H6v2H5c-1.11 0-1.99.9-1.99 2L3 19a2 2 0 002 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm0 16H5V8h14v11zM7 10h5v5H7z" /></symbol><symbol id="icon-twitter" viewBox="0 0 24 24"><path d="M22.46 6c-.77.35-1.6.58-2.46.69.88-.53 1.56-1.37 1.88-2.38-.83.5-1.75.85-2.72 1.05C18.37 4.5 17.26 4 16 4c-2.35 0-4.27 1.92-4.27 4.29 0 .34.04.67.11.98C8.28 9.09 5.11 7.38 3 4.79c-.37.63-.58 1.37-.58 2.15 0 1.49.75 2.81 1.91 3.56-.71 0-1.37-.2-1.95-.5v.03c0 2.08 1.48 3.82 3.44 4.21a4.22 4.22 0 01-1.93.07 4.28 4.28 0 004 2.98 8.521 8.521 0 01-5.33 1.84c-.34 0-.68-.02-1.02-.06C3.44 20.29 5.7 21 8.12 21 16 21 20.33 14.46 20.33 8.79c0-.19 0-.37-.01-.56.84-.6 1.56-1.36 2.14-2.23z" /></symbol><symbol id="icon-video-mashup" viewBox="0 0 24 24"><path d="M10 8v8l5-4-5-4zm9-5H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm0 16H5V5h14v14z" /></symbol><symbol id="icon-video" viewBox="0 0 24 24"><path d="M21 3H3c-1.11 0-2 .89-2 2v12a2 2 0 002 2h5v2h8v-2h5c1.1 0 1.99-.9 1.99-2L23 5a2 2 0 00-2-2zm0 14H3V5h18v12zm-5-6l-7 4V7l7 4z" /></symbol><symbol id="icon-whatsapp" viewBox="0 0 24 24"><path d="M16.75 13.96c.25.13.41.2.46.3.06.11.04.61-.21 1.18-.2.56-1.24 1.1-1.7 1.12s-.47.36-2.96-.73c-2.49-1.09-3.99-3.75-4.11-3.92s-.96-1.38-.92-2.61c.05-1.22.69-1.8.95-2.04.24-.26.51-.29.68-.26h.47c.15 0 .36-.06.55.45l.69 1.87c.06.13.1.28.01.44l-.27.41-.39.42c-.12.12-.26.25-.12.5.12.26.62 1.09 1.32 1.78.91.88 1.71 1.17 1.95 1.3.24.14.39.12.54-.04l.81-.94c.19-.25.35-.19.58-.11l1.67.88zM12 2a10.01 10.01 0 017.071 2.929A9.992 9.992 0 0122 12a10.001 10.001 0 01-15.35 8.45L2 22l1.55-4.65A10.001 10.001 0 0112 2zm0 2a8 8 0 00-8 8c0 1.72.54 3.31 1.46 4.61L4.5 19.5l2.89-.96A7.95 7.95 0 0012 20a8 8 0 100-16z" /></symbol><symbol id="icon-youtube" viewBox="0 0 24 24"><path d="M10 15l5.19-3L10 9v6zm11.56-7.83c.13.47.22 1.1.28 1.9.07.8.1 1.49.1 2.09L22 12c0 2.19-.16 3.8-.44 4.83-.25.9-.83 1.48-1.73 1.73-.47.13-1.33.22-2.65.28-1.3.07-2.49.1-3.59.1L12 19c-4.19 0-6.8-.16-7.83-.44-.9-.25-1.48-.83-1.73-1.73-.13-.47-.22-1.1-.28-1.9-.07-.8-.1-1.49-.1-2.09L2 12c0-2.19.16-3.8.44-4.83.25-.9.83-1.48 1.73-1.73.47-.13 1.33-.22 2.65-.28 1.3-.07 2.49-.1 3.59-.1L12 5c4.19 0 6.8.16 7.83.44.9.25 1.48.83 1.73 1.73z" /></symbol></defs></svg>
<div class="ud-app-loader ud-component--event-tracking--tracker-initializer" data-module-id="common/desktop" data-module-priority="-10"></div>
</body>
</html>
