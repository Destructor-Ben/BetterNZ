# To Do List
## Next Release
- Clean up the TODOs

## Future
- Make RPS and APS lists in code
- Learn to use scripted effects
- Add more states to the map for islands


TODO:
- Add Iron Sand national focus

TODO: make the decisions highlight what states will be affected

### Australia
TODO
- Exclusive branches
  - Requres Polynesia Volunteers
  - Ask Australia To Join Faction
    - Australia joins the faction and becomes part of a reasearch sharing group
  - Demand Australia
    - Australia either is annexed or we get an annex wargoal
  - Puppet Australia
    - Australia either is puppeted or we get a puppet wargoal

### Non-Aligned (National)
TODO

### Non-Aligned (Maori)
TODO


TODO
- Polynesian Volunteers
  - Get free units from the islands
  - Requires the 3 develop focuses
- Polynesian Conscription
  - Adds national idea
  - Requires the 3 develop focuses

TODO:
- Develop Polynesian Island Economies
  - Build infrastructure in island states
  - Add 2 building slots to island states
  - Requires Unite Polynesia
- Develop Polynesian Island Naval Bases
  - Add dockyards to island states
  - Requires Unite Polynesia
- Develop Polynesian Island Defenses
  - Build forts on island states
  - Build naval forts on island states
  - Requires Unite Polynesia

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