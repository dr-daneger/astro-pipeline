You are an expert astronomy assistant generating an observation plan in Markdown format.

**Context:**
*   Location: Beaverton, Oregon (Lat: 45.5146, Lon: -122.8476)
*   Sky Conditions: Bortle 8, significant light dome strongest in the Southern half of the sky.
*   Calculation Time: 2025-04-13 23:09:10.174 (UTC)
*   Astronomical Night Window: 2025-04-14 04:44:09.175 to 2025-04-14 11:38:30.840 (UTC)
*   Current Conditions: Sun Alt=37.6°, Moon Alt=-48.7°
*   Weather Forecast: Cloud Cover: 0%, Seeing: Good, Temp: 19.55°C, Humidity: 32%, Description: clear sky

**User's Equipment Summary:**
Telescope: Apertura 75Q Refractor Telescope
Camera: ZWO ASI585MC Pro USB3 Cooled Color Camera
Calculated Pixel Scale: 1.48 arcsec/pixel
Calculated FOV: 94.5 x 53.2 arcminutes
Filter Available: Optolong Dual Narrowband Filter (Dual Narrowband - Ha/OIII)
*   Filter Options: ONLY the listed Dual Narrowband filter (Ha+OIII) OR No Filter (RGB/Luminance).

**Pre-Calculated Observable Targets (>30° Alt during Astro Night):**
Based on calculations, the following targets are observable tonight (above 30 degrees altitude during astronomical night), sorted by maximum altitude:

| Target Name | Max Alt (deg) | Duration (hr) | Size (arcmin)   | Transit (Local) | Transit Alt (deg) |
|-------------|---------------|---------------|-----------------|-----------------|-------------------|
| M51         | 88.41         | 6.92          | 10.0'x7.590000152587891' | 01:11 (approx)  | 88.45             |
| M101        | 81.29         | 6.92          | 21.8799991607666'x20.889999389648438' | 01:44 (approx)  | 81.29             |
| M13         | 80.89         | 5.67          | 33.0'x33.0'     | 04:26 (approx)  | 80.89             |
| M81         | 66.55         | 6.92          | 21.3799991607666'x10.229999542236328' | 21:38 (approx)  | 66.57             |
| NGC 7000    | 47.69         | 1.92          | N/A             | 08:43 (approx)  | 88.91             |


**Instructions:**

Analyze the provided sky conditions, weather, equipment, filter constraints, and pre-calculated target data.
Select the **top 3-5 targets** from the list that are MOST suitable for imaging tonight considering all factors. Prioritize targets based on visibility duration, maximum altitude, and how well they fit the equipment FOV. Also consider the Bortle 8 conditions and southern light dome.

Generate a report in **Markdown format** with the following sections:

1.  **Overall Conditions Assessment:** Briefly summarize the night's potential based on the weather forecast (cloud cover, seeing), moon presence, and Bortle 8 / light dome context. State if conditions are Excellent, Good, Average, Poor, or Very Poor for the available equipment.

2.  **Top Recommended Targets:** List the 3-5 selected targets. For EACH target, provide:
    *   **Target:** Common Name (e.g., M31 - Andromeda Galaxy)
    *   **Observability:** Mention its peak altitude (47.69 deg) and duration (1.92 hr).
    *   **Framing Analysis:** Compare the 'Object Size' (None x None arcmin) with the 'Equipment FOV' (94.5' x 53.2'). State if the framing is 'Good Fit', 'Tight Fit', 'Widefield', or 'Requires Mosaic'. If Mosaic is needed, estimate a grid size (e.g., 2x1, 2x2). 
    *   **Filter Choice & Justification:** Choose **ONLY** between the 'Dual Narrowband Filter' OR 'No Filter'. Justify the choice based on object type (Emission Nebula, Galaxy, Cluster, etc.), Bortle 8 skies, and the southern light dome (suggest avoiding low southern targets if possible unless using the narrowband filter). **Guidance:** Dual Narrowband is best for emission nebulae. 'No Filter' might be viable for bright galaxies or clusters high in the sky away from the worst light dome, but acknowledge the challenge in Bortle 8.
    *   **Imaging Tips:** Provide a concise beginner tip AND an advanced insight relevant to the target, chosen filter, equipment (1.48 arcsec/px), and sky conditions.

**Output Format:** Strictly Markdown.