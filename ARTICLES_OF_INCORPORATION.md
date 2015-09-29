---
layout: page
header: light
title: Articles of Incorporation
permalink: /our_mission/articles_of_incorporation/
registered_agent: "[REGISTERED_AGENT]"
incorporator_address_1: "[INC_ADD1]"
incorporator_address_2: "[INC_ADD2]"
incorporator_city: "[INC_CITY]"
incorporator_state: "[INC_STATE]"
incorporator_postal_code: "[INC_POSTALCODE]"
adopted_at: 2015-09-29
---

{% assign initial_board_members = site.data.board_of_directors | where:'initial_member',true %}

**NOTE:** These {{ page.title }} are a placeholder and have not yet been reviewed nor
adopted.

# Article I

## Name

### 1.01 - Name

The name of this corporation shall be {{ site.legal_title }}. The business of the corporation may be conducted as {{ site.title }} or {{ site.legal_title }}.

# Article II

## Duration

### 2.01 - Duration

The period of duration of the corporation is perpetual.

# Article III

## Purpose

### 3.01 - Purpose

{{ site.legal_title }} is a non-profit corporation and shall operate exclusively for educational and charitable purposes within the meaning of Section 501 (c)(3) of the Internal Revenue Code, or the corresponding section of any future Federal tax code. {{ site.legal_title }}’s purpose is to (the purpose).

    Sample purpose in detail: We provide education by giving free lectures and slideshows titled “The World Hunger Exhibition,” in schools, libraries, and other public venues as well as utilizing social media channels and the corporation’s website to provide facts, statistics, and other related data on causes, current efforts and solutions to eradicating chronic malnutrition and hunger.

Our programs include sending out ambassadors to raise social consciousness about the cause on a local and global level, and to hold fundraising events in order to provide immediate relief and assistance to those suffering from chronic malnutrition and hunger regardless of their race, ethnicity, or religion.

To maximize our impact on current efforts, we may seek to collaborate with other non-profit organizations which fall under the 501(c) (3) section of the internal revenue code and are operated exclusively for educational and charitable purposes.

At times, per the discretion of the board of directors, we may provide internships or volunteer opportunities which will provide opportunities for involvement in said activities and programs in order to have a greater impact for change.

### 3.02 - Public Benefit

{{ site.legal_title }} is designated as a public benefit corporation.

# Article IV

## Non-Profit Nature

### 4.01 - Non-profit Nature

{{ site.legal_title }} is organized exclusively for charitable and educational purposes including, for such purposes, the making of distributions to organizations that qualify as exempt organizations under section 501 (c) (3) of the Internal Revenue Code, or corresponding section of any future federal tax code. No part of the net earnings of {{ site.legal_title }} shall inure to the benefit of, or be distributable to its members, trustees, officers, or other private persons, except that the corporation shall be authorized and empowered to pay reasonable compensation for services rendered and to make payments and distributions in furtherance of the purposes set forth in the purpose clause hereof.

Notwithstanding any other provision of this document, the corporation shall not carry on any other activities not permitted to be carried on (a) by any organization exempt from federal income tax under section 501 (c) (3) of the Internal Revenue Code, corresponding section of any future federal tax code, or (b) by an organization, contributions to which are deductible under section 170 (c) (2) of the Internal Revenue Code, or corresponding section of any future federal tax code.

{{ site.legal_title }} is not organized and shall not be operated for the private gain of any person. The property of the corporation is irrevocably dedicated to its educational and charitable purposes. No part of the assets, receipts, or net earnings of the corporation shall inure to the benefit of, or be distributed to any individual. The corporation may, however, pay reasonable compensation for services rendered, and make other payments and distributions consistent with these Articles.


### 4.02 - Personal Liability

No officer or director of this corporation shall be personally liable for the debts or obligations of {{ site.legal_title }} of any nature whatsoever, nor shall any of the property or assets of the officers or directors be subject to the payment of the debts or obligations of this corporation.

### 4.03 - Dissolution

Upon termination or dissolution of the {{ site.legal_title }}, any assets lawfully available for distribution shall be distributed to one (1) or more qualifying organizations described in Section 501(c)(3) of the Internal Revenue Code of 1986 (or described in any corresponding provision of any successor statute) which organization or organizations have a charitable purpose which, at least generally, includes a purpose similar to the terminating or dissolving corporation.

