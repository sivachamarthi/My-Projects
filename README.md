VisualStudio
============

All Samples done in VisualStudio



select [identity].id as IdentityId, IdentityName, IsActive, aheaditemtype.Name, TEquipmentId, Country, EquipmentNumber, IsRTCEnabled, UnsubscribeAfter from [identity]
    inner join identityresource on [identity].id = identityresource.identityid
    inner join aheaditemtype on aheaditemtype.id = aheaditemtypeid
    right outer join equipment on equipment.tequipmentid = identityresource.tresourceid
    inner join unittype on unittype.id = unittypeid
    order by [identity].id
