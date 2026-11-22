# Testing Methodology

## Overview

We run controlled short-form video tests on TikTok.  
Each experiment changes only a limited number of variables so that performance differences can be attributed with reasonable confidence.

## Variables We Control

### Primary Variables
- **Visual Archetype** (body type, facial features, hair, skin tone, styling)
- **Outfit & Material** (latex, metallic, sequin, micro-bikini, velvet, etc.)
- **Setting** (dark club, beach sunset, luxury lounge with money/champagne, stage)
- **Music** (mood, BPM range, energy curve)

### Fixed Variables (kept constant)
- Video length: 8–13 seconds
- Camera: completely locked / static
- Movement style: continuous fluid go-go (hip rolls, soft body waves, isolations)
- Facial performance: short subtle smile → poker face + strong eye contact
- Hand placement: only on own body

## Experiment Process

1. **Define hypothesis**  
   Example: “Soft curvy + black metallic outfit + dark techno will outperform beach sunset version on male 18–34 audience in retention.”

2. **Generate still**  
   Use archetype-specific image prompt.

3. **Animate**  
   Apply the current master video prompt (locked camera version).

4. **Publish**  
   Same posting time window, similar hashtag sets, no heavy boosting at first.

5. **Collect data** (first 24–48 hours + day 7)
   - Views
   - Average watch time / % watched
   - Likes, comments, saves, shares
   - Profile visits
   - Any donation or link clicks

6. **Log results**  
   Use the template in `/experiments`.

7. **Update ranking**  
   Move winning combinations higher in the main README table.

## Rules to Keep Tests Clean

- Never change more than 2 major variables at once when possible
- Keep the movement prompt almost identical across tests
- Avoid posting the same archetype + music pair twice in a short period
- Record external factors (algorithm changes, time of day, whether the account was warm or cold)

## Success Criteria (examples)

- Average watch percentage > 60–70%
- Save rate significantly above account average
- Clear lift in profile visits per 1000 views
- Qualitative signal: comments asking for more / “who is she” type engagement
