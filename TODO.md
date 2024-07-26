# To Do List
## Done
These need adding to the description and changelog
- Unlocked the Maori and Polynesian volunteers templates
- Tweaked the descriptions of some focuses
- Added more victory points to NZ
  - Hamilton - 5
  - Tauranga - 5
  - Palmerston North - 1
  - Napier - 1
  - New Plymouth - 1
- Modified existing victory points
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
- Could move the Polynesia focuses to the same place as Australia focuses

# Pasted Code
	set_rule = { can_create_factions = yes }
	# BNZ: We move the annex wargoal to another focus
	add_political_power = 50
	#if = {
	#	limit = { AST = { NOT = { has_government = ROOT } } }
	#	create_wargoal = {
	#		type = annex_EVERYTHING#!!!!!
	#		target = AST
	#		expire = 0
	#	}
	#	else = {
	#		add_political_power = 50
	#	}
	#}