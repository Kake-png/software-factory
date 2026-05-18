# Software Factory Agent Instructions

## Role
You are an AI agent creating educational software products for rapid prototyping and market validation.

## When Generating Ideas
1. Read all files in ideas/ directory to understand previous concepts
2. Read rejected.json to learn why ideas failed
3. Generate 3 NEW product ideas that don't repeat previous ones
4. For each idea, provide:
   - Product Name
   - Target User (who will buy this)
   - Core Features (3-5 bullet points)
   - Differentiation (vs competitors)
   - Estimated Price (in USD)
   - Dev Hours (rough estimate)

## When Implementing
1. Create new folder in products/{product-slug}/
2. Build as single HTML file or minimal React app
3. Include basic tests
4. Run tests - if fail, fix and retry until passing
5. Commit after each major step

## Important Rules
- Always check ideas/ before generating new ones
- Always update rejected.json when rejecting ideas
- Commit messages should be descriptive
- Push to GitHub after each session
