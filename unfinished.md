

	# TODO: Make all of these do what they say
	# Develop islands economy
	focus = {
		id = NZL_BNZ_develop_polynesian_economy
		icon = GFX_goal_generic_production
		prerequisite = { focus = NZL_BNZ_unite_polynesia }
		x = -2
		y = 1
		relative_position_id = NZL_BNZ_unite_polynesia

		cost = 10

		ai_will_do = {
			factor = 25
		}

		available = {

		}

		bypass = {

		}

		search_filters = { FOCUS_FILTER_INDUSTRY }

		complete_tooltip = {

		}

		completion_reward = {
			
		}
	}

	# Develop islands naval bases
	focus = {
		id = NZL_BNZ_develop_polynesian_naval_bases
		icon = GFX_goal_generic_construct_naval_dockyard
		prerequisite = { focus = NZL_BNZ_unite_polynesia }
		x = 0
		y = 1
		relative_position_id = NZL_BNZ_unite_polynesia

		cost = 10

		ai_will_do = {
			factor = 25
		}

		available = {

		}

		bypass = {

		}

		search_filters = { FOCUS_FILTER_INDUSTRY }

		complete_tooltip = {

		}

		completion_reward = {
			
		}
	}

	# Develop islands defenses
	focus = {
		id = NZL_BNZ_develop_polynesian_defenses
		icon = GFX_goal_generic_fortify_city
		prerequisite = { focus = NZL_BNZ_unite_polynesia }
		x = 2
		y = 1
		relative_position_id = NZL_BNZ_unite_polynesia

		cost = 10

		ai_will_do = {
			factor = 25
		}

		available = {

		}

		bypass = {

		}

		search_filters = { }

		complete_tooltip = {

		}

		completion_reward = {
			
		}
	}