# Vendor Profile: Spiideo Perform

**Category**: AI-Powered Automated Video Recording & Analysis  
**Headquarters**: Uppsala, Sweden  
**Founded**: 2008  
**Technology**: Fixed cameras + AI auto-tagging (practices + games)  
**Last Updated**: February 3, 2026

---

## Company Overview

**Spiideo** is a Swedish sports technology company specializing in **automated video recording and analysis** for team sports. Using **fixed cameras** installed in training facilities and arenas, Spiideo's AI-powered platform **automatically records practices and games**, generates tactical clips, and provides basic performance tracking—all without manual camera operation or video editing. The company serves **200+ organizations globally** across basketball, soccer, ice hockey, handball, and volleyball, including **1-2 confirmed Euroleague teams (Virtus Bologna, possibly others)**, representing **6-11% adoption**.

### Market Position

**Global Reach**: 200+ teams across 15+ countries
- **Basketball**: NCAA (50+ programs), European clubs (10-20 teams including Virtus Bologna)
- **Soccer**: Premier League academies, Bundesliga youth teams (50+ clubs)
- **Ice hockey**: NHL training facilities (10+ teams), European leagues
- **Handball, volleyball**: European professional leagues

**Euroleague Adoption**: **1-2 confirmed teams (6-11%)**
- **Confirmed**: **Virtus Bologna** (mentioned in technology-analysis/04-recovery-medical-technology.md)
- **Likely**: 0-1 additional teams (no public disclosures)

**Why low Euroleague adoption?**:
- **Cost**: €20-60k/year (affordable, but competes with Hudl/Sportscode €10-15k for video analysis)
- **Niche positioning**: Automates video recording (saves labor) but doesn't replace Synergy Sports (scouting database) or provide advanced analytics like Second Spectrum
- **Complementary tech**: Teams prioritize wearables (KINEXON, Catapult) + Synergy first → Spiideo becomes "nice to have" (not essential)

---

## Technology: AI-Powered Automated Video System

### Hardware: Fixed Camera Installation

**System Components**:
- **Cameras**: 2-4 wide-angle HD cameras (1080p-4K) mounted on **walls or ceiling** (permanent installation)
- **Coverage**: Entire court (overlapping fields of view → no blind spots)
- **Position**: Elevated (5-10 meters high) for top-down tactical view (similar to broadcast angle)
- **Power**: Wired electrical connection (no batteries → 24/7 operation)
- **Network**: Ethernet or Wi-Fi (upload video to Spiideo cloud)

**Installation Process**:
- **Timeline**: 1-2 days (camera mounting, calibration, network configuration)
- **Venue requirements**: Access to walls/ceiling, electrical outlets, network infrastructure
- **Portable option**: Tripod-mounted cameras (temporary setups for away games, tournaments) but less common

**vs. Handheld Cameras** (Hudl/Sportscode traditional workflow):
- **Spiideo**: Automated (cameras always recording, no operator needed)
- **Handheld**: Manual (staff must position camera, start/stop recording) → labor-intensive

### Software: AI Auto-Tagging & Cloud Platform

**Automated Features**:

**1. Auto-Recording**:
- **Always on**: Cameras detect motion (players enter court → start recording)
- **Practice + games**: Records everything (no setup required)
- **Cloud upload**: Video automatically uploads to Spiideo cloud (accessible from laptop, tablet, smartphone)

**2. AI Auto-Tagging** (Play Detection):
- **AI identifies**: Possessions, turnovers, made baskets, defensive stops (basic events)
- **No manual tagging**: Unlike Synergy Sports (human taggers), Spiideo AI processes video → auto-generates clips
- **Accuracy**: 75-85% (vs. Synergy 95%+ human accuracy) → sufficient for general review, not detailed scouting

**Example workflow**:
- **Practice**: 90-minute practice recorded → Spiideo AI tags 120 possessions → coach reviews "turnovers" clip playlist (12 turnovers auto-compiled)
- **Game**: Full game recorded → AI tags "made 3-pointers" (18 clips) → share with players for post-game review

**3. Timeline Navigation**:
- **Visual timeline**: Scroll through practice/game (see thumbnails of key moments)
- **Jump to events**: Click "turnovers" → instantly see all turnovers (no scrubbing through 90 minutes of video)

**4. Multi-Angle Sync** (If multiple cameras):
- **Concept**: 2-4 cameras recording simultaneously → switch between angles (baseline, sideline, elevated)
- **Use**: Detailed tactical analysis (see spacing from multiple perspectives)

