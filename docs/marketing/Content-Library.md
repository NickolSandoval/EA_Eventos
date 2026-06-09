# EA-003 — Content Library Organization

## Objective

Create a structured and scalable content management system for EA Eventos.

The goal is to ensure that all video assets can be easily located, classified, prioritized, edited and reused for future marketing campaigns.

---

# Business Justification

Before this process, event footage existed as a collection of unorganized files with no clear structure, making it difficult to:

- Locate specific content.
- Prioritize editing efforts.
- Plan publications.
- Track content status.
- Reuse assets in future campaigns.

A structured content library reduces operational friction and creates a repeatable workflow for future events.

---

# Folder Structure

The following folder hierarchy was implemented:

```plaintext
EA Eventos/
│
└── Videos/
    │
    └── Evento B-001/
        │
        ├── Raw/
        │   │
        │   ├── A-Utilizable/
        │   ├── B-Rescatable/
        │   └── C-Archivo/
        │
        └── Editado/
```

### Description

| Folder | Purpose |
|----------|----------|
| Raw | Original event footage |
| A-Utilizable | Content ready for immediate production |
| B-Rescatable | Content requiring additional editing |
| C-Archivo | Content preserved for historical reference |
| Editado | Processed and edited content |

---

# Naming Convention

A standardized naming system was implemented.

Format:

```plaintext
Video [Category]-[Event Type]-[Number].mp4
```

Examples:

```plaintext
Video A-Boda-01.mp4
Video A-Boda-02.mp4
Video B-Boda-08.mp4
Video C-Boda-15.mp4
```

### Benefits

- Easy identification.
- Consistent organization.
- Scalability for future events.
- Faster content retrieval.

---

# Metadata System

A metadata table was created to support content management and production planning.

## Fields

| Field | Description |
|----------|----------|
| Asset | File name |
| Category | Content quality classification |
| Status | Current lifecycle status |
| Platform | Intended publication platform |
| Suggested Use | Recommended content type |
| Priority | Production order recommendation |
| Observations | Editing notes and recommendations |

---

# Classification System

## Category A — Utilizable

Content suitable for immediate production.

Characteristics:

- Acceptable framing.
- Visible audience engagement.
- Functional lighting effects.
- Sufficient duration.

Results:

```plaintext
6 videos
```

---

## Category B — Rescatable

Content containing usable moments but requiring additional editing.

Characteristics:

- Minor quality issues.
- Short duration.
- Camera angle corrections required.

Results:

```plaintext
20 videos
```

---

## Category C — Archivo

Content preserved for reference purposes only.

Characteristics:

- Excessively short duration.
- Limited audience visibility.
- Direct exposure to event lighting.
- Poor framing.

Results:

```plaintext
17 videos
```

---

# Asset Status System

The following status definitions were adopted:

| Status | Description |
|----------|----------|
| Disponible | Content available for production |
| En edición | Content currently being edited |
| Publicado | Content already published |
| Archivado | Content removed from active production |

---

# Priority System

To optimize production efforts, a priority system was implemented.

## High Priority

Content recommended for immediate production.

Examples:

- Strong audience engagement.
- Good event atmosphere.
- Suitable for promotional content.

---

## Medium Priority

Content useful for secondary publications and support material.

---

## Low Priority

Content retained for future use or archival purposes.

---

# Publication Platforms

Current platforms:

- Facebook
- Instagram

Future scalability:

- TikTok
- YouTube Shorts
- Website
- Additional social platforms

---

# Suggested Content Uses

The metadata system includes recommended content formats.

| Use | Description |
|----------|----------|
| Reel corto | Short-form video content |
| Reel largo | Extended promotional content |
| Story | Temporary social media content |
| Post | Standard social media publication |
| Promoción | Service-focused marketing content |
| Compilación | Combination of multiple clips |

---

# Event B-001 Results

## Total Assets Reviewed

```plaintext
43 videos
```

## Classification Results

| Category | Quantity |
|----------|----------|
| A - Utilizable | 6 |
| B - Rescatable | 20 |
| C - Archivo | 17 |

---

# Process Improvements

Before implementation:

- No content structure existed.
- No classification system existed.
- No production prioritization existed.
- No asset tracking existed.

After implementation:

- Standardized folder hierarchy.
- Metadata-based asset management.
- Priority-driven production workflow.
- Scalable content organization system.

---

# Key Outcome

EA Eventos now has a structured content library capable of supporting future content production, publication planning and marketing campaigns.

The implemented system can be replicated across future events, reducing content management time and improving operational efficiency.

---

# Next Step

EA-004 — Priority Content Selection

Objective:

Identify the highest-value assets from Categories A and B to create the first wave of social media content.