The organization to receive the assets of the {{ site.legal_title }} hereunder shall be selected by the discretion of a majority of the managing body of the {{ site.legal_title }}and if its members cannot so agree, then the recipient organization shall be selected pursuant to a verified petition in equity filed in a court of proper jurisdiction against the {{ site.legal_title }} by one (1) or more of its managing body which verified petition shall contain such statements as reasonably indicate the applicability of this section. The court upon a finding that this section is applicable shall select the qualifying organization or organizations to receive the assets to be distributed, giving preference if practicable to organizations located within the State of Montana.

In the event that the court shall find that this section is applicable but that there is no qualifying organization known to it which has a charitable purpose, which, at least generally, includes a purpose similar to this corporation, then the court shall direct the distribution of its assets lawfully available for distribution to the Treasurer of the State of Montana to be added to the general fund.

### 4.03 - Prohibited Distributions

No part of the net earnings, or properties of this corporation, on dissolution or otherwise, shall inure to the benefit of, or be distributable to, its members, directors, officers or other private person or individual, except that the corporation shall be authorized and empowered to pay reasonable compensation for services rendered and to make payments and distributions in furtherance of the purposes set forth in Article III, Section 3.01.

### 4.04 - Restricted Activities

No substantial part of the corporation’s activities shall be the carrying on of propaganda, or otherwise attempting to influence legislation, and the corporation shall not participate in, or intervene (including the publishing or distribution of statements) in any political campaign on behalf of or in opposition to any candidate for public office.

### 4.05 - Prohibited Activities

Notwithstanding any other provision of these Articles, the corporation shall not carry on any activities not permitted to be carried on (I) by a corporation exempt from federal income tax as an organization described by Section 501(c)(3) of the Internal Revenue Code, or the corresponding section of any future federal tax code, or (II) by a corporation, contributions to which are deductible under Section 170(c)(2) of the Internal Revenue Code, or the corresponding section of any future federal tax code.

# Article V

## Board of Directors

### 5.01 - Governance

{{ site.legal_title }} shall be governed by its board of directors.

### 5.02 - Initial Directors

The initial directors of the corporation shall be:

{% for board_member in initial_board_members %}
  * {{ board_member.name }} - _{{ board_member.title }}_
{% endfor %}

# Article VI

## Membership

### 6.01 - Membership

{{ site.legal_title }} shall have no members.  The management of the affairs of the corporation shall be vested in a board of directors, as defined in the corporation’s bylaws.

# Article VII

## Amendments

### 7.01 - Amendments

Any amendment to the Articles of Incorporation may be adopted by approval of two-thirds (2/3) of the board of directors.

# Article VIII

## Addresses of the Corporation

### 8.01 - Corporate Address

The physical address of the corporation is:

    {{ site.corporate_physical_address_1 }}
    {{ site.corporate_physical_address_2 }}
    {{ site.corporate_physical_city }}, {{ site.corporate_physical_state }} {{ site.corporate_physical_postal_code }}

The mailing address of the corporation is:

    {{ site.corporate_mailing_address_1 }}
    {{ site.corporate_mailing_address_2 }}
    {{ site.corporate_mailing_city }}, {{ site.corporate_mailing_state }} {{ site.corporate_mailing_postal_code }}

# Article IX

## Appointment of registered agent

### 9.01 - Registered Agent

The registered agent of the corporation shall be:

  {{ page.registered_agent }}

# Article X

## Incorporator

The incorporators of the corporation are as follow:

    {{ page.incorporator_address_1 }}
    {{ page.incorporator_address_2 }}
    {{ page.incorporator_city }}, {{ page.incorporator_state }} {{ page.incorporator_postal_code }}

# Certificate Of Adoption Of Articles Of Incorporation

We, the undersigned, do hereby certify that the above stated Articles of Incorporation of {{ site.legal_title }} were approved by the board of directors on {{ page.adopted_at | date: '%A, %B %-d, %Y' }} and constitute a complete copy of Articles of Incorporation of the {{ site.legal_title }}.

{% for board_member in initial_board_members %}
  * {{ board_member.name }}

      _Signature_
{% endfor %}

#### Acknowledgment of consent to appointment as registered agent

I, {{ page.registered_agent }}, agree to be the registered agent for {{ site.legal_title }} as appointed herein.

Registered Agent ____________________

Date: _______________________