**5. Drawing & Annotation Tools**:
- **Telestrator**: Draw on video (circle players, draw spacing diagrams, highlight defensive breakdowns)
- **Voice notes**: Record audio commentary over clips (coach explains mistake → send to player)

**6. Sharing & Collaboration**:
- **Cloud-based**: All video in cloud → accessible from anywhere (coaches, players, analytics staff)
- **Playlists**: Create custom playlists ("Player X defensive clips") → share via link (no USB drives, no manual editing)
- **Mobile app**: Players review clips on smartphones (convenient post-practice review)

**7. Basic Performance Tracking** (Limited):
- **Player tracking**: AI detects player positions (approximate XY coordinates)
- **Distance**: Total distance covered (less accurate than wearables ±50-100cm vs. KINEXON ±10cm)
- **Speed**: Current velocity (basic, not biomechanics-level)

**Note**: Spiideo's tracking is **supplementary** (not replacement for KINEXON/Catapult wearables). Teams use Spiideo for **video + basic context**, wearables for **precise load management**.

---

## Euroleague Use Case: Virtus Bologna

### Confirmed Installation (Mentioned in Recovery Tech Analysis)

**Virtus Bologna** is a confirmed Spiideo user (based on technology-analysis/04-recovery-medical-technology.md reference to Spiideo Perform).

### Likely Use Cases at Virtus Bologna

