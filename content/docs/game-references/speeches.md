---
title: Speeches
---

Example
-------

### Lua

```lua
-- Create a random ped
local coords = GetEntityCoords(PlayerPedId(), false)
local ped = CreateRandomPed(coords.x, coords.y, coords.z)

-- Makes the ped shout an insult
PlayPedAmbientSpeechNative(ped, GENERIC_INSULT_HIGH--[[speechName]], SPEECH_PARAMS_FORCE--[[speechParam]])
```

Speech Params
------------

|Speech Param|Description|
|--|--|
|`SPEECH_PARAMS_ADD_BLIP`||
|`SPEECH_PARAMS_ADD_BLIP_ALLOW_REPEAT`||
|`SPEECH_PARAMS_ADD_BLIP_FORCE`||
|`SPEECH_PARAMS_ADD_BLIP_INTERRUPT`||
|`SPEECH_PARAMS_ADD_BLIP_INTERRUPT_FORCE`||
|`SPEECH_PARAMS_ADD_BLIP_SHOUTED`||
|`SPEECH_PARAMS_ADD_BLIP_SHOUTED_FORCE`||
|`SPEECH_PARAMS_ALLOW_REPEAT`||
|`SPEECH_PARAMS_BEAT`||
|`SPEECH_PARAMS_FORCE`||
|`SPEECH_PARAMS_FORCE_FRONTEND`||
|`SPEECH_PARAMS_FORCE_HELI`||
|`SPEECH_PARAMS_FORCE_MEGAPHONE`||
|`SPEECH_PARAMS_FORCE_NORMAL`||
|`SPEECH_PARAMS_FORCE_NORMAL_CLEAR`||
|`SPEECH_PARAMS_FORCE_NORMAL_CRITICAL`||
|`SPEECH_PARAMS_FORCE_NO_REPEAT_FRONTEND`||
|`SPEECH_PARAMS_FORCE_PRELOAD_ONLY`||
|`SPEECH_PARAMS_FORCE_PRELOAD_ONLY_SHOUTED`||
|`SPEECH_PARAMS_FORCE_PRELOAD_ONLY_SHOUTED_CLEAR`||
|`SPEECH_PARAMS_FORCE_PRELOAD_ONLY_SHOUTED_CRITICAL`||
|`SPEECH_PARAMS_FORCE_SHOUTED`||
|`SPEECH_PARAMS_FORCE_SHOUTED_CLEAR`||
|`SPEECH_PARAMS_FORCE_SHOUTED_CRITICAL`||
|`SPEECH_PARAMS_HELI`||
|`SPEECH_PARAMS_INTERRUPT`||
|`SPEECH_PARAMS_INTERRUPT_FRONTEND`||
|`SPEECH_PARAMS_INTERRUPT_NO_FORCE`||
|`SPEECH_PARAMS_INTERRUPT_NO_FORCE_FRONTEND`||
|`SPEECH_PARAMS_INTERRUPT_SHOUTED`||
|`SPEECH_PARAMS_INTERRUPT_SHOUTED_CLEAR`||
|`SPEECH_PARAMS_INTERRUPT_SHOUTED_CRITICAL`||
|`SPEECH_PARAMS_MEGAPHONE`||
|`SPEECH_PARAMS_SHOUTED`||
|`SPEECH_PARAMS_SHOUTED_CLEAR`||
|`SPEECH_PARAMS_SHOUTED_CRITICAL`||
|`SPEECH_PARAMS_STANDARD`||
|`SPEECH_PARAMS_STANDARD_SHORT_LOAD`||
|`0x37e09d70`||
|`0xfc88a240`||

Speech Names
--------

