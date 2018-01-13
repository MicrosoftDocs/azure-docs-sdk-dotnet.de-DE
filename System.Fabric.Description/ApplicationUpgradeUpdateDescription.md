<Type Name="ApplicationUpgradeUpdateDescription" FullName="System.Fabric.Description.ApplicationUpgradeUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpgradeUpdateDescription : System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpgradeUpdateDescription extends System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationUpgradeUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpgradeUpdateDescription&#xA;Inherits UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="F#" Value="type ApplicationUpgradeUpdateDescription = class&#xA;    inherit UpgradeUpdateDescriptionBase" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.UpgradeUpdateDescriptionBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>So ändern Sie die Upgrade-Parameter, die das Verhalten des Anwendungsupgrades beschreibt verwendet. Weitere Informationen finden Sie unter <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpgradeUpdateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpgradeUpdateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt eine Instanz der <see cref="T:System.Fabric.Description.ApplicationUpgradeUpdateDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeUpdateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationUpgradeUpdateDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Namen der Anwendung mit einem aktuellen Upgrade zu ändern.</para>
        </summary>
        <value>
          <para>Der Name der Anwendung mit einem aktuellen Upgrade zu ändern.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeUpdateDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ApplicationUpgradeUpdateDescription.HealthPolicy" />
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
          <para>Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />.</para>
        </summary>
        <value>
          <para>Der neue Wert des <see cref="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />.</para>
        </value>
        <remarks>Die Integritätsrichtlinie für die Anwendung wird zum Auswerten der Anwendungsintegrität.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>