---
type: PostLayout
title: "Sharing my Pwn-tools with the world \U0001F30E"
colors: colors-a
date: '2024-02-01'
author: content/data/team/doris-soto.json
excerpt: More context that may or may not be helpful
featuredImage:
  type: ImageBlock
  url: /images/featured-Image4.jpg
  altText: Post thumbnail image
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
With over a decade of experience in vulnerability research and exploitation following Common Vulnerabilities and Exposures (CVE), I've honed my skills in analyzing and tackling newly published vulnerabilities. My daily routine involves meticulously monitoring updates on CVEs, allowing me to stay ahead in the rapidly evolving cybersecurity landscape.

The process begins with identifying the latest CVEs that affect software products. Once a CVE is published, I recreate the exploitation environment using older, unpatched versions of the software. This pivotal step enables me to discern the differences between the patched and unpatched versions, unraveling the mechanics behind the vulnerability.

Through this methodical analysis, I gain insights into how the vulnerability operates, laying the groundwork for the next phase—developing Proof of Concept (PoC) exploits. Writing exploit scripts for both 1-day and n-day vulnerabilities not only enhances my skills but also contributes to the wider security community by shedding light on potential risks and remediation strategies.

Sharing these Pwn-tools with the world is about fostering collaboration and knowledge exchange within the cybersecurity community. By providing detailed PoCs and insights derived from my research, I aim to empower other security professionals and developers to close security gaps, thereby enhancing the overall security posture of applications and systems.

In conclusion, my journey in vulnerability research is driven by a passion for discovery and a commitment to improving cybersecurity. By sharing my findings and tools, I hope to inspire others to take proactive steps in addressing vulnerabilities and cultivating a safer digital environment for us all.
