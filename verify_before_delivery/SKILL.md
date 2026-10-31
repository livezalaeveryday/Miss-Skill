# Verify Before Delivery

## Choose the ground truth first

- Pick the source that still shows the thing you must prove before you open any report or composed output.

- Use the raw panel when you check whether a balloon covers a face, because a face that is fully covered cannot be found in the composed page.

- Use the rendered page when you check layout or styling, because markup can be present while its stylesheet is missing.

- Name the ground truth in your check before you start, and check against that source rather than against a summary of it.

## Open the artifact yourself

- Open the final file, page, or live URL yourself instead of accepting a checking report as your own check.

- Compare the delivered artifact with the ground truth item by item, and open every changed page or section rather than sampling one disputed case.

- Treat a subagent or team report as a claim to test, and test the parts that matter before you repeat its conclusion.

- Stop and fix the check when your own opening contradicts the report, and say plainly that the report was wrong.

## Cover what a check cannot see

- Ask what evidence would be invisible if the defect were present, such as a fully covered face or a missing stylesheet, and design the check to reveal that case.

- Check absence as well as presence, and check the parts a tool cannot detect by opening them with your own eyes.

- Re-run the full check after a fix rather than checking only the fixed spot, because a fix can move a problem to another page or section.

- Keep a tolerance of zero for a defect the user has already ruled out, and do not soften it to slight or minor without a new decision from the user.

## Report only what you checked

- Report the artifact you opened, the ground truth you compared it with, and the pages or sections you actually viewed.

- Say whose eyes were on the work when a team or subagent did the checking, and do not present their check as your own.

- Hold the word done until your own check passes, and name any part you could not open as untested rather than passing it silently.

- When the user finds a defect you missed, admit the missed check, name the check that failed, and change that check before you re-deliver.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.

## Alternatives for better results

- Ask for the raw source alongside any composed deliverable when the composed form can hide the defect you must check.

- Split a large deliverable into changed pages or sections and check each one, rather than accepting one overall pass claim for the whole work.

- Keep the checking method beside the deliverable so a later fix uses the same ground truth instead of a new weaker check.
