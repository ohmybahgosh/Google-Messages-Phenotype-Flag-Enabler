# Google-Messages-Phenotype-Flag-Enabler
Enables a shit ton of Phenotype flags for messages, activating every test feature in the apk

## Running the script..  
This obviously requires root, and sqlite3

Put the ENABLE_PHENO_FLAGS script inside of /sdcard

Make the script executable..just simply run:  
```console
chmod +x /sdcard/ENABLE_PHENO_FLAGS  
```

Then just run:  
```console  
sh /sdcard/ENABLE_PHENO_FLAGS  
```

After it's done, open and force-close Messages several times.. Then you're golden


## Here are all the current flags being enabled in this script: 
Etouffee__enable_group_e2ee_tombstones_ui
Etouffee__enable_group_etouffee
Etouffee__enable_message_resending_full
Etouffee__enable_save_etouffee_to_telephony_setting
FastTrackCslib__enable_fast_track
ProvisioningEngineV2__enabled
bugle_phenotype__actions_use_work_manager
bugle_phenotype__allow_max_message_size_for_group
bugle_phenotype__allow_q_text_classifier_actions_in_notifications
bugle_phenotype__append_debug_info_message_details
bugle_phenotype__async_broadcast_receiver_remove_timeout_and_log
bugle_phenotype__automatically_migrate_blocked_contacts
bugle_phenotype__bcm_detailed_crash_log_on_moat
bugle_phenotype__bcm_shadow_receive_downloaded_mms_canonical_addresses
bugle_phenotype__bcm_shadow_receive_downloaded_mms_message_recipients
bugle_phenotype__bcm_shadow_receive_downloaded_mms_recipients
bugle_phenotype__bcm_shadow_receive_mms_wap_push_normalized_sender
bugle_phenotype__bcm_shadow_receive_mms_wap_push_raw_sender
bugle_phenotype__bcm_shadow_receive_mms_wap_push_thread_data_recipients
bugle_phenotype__bcm_shadow_receive_sms
bugle_phenotype__block_ditto_content_observer_if_large_updates
bugle_phenotype__bubble_conversation_refresh_account
bugle_phenotype__bug_137326709
bugle_phenotype__bug_145257547_use_media_action_sound
bugle_phenotype__bug_145539750
bugle_phenotype__bug_147950485
bugle_phenotype__bug_147950486
bugle_phenotype__bug_148337804_enable_npe_onclick_fix
bugle_phenotype__bug_148881571
bugle_phenotype__bug_149059866_phenotype_listener
bugle_phenotype__bug_150089955
bugle_phenotype__bug_150629952
bugle_phenotype__bug_150675965
bugle_phenotype__bug_151368201
bugle_phenotype__bug_153082962
bugle_phenotype__bug_153821865_broadcast_tachygram_information
bugle_phenotype__bug_154360866
bugle_phenotype__bug_154660302_enable_reclaiming_memory
bugle_phenotype__bug_155420160_log_ditto_events_to_bugle_clearcut
bugle_phenotype__bug_157652581
bugle_phenotype__bug_159720439_enable_is_composing_ditto_sender_default_callback
bugle_phenotype__bug_159911759_fetch
bugle_phenotype__bug_160756473
bugle_phenotype__bug_160756473_tag_grpc_traffic
bugle_phenotype__bug_161328181_dismiss_delete_dialog_if_no_messages_selected
bugle_phenotype__bug_161420308
bugle_phenotype__bug_161489454_enable_sequential_restore
bugle_phenotype__bug_162261317_enable_foreground_service_clearcut_logging
bugle_phenotype__bug_164486593_use_attachment_to_blobstore_uploader_worker
bugle_phenotype__bug_165096879_remote_device_loader_only_catch_status_runtime_exception
bugle_phenotype__bug_165096879_remote_instance_setup_passes_up_exception
bugle_phenotype__bug_168221060
bugle_phenotype__bug_168737211_cms_triggers_delete_conversation_on_delete_timestamp_update
bugle_phenotype__bug_169938930_signature_manager_integration
bugle_phenotype__bug_170762622_skip_data_listener_in_wearable_service
bugle_phenotype__bug_170882924_abandon_conversation_delete_on_failed_precondition
bugle_phenotype__bug_171456829_show_actionbar_after_config_change
bugle_phenotype__bug_172027493
bugle_phenotype__bug_172486984_enable_handle_conversation_status_opaque_data_update
bugle_phenotype__bug_172569191
bugle_phenotype__bug_173025790
bugle_phenotype__bug_173194234
bugle_phenotype__bug_174611609_keep_legacy_destination_normalized_for_contacts
bugle_phenotype__bug_178627097_enable_batch_message_restore
bugle_phenotype__bug_180427644_ditto_satellite_use_messageport_transport
bugle_phenotype__bug_183538828_hats_next_survey_client_logging
bugle_phenotype__bug_183634973_use_account_controller_in_conversation_activity
bugle_phenotype__bug_183634973_use_account_controller_in_home_activity
bugle_phenotype__bug_183634973_use_account_controller_in_main_activity
bugle_phenotype__bug_184269564_enable_outgoing_message_insertion_listeners
bugle_phenotype__bug_184294411
bugle_phenotype__bug_185831101_supersort_enable_primary_view_banner
bugle_phenotype__bug_185945664
bugle_phenotype__bug_186182985_use_messaging_identity_in_identity_worker_parameters
bugle_phenotype__bug_187727046_supersort_default_to_all_if_personal_is_empty
bugle_phenotype__bug_187806837_add_contacts_list_padding
bugle_phenotype__bug_190692719_fix_pin_to_top_plural_toast
bugle_phenotype__bug_191287092_enable_preferred_suggestion_score
bugle_phenotype__bug_191513431_moirai_enable_spam_reporting
bugle_phenotype__bug_192549346_apply_circular_padding
bugle_phenotype__bug_193533489_show_icon_on_work_profile
bugle_phenotype__bug_199628724_samsung_settings_index_fix
bugle_phenotype__bug_201557041_bubble_conversation_uses_default_account_selector
bugle_phenotype__bug_201639318_allow_media_metadata_extraction_from_uri_instead_of_file_descriptor
bugle_phenotype__bug_202332654_enable_vendor_ims_master_switch_broadcast
bugle_phenotype__bug_202740020_specify_order_by_for_conversations_and_messages
bugle_phenotype__bug_202997105_enable_messaging_identity_in_receive_sms_message_helper_v2
bugle_phenotype__bug_203590755_enable_mi_in_encrypted_read_notification_sender
bugle_phenotype__bug_203590782_enable_chat_endpoint_in_encrypted_file_receiver_sender
bugle_phenotype__bug_203591048_enable_mi_in_incoming_ftd_processor
bugle_phenotype__bug_203592305_enable_mi_in_contact_recipient_entry_utils
bugle_phenotype__bug_203592350_enable_mi_in_national_emergency_util
bugle_phenotype__bug_203592472_enable_mi_in_contact_util
bugle_phenotype__bug_203592545_enable_messaging_identity_in_spam_prechecker
bugle_phenotype__bug_203592690_enable_messaging_identity_in_scooby_spam_protection
bugle_phenotype__bug_20359380_enable_mi_in_database_messages
bugle_phenotype__bug_203593934_enable_mi_in_wearable_message
bugle_phenotype__bug_203593994_enable_mi_in_hidden_contacts
bugle_phenotype__bug_203594027_enable_mi_in_sync_message_batch
bugle_phenotype__bug_203594323_enable_mi_in_tachygram
bugle_phenotype__bug_203594365_enable_mi_in_sim_selection_settings_data
bugle_phenotype__bug_203594489_enable_mi_in_phone_number_record_manager
bugle_phenotype__bug_203594531_enable_mi_in_sim_messages_data
bugle_phenotype__bug_203594828_enable_messaging_identity_in_bugle_recipient_entry
bugle_phenotype__bug_203594842_enable_mi_in_v_card_request
bugle_phenotype__bug_203594851_enable_mi_in_notification_intents
bugle_phenotype__bug_203594888_enable_mi_in_update_message_verification_status_work_helper
bugle_phenotype__bug_203594972_enable_messaging_identity_in_conversation_helper
bugle_phenotype__bug_203595010_enable_mi_for_contacts_intents
bugle_phenotype__bug_203595010_enable_sub_id_in_selected_conversation
bugle_phenotype__bug_203595555_enable_mi_in_wearable_bind_service
bugle_phenotype__bug_207531482_gaia_device_pairing_nav_item_fix
bugle_phenotype__bug_207728609_gaia_esi_subtitle_overlap_with_how_it_works_link_fix
bugle_phenotype__bug_208370145_gaia_esi_handle_config_change_fix
bugle_phenotype__bug_209309856
bugle_phenotype__bug_209965112
bugle_phenotype__bug_210018916_deprecate_messages_spam_full_in_report_to_tachyon
bugle_phenotype__bug_210018916_deprecate_messages_spam_full_query_moirai
bugle_phenotype__bug_210018916_deprecate_messages_spam_full_query_report
bugle_phenotype__bug_210018916_use_dynamic_join_for_reactions_present_query
bugle_phenotype__bug_210675644
bugle_phenotype__bug_211420924
bugle_phenotype__bug_213574317_esi_how_it_works_tooltip_use_text_with_fixed_line_break
bugle_phenotype__bug_213929016_log_self_and_sub_id_in_insert_new_message_action
bugle_phenotype__bug_220887559_show_notifications_for_unread_incoming_messages_only
bugle_phenotype__bug_227137812_enable_account_ditto_welcome_fragment
bugle_phenotype__bug_228386534_enable_mi_is_emergency_phone_number
bugle_phenotype__bug_228386851_enable_mi_in_process_file_transfer_action
bugle_phenotype__bugle_participant_update_use_create_from_send_participant
bugle_phenotype__can_resend_ftd_message_as_unencrypted_from_ditto
bugle_phenotype__carrier_is_amx
bugle_phenotype__carrier_is_att
bugle_phenotype__carrier_is_tmobile
bugle_phenotype__carrier_spam_reporter_use_raw_destination
bugle_phenotype__check_server_side_text_twinned_devices
bugle_phenotype__close_navigation_menu_when_clicking_messages
bugle_phenotype__cmc_setting_search_index
bugle_phenotype__cms_create_trigger_check_for_cms_id
bugle_phenotype__cms_enable_batch_backup
bugle_phenotype__cms_fi_delete_button
bugle_phenotype__cms_match_sim_for_multi_sim
bugle_phenotype__cms_use_block_list
bugle_phenotype__colored_suggestions_enabled
bugle_phenotype__conversation_starters_enabled
bugle_phenotype__debug_heterodyne_is_1gb_memory_or_less_device_false
bugle_phenotype__debug_heterodyne_is_1gb_memory_or_less_device_true
bugle_phenotype__debug_heterodyne_is_adp_memory_none
bugle_phenotype__debug_heterodyne_is_android_go_false
bugle_phenotype__debug_heterodyne_is_android_go_true
bugle_phenotype__debug_heterodyne_is_english_locale_false
bugle_phenotype__debug_heterodyne_is_english_locale_true
bugle_phenotype__debug_heterodyne_is_gmscore_memory_1gb_plus
bugle_phenotype__debug_heterodyne_is_new_locale_capitalization
bugle_phenotype__debug_heterodyne_is_platform_l_above_false
bugle_phenotype__debug_heterodyne_is_platform_l_above_true
bugle_phenotype__debug_menu_default_available
bugle_phenotype__determine_single_reg_support_in_chat_transport_controller_using_acs_config
bugle_phenotype__directly_intent_into_premium_sms_setting_in_s
bugle_phenotype__disable_marking_messages_as_notified_on_home
bugle_phenotype__disable_shortcut_badger
bugle_phenotype__disable_thread_id_dependency
bugle_phenotype__display_gaia_pw_change_dialog
bugle_phenotype__ditto_revoke_messages_when_needed
bugle_phenotype__ditto_satellite_enable_share_intent_support
bugle_phenotype__drop_incoming_mms_if_mms_disabled
bugle_phenotype__dropping_mms_when_mms_is_not_enabled
bugle_phenotype__early_return_for_readyToSendAndReceiveChat
bugle_phenotype__enable_account_fragments
bugle_phenotype__enable_action_success_metrics_177936406
bugle_phenotype__enable_advanced_feedback_flow
bugle_phenotype__enable_all_contact_directories_search_by_name
bugle_phenotype__enable_andromeda_mde
bugle_phenotype__enable_annotations_indexing
bugle_phenotype__enable_app_control_in_depth_funnel_logging
bugle_phenotype__enable_assistant_on_demand_popup
bugle_phenotype__enable_automatic_vmt
bugle_phenotype__enable_battery_monitoring
bugle_phenotype__enable_birthday_banner_settings_button
bugle_phenotype__enable_birthday_coverage_logging
bugle_phenotype__enable_block_list_resolver_count_users
bugle_phenotype__enable_blocking_on_toolstone_calculation
bugle_phenotype__enable_bnr_storage_card
bugle_phenotype__enable_broadcast_receiver_foreground_notification_extra_info
bugle_phenotype__enable_bug_report_capture
bugle_phenotype__enable_bugle_account
bugle_phenotype__enable_bugle_bug_report_data_v2
bugle_phenotype__enable_bugle_feedback_psd_v2
bugle_phenotype__enable_bugle_internet_connectivity_check_for_caps
bugle_phenotype__enable_c2o_customization
bugle_phenotype__enable_c2o_device_camera
bugle_phenotype__enable_chat_endpoint_and_messaging_identity_in_etouffee
bugle_phenotype__enable_chatbot_directory
bugle_phenotype__enable_clearcut_logs_for_custom_reactions
bugle_phenotype__enable_cms_bnr_settings
bugle_phenotype__enable_compose_camera_gallery_screen
bugle_phenotype__enable_compose_camera_in_gallery_screen
bugle_phenotype__enable_compose_tracing
bugle_phenotype__enable_conference_info_migration_into_bugle_db
bugle_phenotype__enable_contact_preview
bugle_phenotype__enable_cpu_profiling_v2
bugle_phenotype__enable_dark_mode_fix
bugle_phenotype__enable_debug_toast_for_icing
bugle_phenotype__enable_device_camera_popup
bugle_phenotype__enable_directory_query_limit
bugle_phenotype__enable_ditto_cms_pairing
bugle_phenotype__enable_ditto_screen_during_multidevice_flow
bugle_phenotype__enable_donation_feature
bugle_phenotype__enable_downgrade_event_metrics
bugle_phenotype__enable_draft_toolstone
bugle_phenotype__enable_duo_video_icon
bugle_phenotype__enable_emotion_fa_logging
bugle_phenotype__enable_enable_system_camera_popup
bugle_phenotype__enable_error_if_e164_phone_number_lookup_failed
bugle_phenotype__enable_error_message_logging_for_icing_search
bugle_phenotype__enable_experiment_carrier_config_override
bugle_phenotype__enable_express_sign_in
bugle_phenotype__enable_expressive_camera_effects
bugle_phenotype__enable_failure_for_sending_reports_to_non_normalized_numbers
bugle_phenotype__enable_federated_analytics_logging
bugle_phenotype__enable_feedback_location_data
bugle_phenotype__enable_flagged_empty_subject_strings
bugle_phenotype__enable_foreground_notification_send_feedback_action
bugle_phenotype__enable_forward_sync_management_redesign
bugle_phenotype__enable_gaia_bit_logging
bugle_phenotype__enable_gaia_home_screen_growth_kit_fix
bugle_phenotype__enable_gaia_logging_account_events
bugle_phenotype__enable_get_conversation_by_conversation_id
bugle_phenotype__enable_gm3_top_app_bar
bugle_phenotype__enable_google_photos_image_by_link
bugle_phenotype__enable_google_photos_integration
bugle_phenotype__enable_google_photos_picker_send_event_after_resume
bugle_phenotype__enable_granularity_nullness_fix
bugle_phenotype__enable_group_ftd_message_status
bugle_phenotype__enable_handle_conversation_status_opaque_data_update
bugle_phenotype__enable_home_search_bar_hint_cycling
bugle_phenotype__enable_ims_sms_capability_check
bugle_phenotype__enable_inbox_archive_animation
bugle_phenotype__enable_latency_monitoring
bugle_phenotype__enable_lg_default_sim_switch
bugle_phenotype__enable_link_preview_view_customization
bugle_phenotype__enable_logging_send_failure_country_code
bugle_phenotype__enable_material_fab
bugle_phenotype__enable_memory_monitoring
bugle_phenotype__enable_message_replies_promo
bugle_phenotype__enable_message_replies_sending
bugle_phenotype__enable_message_replies_swipe
bugle_phenotype__enable_message_replies_vcard_snippets
bugle_phenotype__enable_message_status_logging
bugle_phenotype__enable_message_status_ui
bugle_phenotype__enable_messaging_identity_in_contact_picker
bugle_phenotype__enable_messaging_identity_in_location_search_item_data
bugle_phenotype__enable_messaging_identity_in_video_calling_impl
bugle_phenotype__enable_mi_in_receive_cloud_sync_message_action
bugle_phenotype__enable_miniature_contact_message_annotations
bugle_phenotype__enable_model_based_provider_backoff_merged
bugle_phenotype__enable_model_based_reranker
bugle_phenotype__enable_mosaic
bugle_phenotype__enable_nav_padding_fix
bugle_phenotype__enable_network_monitoring
bugle_phenotype__enable_new_image_compression
bugle_phenotype__enable_non_contact_participant_indexing
bugle_phenotype__enable_non_dds_mms_popup
bugle_phenotype__enable_notification_suppression
bugle_phenotype__enable_on_device_stranger_danger
bugle_phenotype__enable_p2p_conversation_continuation_suggestions
bugle_phenotype__enable_p2p_conversation_suggestions_non_fi
bugle_phenotype__enable_p2p_payments_suggestion
bugle_phenotype__enable_p2p_share_location_suggestion
bugle_phenotype__enable_p2p_smart_assistant_suggestions
bugle_phenotype__enable_package_monitoring
bugle_phenotype__enable_parsing_emoji_suggestions
bugle_phenotype__enable_participant_empty_destination_exception
bugle_phenotype__enable_periodic_corp_contacts_refresh
bugle_phenotype__enable_phenotype_override
bugle_phenotype__enable_prefix_map_link_annotations_regex
bugle_phenotype__enable_primes_tracing
bugle_phenotype__enable_problematic_messages_or_conversations_feedback_data
bugle_phenotype__enable_rbm_rich_card_suggestion_button_style
bugle_phenotype__enable_reactions_configurable_logging
bugle_phenotype__enable_recording_via_drishti
bugle_phenotype__enable_reminder_expiration
bugle_phenotype__enable_reminder_growth_kit_popup
bugle_phenotype__enable_remove_dup_call_to_get_last_message
bugle_phenotype__enable_replace_google_photos_attachment_with_link_and_preview_on_send
bugle_phenotype__enable_report_issue_action_for_message_failure_notification
bugle_phenotype__enable_report_spam_conversation_banner
bugle_phenotype__enable_retry_for_failed_or_empty_decorations
bugle_phenotype__enable_reverse_telephony_sync_on_upgrade
bugle_phenotype__enable_reverse_telephony_sync_on_upgrade_2
bugle_phenotype__enable_same_birthday_nudge_string
bugle_phenotype__enable_send_conversation_id_to_gboard
bugle_phenotype__enable_sending_custom_reaction_emojis
bugle_phenotype__enable_shake_to_report
bugle_phenotype__enable_silent_crash_issue_notification
bugle_phenotype__enable_silent_feedback_on_invalid_duration
bugle_phenotype__enable_silent_suggestion_fa_logging
bugle_phenotype__enable_simplified_messaging_notification_v2_api
bugle_phenotype__enable_single_reg_shadow_launch
bugle_phenotype__enable_smart_action_settings_page
bugle_phenotype__enable_smart_actions_in_notifications
bugle_phenotype__enable_smart_compose
bugle_phenotype__enable_smart_reply_lib_creation_memory_diff
bugle_phenotype__enable_smarts_settings_page_v2
bugle_phenotype__enable_sms_capability_check
bugle_phenotype__enable_sms_capability_logging
bugle_phenotype__enable_sms_rejected_receiver
bugle_phenotype__enable_spotlight_settings_page
bugle_phenotype__enable_spotlights
bugle_phenotype__enable_sqs_integration
bugle_phenotype__enable_starred_messages_fix
bugle_phenotype__enable_starring_suggestion
bugle_phenotype__enable_suggestion_persistence_fix
bugle_phenotype__enable_suggestion_shortcuts
bugle_phenotype__enable_system_picker_tile_in_gallery_screen
bugle_phenotype__enable_tachystick_setup_invite
bugle_phenotype__enable_text_classifier_actions_in_notifications
bugle_phenotype__enable_text_classifier_contact_message_annotations
bugle_phenotype__enable_text_classifier_email_message_annotations
bugle_phenotype__enable_text_classifier_map_link_message_annotations
bugle_phenotype__enable_text_classifier_phone_message_annotations
bugle_phenotype__enable_too_many_1on1_participants_check
bugle_phenotype__enable_toolstones
bugle_phenotype__enable_unredacted_phone_numbers_feedback_data
bugle_phenotype__enable_updated_message_reminder_feature
bugle_phenotype__enable_use_fife_model_for_link_preview_image
bugle_phenotype__enable_verbose_bug_reports
bugle_phenotype__enable_vilte_picker
bugle_phenotype__enable_vmt
bugle_phenotype__enable_vmt_aiai
bugle_phenotype__enable_warn_of_exceeding_sms_message_length_to_emergency_number_dialog
bugle_phenotype__enable_wear_clearcut_reliability_logging
bugle_phenotype__enable_welcome_tooltip_touch_pass_back
bugle_phenotype__enable_xms_reactions_sending
bugle_phenotype__enable_xsl
bugle_phenotype__enable_xsl_smapi_get_incoming_messages
bugle_phenotype__enable_xsl_smapi_process_intent_chat
bugle_phenotype__enable_xsl_smapi_send_message_method
bugle_phenotype__enable_xsl_smapi_send_service_chat
bugle_phenotype__enable_xsl_smapi_update_incoming_intent
bugle_phenotype__enable_xsl_smapi_update_sent_intent
bugle_phenotype__enable_youtube_pip_view
bugle_phenotype__enable_zero_connectivity_banner
bugle_phenotype__enable_zero_connectivity_settings_panel
bugle_phenotype__enabled_testopenbeta_feature
bugle_phenotype__esi_how_it_works_tooltip_use_max_width
bugle_phenotype__extract_mms_metadata_on_receiving_exp
bugle_phenotype__filter_non_northstar_clearcut_logs_enable
bugle_phenotype__fix_item_disappearing_and_crashing_when_clicking_archive_or_spam
bugle_phenotype__foldable_ux_optimization
bugle_phenotype__gaia_check_fragment_is_saved_before_commit_apd_fragment
bugle_phenotype__gaia_hide_option_to_switch_to_work_profile
bugle_phenotype__gaia_swallow_account_operation_parcelled_before_complete_exception
bugle_phenotype__generate_log_id_before_sending_message
bugle_phenotype__generate_otp_for_mms
bugle_phenotype__get_mms_group_phone_number_in_data_service
bugle_phenotype__guest_cloud_beta
bugle_phenotype__include_mms_metadata_on_sending_exp
bugle_phenotype__include_terms_summary_in_google_tos
bugle_phenotype__invalidate_config_and_schedule_new_task_on_battery_optimization
bugle_phenotype__invalidate_data_source_after_block
bugle_phenotype__lighter_enable_password_change_support
bugle_phenotype__limit_showing_fallback_options_in_etouffee_groups
bugle_phenotype__log_cronet_errors_for_business_info
bugle_phenotype__log_navigation_menu_and_legacy_overflow_menu_item_click_event
bugle_phenotype__log_silent_feedback_on_account_error
bugle_phenotype__log_srlib_exceptions_silent_feedback
bugle_phenotype__log_super_sort_query_paged
bugle_phenotype__make_application_settings_external_for_gaia
bugle_phenotype__mdd_lib_enable_downloads_only
bugle_phenotype__move_tombstone_computation_to_background
bugle_phenotype__national_emergency_intent
bugle_phenotype__new_query_last_message_for_each_conversation
bugle_phenotype__no_op_rasta_test_feature_always_failing
bugle_phenotype__p13n_enabled
bugle_phenotype__p2p_conversation_suggestions_disable_apk_model
bugle_phenotype__p2p_conversation_suggestions_fail_fast
bugle_phenotype__p2p_conversation_suggestions_force_use_server
bugle_phenotype__p2p_enable_entity_telemetry
bugle_phenotype__part_table_based_heuristic_ignored
bugle_phenotype__predictable_back_navigation_enable
bugle_phenotype__rbm_toolstone_visible_by_default
bugle_phenotype__reactions_promo_control_group
bugle_phenotype__remove_banner_full_screen
bugle_phenotype__remove_calendar_title
bugle_phenotype__remove_conversation_details_app_settings_row_when_account_fragments_enabled
bugle_phenotype__reranker_enable_type_sorting
bugle_phenotype__sanity_check_sms_count
bugle_phenotype__sanity_check_thread_ids
bugle_phenotype__send_encrypted_display_imdn_with_control_message_source
bugle_phenotype__show_emoji_variant_selector_on_first_tap
bugle_phenotype__show_otp_chip_in_conversation_list
bugle_phenotype__skip_signature_check_for_g1_restore
bugle_phenotype__ss_use_work_manager_specific_msg
bugle_phenotype__start_chat_multiselect_mode
bugle_phenotype__sub_utils_throws_for_invalid_sub_id
bugle_phenotype__suggestion_feedback_enabled
bugle_phenotype__super_sort_disable_all_logging
bugle_phenotype__support_non_prod_packages_for_andromeda
bugle_phenotype__support_paths_in_bot_domain
bugle_phenotype__switch_to_pseudonymous_on_account_error
bugle_phenotype__text_classifier_use_mddlib_actions_model
bugle_phenotype__thread_id_duplicate_conversations
bugle_phenotype__thread_id_mismatch_recover
bugle_phenotype__trigger_starring_suggestion_for_non_contacts
bugle_phenotype__update_participant_with_received_sms
bugle_phenotype__use_bugle_conversation_matching
bugle_phenotype__use_bugle_express_sign_in_framework
bugle_phenotype__use_bugle_shared_prefs_for_terms_and_conditions
bugle_phenotype__use_contact_event_logger
bugle_phenotype__use_guessed_min_match_value
bugle_phenotype__use_hmac_participant_hash
bugle_phenotype__use_legacy_normalized_destination_in_participant_creation
bugle_phenotype__use_main_activity_everywhere_v2
bugle_phenotype__use_messaging_identity_list_in_insert_protocol_tombstone
bugle_phenotype__verify_participant_in_conversation
bugle_phenotype__verify_thread_ids_cache
bugle_phenotype__verify_unique_session_ids
enable_lighter_clean_up_handler
bugle_phenotype__bug_169439511_change_default_filter
bugle_phenotype__conversation_labels_enabled
bugle_phenotype__enable_additional_annotation_logging
bugle_phenotype__enable_home_screen_banner
bugle_phenotype__enable_maestro_demo
bugle_phenotype__enable_otp_auto_deletion
bugle_phenotype__enable_supersort_annotators
bugle_phenotype__supersort_badge_all_filter
bugle_phenotype__supersort_enable_otp_banner_in_business_updates
bugle_phenotype__supersort_enable_qpbc
bugle_phenotype__supersort_enable_update_donation_banner
