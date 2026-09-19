# Website Blueprint — MON MON

## Research snapshot — 20 Sep 2026
- Home-based coffee + matcha in Yishun, Singapore.
- Public location: 334A Yishun Street 31.
- Current ordering: Tabaous; older Take App page redirects there.
- Current evidence: listing says homebased takeaway cafe, current products include matcha, coffee, seasonal drinks; customers are prompted to WhatsApp after checkout to confirm payment/order.
- Instagram/TikTok presence is evidenced by public business listings; exact Instagram handle not independently verified in this pass.
- Phone: not independently verified.
- WhatsApp: ordering workflow is evidenced, but exact public number is not independently verified.
- Standalone official website: none found in this pass.
- Current public review signal: 4.8/5 from 29 reviews on WorldCafeMap.
Sources: https://tabaous.com/monmon.sg ; https://take.app/monmon ; https://worldcafemap.com/en/singapore/yishun-new-town/mon-mon-home-based-coffee-and-matcha-in-yishun

## Site map
Home / Menu / Order / About / Visit & Pickup / Seasonal / FAQ / Contact.

## UX
Make ordering the primary conversion. Hero should show “home-based coffee + matcha in Yishun”, current open/closed state, signature item and Order Now. Menu supports seasonal/sold-out badges. Order page explains checkout → WhatsApp confirmation. Visit page protects residential privacy and shows only owner-approved instructions.

## Visual + motion
Warm modern Asian café editorial: oat, espresso brown, cream and restrained matcha green. Use large drink photography, thin rules, soft grain.
- Hero liquid/foam shader.
- Scroll enter/exit: blur→sharp + translate + opacity.
- Menu card tilt and ingredient micro-reveal.
- Sticky mobile order CTA.
- Page transitions via clip-path.
- Subtle floating coffee/matcha particles.
- Reduced-motion mode.

## Technical
Multipage; separate CSS/JS; GSAP/ScrollTrigger; lightweight WebGL only where useful; lazy images; schema/local SEO; accessible navigation.

## Do not invent
Phone, exact social handles, current hours, payment details, prices or residential instructions beyond verified/owner-approved data.