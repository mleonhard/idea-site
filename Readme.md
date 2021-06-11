# Idea Site

Goal: To be the primary site for the smartest humans to read every day.

Strategies:
- Help users to teach.
  - Users can add new ideas for discussion.
    You write an idea as a statement.
    Examples:
      - "Vertical mice are superior in ergonomics to all other mouse designs."
      - "People can learn to be more careful or conscientious."
      - "AMD's new 3D SRAM tech will increase CPU performance but not power efficiency."
      - "Big Five personality research produces no knowledge."
  - Users can add "points" to an idea.
    Each point is also a single statement.
    Examples:
      - "The neutral position of a wrist on a table is a 45-degrees counter-clockwise rotation from the table surface."
      - "When using Evoluent Vertical Mouse V1-5, the wrist rotates 110-degrees."
      - "When using a traditional mouse, the wrist rotates 165-degrees."
      - "Anecdata: Wrist pain subsides after switching from a traditional mouse to a vertical mouse."
      - "Anecdata: Evoluent mouse wheels wear out faster than most mouse wheels."
  - Users can add comments under the idea or any point.
  - Users can use basic Markdown in comments.
  - Users can mark their content as spoilers or potentially offensive content.
    Users can click to reveal it.
  - Users can include ASCII diagrams.  There is an ASCII diagram editor.
    Users can include vector images which must be a subset of SVG.
  - Users can link to media files.
    The site can display media files inline, with a blurred thumbnail and a button to display.
    The site will archive linked files in comments that get some tags and don't get removed.
- Help others to quickly identify content written by experts.
  - Every user may publicly tag an idea, point, or comment as "worth-discussing".
    These are similar to upvotes.
    Many incorrect ideas are worth discussing since they help to teach.
    Therefore, tagging an incorrect or offensive point is not endorsing it.
    An incorrect point should receive a comment refuting it.
    Users should tag the best refuting comment.
  - Each user may only tag one comment under a point.
    As comments appear under a point, users will read them and move their tag to the best one.
    A user can contribute a well-written summary of the comments under a point and receive many tags.
- Help users quickly identify the most relevant content.
  - The site displays points in order of number of tags, with the highest-tagged first.
  - High-tagged comments have bold colors.
  - Low-tagged comments appear in dim colors.
  - The site weights tags by tag age and by the user's tag coefficient.
    This means that new points can rise above old points that have become irrelevant.
- Help users learn better ways of thinking.
  - A user writing a comment must label each paragraph with one of:
    - Knowledge.  This is information which is generally accepted as true.
      If it is accepted as true by a certain group of people, state that.
      The user should provide one or more source references.
    - Analysis.  The user should clearly state their assumptions.
      The users should provide one or more references which teach the analysis technique.
    - Opinion.  Ideally, the user will state their experience level
      or other reason why their opinion is worth reading.
    - Anecdata
    - Humor
  - New users must complete a mini-course on logical thinking and fallacies,
    with a short exam.
  - The site's guidelines will encourage pointing out fallacies of ideas, points, and comments.
    The moderators and initial users will help instill a culture of logical
    thinking and calling out logical errors.
    Moderators will reward users who focus call out logical errors with
    clear explanations.  The reward will be 10-100 tags on their comment.
- Help users improve communication skills.
  - Any user can propose a change to a comment, with a short explanation.
    The original author can click a button to accept the proposed change.
  - Users can propose alternatives for ideas and points.
    These alternatives appear directly under the idea or point.
    Each user can tag one alternative.
    The alternative with the most tags becomes the primary version.
- Let users collaborate to develop ideas.
  - Users can quote comments and link to comments.
  - Users can subscribe to ideas, points, and comments.
    They will receive an email or notification when someone
    links to a subscribed item or adds or edits a comment under a subscribed item.
- Encourage high-effort contributions.
  - Each user gets a "tag coefficient" that is calculated from:
    - The number of tags on their ideas, points, and comments.
    - The number of points, comments, tags, and page views received by the ideas they submit.
    - The number of comments and tags received by points they submit.
    - The site will adjust these numbers to avoid rewarding posting on controversial topics.
    - A reduction for new accounts.
    - A bonus for accounts publicly tied to the person's identity.
      For example, verified via email address from a well-known organization.
      Another example: a verified LinkedIn or Facebook account.
- Discourage low-effort contributions.
  - Limit users to adding one item per day:
    - One idea, with a comment, one or more points, and a comment under each point.
    - One point and a comment under it.
    - One comment on an existing idea or point.
  - Limit the number of new tags a user can add per day.
    Moving a tag from one comment to another does not consume a tag.
  - Users can flag items to moderators.

# TO DO
- Readme to use a better example of points.
- Add main.rs
- Pick a template library
- Add lib.rs with rouille router
- Add home page HTML
- Add CSS
- Add initial database tables
- /new-account
- /logout
- /login
- /account GET
- /account POST, require password to change password or email address
- Add idea
- /, home page
- View idea
- Tag idea
- Tag point
- Add point
- Add comment
- Aag comment
- Calculate user tag coefficient
- Functional tests.
- Deployment script.
- Automatic backups.
- Automatic backup tests.
- Guidelines
- Terms of Use
- Privacy Statement
- Flag idea
- Flag point
- Flag comment
- Hard-coded moderator list
- Hide idea
- Hide point
- Hide comment
- Lock user account
- Contact Us page
- Support email tool (ticketing).
- Markdown
- List draft ideas
- New draft idea
- Preview draft idea
- Preview draft point
- Preview draft comment
- Auto-save draft idea
- Auto-save draft point
- Auto-save draft comment
- Add point alternative
- Tag point alternative
- Edit comment
- Auto-save edited comment draft
- Preview edited comment draft
- Suggest change to comment
- Accept change to comment
- View comment changes
- Draft idea undo history
- Continuous deployment.
- Site monitoring.
- ASCII diagram editor
- SVG uploads
- Inline media
- Verify email address
- Verify LinkedIn
- Verify Facebook
- Logical Thinking course and exam
