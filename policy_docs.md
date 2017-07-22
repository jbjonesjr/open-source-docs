# Table of Contents

This list does not actually reflect the contents of this repository
yet.  Instead, it lists topics being considered for inclusion in this
policy kit.  Each top-level item is one proposed policy template
document.

* **How To Use These Policy Kits and Templates**
  - Establish an open source committee ("OSC") w/ representative stakeholders
    - OSC considers policies and either recommends or adopts policies
    - Using these templates as a starting point for your own policy
* **Using Open Source Software**
  - Internal use vs product use
    - Internal tools
    - SaaS
    - Products that are distributed to customers
    - Verbatim use
          This has different implications for internal vs SaaS vs
          distributed product use, and may be treated separately in
          each of those sections above.
    - Use with modifications
          (Same comment as above in "Verbatim use")
  - Licenses that are automatically approved for use.
  - Licenses that require permission, and from whom.
    - Don't make the permission chain too complex.
    - Put the decision as close to the engineer as possible,
          while still maintaining appropriate controls.
  - Don't use something you wouldn't contribute to.
  - Evaluating upstream stability and sustainability.
    - Picking the right fork
  - Evaluating support options (informal vs paid).
    - Remembering to budget even for informal support:
          getting support from a community takes time and practice.
  - Tracking open source dependencies.
    - Systematize this, especially for products you ship.
  - Staying on top of security.
    - If you take in software, subscribe to its security alerts.
  - Handling license violation reports
    - Move toward compliance
      - Maintain communication with violation reporter
      - Escalate to compliance team
  - Policy on permissible divergence from upstreams.
    - Policies on what degree of internal forking are acceptable
          under what circumstances (measured by time, or by releases,
          or by amount of code change, etc).  This is important to
          have in a policy because without a policy to point to, it
          ends up being governed by each individual developer's or
          manager's tolerance for technical debt.  But later when some
          other group has to maintain that code, or -- via
          innersourcing! -- fix bugs in it, they may find themselves
          in a bind.  (Exactly this has happened to multiple clients
          of ours, and it was severe enough that they sought outside
          help to fix it.)
     - Divergence in process can be as bad as divergence in code.
* **[Employee Agreements and Contractor Agreements](employees-and-contractors.md)**
  - Copyright language, ownership of contributions.
  - External (non-work-time) participation
  - Distinguishing between corporate IP and personal IP
  - Hiring contractors for open source; delivery expectations.
    E.g., language stipulating that the contractor delivers a
    specific release of upstream plus a change relative to that
    release, and makes a "best effort" to get the change permanently
    incorporated into upstream.
    - Minimizing NDA language
* **[Participating in External Open Source Projects](upstream-participation.md)**
  - Participation as the norm, not the exception.
    - Be wary of requiring an engineer to ask for permission
          before participating in an upstream project.
      - How to report issues and request features
      - What to do when your needs are ignored
  - Keeping management in the loop.
    - Engineer participation in open source is not just a matter
          of contributing technical work.  It's also a two-way
          information exchange with customers/partners/competitors who
          may also be active in the project.  Management should
          discuss open source participation regularly with engineers,
          and directly observe the interactions in public forums.
  - Attribution policies
    - The company should get credit for its work.
    - Some engineers have a personal history with a project that may
          predate their time at your company; how to navigate this.
  - Navigating upstream contribution requirements
    - How to evaluate a CLA/CA/DCO
    - Patents: Understanding implicit/explicit promises; how open
          source activity can affect a company's public patent stance.
  - Acceptable upstream licenses for contribution purposes
* **Launching New Open Source Projects**
  - Who gets to decide when this happens.
    - Don't put the decision at the C-suite level without a reason.
  - Default licensing policy and who can make exceptions.
  - Understand governance model up front
    - Involve competitors, clients and other stakeholders
      - How, when, why, etc.
  - Have a clear contribution policy
    - CLA/CA/DCO
      - Code vs non-code elements
  - Have a publicity strategy -- don't waste a good OSS release
  - Legacy vs non-legacy: you can do both.
    - Distinguish between two kinds of open source release
          methods, one for actively maintained code, another for
          useful but non-maintained code.  Set release process &
          expectations accordingly.
  - For U.S. government entities: address the public-domain issue.
    - (DoD's code.mil policy good place to start.)
  - Commercial code-of-conduct.
    E.g., see the "General Guidelines for Commercial Entities and
    Others Deploying Arches" section in [Arches Project Code of
    Conduct](http://archesproject.org/code-of-conduct/).
  - Default to being open from the start.
    - I.e., If you're going to release it as open source, then the
          policy should be, whenever possible, to just develop in the
          open from the beginning, unless there's some convincing
          business reason not to.  (There are times when surprise is
          part of the strategy, but don't overvalue it -- there's also
          a cost to doing the development behind closed doors and then
          opening later too).
    - Support policy
      - I.e. how to protect yourself from a flood of support requests
  - Trademarks: (See existing Legal section of Open Source Guides for
    some ideas.)
    - Control vs community
      - Community marks in parallel
        - Domain names, corporate names, books, products, services
        - Certification mark
        - Get some community advice and some legal advice
        - The myth of policing
  - L10n and I18n
  - Responsible handling of security vulnerability discoveries
    - Receiving vulnerability reports
      - This has certain subtle interactions between
                 corporate interests and public OSS project interests.
                 Er, as recent events have demonstrated, sigh.
    - Handling the vulnerability itself
      - E.g., in product vis-à-vis upstream project
* **Community Relations and Community Management**
  - How employees represent the company in the project, at conferences, etc.
  - Technical disagreements are acceptable in public
  - Codes of Conduct
  - Attribution practices
    - E.g., use company email address or attribution for
          contributions?  What about projects where the employee was
          active before being employed here and wants to keep
          consistent identity?  (This really belongs here, not in the
          "Employee Agreements" document, because this is not so much
          about the formal agreement between employer and employee as
          it is about the company's community relations goals and how
          the employee's participation affects those goals.)
  - Conferences/workshops/webinars
    - When should employees participate
    - What they say/do
  - GSoC, Outreachy, and other similar programs
    - When to participate
    - How to maximize benefits of participation
* **Management and Open Source**
  - Hiring, training, and retention.
  - Including open source activity in performance reviews / OKRs.
    - Open source goals must be included in official performance
          review systems, such as OKRs, so that open source activity
          can be managed in the same way as any other part of company
          work.
  - Time allocation
    - 20%, etc.
  - Training/workshops
  - Importance of getting the most out of engineer OSS activity
    - It's not just about coding.  Open source participation is
          also an information source about competitor, partner, and
          customer priorities and trends.
  - Negotiating dev time across management boundaries
  - InnerSource
    - Understanding what InnerSourcing does and doesn't do.
    - Goals: Make innersourcing a road to open source, not a cul-de-sac.
      - Incentivizing internal sharing and cooperation
    - Process should be heavily customized for your environment and context.
      (What happens when your engineering tooling and/or culture are
      very different from common open source tooling and culture?  Do we
      assume that one of the goals of InnerSource is to bring the
      company more in line with open source standards internally?)
    - Approving new projects
      - Common infrastructure?
      - Tracking value of use across the org
    - Have a centralized Open Source Program Office?
* **Open Source ROI and Budgeting**
  - How to think about the ROI of using, contributing to, creating
    open source software.
      - Not just in technical terms, but also organizationally.  
          For example: quantify the cost of engineer non-retention,
          then look at OSS's effect on retention.
      - Acquisitions / M&A
        - Due diligence re software assets
        - How to value the acquisition's relationship w/ OSS project(s)
          - Auditing
          - Insurance
