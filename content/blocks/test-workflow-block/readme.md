---
title: Test Workflow Block
description: Delete this block after testing
modules: Fundamentals
week: "1"
skills:
  - Problem Solving
time: 0
prep: I was having trouble writing in these fields.
introduction: |-
  But now it seems to be working fine.



  Scenario: remove draft status

  GIVEN I am on the Approval of the content board

  WHEN I see the status

  THEN I can only see "In Review" and "Ready"



  Scenario: show in review from uploaded blocks

  GIVEN a new block was created via the CMS PD platform

  WHEN I am on the Approval of the content board

  THEN I can see all blocks in the "In Review" column



  Scenario: ready columns

  GIVEN a new block was available for review

  WHEN I approve the block

  THEN it is moved to the "Ready" column
---