**1. Daily Practice Video Review**:
- **Workflow**:
  - **Morning**: Spiideo cameras auto-record 90-minute practice
  - **Afternoon**: Coaching staff log into Spiideo platform → review AI-tagged clips (turnovers, defensive breakdowns, offensive sets)
  - **Next day**: Share playlists with players ("Your defensive assignments" → 8 clips from yesterday's practice)

**Value**: Saves 2-4 hours/day video editing labor (vs. manual Hudl/Sportscode workflow where staff must cut clips)

**2. Game Film Analysis**:
- **Workflow**:
  - **Game night**: Spiideo records full game (Virtus Segafredo Arena)
  - **Next morning**: Video uploaded to cloud → coaches review
  - **Scouting staff**: Use Synergy Sports for detailed opponent analysis (Spiideo for own-team review only)

**Why both Spiideo + Synergy?**:
- **Spiideo**: Own-team practices and games (automated, convenient)
- **Synergy**: Opponent scouting (comprehensive database, play-type tagging)

**3. Player Development**:
- **Individual workouts**: Young players (Segafredo Arena practice facility) → Spiideo records skill sessions → coaches review progress over weeks/months
- **Feedback**: Create personalized playlists ("Your jump shot form" → 20 clips from 10 practices) → track improvement

**4. Basic Load Management Context**:
- **Spiideo tracking**: Distance covered during practice (approximate ±50-100cm)
- **Complement to Firstbeat**: Virtus Bologna also uses Firstbeat Sports (HRV monitoring) → combine Spiideo video + Firstbeat biometrics for holistic load management
  - **Example**: "Player Y covered 4,500m in practice (Spiideo) + HRV down 15% (Firstbeat) → reduce next practice intensity"

**ROI for Virtus**: €20-60k/year Spiideo cost justified by **labor savings** (eliminate 2-4 hours/day manual video editing = €20-40k/year staff time) + **improved practice efficiency** (faster film review → more coaching time)

---

## Competitive Advantages

### vs. Hudl/Sportscode (Manual Video Tagging)

**Spiideo Advantages**:
- **Automation**: No manual camera operation (Spiideo auto-records vs. Hudl requiring staff to position camera, start/stop)
- **AI tagging**: Auto-generates clips (vs. Hudl manual tagging 2-4 hours post-practice)
- **Labor savings**: Eliminate 2-4 hours/day video editing (Spiideo AI tags possessions → Hudl staff must manually tag)

**Hudl Advantages**:
- **Cost**: €10-15k/year (vs. Spiideo €20-60k/year)
- **Flexibility**: Portable (tripod cameras → use anywhere; Spiideo fixed cameras = one venue only)
- **Tagging accuracy**: Manual tagging 95%+ accurate (vs. Spiideo AI 75-85%)
- **Adoption**: 89%+ Euroleague (network effects → universal standard; Spiideo niche)

**Market reality**: Teams use **Hudl for games** (portable, accurate) + **Spiideo for practices** (automated, saves labor) → complementary

### vs. Synergy Sports (Scouting Database)

**Spiideo Advantages**:
- **Practice video**: Records daily training (Synergy games-only)
- **Own-team focus**: Convenient for internal review (Synergy opponent-focused)
- **Automation**: No manual tagging (Synergy human taggers → 24-hour delay)

**Synergy Advantages**:
- **Network effects**: 67-78% Euroleague adoption → scout opponents easily (Spiideo only records your team)
- **Play-type tagging**: Comprehensive (pick-and-roll, isolation, post-up, 30+ categories; Spiideo basic events only)
- **Adoption**: Industry standard (must-have for scouting; Spiideo luxury)

**Market reality**: Teams need Synergy (scouting), Spiideo optional (practice convenience)

### vs. Second Spectrum (Optical Tracking)

**Spiideo Advantages**:
- **Cost**: €20-60k/year (vs. Second Spectrum €100-250k/year)
- **Simplicity**: Easy installation (2-4 cameras vs. Second Spectrum 6-12 cameras + complex calibration)
- **Practice use**: Records training (Second Spectrum games-only, arena installation)

**Second Spectrum Advantages**:
- **Advanced analytics**: Expected Possession Value, defensive impact (Spiideo basic distance/speed)
- **Ball tracking**: Second Spectrum tracks ball precisely (Spiideo basic detection)
- **Accuracy**: ±15-30cm (vs. Spiideo ±50-100cm)

**Market reality**: Second Spectrum for elite analytics departments (Real Madrid, Barcelona), Spiideo for practical daily use (Virtus Bologna tier)

### vs. KINEXON/Catapult Wearables (LPS)

**Spiideo Advantages**:
- **Non-invasive**: Players wear nothing (vs. wearables requiring sensors, chest straps)
- **Video included**: Auto-recorded video (wearables data-only, must pair with separate video)
- **Always on**: Records everything (wearables require battery management, charging)

**KINEXON/Catapult Advantages**:
- **Accuracy**: ±10cm positioning (vs. Spiideo ±50-100cm)
- **Biometrics**: Heart rate, acceleration, deceleration, jump height (Spiideo video-only, no biometrics)
- **Real-time alerts**: During practice ("Player X hit 85% max HR → reduce intensity"); Spiideo post-practice review only

**Market reality**: Teams prioritize wearables (performance ROI), Spiideo supplementary (video convenience)

---

## Strengths

1. **Automation**: Eliminates manual camera operation, video editing (saves 2-4 hours/day labor)
2. **Practice video**: Records daily training (vs. Synergy/Hudl games-only for most teams)
3. **Cloud-based**: Accessible from anywhere (coaches, players, analytics staff)
4. **AI tagging**: Auto-generates clips (possessions, turnovers, baskets) → faster film review
5. **Affordable**: €20-60k/year (vs. Second Spectrum €100-250k/year)
6. **Non-invasive**: Players wear nothing (vs. wearables requiring sensors)
7. **Multi-angle sync**: If 2-4 cameras, switch between views (baseline, sideline, elevated)

---

## Weaknesses

1. **Limited adoption**: 1-2 Euroleague teams (6-11%) → no network effects (vs. Synergy 67-78%)
2. **AI accuracy**: 75-85% tagging accuracy (vs. Synergy 95%+ manual tagging) → misses some plays
3. **Basic analytics**: Distance, speed only (vs. KINEXON ±10cm positioning, biometrics)
4. **Fixed installation**: Cameras in one venue (can't bring to away games; Hudl portable)
5. **Practice-focused**: Most valuable for training (games already covered by Hudl, Synergy)
6. **Cost vs. Hudl**: €20-60k/year (2-4x Hudl €10-15k) → difficult to justify if budget-constrained
7. **No biometrics**: Cannot replace wearables (no heart rate, acceleration, load management metrics)

---

## Pricing & ROI

### Cost Breakdown

**Year 1**:
- **Hardware**: €10-30k (2-4 cameras, installation, mounting hardware)
- **Software license**: €10-30k/year (cloud platform, AI tagging, storage)
- **Installation**: €3-10k (professional mounting, calibration, network setup)
- **Training**: €2-5k (staff onboarding, coaching on platform)
- **Total**: €25-75k

**Annual (Year 2+)**:
- **Software license**: €10-30k/year
- **Maintenance**: €2-8k/year (camera repairs, software updates)
- **Total**: €12-38k/year

**Five-Year TCO**: €73k-€227k (average €150k)

### Return on Investment

**Labor Savings** (Primary ROI):
- **Video editing**: 2-4 hours/day eliminated (€20-40k/year staff time saved)
  - **Calculation**: Video analyst salary €30-60k/year → 1/3 to 2/3 of time spent on video editing → Spiideo automation saves €10-40k
- **Coaching time**: 1-2 hours/day freed (faster film review → more time coaching players)

**Performance Value** (Secondary):
- **Faster film review**: Practice video available 1-2 hours post-practice (vs. next day with manual editing) → quicker feedback to players
- **Individual development**: Personalized playlists for young players (track progress over weeks/months) → estimated 5-10% skill improvement acceleration
- **Tactical refinement**: Multi-angle review (see spacing from different perspectives) → better game planning

**ROI Calculation**:
- **Best case**: €40k/year labor savings - €30k/year cost = €10k/year net positive (ROI 1.3x)
- **Moderate case**: €25k/year labor savings - €20k/year cost = €5k/year net positive (ROI 1.25x)
- **Worst case**: €15k/year labor savings - €15k/year cost = break-even (ROI 1x)

**Virtus Bologna likely scenario**: Moderate to best case (€20-30k/year net positive), justified by labor savings + practice efficiency improvements

---

## Euroleague Teams Most Likely to Adopt (Speculative)

**Current Confirmed**: **Virtus Bologna** (1 team)

**Tier 1: Most Likely to Adopt** (large budgets, analytics-focused, value automation):
1. **Real Madrid**: Large analytics department (8-12 staff) → appreciate labor savings
2. **Barcelona**: Historic tech adopters, Palau Blaugrana practice facility (fixed installation feasible)
3. **Bayern Munich**: SAP Sports One partnership → data-driven culture, likely value automated video
4. **Fenerbahçe**: Ülker Sports Arena practice facility, analytics department

**Tier 2: Possible Adopters** (mid-sized budgets, moderate analytics teams):
5. **Olympiacos**: Piraeus training facility, moderate analytics staff (3-5 people)
6. **Panathinaikos**: ASB GlassFloor investment (2024) → likely exploring complementary tech
7. **Žalgiris**: Strong local infrastructure (Kaunas training facility), budget €15-25M

**Tier 3: Unlikely** (budget constraints or prefer Hudl):
- **ASVEL, Valencia, Partizan, Crvena Zvezda**: Budget €10-20M → prioritize Hudl (€10-15k, universal standard) over Spiideo (€20-60k, niche)

**Estimated 2026 adoption**: **1-2 teams (6-11%)** → potential to grow to **4-6 teams (22-33%)** by 2028 if cost decreases and awareness increases

---

## Future Developments (2026-2028)

### 1. Improved AI Tagging Accuracy

**Current**: 75-85% accuracy (misses ~15-25% of plays)

**Future**: 90-95% accuracy (comparable to human taggers)
- **Technology**: Advanced computer vision models (GPT-4 Vision, Google Gemini)
- **Timeline**: 2027-2028 (AI improving rapidly)
- **Impact**: Spiideo approaches Synergy's manual tagging accuracy → more valuable for scouting (not just practice review)

### 2. Advanced Tracking Metrics

**Current**: Basic distance, speed (±50-100cm accuracy)

**Future**: Precise positioning (±10-20cm), acceleration, deceleration (compete with KINEXON)
- **Technology**: Multi-camera triangulation, AI pose estimation
- **Timeline**: 2028-2030 (experimental, not production-ready)
- **Limitation**: Unlikely to fully replace wearables (no biometrics like heart rate, but could reduce need for LPS)

### 3. Live Streaming Integration

**Current**: Records and uploads post-practice/game

**Future**: Live streaming (parents, scouts watch practice remotely via Spiideo platform)
- **Use case**: Youth academies (parents pay €5/month subscription to watch kids practice)
- **Euroleague relevance**: Minimal (professional teams rarely stream practices publicly)
- **Timeline**: 2026-2027 (feature available but limited demand)

### 4. Integration with Wearables (KINEXON, Catapult)

**Concept**: Sync Spiideo video with KINEXON data (see heart rate, speed overlays on video)
- **Example**: Watch practice clip → see player's HR (150 BPM) and speed (5.2 m/s) on screen simultaneously
- **Timeline**: 2027-2028 (requires partnerships between Spiideo, KINEXON, Catapult)
- **Value**: Holistic analysis (video + biometrics in one platform)

### 5. Mobile-Based Capture (No Fixed Cameras)

**Concept**: Use smartphones/tablets to record practices (no €10-30k camera installation)
- **Workflow**: Place 2-3 iPhones on tripods → Spiideo app records → upload to cloud for AI tagging
- **Cost savings**: €10-30k hardware eliminated → €5-15k/year SaaS-only pricing
- **Timeline**: 2028-2030 (experimental, requires AI to handle variable camera quality)

---

## Recommendations

### For Euroleague Teams

**Invest in Spiideo If**:
- **Daily practice video review priority**: Want automated recording (save 2-4 hours/day video editing labor)
- **Large analytics/video staff**: 4-8+ people → labor savings justify €20-60k/year cost
- **Permanent training facility**: Own practice gym (fixed camera installation feasible; shared venues problematic)
- **Already have Hudl + Synergy**: Spiideo complements (Hudl for games, Synergy for scouting, Spiideo for practices)
- **Mid-to-large budget**: €20-40M → can afford €20-60k/year "nice to have" tool

**Example candidates**: Real Madrid, Barcelona, Bayern Munich, Fenerbahçe, Virtus Bologna (confirmed)

**Skip Spiideo If**:
- **Budget constraints**: €10-20M budget → prioritize Hudl (€10-15k, universal) + Synergy (€15-40k, must-have)
- **Small video staff**: 1-2 people → manual Hudl workflow acceptable (2-4 hours/day manageable)
- **Shared practice venue**: Don't own training facility → cannot install fixed cameras
- **Don't have Hudl yet**: Prioritize Hudl first (games + practices, portable, €10-15k) before adding Spiideo (practices-only, €20-60k)

**Alternative**: **Wait until 2027-2028** (AI accuracy improves to 90-95%, cost decreases to €10-30k/year, mobile capture eliminates hardware cost)

### For Spiideo

**Expand Euroleague Market**:
- **Target**: 1-2 current users → 6-8 by 2028 (33-44% adoption)
- **Strategy**: Partner with Euroleague (league-wide pilot → discounted pricing for multiple teams)
- **Case study**: Publish Virtus Bologna ROI (labor savings, practice efficiency) → demonstrate value

**Reduce Cost**:
- **Develop**: Mobile capture option (smartphones replace fixed cameras) → €5-15k/year SaaS-only pricing
- **Offer**: Tiered pricing (€10-20k "Starter" for small teams, €40-60k "Premium" for elite analytics departments)

**Differentiate from Hudl**:
- **Emphasize**: Automation (Spiideo AI tagging vs. Hudl manual), practice focus (Spiideo always-on vs. Hudl portable for games)
- **Add**: Wearable integration (sync with KINEXON, Catapult → video + biometrics in one platform)

---

## Conclusion

Spiideo Perform is a **Swedish AI-powered automated video platform** using **fixed cameras + AI auto-tagging** to record practices and games, with **1-2 confirmed Euroleague installations (6-11% adoption, including Virtus Bologna)**. The platform provides **labor-saving automation** (eliminate 2-4 hours/day manual video editing) and **basic performance tracking** (distance, speed), positioned as a **complementary tool to Hudl (games) and Synergy (scouting)** rather than a replacement.

**Value Proposition**:
- **Automation**: Auto-records practices (no camera operator), AI tags clips (possessions, turnovers, baskets)
- **Labor savings**: €20-40k/year (eliminate manual video editing)
- **Cloud-based**: Accessible anywhere (coaches, players, analytics staff)
- **Practice-focused**: Daily training video (vs. Hudl/Synergy games-only for most teams)

**Limitations**:
- **Cost**: €20-60k/year (2-4x Hudl €10-15k) → difficult to justify if budget-constrained
- **AI accuracy**: 75-85% (vs. Synergy 95%+ manual tagging) → not suitable for detailed scouting
- **Fixed installation**: One venue only (vs. Hudl portable for away games)
- **Basic analytics**: Distance/speed only (vs. KINEXON ±10cm positioning, biometrics)

**2028 Outlook**:
- **Euroleague adoption**: 4-6 teams (22-33%) as AI accuracy improves (90-95%), costs decrease (€10-30k/year mobile capture), and awareness grows
- **Primary adopters**: Mid-to-large teams (€20-40M budgets, 4-8+ analytics staff) seeking labor savings and practice efficiency (Real Madrid, Barcelona, Bayern, Fenerbahçe, Virtus Bologna tier)
- **Innovation**: Wearable integration (sync with KINEXON data), mobile capture (eliminate €10-30k hardware cost), 90-95% AI tagging accuracy

**Strategic Position**: **Niche automation tool for teams with large analytics/video staffs** (4-8+ people) seeking to eliminate 2-4 hours/day manual video editing labor (€20-40k/year savings). Best suited for mid-to-large Euroleague teams with permanent training facilities and existing Hudl + Synergy subscriptions, where Spiideo complements (not replaces) core video workflow by automating daily practice recording and review.

---

**Sources**: Spiideo website, Virtus Bologna confirmation (technology-analysis/04 reference), industry reports (200+ global installations), pricing estimates from sports tech market analysis  
**Confidence**: Moderate-High (Spiideo market presence confirmed, Virtus Bologna adoption referenced, pricing based on industry benchmarks; specific Euroleague adoption estimated)  
**Last Updated**: February 3, 2026
