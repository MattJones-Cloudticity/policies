# 10. Facility Access Policy

Cloudticity was born in the cloud, and has never been saddled with physical infrastructure. From the beginning we decided to focus on Amazon Web Services (AWS). Of note, Cloudticity does not have ready access to ePHI; it provides cloud-based, compliant infrastructure to covered entities and business associates. Cloudticity does not physically house any systems used by its platform in Cloudticity facilities. Physical security of our platform servers is outlined in [§1.4](01-introduction.md#14-cloudticity-organizational-concepts).

## 10.1 Applicable Standards

### 10.1.1 Applicable Standards from the HITRUST Common Security Framework

* 08.b - Physical Entry Controls
* 08.d - Protecting Against External and Environmental Threats
* 08.j - Equipment Maintenance
* 08.l - Secure Disposal or Re-Use of Equipment
* 09.p - Disposal of Media

### 10.1.2 Applicable Standards from the HIPAA Security Rule

* 164.310(a)(2)(ii) Facility Security Plan
* 164.310(a)(2)(iii) Access Control & Validation Procedures
* 164.310(b-c) Workstation Use & Security

## 10.2 Cloudticity-controlled Facility Access Policies

1. With no physical offices, visitors and third party support access is unnecessary. If a physical location is obtained, visitor and third-party support access will be recorded and supervised unless previously approved. Cloudticity employees that require a business visit involving covered information must obtain permission from the Security Officer prior to the visit.
2. With no physical offices, repairs and their documentation are unnecessary. If a physical location is obtained, repairs or modifications to the physical components of the facility which are related to security (e.g., hardware, walls, doors and locks) will be  documented and retained in accordance with the retention policy.
3. Within our homes, fire extinguishers and detectors are installed according to applicable laws and regulations.
4. With no physical offices, maintenance and its documentation is unnecessary. If a physical location is obtained, maintenance and service will be controlled and conducted by authorized personnel in accordance with supplier-recommended intervals, insurance policies, and the organizations future maintenance program, taking into account whether this maintenance is performed by personnel on site or external to the organization.
5. Cloudticity electronic and physical media does not contain covered information. If covered information is received on electronic and physical media, it will be securely destroyed (or the information securely removed) prior to disposal.
6. The organization will securely dispose of media with sensitive information.
7. With no physical offices, smart locks are unnecessary.
8. Enforcement of Facility Access Policies
   * Report violations of this policy to the restricted area's department team leader, supervisor, manager, or director, or the Privacy Officer.
   * Workforce members in violation of this policy are subject to disciplinary action, up to and including termination.
9. Workstation Security
   * Workstations may only be accessed and utilized by authorized workforce members to complete assigned job/contract responsibilities.
   * All workforce members are required to monitor workstations and report unauthorized users and/or unauthorized attempts to access systems/applications as per the [Systems Access Policy](07-systems_access_policy.md).
   * All workstations purchased by Cloudticity are the property of Cloudticity and are distributed to users by the company.

## 10.3 AWS-controlled Physical & Environmental Security Policies
The following controls are inherited from AWS:

1. Visitor and third-party support access is recorded and supervised unless previously approved.
2. Areas where sensitive information (e.g., covered information, payment card data) is stored or processed are controlled and restricted to authorized individuals only.
3. Repairs or modifications to the physical components of a facility which are related to security (e.g., hardware, walls, doors and locks) are documented and retained in accordance with the organization's retention policy.
4. A documented patch list and clearly identifiable cable and equipment markings are used to minimize handling errors, such as accidental patching of wrong network cables; and access to patch panels and cable rooms is controlled.
5. The organization formally addresses the purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities and compliance requirements for its equipment maintenance program (e.g., through policy, standards, guidelines, and procedures).
6. The organization maintains a list of authorized maintenance organizations or personnel, ensures that non-escorted personnel performing maintenance on the information system have required access authorizations, and designates organizational personnel with required access authorizations and technical competence to supervise the maintenance activities of personnel who do not possess the required access authorizations.
7. The organization monitors and controls nonlocal maintenance and diagnostic activities; and prohibits nonlocal system maintenance unless explicitly authorized, in writing, by the CIO or his/her designated representative.
8. The organization obtains maintenance support and/or spare parts for defined key information system components (defined in the applicable security plan) within the applicable Recovery Time Objective (RTO) specified in the contingency plan.
9. The organization ensures the risk of information leakage to unauthorized persons during secure media disposal is minimized. If collection and disposal services offered by other organizations are used, care is taken in selecting a suitable contractor with adequate controls and experience.
10. Disposal methods are commensurate with the sensitivity of the information contained on the media.
11. Fire extinguishers and detectors are installed according to applicable laws and regulations.
12. Maintenance and service are controlled and conducted by authorized personnel in accordance with supplier-recommended intervals, insurance policies and the organizations maintenance program, taking into account whether this maintenance is performed by personnel on site or external to the organization.
13. Electronic and physical media containing covered information is securely sanitized prior to reuse, or if it cannot be sanitized, is destroyed prior to disposal.
14. The organization securely disposes of media containing sensitive information.
15. Perimeters of a building or site containing information assets are physically sound, with no gaps and of solid construction; and all external doors are protected against unauthorized access with control mechanisms (e.g. bars, alarms, locks).
16. Any repairs or modifications to the physical components of a facility which are related to security are documented, and the documentation is retained in accordance with the organization's retention policy.
17. The organization develops, approves and maintains a list of individuals with authorized access to the facility where the information system resides; issues authorization credentials for facility access; reviews the access list and authorization credentials periodically but no less than quarterly; and removes individuals from the facility access list when access is no longer required.
18. For facilities where the information system resides, the organization enforces physical access authorizations at defined entry/exit points to the facility where the information system resides, maintains physical access audit logs, and provides security safeguards that the organization determines necessary for areas officially designated as publicly accessible.
19. Relevant health and safety regulations and standards are taken into consideration when securing facilities.
20. Fire authorities are automatically notified when a fire alarm is activated.
21. Access to a delivery and loading area from outside of the building is restricted to identified and authorized personnel, and the external doors of the area are secured when the internal doors are opened.
22. The delivery and loading area is designed so that supplies can be unloaded without delivery personnel gaining access to other parts of the building.
23. Incoming material is registered in accordance with asset management procedures on entry to the site; and incoming and outgoing shipments are physically segregated, where possible.
24. Lightning protection is applied to all buildings, and lightning protection filters (e.g. surge protectors) are fitted to all incoming power and communications lines.
25. Information assets handling covered information are positioned and the viewing angle restricted to reduce the risk of information being viewed by unauthorized persons during their use, and storage devices are secured to avoid unauthorized access.
26. Device locks are distributed and installed (implemented) for equipment containing covered information.
27. The organization plans the location or site of the facility where the information system resides with regard to physical and environmental hazards and for existing facilities, and considers the physical and environmental hazards in its risk mitigation strategy.
Controls are implemented to minimize the risk of potential physical threats including theft, fire, explosives, smoke, water (or water supply failure), dust, vibration, chemical effects, electrical supply interference, communications interference, electromagnetic radiation, vandalism, explosion, civil unrest, and other forms of natural or man-made disaster.
28. All supporting utilities are adequate for the systems they are supporting, and they are regularly inspected and tested.
29. The organization has a suitable electrical supply that conforms to the equipment manufacturer's specifications.
30. An uninterruptable power supply (UPS) is used for equipment supporting critical business operations to support orderly shutdown or continuous running (transition to long-term alternate power); UPS equipment and generators are regularly checked to ensure they have adequate capacity and are tested in accordance with the manufacturer's recommendations; and power contingency plans cover the action to be taken should the UPS fail.
31. The water supply is stable and adequate to supply air conditioning, humidification equipment and fire suppression systems.
32. The organization protects power equipment and power cabling for the information system from damage and destruction.