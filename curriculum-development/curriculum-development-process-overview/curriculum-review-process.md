# Curriculum review process

## Summary

While there are many points in the curriculum development process where errors can be caught and changes can be requested, the Curriculum Review phase is the development process's primary source of quality control.

#### People involved: 

* Curriculum Developer
* Copy Editor
* Subject Matter Expert

#### Prerequisites:

* Experience using [**Git**](https://thenewstack.io/tutorial-git-for-absolutely-everyone/) and [**Markdown**](https://commonmark.org/help/)
* Training as necessary
* Access to the curriculum repository. **Contact your manager for access.**

**Methods:**

Curriculum is "live" when it has been added to Canvas and published. 

For material that **is** **not** **live**: Using Git, make PR requests to `develop`.

For material that **is** **live**: Using Slack, post change requests to the project channel \(eg., \#mern-curriculum or \#ata-curriculum\). The LMS Administrator and Curriculum Developers will collaborate to triage and execute changes.

### **Process**

1. Curriculum developers move Asana cards to "Ready to Review", when the content described by the card is complete. At the same time, content is marked "Ready to Review" in the Gatsby app.
2. Review team updates local git repository and reviews markdown files for grammar, clarity, style, code syntax, and accuracy.
3. Review team commits their changes to a new branch and submits pull requests to the `develop` branch of the git repository. Approved changes are merged to `main` to go live.
4. Review team will send significant change requests back to Curriculum Developers for revision **using the relevant cards in Asana**.
5. Sections that are ready for implementation should be assigned to the LMS Administrator and marked "In Implementation" in Asana.
6. During the Implementation phase, the LMS Administrator will submit further pull requests or escalations, as necessary. The LMS Administrator will mark Asana cards complete as content is added to Canvas and is sufficiently revised. 
7. The Curriculum developers will notify the LMS Administrator and Instruction teams of approved pull requests, as able. 
8. The LMS Administrator will notify relevant instruction teams of completed content via Slack.
9. Instruction Teams will review content prior to publishing for students, testing functionality and making pull requests as necessary.
10. **The Instruction Team should escalate live errors to the LMS Administrator**, who will support as able or escalate to Curriculum Developers or other appropriate parties as necessary.



