1- ENTITIES 
Segurity
-User
-Rol
-Permission

Organization
-Season
-Estate/Farm
=Lot
-Variety

RRHH
-Worker
-Foreman
-Supervisor
-Crew

Operations
-Labor
-Labor Log - Fehca - Labor - Operator - Lot - If labor is cosecha, generates production
-Production

Quality
-Incident
-IncidentType
-Severity
-Photography

Intelligence 
-Indicator
-Alert
-Recommendation
-IA Consulting

2- Relationship
Season: 1 - n funds
Fund: 1 - n Lots
Lot: 1 - n LaborRegister
Crews: 1 - n Operators
Operator: n - 1 Crews
LaborRegister: 1 - 1 Labor
LaborRegister: 1 - 0..1 Production
Production: 1 - n Incidents
Production: 1 - n Alerts
Alert: 1 - n Recommendations

3- RESPONSIBILITIES 
SEAS0N
Responsability:
Group all information pertaining to an agricultural season

FUND
Responsability:
Management the general information for each agricultural unit

Lot
Responsability:
To represent a specific area within a farm or estate

LaborRegister
Responsability:
Record the execution of any agricultural task performed by a crew or operator

Production
Responsability:
Record the yield obtained when the task involves hervesting

Incidents
Responsability:
Recorded any event that affects quality, productivity, or operational continuity

