
<h1 align="center">💎TTKAPI [ TikTok Stats API ]</h1>

<p align='center'>
  <b>Star ⭐ to keep free</b><br>
</p>

## Endpoint:

```python
https://api.xtekky.com/tiktok/video?link=
```

## Usage:

### Python
```python 
import requests

link = "https://tiktok.com/@user/video/7086595171827322158"

vidinfo = requests.get(f"https://api.xtekky.com/tiktok/video?link={}").json()
print(vidinfo)

```
### Response:

```json
{
  "aweme_details": [
    {
      "anchors": null, 
      "author": {
        "accept_private_policy": false, 
        "account_region": "", 
        "ad_cover_url": null, 
        "advance_feature_item_order": null, 
        "advanced_feature_info": null, 
        "apple_account": 0, 
        "authority_status": 0, 
        "avatar_168x168": {
          "height": 720, 
          "uri": "tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4", 
          "url_list": [
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_168x168.webp?x-expires=1652475600&x-signature=oM5WbuXrsTiVYtsp5HD3Afy3HoU%3D", 
            "https://p77-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_168x168.webp?x-expires=1652475600&x-signature=fzlNqeDuWX9Q0qeXwQVMa4HSmS4%3D", 
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_168x168.jpeg?x-expires=1652475600&x-signature=V56QYNtuqJPlSvEvgDiME97lLKY%3D"
          ], 
          "width": 720
        }, 
        "avatar_300x300": {
          "height": 720, 
          "uri": "tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4", 
          "url_list": [
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_300x300.webp?x-expires=1652475600&x-signature=%2BnnyBmQZUE%2BXm0IG6VEOhExWgfQ%3D", 
            "https://p77-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_300x300.webp?x-expires=1652475600&x-signature=kCERyNrv9RyqV9Ekjtq8RDQC7Po%3D", 
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_300x300.jpeg?x-expires=1652475600&x-signature=2MiLXY2MTUkHH5253giAEr8DePs%3D"
          ], 
          "width": 720
        }, 
        "avatar_larger": {
          "height": 720, 
          "uri": "tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4", 
          "url_list": [
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_1080x1080.webp?x-expires=1652475600&x-signature=uXQ6Z6yjClYS%2BJ%2Fh%2BVBK6T3VcRM%3D", 
            "https://p77-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_1080x1080.webp?x-expires=1652475600&x-signature=7ZstIAB4fuyXUpnJJFNWNGzTZiQ%3D", 
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_1080x1080.jpeg?x-expires=1652475600&x-signature=6X1EX%2BsQruK%2F5FASCJzb8NSx4P8%3D"
          ], 
          "width": 720
        }, 
        "avatar_medium": {
          "height": 720, 
          "uri": "tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4", 
          "url_list": [
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_720x720.webp?x-expires=1652475600&x-signature=ouIcutmgtzxFfYI%2FjOMgMOTjY4k%3D", 
            "https://p77-sign-va-lite.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_720x720.webp?x-expires=1652475600&x-signature=Ra0SVWtnyU0JPkldYFNfu9fcLJE%3D", 
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_720x720.jpeg?x-expires=1652475600&x-signature=HjjnVBqgI9l%2BL9JRegygMPfRXe8%3D"
          ], 
          "width": 720
        }, 
        "avatar_thumb": {
          "height": 720, 
          "uri": "tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4", 
          "url_list": [
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_100x100.webp?x-expires=1652475600&x-signature=EoexBg794bFfrIdY6pOgBNmneKs%3D", 
            "https://p77-sign-va-lite.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_100x100.webp?x-expires=1652475600&x-signature=I3qS3qn1hhWSGoD5L1HOyHWUHqk%3D", 
            "https://p16-sign-va.tiktokcdn.com/tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4~c5_100x100.jpeg?x-expires=1652475600&x-signature=Cot7szheaajaqDwVJcKUKERE8ss%3D"
          ], 
          "width": 720
        }, 
        "avatar_uri": "tos-maliva-avt-0068/a5dc281485db465c9787987f9a6545c4", 
        "aweme_count": 0, 
        "badge_info": {}, 
        "bind_phone": "", 
        "bold_fields": null, 
        "can_set_geofencing": null, 
        "cha_list": null, 
        "comment_filter_status": 1, 
        "comment_setting": 0, 
        "commerce_user_level": 0, 
        "cover_url": [
          {
            "height": 720, 
            "uri": "tiktok-obj/1613727517271041", 
            "url_list": [
              "https://p77-sg.tiktokcdn.com/obj/tiktok-obj/1613727517271041"
            ], 
            "width": 720
          }
        ], 
        "create_time": 0, 
        "custom_verify": "", 
        "cv_level": "", 
        "download_prompt_ts": 0, 
        "download_setting": 3, 
        "duet_setting": 3, 
        "enterprise_verify_reason": "", 
        "events": null, 
        "favoriting_count": 0, 
        "fb_expire_time": 0, 
        "follow_status": 0, 
        "follower_count": 0, 
        "follower_status": 0, 
        "followers_detail": null, 
        "following_count": 0, 
        "geofencing": null, 
        "google_account": "", 
        "has_email": false, 
        "has_facebook_token": false, 
        "has_insights": false, 
        "has_orders": false, 
        "has_twitter_token": false, 
        "has_youtube_token": false, 
        "hide_search": false, 
        "homepage_bottom_toast": null, 
        "ins_id": "", 
        "is_ad_fake": false, 
        "is_block": false, 
        "is_discipline_member": false, 
        "is_phone_binded": false, 
        "is_star": false, 
        "item_list": null, 
        "language": "en", 
        "live_agreement": 0, 
        "live_commerce": false, 
        "live_verify": 0, 
        "mention_status": 1, 
        "mutual_relation_avatars": null, 
        "need_points": null, 
        "need_recommend": 0, 
        "nickname": "ixxa", 
        "platform_sync_info": null, 
        "prevent_download": false, 
        "react_setting": 3, 
        "region": "FR", 
        "relative_users": null, 
        "room_id": 0, 
        "search_highlight": null, 
        "sec_uid": "MS4wLjABAAAA91zET2DNGUuOQnZe-rlWsHBSLQW1mhxY5RMwTFWhq5yWo2bmm2O1guT72pdY5-RZ", 
        "secret": 0, 
        "share_info": {
          "share_desc": "", 
          "share_desc_info": "", 
          "share_qrcode_url": {
            "height": 720, 
            "uri": "", 
            "url_list": [], 
            "width": 720
          }, 
          "share_title": "", 
          "share_title_myself": "", 
          "share_title_other": "", 
          "share_url": "", 
          "share_weibo_desc": ""
        }, 
        "share_qrcode_uri": "", 
        "shield_comment_notice": 0, 
        "shield_digg_notice": 0, 
        "shield_follow_notice": 0, 
        "short_id": "0", 
        "show_image_bubble": false, 
        "signature": "Tekky#9999\nDiscord: .gg/onlp and discord.gg/kXvJcZbTef\nBots/Scripts", 
        "special_lock": 1, 
        "status": 1, 
        "stitch_setting": 3, 
        "story_status": 0, 
        "total_favorited": 0, 
        "tw_expire_time": 0, 
        "twitter_id": "", 
        "twitter_name": "", 
        "type_label": null, 
        "uid": "7022407054702806022", 
        "unique_id": "ixxa", 
        "unique_id_modify_time": 1652390734, 
        "user_canceled": false, 
        "user_mode": 1, 
        "user_period": 0, 
        "user_rate": 1, 
        "user_tags": null, 
        "verification_type": 1, 
        "verify_info": "", 
        "video_icon": {
          "height": 720, 
          "uri": "", 
          "url_list": [], 
          "width": 720
        }, 
        "white_cover_url": null, 
        "with_commerce_entry": false, 
        "with_shop_entry": false, 
        "youtube_channel_id": "", 
        "youtube_channel_title": "", 
        "youtube_expire_time": 0
      }, 
      "author_user_id": 7022407054702806022, 
      "aweme_id": "7086595171827322158", 
      "aweme_type": 0, 
      "bodydance_score": 0, 
      "cha_list": [
        {
          "author": {
            "ad_cover_url": null, 
            "advance_feature_item_order": null, 
            "advanced_feature_info": null, 
            "bold_fields": null, 
            "can_set_geofencing": null, 
            "cha_list": null, 
            "cover_url": null, 
            "events": null, 
            "followers_detail": null, 
            "geofencing": null, 
            "homepage_bottom_toast": null, 
            "item_list": null, 
            "mutual_relation_avatars": null, 
            "need_points": null, 
            "platform_sync_info": null, 
            "relative_users": null, 
            "search_highlight": null, 
            "type_label": null, 
            "user_tags": null, 
            "white_cover_url": null
          }, 
          "banner_list": null, 
          "cha_attrs": null, 
          "cha_name": "xyzbca", 
          "cid": "1652484531221509", 
          "collect_stat": 0, 
          "connect_music": [], 
          "desc": "Asla bir sonraki hamleni bilmelerine izin verme! \ud83d\udc40", 
          "extra_attr": {
            "is_live": false
          }, 
          "hashtag_profile": "tiktok-obj/f10d345927d966e1b69d1b2c1c5fdf98.png", 
          "is_challenge": 0, 
          "is_commerce": false, 
          "is_pgcshow": false, 
          "schema": "aweme://aweme/challenge/detail?cid=1652484531221509", 
          "search_highlight": null, 
          "share_info": {
            "bool_persist": 0, 
            "share_desc": "Check out #xyzbca on TikTok!", 
            "share_desc_info": "Check out #xyzbca on TikTok!", 
            "share_quote": "", 
            "share_signature_desc": "", 
            "share_signature_url": "", 
            "share_title": "It is a becoming a big trend on TikTok now! Click here: xyzbca", 
            "share_title_myself": "", 
            "share_title_other": "", 
            "share_url": "https://m.tiktok.com/h5/share/tag/1652484531221509.html?name=xyzbca&u_code=-1&language=en&_d=0&share_challenge_id=1652484531221509&source=h5_m", 
            "share_weibo_desc": "Check out #xyzbca on TikTok!"
          }, 
          "show_items": null, 
          "sub_type": 0, 
          "type": 2, 
          "user_count": 0, 
          "view_count": 0
        }
      ], 
      "challenge_position": null, 
      "cmt_swt": false, 
      "collect_stat": 0, 
      "commerce_config_data": null, 
      "commerce_info": {
        "adv_promotable": false, 
        "auction_ad_invited": false, 
        "with_comment_filter_words": false
      }, 
      "content_desc": "", 
      "content_desc_extra": [], 
      "cover_labels": null, 
      "create_time": 1649976516, 
      "desc": ".gg/kXvJcZbTef #xyzbca #fyp #fyp\u30b7 #share #tiktok #python #bot #tool #script #lol #discord", 
      "desc_language": "pl", 
      "disable_search_trending_bar": false, 
      "distance": "", 
      "distribute_type": 1, 
      "follow_up_publish_from_id": -1, 
      "geofencing": null, 
      "geofencing_regions": null, 
      "green_screen_materials": null, 
      "group_id": "7086595171827322158", 
      "group_id_list": {
        "GroupdIdList0": null, 
        "GroupdIdList1": [
          7086595171827322158
        ]
      }, 
      "have_dashboard": false, 
      "hybrid_label": null, 
      "image_infos": null, 
      "interaction_stickers": null, 
      "is_ads": false, 
      "is_hash_tag": 1, 
      "is_pgcshow": false, 
      "is_preview": 0, 
      "is_relieve": false, 
      "is_top": 0, 
      "is_vr": false, 
      "item_comment_settings": 0, 
      "item_duet": 1, 
      "item_react": 1, 
      "item_stitch": 1, 
      "label_top": {
        "height": 720, 
        "uri": "tiktok-obj/1598708589477025.PNG", 
        "url_list": [
          "https://p77-sg.tiktokcdn.com/obj/tiktok-obj/1598708589477025.PNG"
        ], 
        "width": 720
      }, 
      "label_top_text": null, 
      "long_video": null, 
      "mask_infos": [], 
      "misc_info": "{}", 
      "music": {
        "album": "Trunk", 
        "artists": [], 
        "audition_duration": 0, 
        "author": "Phonk Killer & Kingpin Skinny Pimp", 
        "author_deleted": false, 
        "author_position": null, 
        "binded_challenge_id": 0, 
        "collect_stat": 0, 
        "cover_large": {
          "height": 720, 
          "uri": "tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a", 
          "url_list": [
            "https://p16-sg-default.akamaized.net/aweme/720x720/tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a.jpeg"
          ], 
          "width": 720
        }, 
        "cover_medium": {
          "height": 720, 
          "uri": "tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a", 
          "url_list": [
            "https://p16-sg-default.akamaized.net/aweme/200x200/tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a.jpeg"
          ], 
          "width": 720
        }, 
        "cover_thumb": {
          "height": 720, 
          "uri": "tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a", 
          "url_list": [
            "https://p16-sg-default.akamaized.net/aweme/100x100/tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a.jpeg"
          ], 
          "width": 720
        }, 
        "dmv_auto_show": false, 
        "duration": 60, 
        "external_song_info": [], 
        "extra": "{\"schedule_search_time\":0,\"aed_music_dur\":53.16,\"is_ugc_mapping\":false,\"has_edited\":0,\"reviewed\":1,\"review_unshelve_reason\":0,\"beats\":{}}", 
        "id": 6968593956024092673, 
        "id_str": "6968593956024092673", 
        "is_audio_url_with_cookie": false, 
        "is_author_artist": false, 
        "is_commerce_music": true, 
        "is_matched_metadata": false, 
        "is_original": false, 
        "is_original_sound": false, 
        "is_pgc": true, 
        "lyric_short_position": null, 
        "matched_song": {
          "author": "Phonk Killer & Kingpin Skinny Pimp", 
          "chorus_info": {
            "duration_ms": 24244, 
            "start_ms": 89420
          }, 
          "cover_medium": {
            "height": 720, 
            "uri": "tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a", 
            "url_list": [
              "https://p16-sg-default.akamaized.net/aweme/200x200/tos-alisg-v-2774/76ef094da161494da20bd971f98ca96a.jpeg"
            ], 
            "width": 720
          }, 
          "h5_url": "", 
          "id": "6968593955232188418", 
          "performers": null, 
          "title": "Trunk"
        }, 
        "mid": "6968593956024092673", 
        "multi_bit_rate_play_info": null, 
        "mute_share": false, 
        "offline_desc": "", 
        "owner_handle": "", 
        "owner_nickname": "", 
        "play_url": {
          "height": 720, 
          "uri": "https://sf16-sg-default.akamaized.net/obj/tos-alisg-ve-2774/dc7b475ef7044cd088c556f8e11a29e0", 
          "url_list": [
            "https://sf16-sg-default.akamaized.net/obj/tos-alisg-ve-2774/dc7b475ef7044cd088c556f8e11a29e0"
          ], 
          "width": 720
        }, 
        "position": null, 
        "prevent_download": false, 
        "preview_end_time": 0, 
        "preview_start_time": 0, 
        "search_highlight": null, 
        "shoot_duration": 0, 
        "source_platform": 10033, 
        "status": 1, 
        "strong_beat_url": {
          "height": 720, 
          "uri": "https://sf16-sg-default.akamaized.net/obj/tos-alisg-v-2774/1c7a471602f74acaa42f46cfc5459543", 
          "url_list": [
            "https://sf16-sg-default.akamaized.net/obj/tos-alisg-v-2774/1c7a471602f74acaa42f46cfc5459543"
          ], 
          "width": 720
        }, 
        "tag_list": null, 
        "title": "Trunk", 
        "user_count": 0, 
        "video_duration": 0
      }, 
      "music_begin_time_in_ms": 0, 
      "music_end_time_in_ms": 39662, 
      "need_trim_step": false, 
      "nickname_position": null, 
      "origin_comment_ids": null, 
      "playlist_blocked": false, 
      "position": null, 
      "prevent_download": false, 
      "products_info": null, 
      "question_list": null, 
      "rate": 12, 
      "region": "FR", 
      "retry_type": 0, 
      "risk_infos": {
        "content": "", 
        "risk_sink": false, 
        "type": 0, 
        "vote": false, 
        "warn": false
      }, 
      "search_highlight": null, 
      "share_info": {
        "bool_persist": 0, 
        "share_desc": "Check out ixxa's video! #TikTok", 
        "share_desc_info": "TikTok: Make Every Second CountCheck out ixxa\u2019s video! #TikTok > ", 
        "share_link_desc": "", 
        "share_quote": "", 
        "share_signature_desc": "", 
        "share_signature_url": "", 
        "share_title": "Check out ixxa\u2019s video! #TikTok > ", 
        "share_title_myself": "", 
        "share_title_other": "", 
        "share_url": "https://m.tiktok.com/v/7086595171827322158.html?u_code=-1&preview_pb=0&language=en&_d=0&share_item_id=7086595171827322158&source=h5_m", 
        "share_weibo_desc": "TikTok: Make Every Second CountCheck out ixxa\u2019s video! #TikTok > "
      }, 
      "share_url": "https://m.tiktok.com/v/7086595171827322158.html?u_code=-1&preview_pb=0&language=en&_d=0&share_item_id=7086595171827322158&source=h5_m", 
      "sort_label": "", 
      "statistics": {
        "aweme_id": "7086595171827322158", 
        "collect_count": 9, 
        "comment_count": 39, 
        "digg_count": 66, 
        "download_count": 0, 
        "forward_count": 0, 
        "lose_comment_count": 0, 
        "lose_count": 0, 
        "play_count": 4964, 
        "share_count": 415578, 
        "whatsapp_share_count": 0
      }, 
      "status": {
        "allow_comment": true, 
        "allow_share": true, 
        "aweme_id": "7086595171827322158", 
        "download_status": 0, 
        "in_reviewing": false, 
        "is_delete": false, 
        "is_prohibited": false, 
        "private_status": 0, 
        "review_result": {
          "review_status": 0
        }, 
        "reviewed": 0, 
        "self_see": false
      }, 
      "text_extra": [
        {
          "end": 22, 
          "hashtag_id": "1652484531221509", 
          "hashtag_name": "xyzbca", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 15, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 27, 
          "hashtag_id": "229207", 
          "hashtag_name": "fyp", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 23, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 33, 
          "hashtag_id": "1637342470396934", 
          "hashtag_name": "fyp\u30b7", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 28, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 40, 
          "hashtag_id": "5219", 
          "hashtag_name": "share", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 34, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 48, 
          "hashtag_id": "23428", 
          "hashtag_name": "tiktok", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 41, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 56, 
          "hashtag_id": "163195", 
          "hashtag_name": "python", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 49, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 61, 
          "hashtag_id": "139169", 
          "hashtag_name": "bot", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 57, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 67, 
          "hashtag_id": "48284", 
          "hashtag_name": "tool", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 62, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 75, 
          "hashtag_id": "32746", 
          "hashtag_name": "script", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 68, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 80, 
          "hashtag_id": "1745", 
          "hashtag_name": "lol", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 76, 
          "type": 1, 
          "user_id": ""
        }, 
        {
          "end": 89, 
          "hashtag_id": "345686", 
          "hashtag_name": "discord", 
          "is_commerce": false, 
          "sec_uid": "", 
          "start": 81, 
          "type": 1, 
          "user_id": ""
        }
      ], 
      "uniqid_position": null, 
      "user_digged": 0, 
      "video": {
        "ai_dynamic_cover": {
          "height": 720, 
          "uri": "tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518", 
          "url_list": [
            "https://p16-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518~tplv-dmt-logom:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.image?x-expires=1652410800&x-signature=PsrxdrCmLK%2F4LT1cSKUMMeYB0ZY%3D", 
            "https://p19-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518~tplv-dmt-logom:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.image?x-expires=1652410800&x-signature=4kkfqPu%2F6BaPvajcR15jm7GSn6E%3D"
          ], 
          "width": 720
        }, 
        "ai_dynamic_cover_bak": {
          "height": 720, 
          "uri": "tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518", 
          "url_list": [
            "https://p16-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518~tplv-dmt-logom:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.image?x-expires=1652410800&x-signature=PsrxdrCmLK%2F4LT1cSKUMMeYB0ZY%3D", 
            "https://p19-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518~tplv-dmt-logom:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.image?x-expires=1652410800&x-signature=4kkfqPu%2F6BaPvajcR15jm7GSn6E%3D"
          ], 
          "width": 720
        }, 
        "big_thumbs": null, 
        "bit_rate": [
          {
            "bit_rate": 1144765, 
            "dub_infos": null, 
            "gear_name": "normal_540_0", 
            "is_bytevc1": 0, 
            "is_h265": 0, 
            "play_addr": {
              "data_size": 5701646, 
              "file_cs": "c:0-33248-e6a8", 
              "file_hash": "753a016c32bca49008cdcb8ce9e96299", 
              "height": 1218, 
              "uri": "v12044gd0000c9c9tlrc77udqtlfi68g", 
              "url_key": "v12044gd0000c9c9tlrc77udqtlfi68g_h264_540p_1144765", 
              "url_list": [
                "https://v16m-default.akamaized.net/5d6666614704f4bbf29ce95f342ee565/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/d532a49fbb1c476a9f571d0ebf688c7d/?a=0&br=2234&bt=1117&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajlpd2c6Zm88PDMzZzczNEApZDc6PDNoNGVpN2RmaWQ5ZWc1ZmlucjRvcWBgLS1kMS9zc2ItY2FfM18zMjBeYy0tLjE6Yw%3D%3D&vl=&vr=", 
                "https://v16m.byteicdn.com/5d6666614704f4bbf29ce95f342ee565/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/d532a49fbb1c476a9f571d0ebf688c7d/?a=0&br=2234&bt=1117&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajlpd2c6Zm88PDMzZzczNEApZDc6PDNoNGVpN2RmaWQ5ZWc1ZmlucjRvcWBgLS1kMS9zc2ItY2FfM18zMjBeYy0tLjE6Yw%3D%3D&vl=&vr=", 
                "https://api.tiktokv.com/aweme/v1/play/?video_id=v12044gd0000c9c9tlrc77udqtlfi68g&line=0&is_play_url=1&source=PackSourceEnum_AWEME_DETAIL&file_id=b461a0f0cfaa43f5b61be60b9d7f40ae"
              ], 
              "width": 576
            }, 
            "quality_type": 20
          }, 
          {
            "bit_rate": 635685, 
            "dub_infos": null, 
            "gear_name": "lower_540_0", 
            "is_bytevc1": 0, 
            "is_h265": 0, 
            "play_addr": {
              "data_size": 3166110, 
              "file_cs": "c:0-33248-51ef", 
              "file_hash": "7496f8b34a4d8ef93902f306f690f859", 
              "height": 1218, 
              "uri": "v12044gd0000c9c9tlrc77udqtlfi68g", 
              "url_key": "v12044gd0000c9c9tlrc77udqtlfi68g_h264_540p_635685", 
              "url_list": [
                "https://v16m-default.akamaized.net/4cc4e797ffe93953ef6ab1f708c130f9/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/60ccbb03830541a2ab7ee4516030bd38/?a=0&br=1240&bt=620&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=ajlpd2c6Zm88PDMzZzczNEApPDszaTQ6O2Q0Nzo6NTQ4aWc1ZmlucjRvcWBgLS1kMS9zcy1hMS0zLmAxLmIuNDJfXi86Yw%3D%3D&vl=&vr=", 
                "https://v16m.byteicdn.com/4cc4e797ffe93953ef6ab1f708c130f9/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/60ccbb03830541a2ab7ee4516030bd38/?a=0&br=1240&bt=620&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=4&rc=ajlpd2c6Zm88PDMzZzczNEApPDszaTQ6O2Q0Nzo6NTQ4aWc1ZmlucjRvcWBgLS1kMS9zcy1hMS0zLmAxLmIuNDJfXi86Yw%3D%3D&vl=&vr=", 
                "https://api.tiktokv.com/aweme/v1/play/?video_id=v12044gd0000c9c9tlrc77udqtlfi68g&line=0&is_play_url=1&source=PackSourceEnum_AWEME_DETAIL&file_id=f25a1b2577714e11a48c7116f0048d90"
              ], 
              "width": 576
            }, 
            "quality_type": 24
          }, 
          {
            "bit_rate": 476812, 
            "dub_infos": null, 
            "gear_name": "lowest_540_0", 
            "is_bytevc1": 0, 
            "is_h265": 0, 
            "play_addr": {
              "data_size": 2374826, 
              "file_cs": "c:0-33248-28b3", 
              "file_hash": "c1fef5b687e68c91a6b0846bc144c99b", 
              "height": 1218, 
              "uri": "v12044gd0000c9c9tlrc77udqtlfi68g", 
              "url_key": "v12044gd0000c9c9tlrc77udqtlfi68g_h264_540p_476812", 
              "url_list": [
                "https://v16m-default.akamaized.net/093d28f03d0c7b01ffb27bd9e2de0d6c/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/428fa7a6d0744d368f5ae337ec3ef687/?a=0&br=930&bt=465&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=ajlpd2c6Zm88PDMzZzczNEApNjY6ZDdnOWRpNzQ5ZDk6Omc1ZmlucjRvcWBgLS1kMS9zczNfMjEwNV8yNWNfYzM0NjY6Yw%3D%3D&vl=&vr=", 
                "https://v16m.byteicdn.com/093d28f03d0c7b01ffb27bd9e2de0d6c/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/428fa7a6d0744d368f5ae337ec3ef687/?a=0&br=930&bt=465&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=5&rc=ajlpd2c6Zm88PDMzZzczNEApNjY6ZDdnOWRpNzQ5ZDk6Omc1ZmlucjRvcWBgLS1kMS9zczNfMjEwNV8yNWNfYzM0NjY6Yw%3D%3D&vl=&vr=", 
                "https://api.tiktokv.com/aweme/v1/play/?video_id=v12044gd0000c9c9tlrc77udqtlfi68g&line=0&is_play_url=1&source=PackSourceEnum_AWEME_DETAIL&file_id=797967a66f1b4ff8a56bd843a4753b36"
              ], 
              "width": 576
            }, 
            "quality_type": 25
          }
        ], 
        "cdn_url_expired": 0, 
        "cover": {
          "height": 720, 
          "uri": "tos-useast5-p-0068-tx/199ee79b9da0452e9f7007cd1455179c_1649976525", 
          "url_list": [
            "https://p16-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/199ee79b9da0452e9f7007cd1455179c_1649976525~tplv-dmt-logoccm:300:400:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.webp?x-expires=1652410800&x-signature=ymZzhpvJyL%2FUKIVhtIfOe0NMiVU%3D", 
            "https://p19-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/199ee79b9da0452e9f7007cd1455179c_1649976525~tplv-dmt-logoccm:300:400:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.webp?x-expires=1652410800&x-signature=aKo6Eif51EJRvTZ3qt1WzgYuPP4%3D", 
            "https://p16-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/199ee79b9da0452e9f7007cd1455179c_1649976525~tplv-dmt-logoccm:300:400:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.jpeg?x-expires=1652410800&x-signature=rmg3RHcA6r8oLjOi6IoB9SPKcew%3D"
          ], 
          "width": 720
        }, 
        "download_addr": {
          "data_size": 5725669, 
          "height": 720, 
          "uri": "v12044gd0000c9c9tlrc77udqtlfi68g", 
          "url_list": [
            "https://v16m-default.akamaized.net/03e50144c0a6b8fcb862a41687d5ca61/627dcfd6/video/tos/useast5/tos-useast5-ve-0068c003-tx/3da4abc6c36d4f11b9e07327e0b05a33/?a=0&br=2244&bt=1122&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=3&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajlpd2c6Zm88PDMzZzczNEApZWY2Njo7Ozw3N2czaDs2O2c1ZmlucjRvcWBgLS1kMS9zczVgYDAuNi1iMGMtYjVjNjQ6Yw%3D%3D&vl=&vr=", 
            "https://v16m.byteicdn.com/03e50144c0a6b8fcb862a41687d5ca61/627dcfd6/video/tos/useast5/tos-useast5-ve-0068c003-tx/3da4abc6c36d4f11b9e07327e0b05a33/?a=0&br=2244&bt=1122&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=3&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajlpd2c6Zm88PDMzZzczNEApZWY2Njo7Ozw3N2czaDs2O2c1ZmlucjRvcWBgLS1kMS9zczVgYDAuNi1iMGMtYjVjNjQ6Yw%3D%3D&vl=&vr=", 
            "https://api.tiktokv.com/aweme/v1/play/?video_id=v12044gd0000c9c9tlrc77udqtlfi68g&line=0&watermark=1&logo_name=tiktok_m&source=AWEME_DETAIL&file_id=87398fe80ed04f439e808971333cccb8"
          ], 
          "width": 720
        }, 
        "duration": 39845, 
        "dynamic_cover": {
          "height": 720, 
          "uri": "tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518", 
          "url_list": [
            "https://p16-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518~tplv-dmt-logom:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.image?x-expires=1652410800&x-signature=PsrxdrCmLK%2F4LT1cSKUMMeYB0ZY%3D", 
            "https://p19-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/381d07959bb94160b14b6f01b0896c23_1649976518~tplv-dmt-logom:tos-useast5-p-0000-tx/d3c78f8cf32c40ed9ef9467f15511f8b.image?x-expires=1652410800&x-signature=4kkfqPu%2F6BaPvajcR15jm7GSn6E%3D"
          ], 
          "width": 720
        }, 
        "has_watermark": true, 
        "height": 1920, 
        "is_bytevc1": 0, 
        "is_callback": true, 
        "is_h265": 0, 
        "meta": "{\"loudness\":\"-4.8\",\"peak\":\"1\",\"qprf\":\"1.000000\"}", 
        "need_set_token": false, 
        "origin_cover": {
          "height": 720, 
          "uri": "tos-useast5-p-0068-tx/ded19ef5fddc4628bade89ca56cd1909_1649976517", 
          "url_list": [
            "https://p16-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/ded19ef5fddc4628bade89ca56cd1909_1649976517~tplv-tiktokx-360p.jpeg?x-expires=1652410800&x-signature=JIi0o3R%2BU9vdjFDp1g1wlcO5%2BHo%3D", 
            "https://p19-sign.tiktokcdn-us.com/tos-useast5-p-0068-tx/ded19ef5fddc4628bade89ca56cd1909_1649976517~tplv-tiktokx-360p.jpeg?x-expires=1652410800&x-signature=GKOLacmDWWGeQaKHi7glmQ4iQuA%3D"
          ], 
          "width": 720
        }, 
        "play_addr": {
          "data_size": 5701646, 
          "file_cs": "c:0-33248-e6a8", 
          "file_hash": "753a016c32bca49008cdcb8ce9e96299", 
          "height": 1218, 
          "uri": "v12044gd0000c9c9tlrc77udqtlfi68g", 
          "url_key": "v12044gd0000c9c9tlrc77udqtlfi68g_h264_540p_1144765", 
          "url_list": [
            "https://v16m-default.akamaized.net/5d6666614704f4bbf29ce95f342ee565/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/d532a49fbb1c476a9f571d0ebf688c7d/?a=0&br=2234&bt=1117&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajlpd2c6Zm88PDMzZzczNEApZDc6PDNoNGVpN2RmaWQ5ZWc1ZmlucjRvcWBgLS1kMS9zc2ItY2FfM18zMjBeYy0tLjE6Yw%3D%3D&vl=&vr=", 
            "https://v16m.byteicdn.com/5d6666614704f4bbf29ce95f342ee565/627dcfd6/video/tos/maliva/tos-maliva-ve-0068c799-us/d532a49fbb1c476a9f571d0ebf688c7d/?a=0&br=2234&bt=1117&cd=0%7C0%7C0%7C0&ch=0&cr=0&cs=0&dr=0&ds=6&er=&ft=lbdpfHJ9Myq8Zk99qwe2N0qtsx0Gb&l=202205122125340102450400760A0C892D&lr=all&mime_type=video_mp4&net=0&pl=0&qs=0&rc=ajlpd2c6Zm88PDMzZzczNEApZDc6PDNoNGVpN2RmaWQ5ZWc1ZmlucjRvcWBgLS1kMS9zc2ItY2FfM18zMjBeYy0tLjE6Yw%3D%3D&vl=&vr=", 
            "https://api.tiktokv.com/aweme/v1/play/?video_id=v12044gd0000c9c9tlrc77udqtlfi68g&line=0&is_play_url=1&source=PackSourceEnum_AWEME_DETAIL&file_id=b461a0f0cfaa43f5b61be60b9d7f40ae"
          ], 
          "width": 576
        }, 
        "ratio": "540p", 
        "tags": null, 
        "width": 908
      }, 
      "video_control": {
        "allow_download": false, 
        "allow_duet": false, 
        "allow_dynamic_wallpaper": false, 
        "allow_music": true, 
        "allow_react": true, 
        "allow_stitch": false, 
        "draft_progress_bar": 1, 
        "prevent_download_type": 2, 
        "share_type": 0, 
        "show_progress_bar": 1, 
        "timer_status": 1
      }, 
      "video_labels": [], 
      "video_text": [], 
      "with_promotional_music": false, 
      "without_watermark": false
    }
  ], 
  "aweme_status": null, 
  "extra": {
    "fatal_item_ids": [], 
    "logid": "202205122125340102450400760A0C892D", 
    "now": 1652390735000
  }, 
  "log_pb": {
    "impr_id": "202205122125340102450400760A0C892D"
  }, 
  "status_code": 0
}
```
