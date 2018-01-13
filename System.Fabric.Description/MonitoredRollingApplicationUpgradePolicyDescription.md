<Type Name="MonitoredRollingApplicationUpgradePolicyDescription" FullName="System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class MonitoredRollingApplicationUpgradePolicyDescription : System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MonitoredRollingApplicationUpgradePolicyDescription extends System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MonitoredRollingApplicationUpgradePolicyDescription&#xA;Inherits MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type MonitoredRollingApplicationUpgradePolicyDescription = class&#xA;    inherit MonitoredRollingUpgradePolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.MonitoredRollingUpgradePolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt das Verhalten beim Ausführen eines Anwendungsupgrades zu verwendenden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitoredRollingApplicationUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen oder festlegen die Integritätsrichtlinie zu verwendende hochleistungsfähiger Integrität für eine Aktualisierung Anwendung überprüft.</para>
        </summary>
        <value>
          <para>Beim Ausführen der Integrität zu verwendende Integritätsrichtlinie überprüft für eine Anwendung aktualisieren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>