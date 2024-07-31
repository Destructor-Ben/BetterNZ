# To Do List
## Done
These need adding to the description and changelog.

## Next Release
- FIX ICON

- Non-Aligned Paths
  - Monarchist
    - Take Edward VIII from UK after his abdication and stage a coup
    - King Edward abdicated on 10th December 1936
    - Rename the focus from coup_the_government to something relating to supporting him
  - Maori - Civil war!
    - Create a Maori Government
    - Apirana Ngata
    - Te Puea Herangi
    - Kingitanga

## Future
### Content
- Add more states to the map for islands
- Add more government employees and generals
- Add more initial research for NZ

- Add new flag for communist NZ
- Maybe make new flags for Polynesia

- Add more economy focuses - Iron Sand?
- Add more navy focuses - It needs to be possible for nz to invade Australia
- Australia Focuses
- Remove bypasses for focuses that give NZ equipment - navy one and the coastal defense focus
- Tweak focus completion times
- Tweak focus filters
- Make the AI for New Zealand good

### Balance/Tweaks
- Make RPS and APS state lists in code - ETH_transfer_promised_states
- Road to '56 compatability
- Maybe make the forts focus only give the bonus to a few random islands, since if it does all, then you may as well wait to get all of them
- Could also make the Develop Polynesia focuses unlock decisions instead, and have a decision for each island
- Could also make the demand islands decisions more controlled by having a decision for each state
- Could move the Polynesia focuses to the same place as Australia focuses - maybe not, since the australia are just after the other focuses



	# Institute Royal Dictatorship
	focus = {
		id = NZL_BNZ_institute_royal_dictatorship
		icon = GFX_goal_generic_propaganda
		prerequisite = { focus = NZL_BNZ_coup_the_government }
		x = 0
		y = 1
		relative_position_id = NZL_BNZ_coup_the_government

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

	# Form Maori Government
	focus = {
		id = NZL_BNZ_form_maori_government
		icon = GFX_goal_generic_propaganda
		prerequisite = { focus = NZL_BNZ_oppose_pakeha_government }
		x = 0
		y = 1
		relative_position_id = NZL_BNZ_oppose_pakeha_government

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