<Type Name="MonitoredRollingUpgradePolicyDescription" FullName="System.Fabric.Description.MonitoredRollingUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public abstract class MonitoredRollingUpgradePolicyDescription : System.Fabric.Description.RollingUpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MonitoredRollingUpgradePolicyDescription extends System.Fabric.Description.RollingUpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MonitoredRollingUpgradePolicyDescription&#xA;Inherits RollingUpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type MonitoredRollingUpgradePolicyDescription = class&#xA;    inherit RollingUpgradePolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.RollingUpgradePolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="681a2-101">Gibt das Verhalten beim Ausführen einer überwachten Anwendung oder -Cluster-Upgrades verwenden.</span><span class="sxs-lookup"><span data-stu-id="681a2-101">Specifies the behavior to use when performing a monitored application or cluster upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MonitoredRollingUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.MonitoredRollingUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="681a2-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="681a2-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.RollingUpgradeMonitoringPolicy MonitoringPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.RollingUpgradeMonitoringPolicy MonitoringPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingUpgradePolicyDescription.MonitoringPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitoringPolicy As RollingUpgradeMonitoringPolicy" />
      <MemberSignature Language="F#" Value="member this.MonitoringPolicy : System.Fabric.Description.RollingUpgradeMonitoringPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingUpgradePolicyDescription.MonitoringPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.RollingUpgradeMonitoringPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="681a2-103">Ruft ab oder legt die Überwachung Richtlinie verwenden, wenn ein Upgrade ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="681a2-103">Gets or sets the monitoring policy to use when performing an upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="681a2-104">Die Überwachung Richtlinie verwenden, wenn ein Upgrade ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="681a2-104">The monitoring policy to use when performing an upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>