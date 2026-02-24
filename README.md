  # Splunk SPL — Threat Hunter's Field Reference                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                                        
  A comprehensive, self-contained Splunk SPL reference built for Threat Hunters. Open `index.html` in any browser — no dependencies, no setup.

  ## Live Page

  **[https://sai-deepak-mangipudi.github.io/splunk-spl-handbook/](https://Deepu369619.github.io/splunk-spl-handbook/)**

  > Enable GitHub Pages (Settings → Pages → Branch: `main` → Save) to activate the live link.

  ## What's Inside

  | Section | Covers |
  |---|---|
  | **Core Search** | Search anatomy, modifiers, time snapping |
  | **Filtering & Extraction** | `where`, `search`, `rex`, PCRE cheat sheet |
  | **Grouping & Aggregation** | `stats`, `eventstats`, `streamstats` |
  | **IP Address Operations** | CIDR matching, zone classification, geolocation, subnet extraction |
  | **Correlation & Joining** | Subsearch, `join`, `transaction`, `lookup`, `append` |
  | **Time Graphs** | `timechart`, `chart`, `trendline`, `predict`, `sparkline` |
  | **Eval Functions** | String, numeric, time, conditional, multivalue |
  | **Threat Hunt Cookbook** | 12 production-ready hunt queries with MITRE tags |
  | **Formatting** | `table`, `dedup`, `sort`, `xyseries`, `addtotals` |
  | **Macros & Acceleration** | Macros, `tstats`, data model queries |
  | **Advanced Techniques** | `map`, `makeresults`, anomaly detection, frequency analysis |
  | **Command Cheat Table** | All commands at a glance |
  | **Performance Rules** | 10 rules to keep searches fast |

  ## Hunt Queries Included (Just For Reference)

  - Brute Force Detection (T1110)
  - Password Spray (T1110.003)
  - Lateral Movement / Pass-the-Hash (T1550)
  - DNS Exfiltration / Tunneling (T1071.004)
  - C2 Beaconing Detection (T1071)
  - Data Exfiltration — Z-score (T1048)
  - LOLBins (T1218)
  - Impossible Travel (T1078)
  - First-Time Seen Entity
  - Process Injection (T1055)
  - Scheduled Task Persistence (T1053.005)
  - PowerShell Threat Detection (T1059.001)

  ## Features

  - Dark theme — easy on the eyes during long hunts
  - Ctrl+K page search with highlight
  - Copy button on every code block
  - Sticky nav with section jump links
  - Fully self-contained — single HTML file, zero dependencies

  ## Usage

  Clone and open:

      git clone https://github.com/Deepu369619/splunk-spl-handbook.git
      open splunk-spl-handbook/index.html

  Or just open the GitHub Pages link above.

  ## License

  MIT — use it, share it, fork it.
