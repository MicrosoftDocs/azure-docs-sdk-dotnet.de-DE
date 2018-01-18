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
      <para><span data-ttu-id="2cf03-101">So ändern Sie die Upgrade-Parameter, die das Verhalten des Anwendungsupgrades beschreibt verwendet.</span><span class="sxs-lookup"><span data-stu-id="2cf03-101">Used to modify the upgrade parameters describing the behavior of application upgrades.</span></span> <span data-ttu-id="2cf03-102">Weitere Informationen finden Sie unter <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="2cf03-102">See <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" />.</span></span></para>
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
          <para><span data-ttu-id="2cf03-103">Erstellt eine Instanz der <see cref="T:System.Fabric.Description.ApplicationUpgradeUpdateDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2cf03-103">Creates an instance of the <see cref="T:System.Fabric.Description.ApplicationUpgradeUpdateDescription" /> class.</span></span></para>
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
          <para><span data-ttu-id="2cf03-104">Ruft ab oder legt den Namen der Anwendung mit einem aktuellen Upgrade zu ändern.</span><span class="sxs-lookup"><span data-stu-id="2cf03-104">Gets or sets the name of the application with a current upgrade to modify.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2cf03-105">Der Name der Anwendung mit einem aktuellen Upgrade zu ändern.</span><span class="sxs-lookup"><span data-stu-id="2cf03-105">The name of the application with a current upgrade to modify.</span></span></para>
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
          <para><span data-ttu-id="2cf03-106">Ruft ab oder legt den neuen Wert des <see cref="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="2cf03-106">Gets or sets the new value of <see cref="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2cf03-107">Der neue Wert des <see cref="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="2cf03-107">the new value of <see cref="P:System.Fabric.Description.MonitoredRollingApplicationUpgradePolicyDescription.HealthPolicy" />.</span></span></para>
        </value>
        <remarks><span data-ttu-id="2cf03-108">Die Integritätsrichtlinie für die Anwendung wird zum Auswerten der Anwendungsintegrität.</span><span class="sxs-lookup"><span data-stu-id="2cf03-108">The application health policy is used to evaluate the application health.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>