|Speech Name|Description|
|--|--|
|`ABOUT_TO_DIE_SC`||
|`ACTIVITY_LEAVING_SC`||
|`AGREE_ACROSS_STREET_SC`||
|`AIMED_AT_BY_PLAYER_SC`||
|`AIRROCKING_SC`||
|`ANGRY_WITH_PLAYER_FRANKLIN_SC`||
|`ANGRY_WITH_PLAYER_MICHAEL_SC`||
|`ANGRY_WITH_PLAYER_TREVOR_SC`||
|`APOLOGY_NO_TROUBLE_SC`||
|`ARM_LEAVE_SC`||
|`ARM_LOSE_SC`||
|`ARM_LOST_SC`||
|`ARM_OFFER_SC`||
|`ARM_TAUNT_SC`||
|`ARM_TIRED_SC`||
|`ARM_WON_SC`||
|`ARRESTED_SC`||
|`ARREST_PLAYER_SC`||
|`ARRIVAL_ANNOUNCE_SC`||
|`BARTENDER_GREET_SC`||
|`BARTENDER_SERVE_SC`||
|`BASEJUMP_ABOUT_TO_JUMP_SC`||
|`BASEJUMP_FAIL_SC`||
|`BASEJUMP_SUCCESS_SC`||
|`BLIND_RAGE_SC`||
|`BLOCKED_GENERIC_SC`||
|`BLOCKED_IN_PURSUIT_SC`||
|`BOOTY_FLIRT_RESP_SC`||
|`BOOTY_FLIRT_SC`||
|`BOUNCER_COMMENTS_ON_UNDERWEAR_SC`||
|`BOUNCER_EJECT_TOUCH_SC`||
|`BOUNCER_GREET_FRANKLIN_LIKE_SC`||
|`BOUNCER_GREET_MICHAEL_LIKE_SC`||
|`BOUNCER_GREET_PLAYER_NEUTRAL_SC`||
|`BOUNCER_GREET_TREVOR_LIKE_SC`||
|`BOUNCER_GREET_TREVOR_OWNS_SC`||
|`BOUNCER_PLAYER_MISBEHAVING_TREVOR_OWNS_SC`||
|`BUDDY_DOWN_SC`||
|`BUDDY_SEES_FRANKLIN_DEATH_SC`||
|`BUDDY_SEES_MICHAEL_DEATH_SC`||
|`BUDDY_SEES_TREVOR_DEATH_SC`||
|`BUMP_REPEAT_SC`||
|`BUMP_SC`||
|`BUM_SPARE_CHANGE_SC`||
|`BUY_DRUGS_SC`||
|`CALL_CHOP_SC`||
|`CALL_COPS_COMMIT_SC`||
|`CALL_COPS_THREAT_SC`||
|`CANT_LOSE_ENEMY_SC`||
|`CAR_HIT_PED_DRIVEN_SC`||
|`CAR_HIT_PED_SC`||
|`CHALLENGE_ACCEPTED_BUMPED_INTO_SC`||
|`CHALLENGE_ACCEPTED_GENERIC_SC`||
|`CHALLENGE_ACCEPTED_HIT_CAR_SC`||
|`CHALLENGE_THREATEN_SC`||
|`CHASED_BY_POLICE_SC`||
|`CHASE_VEHICLE_MEGAPHONE_SC`||
|`CHAT_ACROSS_STREET_RESP_SC`||
|`CHAT_ACROSS_STREET_STATE_SC`||
|`CHAT_RESP_SC`||
|`CHAT_STATE_SC`||
|`CINEMA_DISLIKED_SC`||
|`CINEMA_LEFT_EARLY_SC`||
|`CINEMA_LIKED_SC`||
|`CLEAR_AREA_MEGAPHONE_SC`||
|`CLEAR_AREA_PANIC_MEGAPHONE_SC`||
|`CLEAR_THROAT_SC`||
|`CLIMB_LARGE_SC`||
|`CLIMB_SMALL_SC`||
|`COMBAT_TAUNT_SC`||
|`COME_OVER_HERE_SC`||
|`COP_ARRIVAL_ANNOUNCE_MEGAPHONE_SC`||
|`COP_ARRIVAL_ANNOUNCE_SC`||
|`COP_PEEK_SC`||
|`COP_SEES_GRENADE_LAUNCHER_SC`||
|`COP_SEES_GRENADE_SC`||
|`COP_SEES_GUN_SC`||
|`COP_SEES_MINI_GUN_SC`||
|`COP_SEES_ROCKET_LAUNCHER_SC`||
|`COP_SEES_WEAPON_SC`||
|`COP_TALKDOWN_SC`||
|`COUGH_SC`||
|`COVER_ME_SC`||
|`COVER_YOU_SC`||
|`COWER_SC`||
|`CRASH_CAR_DRIVEN_SC`||
|`CRASH_CAR_SC`||
|`CRASH_GENERIC_DRIVEN_SC`||
|`CRASH_GENERIC_INTERRUPT_SC`||
|`CRASH_GENERIC_SC`||
|`CRASH_MOTORCYCLE_SC`||
|`CREWHASH`||
|`CRIMINAL_APPREHEND_SC`||
|`CRIMINAL_GET_IN_CAR_SC`||
|`CRIMINAL_WARNING_SC`||
|`CULT_TALK_SC`||
|`DARTS_140_SC`||
|`DARTS_180_SC`||
|`DARTS_1_DART_AWAY_SC`||
|`DARTS_BOAST_SC`||
|`DARTS_BORED_SC`||
|`DARTS_BULLSEYE_SC`||
|`DARTS_BUST_SC`||
|`DARTS_CHAT_WITH_FRANKLIN_SC`||
|`DARTS_CHAT_WITH_MICHAEL_SC`||
|`DARTS_CHAT_WITH_TREVOR_SC`||
|`DARTS_HAPPY_SC`||
|`DARTS_INVITE_SC`||
|`DARTS_LOSE_SC`||
|`DARTS_LOSING_BADLY_SC`||
|`DARTS_MISS_BOARD_SC`||
|`DARTS_PLAYING_POORLY_SC`||
|`DARTS_PLAYING_WELL_SC`||
|`DARTS_REQUEST_GAME_SC`||
|`DARTS_WIN_SC`||
|`DEATH_GARGLE_SC`||
|`DEATH_HIGH_LONG_SC`||
|`DEATH_HIGH_MEDIUM_SC`||
|`DEATH_HIGH_SHORT_SC`||
|`DEATH_LOW_GENERIC_SC`||
|`DEATH_LOW_TOUGH_SC`||
|`DEATH_LOW_WEAK_SC`||
|`DEATH_UNDERWATER_SC`||
|`DEFAULT_SPEECH_CONTEXT_SC`||
|`DISMISS_MICHAEL_SC`||
|`DISPUTE_FLEE_SC`||
|`DISPUTE_HURRY_SC`||
|`DODGE_SC`||
|`DONOTHING998271`||
|`DONT_IGNORE_ME_INSULT_SC`||
|`DONT_IGNORE_ME_SC`||
|`DRAW_GUN_SC`||
|`DRINK_BAD_SC`||
|`DRINK_GOOD_SC`||
|`DRIVEN_FAST_SC`||
|`DRIVEN_SLOW_SC`||
|`DROWNING_SC`||
|`DUCK_SC`||
|`DYING_MOAN_SC`||
|`ELECTROCUTION_SC`||
|`ENEMY_NOT_SPOTTED_SC`||
|`ENEMY_SPOTTED_BEHIND_SC`||
|`ENEMY_SPOTTED_DOWN_SC`||
|`ENEMY_SPOTTED_FRONT_SC`||
|`ENEMY_SPOTTED_LEFT_SC`||
|`ENEMY_SPOTTED_RIGHT_SC`||
|`ENEMY_SPOTTED_SC`||
|`ENEMY_SPOTTED_UP_SC`||
|`EPSILON_SITE_VISIT_BACKOUT_SC`||
|`EVENT_SHOT_FIRED_BULLET_IMPACT_SC`||
|`EVENT_SHOT_FIRED_SC`||
|`EVENT_SHOT_FIRED_WHIZZED_BY_SC`||
|`EVENT_VEHICLE_ON_FIRE_SC`||
|`EXCUSE_ME_SC`||
|`EXERCISING_SC`||
|`EXHALE_SC`||
|`EXPLOSION_IS_IMMINENT_SC`||
|`EXTREME_GRIEFING_SC`||
|`FALL_BACK_SC`||
|`FCH_FAIL_RP_TIME_PERIOD_10_DIVIDER`||
|`FIGHT_CHEER_SC`||
|`FIGHT_RUN_SC`||
|`FIGHT_SC`||
|`FIRE_IS_OUT_SC`||
|`FLYING_LOW_SKILL_SC`||
|`FOOD_DISLIKED_SC`||
|`FOOD_LIKED_SC`||
|`FOOT_CHASE_HEADING_EAST_SC`||
|`FOOT_CHASE_HEADING_NORTH_SC`||
|`FOOT_CHASE_HEADING_SOUTH_SC`||
|`FOOT_CHASE_HEADING_WEST_SC`||
|`FOOT_CHASE_LOSING_SC`||
|`FOOT_CHASE_RESPONSE_SC`||
|`FOOT_CHASE_SC`||
|`FREEZE_SC`||
|`FRIEND_FOLLOWED_BY_PLAYER_SC`||
|`GAME_BAD_OTHER_SC`||
|`GAME_BAD_SELF_SC`||
|`GAME_GOOD_OTHER_SC`||
|`GAME_GOOD_SELF_SC`||
|`GAME_HECKLE_SC`||
|`GAME_LOSE_SELF_SC`||
|`GAME_QUIT_EARLY_SC`||
|`GAME_QUIT_SC`||
|`GAME_WIN_SELF_SC`||
|`GANG_BUMP_SC`||
|`GASMASK_CHOKE_SC`||
|`GENERIC_AGREE_SC`||
|`GENERIC_BUY_REPEAT_SC`||
|`GENERIC_BUY_SC`||
|`GENERIC_BYE_SC`||
|`GENERIC_CHEER_SC`||
|`GENERIC_CURSE_HIGH_SC`||
|`GENERIC_CURSE_MED_SC`||
|`GENERIC_DEJECTED_SC`||
|`GENERIC_DRINK_SC`||
|`GENERIC_EAT_SC`||
|`GENERIC_FRIGHTENED_HIGH_SC`||
|`GENERIC_FRIGHTENED_MED_SC`||
|`GENERIC_FRUSTRATED_HIGH_SC`||
|`GENERIC_FRUSTRATED_MED_SC`||
|`GENERIC_FUCK_OFF_SC`||
|`GENERIC_FUCK_YOU_SC`||
|`GENERIC_HI_FEMALE_SC`||
|`GENERIC_HI_FLIRTY_SC`||
|`GENERIC_HI_MALE_SC`||
|`GENERIC_HI_SC`||
|`GENERIC_HOWS_IT_GOING_SC`||
|`GENERIC_INSULT_FEMALE_SC`||
|`GENERIC_INSULT_HIGH_SC`||
|`GENERIC_INSULT_MALE_SC`||
|`GENERIC_INSULT_MED_SC`||
|`GENERIC_INSULT_OLD_SC`||
|`GENERIC_INTERRUPT_ANNOYED_SC`||
|`GENERIC_INTERRUPT_HIGH_SC`||
|`GENERIC_INTERRUPT_MED_SC`||
|`GENERIC_NO_SC`||
|`GENERIC_OUT_OF_MY_WAY_SC`||
|`GENERIC_SHOCKED_HIGH_SC`||
|`GENERIC_SHOCKED_MED_SC`||
|`GENERIC_THANKS_SC`||
|`GENERIC_TRIATHLON_COMMENT_SC`||
|`GENERIC_WAR_CRY_SC`||
|`GENERIC_WHATEVER_SC`||
|`GENERIC_YES_SC`||
|`GETTING_OLD_SC`||
|`GET_HIM_SC`||
|`GET_IN_VEHICLE_SC`||
|`GET_OUT_OF_HERE_SC`||
|`GET_OUT_OF_THE_CAR_SC`||
|`GET_UP_FROM_FALL_SC`||
|`GET_WANTED_LEVEL_SC`||
|`GIGGLE_SC`||
|`GOLF_ABOUT_TO_TAKE_SHOT_SC`||
|`GOLF_BAD_LIE_OTHER_SC`||
|`GOLF_BAD_LIE_SELF_SC`||
|`GOLF_BUNKER_OTHER_SC`||
|`GOLF_BUNKER_SELF_SC`||
|`GOLF_CHAT_SC`||
|`GOLF_CHAT_WITH_FRANKLIN_SC`||
|`GOLF_CHAT_WITH_MICHAEL_SC`||
|`GOLF_CHAT_WITH_TREVOR_SC`||
|`GOLF_FORE_SELF_SC`||
|`GOLF_FRUSTRATION_SC`||
|`GOLF_GOOD_LIE_OTHER_SC`||
|`GOLF_IDLE_OTHER_SC`||
|`GOLF_MISS_PUTT_OTHER_SC`||
|`GOLF_MISS_PUTT_SELF_SC`||
|`GOLF_SHOT_BAD_HIT_SELF_SC`||
|`GOLF_SHOT_GOOD_HIT_SELF_SC`||
|`GOLF_SINK_PUTT_OTHER_SC`||
|`GOLF_SINK_PUTT_SELF_SC`||
|`GOODBYE_ACROSS_STREET_SC`||
|`GREET_ACROSS_STREET_SC`||
|`GREET_ATTRACTIVE_F_SC`||
|`GREET_BUM_SC`||
|`GREET_COP_SC`||
|`GREET_EVENING_SC`||
|`GREET_GANG_BALLAS_F_SC`||
|`GREET_GANG_BALLAS_M_SC`||
|`GREET_GANG_FAMILIES_F_SC`||
|`GREET_GANG_FAMILIES_M_SC`||
|`GREET_GANG_VAGOS_F_SC`||
|`GREET_GANG_VAGOS_M_SC`||
|`GREET_HILLBILLY_M_SC`||
|`GREET_HIPPY_F_SC`||
|`GREET_HIPPY_M_SC`||
|`GREET_HIPSTER_F_SC`||
|`GREET_HIPSTER_M_SC`||
|`GREET_JEWISH_SC`||
|`GREET_JUNKIE_SC`||
|`GREET_KOREAN_SC`||
|`GREET_MORNING_SC`||
|`GREET_SC`||
|`GREET_STRONG_M_SC`||
|`GREET_TRANSVESTITE_SC`||
|`GUN_BEG_SC`||
|`GUN_COOL_SC`||
|`GUN_STAND_OFF_SC`||
|`HIGH_FALL_DEATH_SC`||
|`HIGH_FALL_SC`||
|`HIT_BY_PLAYER_SC`||
|`HIT_WOMAN_SC`||
|`HOOKER_CAR_INCORRECT_SC`||
|`HOOKER_CHAT_SOLO_SC`||
|`HOOKER_DECLINED_SC`||
|`HOOKER_DECLINED_TREVOR_SC`||
|`HOOKER_DECLINE_SERVICE_SC`||
|`HOOKER_HAD_ENOUGH_SC`||
|`HOOKER_LEAVES_ANGRY_SC`||
|`HOOKER_OFFER_AGAIN_SC`||
|`HOOKER_OFFER_SERVICE_SC`||
|`HOOKER_REQUEST_SC`||
|`HOOKER_SECLUDED_SC`||
|`HOOKER_STORY_REVULSION_RESP_SC`||
|`HOOKER_STORY_SARCASTIC_RESP_SC`||
|`HOOKER_STORY_SC`||
|`HOOKER_STORY_SYMPATHETIC_RESP_SC`||
|`HOWS_IT_GOING_FEMALE_SC`||
|`HOWS_IT_GOING_GENERIC_SC`||
|`HOWS_IT_GOING_MALE_SC`||
|`HUNTING_KILL_SC`||
|`HUNTING_MISSED_SC`||
|`HUNTING_SPOT_ANIMAL_SC`||
|`HUNTING_SPOT_COUGAR_SC`||
|`HURRY_UP_SC`||
|`INHALE_SC`||
|`INSULT_DEAD_PED_SC`||
|`INSULT_PED_BUM_CONV01_PART1_SC`||
|`INSULT_PED_BUM_CONV01_PART2_SC`||
|`INSULT_PED_BUM_CONV01_PART3_SC`||
|`INSULT_PED_BUM_CONV02_PART1_SC`||
|`INSULT_PED_BUM_CONV02_PART2_SC`||
|`INSULT_PED_BUM_CONV02_PART3_SC`||
|`INSULT_PED_BUM_CONV03_PART1_SC`||
|`INSULT_PED_BUM_CONV03_PART2_SC`||
|`INSULT_PED_BUM_CONV03_PART3_SC`||
|`INSULT_PED_BUM_CONV04_PART1_SC`||
|`INSULT_PED_BUM_CONV04_PART2_SC`||
|`INSULT_PED_BUM_CONV04_PART3_SC`||
|`INSULT_PED_BUM_CONV05_PART1_SC`||
|`INSULT_PED_BUM_CONV05_PART2_SC`||
|`INSULT_PED_BUM_CONV05_PART3_SC`||
|`INSULT_PED_BUM_CONV06_PART1_SC`||
|`INSULT_PED_BUM_CONV06_PART2_SC`||
|`INSULT_PED_BUM_CONV06_PART3_SC`||
|`INSULT_PED_BUM_CONV07_PART1_SC`||
|`INSULT_PED_BUM_CONV07_PART2_SC`||
|`INSULT_PED_BUM_CONV07_PART3_SC`||
|`INSULT_PED_BUM_CONV08_PART2_SC`||
|`INSULT_PED_BUM_CONV08_PART3_SC`||
|`INSULT_PED_BUM_CONV09_PART1_SC`||
|`INSULT_PED_BUM_CONV09_PART2_SC`||
|`INSULT_PED_BUM_CONV09_PART3_SC`||
|`INSULT_PED_BUM_CONV10_PART1_SC`||
|`INSULT_PED_BUM_CONV10_PART2_SC`||
|`INSULT_PED_BUM_CONV10_PART3_SC`||
|`INSULT_PED_BUM_CONV11_PART1_SC`||
|`INSULT_PED_BUM_CONV11_PART2_SC`||
|`INSULT_PED_BUM_CONV11_PART3_SC`||
|`INSULT_PED_BUM_CONV12_PART1_SC`||
|`INSULT_PED_BUM_CONV12_PART2_SC`||
|`INSULT_PED_BUM_CONV12_PART3_SC`||
|`INSULT_PED_BUM_CONV13_PART1_SC`||
|`INSULT_PED_BUM_CONV13_PART2_SC`||
|`INSULT_PED_BUM_CONV13_PART3_SC`||
|`INSULT_PED_BUM_CONV14_PART1_SC`||
|`INSULT_PED_BUM_CONV14_PART2_SC`||
|`INSULT_PED_BUM_CONV14_PART3_SC`||
|`INSULT_PED_BUM_CONV15_PART1_SC`||
|`INSULT_PED_BUM_CONV15_PART2_SC`||
|`INSULT_PED_BUM_CONV15_PART3_SC`||
|`INSULT_PED_COP_CONV01_PART1_SC`||
|`INSULT_PED_COP_CONV01_PART2_SC`||
|`INSULT_PED_COP_CONV01_PART3_SC`||
|`INSULT_PED_COP_CONV02_PART1_SC`||
|`INSULT_PED_COP_CONV02_PART2_SC`||
|`INSULT_PED_COP_CONV02_PART3_SC`||
|`INSULT_PED_COP_CONV03_PART1_SC`||
|`INSULT_PED_COP_CONV03_PART2_SC`||
|`INSULT_PED_COP_CONV03_PART3_SC`||
|`INSULT_PED_COP_CONV04_PART1_SC`||
|`INSULT_PED_COP_CONV04_PART2_SC`||
|`INSULT_PED_COP_CONV04_PART3_SC`||
|`INSULT_PED_COP_CONV05_PART1_SC`||
|`INSULT_PED_COP_CONV05_PART2_SC`||
|`INSULT_PED_COP_CONV05_PART3_SC`||
|`INSULT_PED_COP_CONV06_PART1_SC`||
|`INSULT_PED_COP_CONV06_PART2_SC`||
|`INSULT_PED_COP_CONV06_PART3_SC`||
|`INSULT_PED_COP_CONV07_PART1_SC`||
|`INSULT_PED_COP_CONV07_PART2_SC`||
|`INSULT_PED_COP_CONV07_PART3_SC`||
|`INSULT_PED_COP_CONV08_PART1_SC`||
|`INSULT_PED_COP_CONV08_PART2_SC`||
|`INSULT_PED_COP_CONV08_PART3_SC`||
|`INSULT_PED_COP_CONV09_PART1_SC`||
|`INSULT_PED_COP_CONV09_PART2_SC`||
|`INSULT_PED_COP_CONV09_PART3_SC`||
|`INSULT_PED_COP_CONV10_PART1_SC`||
|`INSULT_PED_COP_CONV10_PART2_SC`||
|`INSULT_PED_COP_CONV10_PART3_SC`||
|`INSULT_PED_COP_CONV11_PART1_SC`||
|`INSULT_PED_COP_CONV11_PART2_SC`||
|`INSULT_PED_COP_CONV11_PART3_SC`||
|`INSULT_PED_COP_CONV12_PART1_SC`||
|`INSULT_PED_COP_CONV12_PART2_SC`||
|`INSULT_PED_COP_CONV12_PART3_SC`||
|`INSULT_PED_COP_CONV13_PART1_SC`||
|`INSULT_PED_COP_CONV13_PART2_SC`||
|`INSULT_PED_COP_CONV13_PART3_SC`||
|`INSULT_PED_COP_CONV14_PART1_SC`||
|`INSULT_PED_COP_CONV14_PART2_SC`||
|`INSULT_PED_COP_CONV14_PART3_SC`||
|`INSULT_PED_COP_CONV15_PART1_SC`||
|`INSULT_PED_COP_CONV15_PART2_SC`||
|`INSULT_PED_COP_CONV15_PART3_SC`||
|`INSULT_PED_FAT_CONV01_PART1_SC`||
|`INSULT_PED_FAT_CONV01_PART2_SC`||
|`INSULT_PED_FAT_CONV01_PART3_SC`||
|`INSULT_PED_FAT_CONV02_PART1_SC`||
|`INSULT_PED_FAT_CONV02_PART2_SC`||
|`INSULT_PED_FAT_CONV02_PART3_SC`||
|`INSULT_PED_FAT_CONV03_PART1_SC`||
|`INSULT_PED_FAT_CONV03_PART2_SC`||
|`INSULT_PED_FAT_CONV03_PART3_SC`||
|`INSULT_PED_FAT_CONV04_PART1_SC`||
|`INSULT_PED_FAT_CONV04_PART2_SC`||
|`INSULT_PED_FAT_CONV04_PART3_SC`||
|`INSULT_PED_FAT_CONV05_PART1_SC`||
|`INSULT_PED_FAT_CONV05_PART2_SC`||
|`INSULT_PED_FAT_CONV05_PART3_SC`||
|`INSULT_PED_FAT_CONV06_PART1_SC`||
|`INSULT_PED_FAT_CONV06_PART2_SC`||
|`INSULT_PED_FAT_CONV06_PART3_SC`||
|`INSULT_PED_FAT_CONV07_PART1_SC`||
|`INSULT_PED_FAT_CONV07_PART2_SC`||
|`INSULT_PED_FAT_CONV07_PART3_SC`||
|`INSULT_PED_FAT_CONV08_PART1_SC`||
|`INSULT_PED_FAT_CONV08_PART2_SC`||
|`INSULT_PED_FAT_CONV08_PART3_SC`||
|`INSULT_PED_FAT_CONV09_PART1_SC`||
|`INSULT_PED_FAT_CONV09_PART2_SC`||
|`INSULT_PED_FAT_CONV09_PART3_SC`||
|`INSULT_PED_FAT_CONV10_PART1_SC`||
|`INSULT_PED_FAT_CONV10_PART2_SC`||
|`INSULT_PED_FAT_CONV10_PART3_SC`||
|`INSULT_PED_FAT_CONV11_PART1_SC`||
|`INSULT_PED_FAT_CONV11_PART2_SC`||
|`INSULT_PED_FAT_CONV11_PART3_SC`||
|`INSULT_PED_FAT_CONV12_PART1_SC`||
|`INSULT_PED_FAT_CONV12_PART2_SC`||
|`INSULT_PED_FAT_CONV12_PART3_SC`||
|`INSULT_PED_FAT_CONV13_PART1_SC`||
|`INSULT_PED_FAT_CONV13_PART2_SC`||
|`INSULT_PED_FAT_CONV13_PART3_SC`||
|`INSULT_PED_FAT_CONV14_PART1_SC`||
|`INSULT_PED_FAT_CONV14_PART2_SC`||
|`INSULT_PED_FAT_CONV14_PART3_SC`||
|`INSULT_PED_FAT_CONV15_PART1_SC`||
|`INSULT_PED_FAT_CONV15_PART2_SC`||
|`INSULT_PED_FAT_CONV15_PART3_SC`||
|`INSULT_PED_GANG_CONV01_PART1_SC`||
|`INSULT_PED_GANG_CONV01_PART2_SC`||
|`INSULT_PED_GANG_CONV01_PART3_SC`||
|`INSULT_PED_GANG_CONV02_PART1_SC`||
|`INSULT_PED_GANG_CONV02_PART2_SC`||
|`INSULT_PED_GANG_CONV02_PART3_SC`||
|`INSULT_PED_GANG_CONV03_PART1_SC`||
|`INSULT_PED_GANG_CONV03_PART2_SC`||
|`INSULT_PED_GANG_CONV03_PART3_SC`||
|`INSULT_PED_GANG_CONV04_PART1_SC`||
|`INSULT_PED_GANG_CONV04_PART2_SC`||
|`INSULT_PED_GANG_CONV04_PART3_SC`||
|`INSULT_PED_GANG_CONV05_PART1_SC`||
|`INSULT_PED_GANG_CONV05_PART2_SC`||
|`INSULT_PED_GANG_CONV05_PART3_SC`||
|`INSULT_PED_GANG_CONV06_PART1_SC`||
|`INSULT_PED_GANG_CONV06_PART2_SC`||
|`INSULT_PED_GANG_CONV06_PART3_SC`||
|`INSULT_PED_GANG_CONV07_PART1_SC`||
|`INSULT_PED_GANG_CONV07_PART2_SC`||
|`INSULT_PED_GANG_CONV07_PART3_SC`||
|`INSULT_PED_GANG_CONV08_PART1_SC`||
|`INSULT_PED_GANG_CONV08_PART2_SC`||
|`INSULT_PED_GANG_CONV08_PART3_SC`||
|`INSULT_PED_GANG_CONV09_PART1_SC`||
|`INSULT_PED_GANG_CONV09_PART2_SC`||
|`INSULT_PED_GANG_CONV09_PART3_SC`||
|`INSULT_PED_GANG_CONV10_PART1_SC`||
|`INSULT_PED_GANG_CONV10_PART2_SC`||
|`INSULT_PED_GANG_CONV10_PART3_SC`||
|`INSULT_PED_GANG_CONV11_PART1_SC`||
|`INSULT_PED_GANG_CONV11_PART2_SC`||
|`INSULT_PED_GANG_CONV11_PART3_SC`||
|`INSULT_PED_GANG_CONV12_PART1_SC`||
|`INSULT_PED_GANG_CONV12_PART2_SC`||
|`INSULT_PED_GANG_CONV12_PART3_SC`||
|`INSULT_PED_GANG_CONV13_PART1_SC`||
|`INSULT_PED_GANG_CONV13_PART2_SC`||
|`INSULT_PED_GANG_CONV13_PART3_SC`||
|`INSULT_PED_GANG_CONV14_PART1_SC`||
|`INSULT_PED_GANG_CONV14_PART2_SC`||
|`INSULT_PED_GANG_CONV14_PART3_SC`||
|`INSULT_PED_GANG_CONV15_PART1_SC`||
|`INSULT_PED_GANG_CONV15_PART2_SC`||
|`INSULT_PED_GANG_CONV15_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV01_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV01_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV01_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV02_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV02_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV02_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV03_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV03_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV03_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV04_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV04_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV04_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV05_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV05_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV05_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV06_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV06_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV06_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV07_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV07_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV07_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV08_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV08_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV08_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV09_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV09_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV09_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV10_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV10_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV10_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV11_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV11_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV11_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV12_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV12_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV12_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV13_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV13_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV14_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV14_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV14_PART3_SC`||
|`INSULT_PED_HIPSTER_CONV15_PART1_SC`||
|`INSULT_PED_HIPSTER_CONV15_PART2_SC`||
|`INSULT_PED_HIPSTER_CONV15_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV01_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV01_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV01_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV02_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV02_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV02_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV03_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV03_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV03_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV04_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV04_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV04_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV05_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV05_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV05_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV06_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV06_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV06_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV07_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV07_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV07_PART3_SC`||
|`INSULT_PED_JUNKIE_CONV08_PART1_SC`||
|`INSULT_PED_JUNKIE_CONV08_PART2_SC`||
|`INSULT_PED_JUNKIE_CONV08_PART3_SC`||
|`INSULT_PED_OLD_CONV01_PART1_SC`||
|`INSULT_PED_OLD_CONV01_PART2_SC`||
|`INSULT_PED_OLD_CONV01_PART3_SC`||
|`INSULT_PED_OLD_CONV02_PART1_SC`||
|`INSULT_PED_OLD_CONV02_PART2_SC`||
|`INSULT_PED_OLD_CONV02_PART3_SC`||
|`INSULT_PED_OLD_CONV03_PART1_SC`||
|`INSULT_PED_OLD_CONV03_PART2_SC`||
|`INSULT_PED_OLD_CONV03_PART3_SC`||
|`INSULT_PED_OLD_CONV04_PART1_SC`||
|`INSULT_PED_OLD_CONV04_PART2_SC`||
|`INSULT_PED_OLD_CONV04_PART3_SC`||
|`INSULT_PED_OLD_CONV05_PART1_SC`||
|`INSULT_PED_OLD_CONV05_PART2_SC`||
|`INSULT_PED_OLD_CONV05_PART3_SC`||
|`INSULT_PED_OLD_CONV06_PART1_SC`||
|`INSULT_PED_OLD_CONV06_PART2_SC`||
|`INSULT_PED_OLD_CONV06_PART3_SC`||
|`INSULT_PED_OLD_CONV07_PART1_SC`||
|`INSULT_PED_OLD_CONV07_PART2_SC`||
|`INSULT_PED_OLD_CONV07_PART3_SC`||
|`INSULT_PED_OLD_CONV08_PART1_SC`||
|`INSULT_PED_OLD_CONV08_PART2_SC`||
|`INSULT_PED_OLD_CONV08_PART3_SC`||
|`INSULT_PED_OLD_CONV09_PART1_SC`||
|`INSULT_PED_OLD_CONV09_PART2_SC`||
|`INSULT_PED_OLD_CONV09_PART3_SC`||
|`INSULT_PED_OLD_CONV10_PART1_SC`||
|`INSULT_PED_OLD_CONV10_PART2_SC`||
|`INSULT_PED_OLD_CONV10_PART3_SC`||
|`INSULT_PED_OLD_CONV11_PART1_SC`||
|`INSULT_PED_OLD_CONV11_PART2_SC`||
|`INSULT_PED_OLD_CONV11_PART3_SC`||
|`INSULT_PED_OLD_CONV12_PART1_SC`||
|`INSULT_PED_OLD_CONV12_PART2_SC`||
|`INSULT_PED_OLD_CONV12_PART3_SC`||
|`INSULT_PED_OLD_CONV13_PART1_SC`||
|`INSULT_PED_OLD_CONV13_PART2_SC`||
|`INSULT_PED_OLD_CONV13_PART3_SC`||
|`INSULT_PED_OLD_CONV14_PART1_SC`||
|`INSULT_PED_OLD_CONV14_PART2_SC`||
|`INSULT_PED_OLD_CONV14_PART3_SC`||
|`INSULT_PED_OLD_CONV15_PART1_SC`||
|`INSULT_PED_OLD_CONV15_PART2_SC`||
|`INSULT_PED_OLD_CONV15_PART3_SC`||
|`INSULT_PED_TOUGH_CONV01_PART1_SC`||
|`INSULT_PED_TOUGH_CONV01_PART2_SC`||
|`INSULT_PED_TOUGH_CONV01_PART3_SC`||
|`INSULT_PED_TOUGH_CONV02_PART1_SC`||
|`INSULT_PED_TOUGH_CONV02_PART2_SC`||
|`INSULT_PED_TOUGH_CONV02_PART3_SC`||
|`INSULT_PED_TOUGH_CONV03_PART1_SC`||
|`INSULT_PED_TOUGH_CONV03_PART2_SC`||
|`INSULT_PED_TOUGH_CONV03_PART3_SC`||
|`INSULT_PED_TOUGH_CONV04_PART1_SC`||
|`INSULT_PED_TOUGH_CONV04_PART2_SC`||
|`INSULT_PED_TOUGH_CONV04_PART3_SC`||
|`INSULT_PED_TOUGH_CONV05_PART1_SC`||
|`INSULT_PED_TOUGH_CONV05_PART2_SC`||
|`INSULT_PED_TOUGH_CONV05_PART3_SC`||
|`INSULT_PED_TOUGH_CONV06_PART1_SC`||
|`INSULT_PED_TOUGH_CONV06_PART2_SC`||
|`INSULT_PED_TOUGH_CONV06_PART3_SC`||
|`INSULT_PED_TOUGH_CONV07_PART1_SC`||
|`INSULT_PED_TOUGH_CONV07_PART2_SC`||
|`INSULT_PED_TOUGH_CONV07_PART3_SC`||
|`INSULT_PED_TOUGH_CONV08_PART1_SC`||
|`INSULT_PED_TOUGH_CONV08_PART2_SC`||
|`INSULT_PED_TOUGH_CONV08_PART3_SC`||
|`INSULT_PED_TOUGH_CONV09_PART1_SC`||
|`INSULT_PED_TOUGH_CONV09_PART2_SC`||
|`INSULT_PED_TOUGH_CONV09_PART3_SC`||
|`INSULT_PED_TOUGH_CONV10_PART1_SC`||
|`INSULT_PED_TOUGH_CONV10_PART2_SC`||
|`INSULT_PED_TOUGH_CONV10_PART3_SC`||
|`INSULT_PED_TOUGH_CONV11_PART1_SC`||
|`INSULT_PED_TOUGH_CONV11_PART2_SC`||
|`INSULT_PED_TOUGH_CONV11_PART3_SC`||
|`INSULT_PED_TOUGH_CONV12_PART1_SC`||
|`INSULT_PED_TOUGH_CONV12_PART2_SC`||
|`INSULT_PED_TOUGH_CONV12_PART3_SC`||
|`INSULT_PED_TOUGH_CONV13_PART1_SC`||
|`INSULT_PED_TOUGH_CONV13_PART2_SC`||
|`INSULT_PED_TOUGH_CONV13_PART3_SC`||
|`INSULT_PED_TOUGH_CONV14_PART1_SC`||
|`INSULT_PED_TOUGH_CONV14_PART2_SC`||
|`INSULT_PED_TOUGH_CONV14_PART3_SC`||
|`INSULT_PED_TOUGH_CONV15_PART1_SC`||
|`INSULT_PED_TOUGH_CONV15_PART2_SC`||
|`INSULT_PED_TOUGH_CONV15_PART3_SC`||
|`IN_COVER_RESP_SC`||
|`I_GOT_THIS_SC`||
|`JACKED_GENERIC_SC`||
|`JACKED_IN_CAR_SC`||
|`JACKED_ON_STREET_SC`||
|`JACKING_BIKE_SC`||
|`JACKING_CAR_FEMALE_SC`||
|`JACKING_CAR_MALE_SC`||
|`JACKING_DEAD_PED_SC`||
|`JACKING_GENERIC_SC`||
|`JACKING_ORDER_SC`||
|`JACK_VEHICLE_BACK_SC`||
|`JUMP_SC`||
|`KIFFLOM_GREET_SC`||
|`KIFFLOM_RUNNING_SC`||
|`KILLED_ALL_SC`||
|`KNOCK_OVER_PED_SC`||
|`LET_ME_OUT_SC`||
|`LISTEN_TO_RADIO_SC`||
|`LOOKING_AT_PHONE_SC`||
|`LRCLOTHES_CLO_BIM_DECL_49`||
|`MAST_FALL_SC`||
|`MEDIC_ARRIVE_AT_BODY_SC`||
|`MEDIC_REALISE_VICTIM_DEAD_SC`||
|`MEDIC_REFLECT_ON_DEATH_SC`||
|`MEDIC_RETURN_TO_AMBULANCE_STATE_SC`||
|`MELEE_KNOCK_DOWN_SC`||
|`MICHAEL_EPSILON_ROBES_SC`||
|`MOVE_AWAY_FROM_THE_CAR_SC`||
|`MOVE_AWAY_WARNING_SC`||
|`MOVE_IN_PERSONAL_SC`||
|`MOVE_IN_SC`||
|`MP_SHOUT_THREATEN_PED_SC`||
|`NATDISCOVERYSERVERS`||
|`NEAR_MISS_VEHICLE_SC`||
|`NEEDED_ON_SET_SC`||
|`NEED_A_BIGGER_VEHICLE_SC`||
|`NEED_A_VEHICLE_SC`||
|`NEED_SOME_HELP_SC`||
|`NICE_CAR_SC`||
|`NICE_CAR_SHOUT_SC`||
|`NICE_CAR_THANKS_SC`||
|`NICE_SHOT_SC`||
|`NO_CHANGE_SC`||
|`OFFICER_DOWN_SC`||
|`ON_FIRE_SC`||
|`ORDER_DRINK_SC`||
|`ORDER_GENERIC_SC`||
|`OUT_OF_AMMO_GROUP_SHOOTOUT_SC`||
|`OUT_OF_AMMO_SC`||
|`OVER_THERE_SC`||
|`PAIN_GARGLE_SC`||
|`PAIN_HIGH_GENERIC_SC`||
|`PAIN_HIGH_TOUGH_SC`||
|`PAIN_HIGH_WEAK_SC`||
|`PAIN_LOW_GENERIC_SC`||
|`PAIN_LOW_TOUGH_SC`||
|`PAIN_LOW_WEAK_SC`||
|`PAIN_MEDIUM_GENERIC_SC`||
|`PAIN_MEDIUM_TOUGH_SC`||
|`PAIN_MEDIUM_WEAK_SC`||
|`PAIN_TAZER_SC`||
|`PED_RANT_01_SC`||
|`PED_RANT_02_SC`||
|`PED_RANT_03_SC`||
|`PED_RANT_04_SC`||
|`PED_RANT_05_SC`||
|`PED_RANT_06_SC`||
|`PED_RANT_07_SC`||
|`PED_RANT_08_SC`||
|`PED_RANT_RESP_SC`||
|`PED_RANT_SC`||
|`PHONE_CALL_COPS_SC`||
|`PHONE_CALL_NOT_CONNECTED_SC`||
|`PHONE_SURPRISE_EXPLOSION_SC`||
|`PHONE_SURPRISE_GUNFIRE_SC`||
|`PHONE_SURPRISE_PLAYER_APPEARANCE_SC`||
|`PINNED_DOWN_SC`||
|`PLAYER_BEEN_RUN_OVER_SC`||
|`PLAYER_KILLED_FRIEND_SC`||
|`PLAYER_RUN_OVER_RESPONSE_SC`||
|`PLIERS_PANTING_SC`||
|`POLICE_PURSUIT_DRIVEN_SC`||
|`POLICE_PURSUIT_FALSE_ALARM_SC`||
|`POOL_MY_BREAK_SC`||
|`POOL_OFFER_BET_SC`||
|`POOL_PLAYER_FOUL_SC`||
|`POOL_PLAYER_GOES_FOR_BLACK_SC`||
|`POOL_PLAYER_HURRY_UP_SC`||
|`POOL_PLAYER_LOSES_SC`||
|`POOL_PLAYER_MISS_SC`||
|`POOL_PLAYER_POTS_MANY_SC`||
|`POOL_PLAYER_POTS_ON_BREAK_SC`||
|`POOL_PLAYER_POTS_SC`||
|`POOL_PLAYER_WINS_SC`||
|`POOL_PLAY_AGAIN_SC`||
|`POOL_YOUR_BREAK_SC`||
|`POST_STONED_SC`||
|`PRERACE_CHAT_SC`||
|`PRERACE_TAUNT_SC`||
|`PRERACE_TRIATHLON_SC`||
|`PROVOKE_BAR_SC`||
|`PROVOKE_BUMPED_INTO_SC`||
|`PROVOKE_FOLLOWING_SC`||
|`PROVOKE_GENERIC_SC`||
|`PROVOKE_HIT_CAR_SC`||
|`PROVOKE_STARING_SC`||
|`PROVOKE_TRESPASS_SC`||
|`PULL_GUN_SC`||
|`PURCHASE_ONLINE_SC`||
|`PUSHUP_BREATH_SC`||
|`RACE_COLLIDE_OUT_OF_BREATH_SC`||
|`RACE_CRASH_SC`||
|`RACE_FINISHED_OUT_OF_BREATH_SC`||
|`RACE_NEARLY_WIN_OUT_OF_BREATH_SC`||
|`RACE_NEARLY_WIN_SC`||
|`RACE_RANKDOWN_OUT_OF_BREATH_SC`||
|`RACE_RANKDOWN_SC`||
|`RACE_RANKUP_OUT_OF_BREATH_SC`||
|`RACE_RANKUP_SC`||
|`RACE_REACH_START_SC`||
|`RACE_REQUEST_SC`||
|`RACE_STAY_1ST_OUT_OF_BREATH_SC`||
|`RACE_STAY_POSITION_OUT_OF_BREATH_SC`||
|`RACE_WIN_OUT_OF_BREATH_SC`||
|`RADIO_DISLIKE_SC`||
|`RADIO_LIKE_SC`||
|`RELOADING_PROFESSIONAL_SC`||
|`RELOADING_SC`||
|`REQUEST_BACKUP_SC`||
|`REQUEST_NOOSE_SC`||
|`REQUEST_ORAL_SC`||
|`REQUEST_SEX_SC`||
|`RESCUE_INJURED_BUDDY_SC`||
|`RESCUE_INJURED_COP_SC`||
|`ROBBERY_FRIEND_WITNESS_SC`||
|`RUN_OVER_PLAYER_SC`||
|`SCREAM_PANIC_SC`||
|`SCREAM_PANIC_SHORT_SC`||
|`SCREAM_SCARED_SC`||
|`SCREAM_SHOCKED_SC`||
|`SCREAM_TERROR_SC`||
|`SEE_FRANKLIN_SC`||
|`SEE_LAMAR_SC`||
|`SEE_WEIRDO_PHONE_SC`||
|`SEE_WEIRDO_SC`||
|`SELL_DRUGS_SC`||
|`SETTLE_DOWN_SC`||
|`SEX_CLIMAX_SC`||
|`SEX_FINISHED_SC`||
|`SEX_GENERIC_FEM_SC`||
|`SEX_GENERIC_SC`||
|`SEX_ORAL_FEM_SC`||
|`SEX_ORAL_SC`||
|`SHIT_SC`||
|`SHOOTOUT_OPEN_FIRE_SC`||
|`SHOOTOUT_READY_RESP_SC`||
|`SHOOTOUT_READY_SC`||
|`SHOOTOUT_SPECIAL_SC`||
|`SHOOTOUT_SPECIAL_SHOUT_SC`||
|`SHOOTOUT_SPECIAL_TO_NOBODY_SC`||
|`SHOOT_SC`||
|`SHOP_BANTER_SC`||
|`SHOP_BRAVE_SC`||
|`SHOP_BROWSE_ARMOUR_SC`||
|`SHOP_BROWSE_BIG_SC`||
|`SHOP_BROWSE_GUN_SC`||
|`SHOP_BROWSE_MELEE_SC`||
|`SHOP_BROWSE_SC`||
|`SHOP_BROWSE_THROW_SC`||
|`SHOP_BROWSE_VEST_SC`||
|`SHOP_COPS_ARRIVED_SC`||
|`SHOP_CUTTING_HAIR_SC`||
|`SHOP_DOING_MAKEUP_SC`||
|`SHOP_EXTINGUISHER_SC`||
|`SHOP_GAVE_YOU_EVERYTHING_SC`||
|`SHOP_GIVE_FOR_FREE_SC`||
|`SHOP_GOODBYE_SC`||
|`SHOP_GREET_END_SC`||
|`SHOP_GREET_FRANKLIN_BOSS_SC`||
|`SHOP_GREET_FRANKLIN_SC`||
|`SHOP_GREET_MICHAEL_SC`||
|`SHOP_GREET_SC`||
|`SHOP_GREET_SPECIAL_SC`||
|`SHOP_GREET_START_SC`||
|`SHOP_GREET_TREVOR_SC`||
|`SHOP_GREET_UNUSUAL_SC`||
|`SHOP_HAIR_WHAT_WANT_SC`||
|`SHOP_HOLDUP_SC`||
|`SHOP_HURRYING_SC`||
|`SHOP_HURRY_SC`||
|`SHOP_NICE_VEHICLE_SC`||
|`SHOP_NO_COPS_SC`||
|`SHOP_NO_COPS_START_SC`||
|`SHOP_NO_ENTRY_SC`||
|`SHOP_NO_FIGHTING_SC`||
|`SHOP_NO_MESSING_SC`||
|`SHOP_NO_WEAPON_SC`||
|`SHOP_OUT_OF_STOCK_SC`||
|`SHOP_POUR_CAN_SC`||
|`SHOP_PULL_GUN_SC`||
|`SHOP_REACT_TO_SHOUT_SC`||
|`SHOP_RECOGNISE_SC`||
|`SHOP_REMOVE_VEHICLE_SC`||
|`SHOP_SCARED_END_SC`||
|`SHOP_SCARED_SC`||
|`SHOP_SCARED_START_SC`||
|`SHOP_SELL_ARMOUR_SC`||
|`SHOP_SELL_BRAKES_SC`||
|`SHOP_SELL_BULLETPROOF_TYRES_SC`||
|`SHOP_SELL_COSMETICS_SC`||
|`SHOP_SELL_ENGINE_UPGRADE_SC`||
|`SHOP_SELL_EXHAUST_SC`||
|`SHOP_SELL_HORN_SC`||
|`SHOP_SELL_REPAIR_SC`||
|`SHOP_SELL_ROLLCAGE_SC`||
|`SHOP_SELL_SC`||
|`SHOP_SELL_SUSPENSION_SC`||
|`SHOP_SELL_TRANS_UPGRADE_SC`||
|`SHOP_SELL_TURBO_SC`||
|`SHOP_SHOOTING_SC`||
|`SHOP_SPECIAL_DISCOUNT_SC`||
|`SHOP_STEAL_SC`||
|`SHOP_STUBBORN_SC`||
|`SHOP_THREATENED_SC`||
|`SHOP_TRY_ON_ITEM_SC`||
|`SHOP_WORRY_SC`||
|`SHOT_AT_HELI_MEGAPHONE_SC`||
|`SHOT_BY_PLAYER_DISLIKE_SC`||
|`SHOT_BY_PLAYER_SC`||
|`SHOUT_IGNORED_SC`||
|`SHOUT_INSULT_HIPSTER_SC`||
|`SHOUT_INSULT_SC`||
|`SHOUT_PERV_AT_WOMAN_AGGRESSIVE_SC`||
|`SHOUT_PERV_AT_WOMAN_PERV_SC`||
|`SHOUT_THREATEN_COP_SC`||
|`SHOUT_THREATEN_GANG_SC`||
|`SHOUT_THREATEN_PED_SC`||
|`SHOVE_SC`||
|`SLEEPING_SC`||
|`SNORING_SC`||
|`SOLICIT_FRANKLIN_RETURN_SC`||
|`SOLICIT_FRANKLIN_SC`||
|`SOLICIT_GENERIC_SC`||
|`SOLICIT_TREVOR_RETURN_SC`||
|`SOLICIT_TREVOR_SC`||
|`SPACE_RANGER_SC`||
|`SPOT_POLICE_SC`||
|`SPOT_SUSPECT_CHOPPER_MEGAPHONE_SC`||
|`START_CAR_PANIC_SC`||
|`STAY_DOWN_SC`||
|`STEALTH_KILL_SC`||
|`STEPPED_IN_SHIT_SC`||
|`STOP_THE_CAR_SC`||
|`STOP_VEHICLE_BOAT_MEGAPHONE_SC`||
|`STOP_VEHICLE_CAR_MEGAPHONE_SC`||
|`STOP_VEHICLE_CAR_WARNING_MEGAPHONE_SC`||
|`STOP_VEHICLE_GENERIC_MEGAPHONE_SC`||
|`STOP_VEHICLE_GENERIC_WARNING_MEGAPHONE_SC`||
|`STRIP_2ND_DANCE_ACCEPT_SC`||
|`STRIP_2ND_DANCE_DECLINE_SC`||
|`STRIP_2ND_DANCE_OFFER_SC`||
|`STRIP_ACCEPTS_DANCE_SC`||
|`STRIP_ANNOUNCE_CHASTITY_SC`||
|`STRIP_ANNOUNCE_FUFU_SC`||
|`STRIP_ANNOUNCE_GENERIC_SC`||
|`STRIP_ANNOUNCE_INFERNUS_SC`||
|`STRIP_ANNOUNCE_JULIET_SC`||
|`STRIP_ANNOUNCE_NIKKI_SC`||
|`STRIP_ANNOUNCE_PEACH_SC`||
|`STRIP_ANNOUNCE_SAPPHIRE_SC`||
|`STRIP_ARRIVE_EXPECTED_SC`||
|`STRIP_ARRIVE_UNEXPECTED_SC`||
|`STRIP_ASKS_FOR_DANCE_REPEAT_SC`||
|`STRIP_ASKS_FOR_DANCE_SC`||
|`STRIP_COMMENT_DANCE_MULTI_SC`||
|`STRIP_COMMENT_DANCE_SINGLE_SC`||
|`STRIP_DANCE_DECLINE_POLITE_SC`||
|`STRIP_DANCE_QUIT_SC`||
|`STRIP_DANCING_DUO_SC`||
|`STRIP_DANCING_SC`||
|`STRIP_DO_OWN_THING_SC`||
|`STRIP_DROP_CASH_SC`||
|`STRIP_DUO_ACCEPT_SC`||
|`STRIP_DUO_REQUEST_SC`||
|`STRIP_ENJOYING_SELF_SC`||
|`STRIP_GIVE_NUMBER_SC`||
|`STRIP_HOME_REJECT_SC`||
|`STRIP_HOME_REQUEST_SC`||
|`STRIP_INVITE_HOME_ACCEPT_RESP_SC`||
|`STRIP_INVITE_HOME_ACCEPT_SC`||
|`STRIP_INVITE_HOME_DECLINE_RESP_SC`||
|`STRIP_INVITE_HOME_DECLINE_SC`||
|`STRIP_INVITE_HOME_SC`||
|`STRIP_LEAVE_AGREE_SC`||
|`STRIP_LEAVE_DISAGREE_SC`||
|`STRIP_OFFER_DANCE_SC`||
|`STRIP_THANKS_SC`||
|`STRIP_TOUCH_COMMENT_SC`||
|`STRIP_TOUCH_OFFER_SC`||
|`STRIP_TOUCH_SC`||
|`STRIP_TOUCH_WARNING_SC`||
|`STRIP_WALK_TO_POLE_REJECT_SC`||
|`SUPER_HIGH_FALL_SC`||
|`SURPRISED_SC`||
|`SURROUNDED_SC`||
|`SUSPECT_KILLED_REPORT_SC`||
|`SUSPECT_KILLED_SC`||
|`SUSPECT_LOST_SC`||
|`SUSPECT_SPOTTED_SC`||
|`SWIMMING_COME_UP_FOR_AIR_SC`||
|`TAKE_COVER_SC`||
|`TATTOO_APPLIED_SC`||
|`TAXID_AFFORD_PART_JOURNEY_SC`||
|`TAXID_ARRIVE_AT_DEST_SC`||
|`TAXID_BANTER_SC`||
|`TAXID_BEGIN_JOURNEY_SC`||
|`TAXID_CHANGE_DEST_SC`||
|`TAXID_CLOSE_AS_POSS_SC`||
|`TAXID_GET_OUT_EARLY_SC`||
|`TAXID_NO_MONEY_SC`||
|`TAXID_RUN_AWAY_SC`||
|`TAXID_SPEED_UP_SC`||
|`TAXID_TRASHED_SC`||
|`TAXID_WHERE_TO_SC`||
|`TAXI_FAIL_SC`||
|`TAXI_GOOD_SC`||
|`TAXI_HAIL_SC`||
|`TAXI_NO_PAY_SC`||
|`TAXI_START_SC`||
|`TAXI_STOPPED_SC`||
|`TAXI_WHAT_THE_HELL_SC`||
|`TENNIS_ABOUT_TO_SERVE_MIDGAME_WITH_AMANDA_SC`||
|`TENNIS_ACE_SC`||
|`TENNIS_CHAT_SC`||
|`TENNIS_CHAT_WITH_PLAYER_SC`||
|`TENNIS_CLOSE_LINE_CALL_SC`||
|`TENNIS_EXHERT_SC`||
|`TENNIS_HURRY_UP_SC`||
|`TENNIS_LONG_RALLY_SC`||
|`TENNIS_LOSE_SC`||
|`TENNIS_LUCKY_SC`||
|`TENNIS_OUT_SC`||
|`TENNIS_PLAYER_HIT_NET_SC`||
|`TENNIS_START_EARLY_STORY_WITH_AMANDA_SC`||
|`TENNIS_START_WITH_AMANDA_SC`||
|`TENNIS_START_WITH_FRANKLIN_SC`||
|`TENNIS_START_WITH_MICHAEL_SC`||
|`TENNIS_START_WITH_TREVOR_SC`||
|`TENNIS_WIN_SC`||
|`THATS_INTERESTING_SC`||
|`TOOTHPULL_PAIN_SC`||
|`TOUR_ABOUT_TO_START_SC`||
|`TOUR_CHAT_SC`||
|`TOUR_LANDMARK_SC`||
|`TRAPPED_SC`||
|`TRIATHLON_WARMUP_SC`||
|`TURN_RADIO_OFF_SC`||
|`TURN_RADIO_ON_SC`||
|`UP_THERE_SC`||
|`VEHICLE_COLLIDE_BIRD_GENERIC_SC`||
|`VEHICLE_COLLIDE_CHICKEN_SC`||
|`VEHICLE_COLLIDE_COYOTE_SC`||
|`VEHICLE_COLLIDE_DEER_SC`||
|`VEHICLE_COLLIDE_DOG_SC`||
|`VEHICLE_COLLIDE_HORSE_SC`||
|`VEHICLE_COLLIDE_MOUNTAIN_LION_SC`||
|`VEHICLE_COLLIDE_OFFROAD_ANIMAL_GENERIC_SC`||
|`VEHICLE_COLLIDE_ONROAD_ANIMAL_GENERIC_SC`||
|`VEHICLE_FLIPPED_SC`||
|`VEHICLE_JUMP_SC`||
|`VEHICLE_ON_FIRE_SC`||
|`VEND_NO_ITEM_SC`||
|`VPERMI2D256RM`||
|`WAIT_FOR_ME_SC`||
|`WAIT_SC`||
|`WALK_ME_TO_THE_CAR_SC`||
|`WHEEZE_SC`||
|`WHIMPER_SC`||
|`WHISTLES_SC`||
|`WON_DISPUTE_SC`||
|`WORKOUT_FINISHED_SC`||
|`WRENCH_PAIN_SC`||
|`WRENCH_PAIN_TOOTHLESS_SC`||
|`YOU_DRIVE_SC`||
|`0x10a04405`||
|`0x10e3f988`||
|`0x116ea75a`||
|`0x13722734`||
|`0x13f95b9`||
|`0x14854df1`||
|`0x161930d3`||
|`0x172e2243`||
|`0x173b44df`||
|`0x17808c4e`||
|`0x1780eebd`||
|`0x19b830a8`||
|`0x1a984a20`||
|`0x1ce4e5ba`||
|`0x1d4cbc69`||
|`0x1db021a9`||
|`0x1f15240c`||
|`0x1f596c04`||
|`0x20e772d4`||
|`0x21b0606`||
|`0x22487b0e`||
|`0x23d9b091`||
|`0x241f3ca7`||
|`0x2531a6f`||
|`0x25c60317`||
|`0x26129c0f`||
|`0x27c17953`||
|`0x298e0b6e`||
|`0x2a710568`||
|`0x2ae92ba5`||
|`0x2b82a04b`||
|`0x2d099bbd`||
|`0x2d511e12`||
|`0x2d7c7a3c`||
|`0x2e0236d1`||
|`0x306146f2`||
|`0x3106c1c0`||
|`0x312d8e3e`||
|`0x314dd0c5`||
|`0x32253acc`||
|`0x32a17f8b`||
|`0x33394942`||
|`0x33dcd3d8`||
|`0x36dad816`||
|`0x382de689`||
|`0x38c31d31`||
|`0x39fc5741`||
|`0x3af7653a`||
|`0x3d2e5ccf`||
|`0x3d85a097`||
|`0x3e142a50`||
|`0x3e312c51`||
|`0x40600b2`||
|`0x411a59de`||
|`0x411e940e`||
|`0x419a1869`||
|`0x42d5e421`||
|`0x43cc85f1`||
|`0x44bd0240`||
|`0x45270132`||
|`0x474c2b06`||
|`0x482c0e71`||
|`0x494d6eb4`||
|`0x49be74f`||
|`0x4a415ef`||
|`0x4a519f5e`||
|`0x4acfba46`||
|`0x4bc719ea`||
|`0x4bd06734`||
|`0x4cef1ddf`||
|`0x4e8428e`||
|`0x4ea8ded7`||
|`0x4f5efa7f`||
|`0x508f16fa`||
|`0x51b754fa`||
|`0x51d30d6e`||
|`0x51d85aa`||
|`0x537f2a0d`||
|`0x547f73c5`||
|`0x551c0dc1`||
|`0x5532edcb`||
|`0x556daa13`||
|`0x579dc513`||
|`0x583d927f`||
|`0x5a293b1e`||
|`0x5adbb4b8`||
|`0x5c806f49`||
|`0x5e7f0099`||
|`0x5f54a734`||
|`0x61277d8d`||
|`0x61a5993e`||
|`0x625d7e87`||
|`0x62f8c5d6`||
|`0x6315fe1e`||
|`0x642ca946`||
|`0x644cde76`||
|`0x6465714c`||
|`0x64c40840`||
|`0x6710d882`||
|`0x6736169`||
|`0x67421942`||
|`0x6935ef6c`||
|`0x69ca552a`||
|`0x69fa7a4d`||
|`0x6ba4c2f9`||
|`0x6e60bd6b`||
|`0x6eba0e2b`||
|`0x6ee88058`||
|`0x701b17ad`||
|`0x7187e3a2`||
|`0x71aeaaf6`||
|`0x73d0e404`||
|`0x74635379`||
|`0x75e2ae3b`||
|`0x788fbc91`||
|`0x7abad0f1`||
|`0x7c50c222`||
|`0x7c57485e`||
|`0x7f02a046`||
|`0x7f92ed88`||
|`0x7f9b7a4b`||
|`0x808efbb6`||
|`0x809b10f7`||
|`0x80f7ae17`||
|`0x81405e4d`||
|`0x82b17055`||
|`0x82dadc12`||
|`0x82f1c7cc`||
|`0x836a7842`||
|`0x847723d9`||
|`0x84ad5bbe`||
|`0x863713a2`||
|`0x8803ba7a`||
|`0x8830d8cd`||
|`0x8874018c`||
|`0x88eea487`||
|`0x895d6972`||
|`0x8a825f4d`||
|`0x8d5b5761`||
|`0x8e631d94`||
|`0x8ea0d236`||
|`0x8ff4ad`||
|`0x90eef424`||
|`0x9113c2c2`||
|`0x9155be20`||
|`0x91e9d90b`||
|`0x920ba5d8`||
|`0x9516a02c`||
|`0x9521fd28`||
|`0x95a6811a`||
|`0x965205b5`||
|`0x96b7116`||
|`0x98eb2734`||
|`0x98f96d2d`||
|`0x99bc4d2d`||
|`0x99e7d30e`||
|`0x9b436597`||
|`0x9baf63c2`||
|`0x9c89fa1a`||
|`0x9db4f978`||
|`0x9f4ba6d6`||
|`0x9fa97198`||
|`0x9fc81f8e`||
|`0xa15a950`||
|`0xa25ee76a`||
|`0xa31db1d7`||
|`0xa389e0b9`||
|`0xa4d997b8`||
|`0xa4f24592`||
|`0xa7faf5a`||
|`0xa8005c80`||
|`0xa8a6233d`||
|`0xa8d0f41`||
|`0xa8f7bb53`||
|`0xa9f3fa24`||
|`0xab5ea3ce`||
|`0xab9654ce`||
|`0xabf27e9`||
|`0xabfe5f5a`||
|`0xac602a26`||
|`0xac725f46`||
|`0xacb48bee`||
|`0xad414b31`||
|`0xad7bdfd0`||
|`0xaf78f031`||
|`0xafdfd851`||
|`0xb0010eac`||
|`0xb0295bf2`||
|`0xb2261dc4`||
|`0xb24358a6`||
|`0xb377c1a8`||
|`0xb3fe7884`||
|`0xb432fd82`||
|`0xb471620`||
|`0xb57fcb5e`||
|`0xb6151876`||
|`0xb68cd281`||
|`0xba115101`||
|`0xba87dac6`||
|`0xbb2cb576`||
|`0xbb515613`||
|`0xbc183c85`||
|`0xbc6d0516`||
|`0xbcc6b5e6`||
|`0xbcecb88e`||
|`0xbd09f4bb`||
|`0xbd0a4407`||
|`0xbd119745`||
|`0xbeeb3ab`||
|`0xbf1ed8b8`||
|`0xbf7d274e`||
|`0xbfe28dfd`||
|`0xbff61ad5`||
|`0xc18f70b1`||
|`0xc19191be`||
|`0xc1d8a847`||
|`0xc2d76722`||
|`0xc3ceb8ce`||
|`0xc5b82d68`||
|`0xc62d453f`||
|`0xc8398b25`||
|`0xc9fb871b`||
|`0xcecd7174`||
|`0xd090ea92`||
|`0xd0ff3020`||
|`0xd277b07e`||
|`0xd2c3aec6`||
|`0xd37020c0`||
|`0xd6c9c8f3`||
|`0xd726e65d`||
|`0xd97003e6`||
|`0xd98b9cce`||
|`0xda388796`||
|`0xda6f4c65`||
|`0xdb184a47`||
|`0xddb4c0f0`||
|`0xdf8ebe82`||
|`0xe024e9d1`||
|`0xe150de0d`||
|`0xe1b4eba8`||
|`0xe2d1c842`||
|`0xe302f117`||
|`0xe3344e8`||
|`0xe3575b95`||
|`0xe48e79b7`||
|`0xe4e58312`||
|`0xe692c1e3`||
|`0xe97e0328`||
|`0xeaeaac91`||
|`0xeaeb6dd5`||
|`0xeaf502e`||
|`0xeaf902b2`||
|`0xecb90585`||
|`0xed8927fe`||
|`0xeda79f41`||
|`0xedcb1670`||
|`0xedf3531`||
|`0xefe62c5f`||
|`0xf03778dd`||
|`0xf1873148`||
|`0xf2c0b9ee`||
|`0xf7cb561f`||
|`0xf86a9fde`||
|`0xf9ca87be`||
|`0xfd6fb598`||
|`0xfdc6e0df`||
|`0xfeb3a38d`||
|`0xff590cdb`||