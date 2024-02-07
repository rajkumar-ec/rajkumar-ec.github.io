---
layout: page
title: Week 4
---


## Thursday 1 Feb

**9:00am** : start the day

- **9:30am** : Tested furnishing upload for beta.
- **10:00am** : Gave PR for issue(#74).
- **12:00pm** : Fixed requested changes in PR.
- **01:00pm** : Pushed and updated the PR.
- **02:30pm** : Addition of material migration in the script.
- **03:30pm** : Added migration of material for issue(#74).
- **04:00pm** : Waiting for updates form Ab.
- **05:00pm** : Checking why some material refs are absent.
- **06:30pm** : Found and fixed bug in `_applyFilter` and `setPresets`. Waiting for response.
- **07:30pm** : Got update form Ab. Assets are not present on the "adjusted" url?
- **08:00pm** : Updated Ab about the findings, wating for response.
- **08:30pm** : Discussion about the issue. Apperently we were on different context.

**8:30pm** : signout for the day

---

## Friday 2 Feb

**9:00am** : start the day

- **9:30am** : Went over issue (#152) with Ab.
- **11:00am** : Implemented obtaining missing refs in a file.
- **1:00pm** : Implemented thumbnail ref migration for materials
- **01:30pm** : Pushed and gave the PR.
- **02:00pm** : The script is not working correctly for existing refs. Updated Ab. Waiting for response.
- **02:30pm** : Addition of material migration in the script.
- **03:30pm** : Added migration of material for issue(#74).
- **04:00pm** : Waiting for updates form Ab.
- **07:30pm** : Implemented migration of missing furnishing refs for issue(#3)

**7:30pm** : signout for the day

---

## Monday 5 Feb

**9:30am** : start the day

- **9:30am** : Wating for Ab response for next steps.
- **10:00am** : Call with Ab to optimize clia and cli implimentation and organization.
- **12:00pm** : Have to modify the material ref cli flow for new changes.
- **02:30pm** : got carried away due to misunderstanding about texture thumbnails. Wasted a lot of time.
- **03:30pm** : Clarification from Ab. No need for sperate handling of texture thumbnails. Lot of time wasted.
- **04:00pm** : Done with the docs and the cli implementation.
- **04:30pm** : Discusson with Ab about the catalogue branch problem.
- **05:00pm** : Had to pull the new catalogue branch. did `ecreboot`, throwing SQL error. Informed Ab, waiting for response.
- **06:30pm** : SQL error is gone, but _loadFurnishing is not working correctly. Waiting for response.
- **07:00pm** : SQL error occure on starting container, and get fixed after some restarts.
- **07:30pm** : The async error was happening because of missing refs. Have infomed Ab, waiting for response.
- **08:00pm** : Pushed the code for PR. No, review today.


**8:30pm** : signout for the day

---

## Tuesday 6 Feb

**9:00am** : start the day

- **9:30am** : Wating for Ab response for next steps. Moving to furnishing assets migration.
- **10:00am** : Implemented furnishing asstet migration. Furnishing's `frontview` is not being uploaded to the blob, informed Ab.
- **10:30am** : It was a premission problem.
- **11:30am** : Finished and pushed furnishing migration and its docs. Moving to material migration.
- **12:30pm** : Working on material migration from old db.
- **1:30pm** : Done with mat material migration and working on requested changes.
- **2:30pm** : Fixed requested changes, working on docs.
- **3:30pm** : Fixed minor changes and gave updated PR for migrate material. docs are pending.
- **05:00pm** : Finshed docs and migrate furnihing is almost done, problem in slots of furnishing. Updated Ab, waiting for response.
- **06:30pm** : Updated defaults to 75 in slots for `migrate_furn` and added docs for `migrate_furn`.
- **07:30pm** : Updated PR for `migrate_furn`. Updated Ab.

**7:30pm** : signout for the day

---

## Wednesday 7 Feb

**9:30am** : start the day

- **10:00am** : Fixed requested changes. Waiting for Ab's response.
- **1:30pm** : Update from Ab. Gave PR for docs.
- **2:30pm** : Have to update the flow for batch processing.
- **3:30pm** : Added try expect and batch processing.
- **4:00pm** : Added optimization in batch processing.
- **4:30pm** : Updated docs for new changes.
- **5:00pm** : Updated PR for `ec tools v1tov2`, waiting for Ab's response.

**6:00pm** : Sign out for the day.
