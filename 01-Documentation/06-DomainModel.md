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
