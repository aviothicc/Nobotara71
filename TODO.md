# SpaceEdu delivery outcomes

## Reference-derived cinematic mission landing page
- [x] The home route renders the supplied SpaceEdu reference as a cinematic deep-space hero with a full-bleed backdrop, fallback still imagery, mission title, supporting educational copy, primary CTA, and side-mounted visual controls.

## Mission switcher interaction
- [x] Selecting a side mission control updates the mission title, supporting copy, backdrop video/still, adjacent mission imagery, labels, and accessible labels for Earth, Apollo 11, and Voyager 1.
- [x] Background clips are warmed on hover/focus and play only for the active mission, while reduced-motion users retain still-image fallbacks.
- [x] Voyager 1 uses the supplied 4K MP4 as its muted looping background video, with a smooth end-to-start transition and the existing fallback poster retained.

## Responsive navigation and accessibility
- [x] The page includes the SpaceEdu wordmark, primary navigation, enrollment link, an accessible mobile burger menu, click-away close behavior, Escape-to-close behavior, and focus-visible states.
- [x] Desktop, tablet, and mobile layouts preserve hierarchy and usable controls, and the page honors `prefers-reduced-motion: reduce` by removing cinematic motion.

## NASA Space Apps data transparency
- [x] The Policy navigation option opens an accessible Data & Science panel that explains how NASA Open Data, NASA APIs, and JPL Horizons can inform mission briefings, imagery, trajectory timing, communication delay, and science outcomes.
- [x] The panel makes the intended simulation inputs and traceable outcomes visible, links directly to each source, supports Escape/backdrop close behavior, and remains readable on mobile.

## Managed web runtime
- [x] The project has a directly runnable home route on the managed preview port and serves `GET /manus-routes.json` with the complete page route set.
