---
name: Institutional Excellence
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#eac249'
  on-secondary: '#3d2f00'
  secondary-container: '#b08c10'
  on-secondary-container: '#352800'
  tertiary: '#d0cdcd'
  on-tertiary: '#313030'
  tertiary-container: '#b4b2b2'
  on-tertiary-container: '#454544'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffe08b'
  secondary-fixed-dim: '#eac249'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: notoSerif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: notoSerif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: notoSerif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
spacing:
  unit: 8px
  gutter: 24px
  margin: 64px
  container-max: 1200px
---

## Brand & Style

The brand personality of this design system is rooted in the concepts of **Legal Authority**, **Timelessness**, and **Unwavering Integrity**. It is designed for a notary's office where the primary objective is to convey trust and the solemnity of legal certification. The target audience includes high-net-worth individuals, corporate entities, and institutional partners who expect a premium, discreet, and highly professional service.

The design style is a hybrid of **Minimalism** and **Modern Corporate Elegance**. By utilizing heavy whitespace—or in this case, "black-space"—the system allows the rich gold accents and refined typography to command attention. This approach avoids the clutter of traditional legal interfaces, opting instead for a focused, high-contrast aesthetic that feels more like a luxury private bank or a prestigious law chambers than a standard government utility.

## Colors

The palette is strictly curated to evoke the tactile feel of black velvet and gold leaf. 

- **Primary & Secondary:** The Gold tones (#D4AF37 and #C5A028) are used exclusively for key actions, branding, and structural accents like gilded borders. They represent value and the "golden seal" of the notary.
- **Backgrounds:** The foundation is a deep, matte black (#0A0A0A). Secondary surfaces use a slightly lighter charcoal (#1A1A1A) to provide depth without breaking the high-contrast immersion.
- **Typography:** Primary text is rendered in pure white or off-white for maximum legibility, while secondary metadata uses a muted gold to maintain the hierarchy.

## Typography

This design system employs a sophisticated pairing of **notoSerif** for headlines and **manrope** for functional text. 

- **notoSerif** brings a traditional, literary quality to the interface, mimicking the look of printed legal instruments and classic certificates. It is used sparingly for titles and significant callouts to maintain its impact.
- **manrope** provides a modern, balanced counterpoint. Its clean geometry ensures that even dense legal clauses remain legible on digital screens. 
- **Labels** are often treated with increased letter spacing and uppercase styling to evoke the feeling of formal document headers.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model to ensure a sense of permanence and structure. Centered content containers with generous margins create a focused, "letterhead" feel.

- **Grid:** A 12-column grid is used for desktop layouts, with wide 24px gutters to allow the content room to breathe.
- **Rhythm:** An 8px baseline grid dictates all vertical spacing, ensuring mathematical precision in the alignment of legal text and form fields.
- **Margins:** Large outer margins (64px+) are encouraged to frame the content, emphasizing the "exclusive" nature of the services provided within the design system.

## Elevation & Depth

Hierarchy is established through **Gilded Borders** and **Tonal Layering** rather than traditional shadows. 

- **Structural Outlines:** Instead of ambient shadows, elements are separated by 1px solid or gradient borders in satin gold. This creates a "framed" effect similar to physical certificates.
- **Surface Tiers:** To indicate interactivity or layering, background colors shift from the base black (#0A0A0A) to a subtle charcoal (#1A1A1A).
- **Subtle Gradients:** A faint radial gradient (Primary Gold to Secondary Gold) may be used on primary buttons to simulate the sheen of metallic foil, adding a tactile, high-end quality to the UI.

## Shapes

The shape language is strictly **Sharp (0px)**. 

In a notary's office, precision is paramount. Sharp corners reflect the definitive nature of legal contracts and the "cut" of high-quality paper. Every UI element, from buttons to input fields and cards, features 90-degree angles to reinforce the formal, institutional tone of this design system. Any departure from this (such as circular icons) should be rare and motivated by specific functional needs.

## Components

### Buttons
Primary buttons are high-contrast: either a solid Gold background with Black text, or a Black background with a 1px Gold border. Hover states should involve a subtle shift in the gold gradient or a glow effect on the border, never a change in the sharp geometry.

### Inputs
Text inputs are minimalist, featuring only a 1px Gold bottom border (underline style) in their resting state, becoming a full gold frame when focused. Placeholder text should be rendered in a muted, low-opacity version of the gold palette.

### Dividers
Dividers are a signature element of this design system. They are 1px thick and use a linear gradient that fades from transparent to Satin Gold (#D4AF37) and back to transparent, creating a sophisticated "light catch" effect across the page.

### Cards
Cards do not use shadows. They are defined by a #1A1A1A background and a thin, consistent Gold border. They should be used to group related document metadata or service options.

### Signature Blocks
A custom component unique to this design system is the "Signature Block," which uses a Noto Serif "X" mark and a wide horizontal line, mimicking the physical space where a client would sign a deed, used for digital verification steps.