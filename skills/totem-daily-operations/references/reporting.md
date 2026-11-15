# Report coverage and presentation

Read this for daily, weekly or aggregate call reports.

get_daily_report_data and get_operator_brief share sections with different windows:

- Agenda and headline counts use the team-local day.
- Calls are the latest five visible candidates filtered to the last 24 hours, not an exhaustive call total.
- Recent inbound conversations cover the last 24 hours.
- Due outreach can be a bounded permission-filtered scan.
- Notifications and channel incidents retain returned coverage and freshness.

Show generatedAt, the actual window and coverage. Missing, denied or unavailable data never means zero activity. Avoid refetching supplied sections unless a wider period or exact record is needed. Preserve query/view filters during cursor paging; an empty page with hasMore is not the end. Label incomplete reviews as partial.

get_call_report_data and get_call_insights share the authorized aggregate reader. Respect its full-visibility requirement: a restricted user's search page cannot establish business-wide rates. State returned range boundaries, counts and denominators. Never project a daily brief's call slice into a monthly trend.

Choose a chart, table or interactive explanation that answers the question. Use native Intelligent UI or another host visual capability only when available. A readable table remains valid elsewhere. Draw only from returned data; invent no points, comparisons or saved artifacts.

Generated controls may explore report data. Business actions still use Totem tools, permissions and Auto/Manual policy. Do not fabricate a rendering API or imply the generated report was saved. Existing Totem dashboards remain available when requested.
