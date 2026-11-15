# PULSE Fitness

A dark fitness-tracking prototype with workout logging, meal/macronutrient diary, progress overview and technique-first calisthenics suggestions.

## Current status
- Frontend prototype served by Cloudflare Workers.
- Prototype entries are stored locally in the browser; they are not yet synced across devices.
- Neon project and initial PostgreSQL schema have been provisioned.
- Cloudflare Hyperdrive configuration has been created; the next step is adding a PostgreSQL driver/API layer and authentication before enabling persistent writes.

## Safety
Nutrition entries are informational records, not calorie limits or weight-loss targets. Workout suggestions emphasize controlled technique, recovery and gradual progression.
