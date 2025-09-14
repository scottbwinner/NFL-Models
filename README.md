# NFL-Models

# Files



Final Data Sources
- pff_receiving: https://premium.pff.com/nfl/positions/2023/REG/receiving 
- pff_man_zone: https://premium.pff.com/nfl/positions/2023/REG/receiving-scheme?minimum=1
- pfr_fp: https://www.pro-football-reference.com/years/2023/fantasy.htm
- pfr_rz_rec: https://www.pro-football-reference.com/years/2023/redzone-receiving.htm
- pfr_rz_run: https://www.pro-football-reference.com/years/2024/redzone-rushing.htm
- pfr_tm_off: https://www.pro-football-reference.com/years/2023/ (Team Offense Table)
- pff_ol_pass: https://premium.pff.com/nfl/positions/2023/REG/ol-pass-blocking-efficiency
- pff_qb: https://premium.pff.com/nfl/positions/2023/REG/passing?position=QB
- qb_depth_chart: https://www.ourlads.com/nfldepthcharts/
- pff_rushing: https://premium.pff.com/nfl/positions/2024/REG/rushing
- pff_x_fantasy_week_points: https://www.pff.com/fantasy/stats/finishes
    - Week to week fantasy point data from 2022/23-2024/25 seasons
- fantasy_adp: https://www.fantasypros.com/nfl/adp/ppr-overall.php?year=2024
- pff_ol_run: https://premium.pff.com/nfl/positions/2024/REG/offense-run-blocking
- pfr_draft: https://www.pro-football-reference.com/years/2024/draft.htm
- pfr_combine: https://www.pro-football-reference.com/draft/2025-combine.htm
- pff_ncaa_rushing: https://premium.pff.com/ncaa/positions/2024/REGPO/rushing?division=fbs&customMinimum=1&minimum=5
- pff_behind_los_passing: https://premium.pff.com/nfl/positions/2024/REG/passing-depth?position=QB&split=behindLos
- pff_short_passing: https://premium.pff.com/nfl/positions/2024/REG/passing-depth?position=QB&split=short
- pff_int_passing: https://premium.pff.com/nfl/positions/2024/REG/passing-depth?position=QB&split=medium
- pff_deep_passing: https://premium.pff.com/nfl/positions/2024/REG/passing-depth?position=QB&split=deep
- pff_ncaa_receiving: https://premium.pff.com/ncaa/positions/2023/REGPO/receiving?division=fbs&position=WR,TE,RB&customMinimum=1&minimum=5
- pff_ncaa_passing: https://premium.pff.com/ncaa/positions/2024/REGPO/passing?division=fbs&position=QB&customMinimum=1&minimum=10
- pff_screens: https://premium.pff.com/nfl/positions/2024/REG/receiving-concept?position=WR,TE,RB&split=screen&minimum=1
- pff_blitz:  https://premium.pff.com/nfl/positions/2024/REG/passing-pressure?position=QB&split=blitz
- pfr_tm_def: https://www.pro-football-reference.com/years/2024/opp.htm
- pfr_schedule: https://www.pro-football-reference.com/years/2024/games.htm

Potential Data Sources
- https://nextgenstats.nfl.com/stats/receiving#percent-intended-yards
- https://fantasydata.com/nfl/fantasy-football-leaders?season=2023&seasontype=1&scope=1&subscope=1&scoringsystem=2&aggregatescope=1&range=3
- https://nflsavant.com/targets.php?ddlYear=2022&ddlPosition=&week=&rz=redzone&ddlTeam=


** Overall Ideas **
- Models to predict player performance
    - Problem: Rookies | Solution A: Separate model for rookies
    - Problem: Injuries | Solution A: Predict PPG instead of overall points
    - Problem: Situation Changes
        - Sub-Problem: QB change | Solution: Use data from new QB's previous season
        - Sub-Problem: Coach Change
    - Problem: How to factor training camp hype | Solution: Not totally sure, hopefully it is somewhat reflected in the depth chart.
- Reinforcement Learning model to train draft agent to converge on ideal draft position/strategy given player ppg rankings
    - Problem: Need actually accurate Draft Simulator to be able to integrate the Draft Agent | Solution A: Create yourself, Solution B: Use dataset of drafts
- NEED TO LOOK INTO POINTS OVER REPLACEMENT STATISTIC
- Create a Consistency metric, based on player availability, standard deviation of points/usage, likelihood of bust week
- Data analysis on Trending Up players
- Waiver value analyzer
- Injury Risk Stat

