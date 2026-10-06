# MASTER PROMPT — Integrate Humayro 3.3 into Humayro 3.2

You are modifying an existing production project called Humayro 3.2. Humayro_3.3 is a visual and component reference only.

## NON-NEGOTIABLE
Do NOT blindly copy this repository over Humayro 3.2. Adapt its design system, layout and components to the existing architecture. Preserve working functionality.

## BEFORE CHANGING ANYTHING
1. Inspect the complete Humayro 3.2 repository.
2. Identify existing React components, services, API contracts, environment variables, authentication, AI synthesis, news aggregation, globe/region data and routing.
3. Map existing functionality to this UI.
4. Do not invent APIs when an existing service already provides the data.

## PRESERVE
Backend/server architecture; AI services and provider fallback logic; Gemini/Search grounding; RSS/GDELT aggregation; authentication/admin; globe data; bookmarks/history/local storage; environment variables; business rules and rate limits.

## ADAPT
Use this visual language: #05070A background, #0B0F14 surfaces, #11161D secondary surfaces, #FF6A00 primary, #3B82F6 secondary, #22C55E success, restrained borders/glow, Inter/Geist/Manrope UI, Newsreader/Georgia editorial type, intelligence cards, right-side intelligence reader drawer, AI Intelligence Brief, functional globe, responsive mobile bottom navigation.

UX:
LEVEL 1 — DISCOVER: What is happening?
LEVEL 2 — UNDERSTAND: Why is it happening?
LEVEL 3 — INTELLIGENCE: What does it mean?

## MIGRATION
Refactor incrementally. Reuse existing data/services. Replace presentation before logic. Never delete a working feature. Do not invent replacement APIs.

## QUALITY GATES
Run typecheck, lint if configured, production build. Test desktop/tablet/mobile, loading/empty/error/success states, keyboard navigation and contrast. Confirm existing AI/news/auth/globe flows still work.

Final goal: Humayro 3.2 functionality + Humayro 3.3 intelligence-first design, not a rewritten application.