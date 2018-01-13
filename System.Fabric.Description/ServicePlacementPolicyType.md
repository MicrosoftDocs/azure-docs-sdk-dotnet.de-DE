<Type Name="ServicePlacementPolicyType" FullName="System.Fabric.Description.ServicePlacementPolicyType">
  <TypeSignature Language="C#" Value="public enum ServicePlacementPolicyType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePlacementPolicyType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePlacementPolicyType" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServicePlacementPolicyType" />
  <TypeSignature Language="F#" Value="type ServicePlacementPolicyType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt den Typ der spezifischen <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePlacementPolicyType Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePlacementPolicyType.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Description.ServicePlacementPolicyType.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePlacementPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Ungültige Platzierung Richtlinientyp. Gibt an, dass der Typ der angegebenen Richtlinie unbekannt oder ungültig war.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InvalidDomain">
      <MemberSignature Language="C#" Value="InvalidDomain" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePlacementPolicyType InvalidDomain = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePlacementPolicyType.InvalidDomain" />
      <MemberSignature Language="VB.NET" Value="InvalidDomain" />
      <MemberSignature Language="F#" Value="InvalidDomain = 1" Usage="System.Fabric.Description.ServicePlacementPolicyType.InvalidDomain" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePlacementPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> ist eine <see cref="T:System.Fabric.Description.ServicePlacementInvalidDomainPolicyDescription" />, was bedeutet, dass auf einen bestimmten Fehler oder upgradedomäne für die Platzierung von diesem Dienst verwendet werden kann.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NonPartiallyPlaceService">
      <MemberSignature Language="C#" Value="NonPartiallyPlaceService" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePlacementPolicyType NonPartiallyPlaceService = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePlacementPolicyType.NonPartiallyPlaceService" />
      <MemberSignature Language="VB.NET" Value="NonPartiallyPlaceService" />
      <MemberSignature Language="F#" Value="NonPartiallyPlaceService = 5" Usage="System.Fabric.Description.ServicePlacementPolicyType.NonPartiallyPlaceService" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePlacementPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para />
        </summary>
      </Docs>
    </Member>
    <Member MemberName="PreferPrimaryDomain">
      <MemberSignature Language="C#" Value="PreferPrimaryDomain" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePlacementPolicyType PreferPrimaryDomain = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePlacementPolicyType.PreferPrimaryDomain" />
      <MemberSignature Language="VB.NET" Value="PreferPrimaryDomain" />
      <MemberSignature Language="F#" Value="PreferPrimaryDomain = 3" Usage="System.Fabric.Description.ServicePlacementPolicyType.PreferPrimaryDomain" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePlacementPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> ist eine <see cref="T:System.Fabric.Description.ServicePlacementPreferPrimaryDomainPolicyDescription" />, was bedeutet, dass nach Möglichkeit das primäre Replikat für die Partitionen des Diensts in einer bestimmten Domäne zur Optimierung gespeichert werden.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RequireDomain">
      <MemberSignature Language="C#" Value="RequireDomain" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePlacementPolicyType RequireDomain = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePlacementPolicyType.RequireDomain" />
      <MemberSignature Language="VB.NET" Value="RequireDomain" />
      <MemberSignature Language="F#" Value="RequireDomain = 2" Usage="System.Fabric.Description.ServicePlacementPolicyType.RequireDomain" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePlacementPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> ist eine <see cref="T:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription" /> gibt an, dass die Replikate des Diensts in einer bestimmten Domäne platziert werden müssen.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RequireDomainDistribution">
      <MemberSignature Language="C#" Value="RequireDomainDistribution" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePlacementPolicyType RequireDomainDistribution = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePlacementPolicyType.RequireDomainDistribution" />
      <MemberSignature Language="VB.NET" Value="RequireDomainDistribution" />
      <MemberSignature Language="F#" Value="RequireDomainDistribution = 4" Usage="System.Fabric.Description.ServicePlacementPolicyType.RequireDomainDistribution" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePlacementPolicyType</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /> ist eine <see cref="T:System.Fabric.Description.ServicePlacementRequireDomainDistributionPolicyDescription" />, gibt an, dass das System Platzierung von zwei Replikate aus der gleichen Partition in der gleichen Domäne zu einem beliebigen Zeitpunkt verweigert wird.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>