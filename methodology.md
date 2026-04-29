# Methodology

This methodology describes a practical OSINT workflow used to review a suspected Instagram business account clone. The details are redacted, but the process reflects the actual investigation logic.

## 1. Initial Detection of the Suspicious Account

The review started after identifying an Instagram profile that looked very similar to a legitimate business account. At first glance, the profile appeared credible because it used familiar branding, a similar profile image, and a bio that matched the same business category.

The first check was simple: compare the suspected profile against the known legitimate account. The suspected account was labeled `suspected_account`, and the verified or trusted reference profile was labeled `legitimate_account`.

## 2. Username Analysis and Typosquatting Logic

The username was reviewed character by character. The suspected account used a very small variation of the legitimate account name. In this case, the difference was not a random word or a completely separate identity. It looked like a minor spelling variation that could be missed by a normal user.

That pattern is important because typosquatting does not always need a domain name. On social platforms, the same idea can be applied through:

- one extra or missing letter
- swapped letters
- repeated vowels or consonants
- underscore placement
- minor spelling changes in a long business name

The practical question was not whether the username was technically identical. It was whether a normal viewer could confuse it with the legitimate brand.

## 3. Content Comparison

The next step was a manual comparison of visible profile content. The review focused on:

- profile image and logo similarity
- bio wording and service categories
- post thumbnails and reused media
- account age signals, where visible
- follower and following pattern at a high level

The suspected profile appeared to mirror the legitimate account's presentation. The copied elements were not limited to one field. The overall layout, branding, and content selection looked intentionally close.

## 4. Username Intelligence Using Maigret

Maigret was used to check whether the suspected username appeared across other public platforms. The purpose was not to prove ownership of every returned profile. The purpose was to understand whether the username had a broader, consistent digital footprint.

The scan returned a large number of possible matches. This is normal for username tools, especially when they check many sites and generate profile URLs based on username patterns. A returned URL does not automatically mean that a real, active account exists.

The important observations were:

- many results looked auto-generated or low-confidence
- no enriched profile details were extracted
- several platforms were unrelated to the business context
- there was no coherent pattern of long-term activity

## 5. Interpretation of Results

The username intelligence did not support the idea that `suspected_account` had an established identity outside Instagram. Instead, the findings suggested a weak or purpose-specific footprint.

That does not prove malicious intent by itself. It does, however, add weight when combined with the visual cloning indicators and the near-match username.

## 6. False Positives

False positives were treated as a major part of the analysis, not as noise to ignore. Username search tools can produce results that look impressive but are not useful on their own.

Common false positive causes included:

- platforms that create profile pages dynamically when a username is requested
- search pages that accept any query and return a URL
- inactive placeholders with no content
- unrelated communities where the username match has no business relevance
- bot protection or redirect pages interpreted as a partial match

For that reason, results were not counted as meaningful unless they showed signs of real account activity, profile metadata, posts, interaction history, or consistent identity details.

## 7. Risk Evaluation

The risk was assessed from the perspective of brand trust and user confusion. The suspected profile had enough similarity to create confusion, especially for users searching quickly on mobile.

Potential risks included:

- users contacting the wrong account
- brand reputation damage
- redirection to untrusted messages or links
- future phishing or payment-related abuse
- loss of confidence in the legitimate social presence

The final risk level was assessed as high for impersonation likelihood and moderate to high for user impact, depending on whether the account started interacting with customers.
