# Walkthrough - Create a Meeting using Microsoft Teams

This will show the steps for setting up a public meeting as part of a recurring series that happens at the end of a release/sprint. This assumes a company using Microsoft Teams, and running the agenda creation and finalization using respectively GitHub Discussions (private or public repo) and Issues (public repo).

1. Create the draft meeting agenda as a discussion. Kick off the discussion with what you know. [Example](https://github.com/lyledodge-playground-organization/community/discussions/4).
    1. Naming conventions and labels are useful here, the example above uses two labels - "meeting agenda" and "end user community", as well as a standard naming on the title of the issue which includes the date in the format "Meeting Purpose" - YYYY.MM for easy sorting/filtering.
1. When the meeting agenda has been finalized, choose "Create issue from discussion". Paste your finalized agenda into the new issue (which may or may not be using an agenda template). You can link to the discussion if you want to have an easy context trail. [Example](https://github.com/lyledodge-playground-organization/community/issues/5).
1. Create the meeting in Microsoft Teams, with a link in the description to the meeting agenda (the GitHub Issue from the step above). Modify the **Response options** and **Require registration** options to fit your meeting requirements.
    1. Save the meeting, then go back into the meeting after a few seconds. In the meeting information / description field, go to the bottom and click on **Meeting options**. Some example configurations:
        1. Wide open meeting with audio/video enabled for anyone:
        1. :::image type="content" source="images/meeting-options-wide-open.png" alt-text="Wide open meeting with audio/video enabled for anyone":::

- Create a Meeting Agenda template at <your repo>/issues/templates/edit, with something like [Sample Meeting Agenda](sample-meeting-agenda.md).
- Create the draft meeting agenda - see an example at https://github.com/lyledodge-playground-organization/community/issues/5.

## Schedule the Meeting

- Schedule the meeting in your conferencing software, pointing to the meeting agenda above.
- Update the meeting details
  - Click on the meeting, choose more options. Set the desired defaults for people to get into the meeting.
  - Update the GitHub meeting agenda with the conferencing link if applicable.
 