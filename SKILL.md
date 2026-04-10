---
name: horse-skill
description: Deep equine intelligence extension for paw.skill. Riding partnership memory, ground manners tracking, herd dynamics, health and lameness monitoring, temperament profiling. The horse-human relationship is a working partnership — horse.skill tracks both the emotional bond and the performance partnership.
---

# horse.skill 🐴

Everything about your horse, distilled. Built on [paw.skill](https://github.com/realteamprinz/paw-skill).

## What horse.skill Adds Beyond paw.skill

This skill inherits ALL capabilities from paw.skill (personality distillation, interaction mode, memory, content generation) and adds equine-specific depth:

### 1. Riding Partnership Memory
- Track riding sessions (date, duration, discipline, what went well, what was difficult)
- Progress on specific skills (collection, lead changes, jumping heights, trail obstacles)
- Rider-horse communication patterns (what aids the horse responds to best)
- Bad habit tracking and improvement over time (rushing fences, dropping shoulder, behind the leg)
- Warm-up preferences (what routine gets this horse working best)
- Fitness level tracking over time
- Under-saddle behavior patterns (fresh on cold mornings, lazy in heat, spooky in wind)

### 2. Ground Manners & Handling
- Behavior during grooming (stands still, fidgety, loves face brushing, hates ears)
- Tacking up behavior (cinchy, mouths the bit, girthy)
- Trailer loading (walks right on, hesitant, needs persuasion, refuses)
- Farrier visit behavior (stands well, fidgety, kicks, needs sedation)
- Vet visit behavior (good for shots, hates oral meds, difficult for dental float)
- Leading behavior (respectful, pushy, spooky on lead, drags behind)
- Cross-tie behavior (stands quietly, paws, weaves)
- Clipping tolerance (face, ears, legs, body — each can be different)
- How they react to different handlers (gentle with kids, tests new people)

### 3. Herd Dynamics
- Position in herd hierarchy (alpha, middle, omega)
- Bonded companions (horses form deep pair bonds — separation causes distress)
- Reactions to separation from herd buddy (calls, runs fence, anxious, calm)
- Turnout behavior (grazes peacefully, runs, plays, bullies, gets bullied)
- Aggression or bullying patterns (food aggression, chasing, kicking)
- New horse introduction protocols and how this horse reacts
- Buddy-sour behavior under saddle (barn-sour, herd-bound)

### 4. Health & Lameness Intelligence
- Movement analysis from video descriptions (tracking, short-striding, head-bobbing)
- Lameness tracking (which leg, when it appears — cold start, after work, on hard ground, in circles)
- Weight and body condition scoring over time (Henneke scale 1-9)
- Hoof condition tracking (quality, growth rate, thrush history, abscess history)
- Dental schedule and issues (hooks, waves, missing teeth)
- Vaccination log (Eastern/Western encephalitis, tetanus, rabies, influenza, rhinopneumonitis)
- Deworming schedule and fecal egg count history
- Colic risk factors specific to this horse (history, triggers, management)
- Injury history and recovery tracking
- Supplement and medication log

### 5. Temperament Profiling
- Spookiness level and specific triggers (plastic bags, puddles, shadows, farm equipment, deer)
- Energy level baseline (hot horse needs calming, dead-broke needs motivating)
- Work ethic assessment (willing partner, resistant, lazy, overachiever)
- Behavior under stress (shuts down, bolts, bucks, rears, jigging, won't stand still)
- Arena vs trail personality differences (many horses are completely different)
- Competition vs home behavior (show ring nerves, trailer stress, strange environments)
- Weather sensitivity (wind makes them spooky, rain makes them miserable)
- Recovery personality (how they handle stall rest, limited turnout)

### 6. Breed & Discipline Intelligence
Breed-specific baselines and expectations:
- **Thoroughbred:** High energy, sensitive, athletic, forward, can be anxious, ex-racers need retraining
- **Quarter Horse:** Versatile, calm, stocky, good for beginners, western and ranch work
- **Warmblood:** Bred for sport (dressage, jumping), athletic, variable temperament by line
- **Arabian:** Endurance, sensitive, bond deeply, high energy, "look at everything"
- **Draft Breeds:** Gentle giants, calm, cold-blooded, slower metabolism
- **Pony Breeds:** Smart (too smart), hardy, can be stubborn, easy keepers (watch weight)
- **Gaited Breeds:** Smooth ride, unique movement, Tennessee Walker, Icelandic, Paso Fino

Discipline tracking:
- Dressage (collection, movements, tests)
- Jumping (heights, course types, scope)
- Western (reining, cutting, trail, ranch)
- Trail (miles, terrain, obstacles)
- Endurance (distance, conditioning, completion rates)
- Eventing (dressage + cross-country + stadium)

## Horse-Specific Profile Extensions

```
## Horse-Specific Data
- **Breed:** [breed or cross]
- **Height/Weight:** [hands/pounds with date]
- **Discipline:** [primary and secondary]
- **Barn/Stable:** [current facility]
- **Turnout Schedule:** [hours, pasture companions]
- **Feed Program:** [hay type/amount, grain, supplements]
- **Farrier Schedule:** [every X weeks, shod/barefoot]
- **Vet History:** [major events, ongoing conditions]
- **Riding Log Summary:** [recent sessions, progress notes]
- **Spook Triggers:** [known triggers and severity]
- **Herd Companions:** [bonded horse(s)]
- **Trailer Loading:** [status: walks on / needs work / refuses]
- **Competition Record:** [shows, results, notes]
- **Lameness History:** [incidents, legs affected, resolution]
```

## Usage

All paw.skill commands work. Additional horse-specific prompts:

- "Log today's ride: 45 minutes, flatwork, worked on right lead canter — better than last week"
- "How has [name]'s jumping improved this month?"
- "[Name] was head-bobbing on the left front after our ride — add to lameness log"
- "Is [name]'s spookiness getting better or worse based on our logs?"
- "When is [name]'s next farrier appointment due?"
- "Compare [name]'s behavior at shows vs at home"

## Emotional Guidelines

Inherits all paw.skill emotional guidelines, plus:
- Horses represent enormous financial AND emotional investment — respect both dimensions
- Horse people often spend more time with their horse than with most humans — this bond is deep
- Retirement decisions (when a horse can no longer work) are emotionally complex
- Loss of a horse is devastating — they're large, present, and central to daily life
- Career-ending injuries involve grief for the partnership, not just the animal

## Platforms

OpenClaw · Hermes Agent · Claude Code · Codex · Cursor

## Parent Skill

This skill extends [paw.skill](https://github.com/realteamprinz/paw-skill). Install paw.skill first for core pet distillation capabilities.
