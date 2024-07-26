# To Do List
## Done
These need adding to the description and changelog
- Unlock the Maori and Polynesian volunteers templates
- Add more victory points to NZ
  - Hamilton - 5
  - Tauranga - 5
  - Palmerston North - 1
  - Napier - 1
  - New Plymouth - 1
- Modify existing victory points
  - Wellington - 20
  - Auckland - 10
  - Christchurch - 5
  - Dunedin - 3

## Next Release
- FIX ICON

- Non-Aligned Paths
  - Monarchist
	- Take Edward VIII from UK after his abdication and stage a coup
	- King Edward abdicated on 10th December 1936
  - Maori - Civil war!
    - Create a Maori Government
	- Apirana Ngata
	- Te Puea Herangi

- Australia Focuses

## Future
### Content
- Add more states to the map for islands
- Add more government employees and generals
- Add more initial research for NZ

- Add new flag for communist NZ
- Maybe make new flags for Polynesia

- Remove bypasses for focuses that give NZ equipment
- Add more economy focuses - Iron Sand?
- Add more navy focuses - It needs to be possible for nz to invade Australia

### Balance/Tweaks
- Maybe make the forts focus only give the bonus to a few random islands, since if it does all, then you may as well wait to get all of them
- Could also make the Develop Polynesia focuses unlock decisions instead, and have a decision for each island
- Could also make the demand islands decisions more controlled by having a decision for each state

### Code Quality
- Make RPS and APS lists in code

### Code thats pasted in
	### Australia ###
	# Commonwealth
	focus = {
		id = NZL_BNZ_australia_commonwealth
		icon = GFX_goal_tfv_strengthen_commonwealth_ties
		prerequisite = { focus = NZL_technology_sharing_with_britain }
		x = 0
		y = 1
		relative_position_id = NZL_technology_sharing_with_britain

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

	# Fascist
	focus = {
		id = NZL_BNZ_australia_fascist
		icon = GFX_goal_demand_sudetenland
		prerequisite = { focus = NZL_technology_sharing_with_japan }
		x = 0
		y = 1
		relative_position_id = NZL_technology_sharing_with_japan

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

	# Communist
	focus = {
		id = NZL_BNZ_australia_communist
		icon = GFX_goal_demand_sudetenland
		prerequisite = { focus = NZL_technology_sharing_with_soviet_union }
		x = 0
		y = 1
		relative_position_id = NZL_technology_sharing_with_soviet_union

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

	# Independent
	focus = {
		id = NZL_BNZ_australia_independent
		icon = GFX_goal_generic_alliance
		prerequisite = { focus = NZL_independent_new_zealand }
		x = 0
		y = 1
		relative_position_id = NZL_independent_new_zealand

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