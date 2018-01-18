<Type Name="ApplicationUpgradeDescription" FullName="System.Fabric.Description.ApplicationUpgradeDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpgradeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpgradeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationUpgradeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpgradeDescription" />
  <TypeSignature Language="F#" Value="type ApplicationUpgradeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="416ef-101">Beschreibt die Upgraderichtlinie und die Anwendung aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="416ef-101">Describes the upgrade policy and the application to be upgraded.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpgradeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpgradeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="416ef-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationUpgradeDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="416ef-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.ApplicationUpgradeDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationUpgradeDescription.ApplicationName" />
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
          <para><span data-ttu-id="416ef-103">Ruft ab oder legt den URI-Namen der Anwendungsinstanz, die aktualisiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="416ef-103">Gets or sets the URI name of the application instance that needs to be upgraded.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="416ef-104">Der Name der URI der Anwendungsinstanz, die aktualisiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="416ef-104">The URI name of the application instance that needs to be upgraded.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ApplicationParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.ApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationParameters As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ApplicationParameters : System.Collections.Specialized.NameValueCollection" Usage="System.Fabric.Description.ApplicationUpgradeDescription.ApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="416ef-105">Ruft ab oder legt die Auflistung von Name / Wert-Paaren für die Parameter, die in der ApplicationManifest.xml angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="416ef-105">Gets or sets the collection of name-value pairs for the parameters that are specified in the ApplicationManifest.xml.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="416ef-106">Die Auflistung von Name-Wert-Paare für die Parameter, die in der ApplicationManifest.xml angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="416ef-106">The collection of name-value pairs for the parameters that are specified in the ApplicationManifest.xml.</span></span></para>
        </value>
        <remarks>
            <span data-ttu-id="416ef-107">Die maximale zulässige Länge eines Parameterwerts ist 1024 \* 1024 Zeichen (einschließlich das abschließende Nullzeichen).</span><span class="sxs-lookup"><span data-stu-id="416ef-107">The maximum allowed length of a parameter value is 1024\*1024 characters (including the terminating null character).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string TargetApplicationTypeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.TargetApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetApplicationTypeVersion : string with get, set" Usage="System.Fabric.Description.ApplicationUpgradeDescription.TargetApplicationTypeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="416ef-108">Ruft ab oder legt die Version des Anwendungstyps, zu dem die Instanz der Anwendung ein Upgrade durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="416ef-108">Gets or sets the version of the application type to which the application instance is upgrading.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="416ef-109">Die Version der Anwendung vom Typ, den die Instanz der Anwendung ein Upgrade durchgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="416ef-109">The version of the application type to which the application instance is upgrading.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicyDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.UpgradePolicyDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicyDescription As UpgradePolicyDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription with get, set" Usage="System.Fabric.Description.ApplicationUpgradeDescription.UpgradePolicyDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradePolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="416ef-110">Ruft ab oder legt die Beschreibung der Richtlinie für diese Anwendungsinstanz Aktualisierung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="416ef-110">Gets or sets the description of the policy to be used for upgrading this application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="416ef-111">Die Beschreibung der Richtlinie für diese Anwendungsinstanz Aktualisierung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="416ef-111">The description of the policy to be used for upgrading this application instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>