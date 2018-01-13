<Type Name="ServiceGroupFromTemplateDescription" FullName="System.Fabric.Description.ServiceGroupFromTemplateDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupFromTemplateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupFromTemplateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceGroupFromTemplateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupFromTemplateDescription" />
  <TypeSignature Language="F#" Value="type ServiceGroupFromTemplateDescription = class" />
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
            <span data-ttu-id="7502d-101">Eine Dienstgruppe aus einer Gruppe Dienstvorlage erstellt werden, die in das aktuelle Anwendungsmanifest vordefiniert ist.</span><span class="sxs-lookup"><span data-stu-id="7502d-101">Describes a Service Group to be created from a Service Group Template that is pre-defined in the current Application Manifest.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupFromTemplateDescription (Uri applicationName, Uri serviceName, string serviceTypeName, System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, valuetype System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupFromTemplateDescription.#ctor(System.Uri,System.Uri,System.String,System.Fabric.Description.ServicePackageActivationMode,System.Byte[])" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceGroupFromTemplateDescription : Uri * Uri * string * System.Fabric.Description.ServicePackageActivationMode * byte[] -&gt; System.Fabric.Description.ServiceGroupFromTemplateDescription" Usage="new System.Fabric.Description.ServiceGroupFromTemplateDescription (applicationName, serviceName, serviceTypeName, servicePackageActivationMode, initializationData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="servicePackageActivationMode" Type="System.Fabric.Description.ServicePackageActivationMode" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="7502d-102">Der Anwendungsname für die Service-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="7502d-102">Application name for the Service Group.</span></span></param>
        <param name="serviceName"><span data-ttu-id="7502d-103">&gt;Der Dienstname für die Service-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="7502d-103">&gt;Service name for the Service Group.</span></span></param>
        <param name="serviceTypeName"><span data-ttu-id="7502d-104">Typ-Dienstname für die Service-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="7502d-104">Service Type Name for the Service Group.</span></span></param>
        <param name="servicePackageActivationMode">
          <span data-ttu-id="7502d-105"><see cref="T:System.Fabric.Description.ServicePackageActivationMode" />für die Gruppe der diensterstellung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="7502d-105"><see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> to use for service group creation.</span></span>
            </param>
        <param name="initializationData"><span data-ttu-id="7502d-106">Die Initialisierungsdaten, die an die Gruppe "Datenzugriffsdienst" übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="7502d-106">Initialization data that will be passed to Service Group.</span></span></param>
        <summary>
            <span data-ttu-id="7502d-107">Erstellt eine Instanz des <see cref="T:System.Fabric.Description.ServiceGroupFromTemplateDescription" /> mit angegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="7502d-107">Creates an instance of <see cref="T:System.Fabric.Description.ServiceGroupFromTemplateDescription" /> with specified parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ApplicationName" />
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
            <span data-ttu-id="7502d-108">Der Name der Anwendung, zu welcher, die Dienst Gruppe gehört.</span><span class="sxs-lookup"><span data-stu-id="7502d-108">Name of the application to which service group belongs.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7502d-109">Die <see cref="T:System.Uri" /> Service Fabric-Anwendungsnamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="7502d-109">The <see cref="T:System.Uri" /> representing Service Fabric application name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> <span data-ttu-id="7502d-110">Ruft ab oder die Initialisierungsdaten, die übergeben werden bei der Erstellung an Dienstinstanzen oder Replikate legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="7502d-110">Gets or sets the initialization data that will be passed to service instances or replicas when they are created.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="7502d-111">Gibt ein Array von <see cref="T:System.Byte" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="7502d-111">Returns an array of <see cref="T:System.Byte" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceName" />
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
            <span data-ttu-id="7502d-112">Der Name der Dienstgruppe erstellen.</span><span class="sxs-lookup"><span data-stu-id="7502d-112">Name of the service group to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7502d-113">Die <see cref="T:System.Uri" /> Service Fabric-Dienst-Gruppennamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="7502d-113">The <see cref="T:System.Uri" /> representing Service Fabric service group name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ServicePackageActivationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7502d-114">Ruft ab oder legt die <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> der Gruppe "Datenzugriffsdienst".</span><span class="sxs-lookup"><span data-stu-id="7502d-114">Gets or sets the <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> of service group.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7502d-115">Eine <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="7502d-115">A <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Description.ServiceGroupFromTemplateDescription.ServiceTypeName" />
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
            <span data-ttu-id="7502d-116">Der Name des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7502d-116">Name of the service to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7502d-117">Die <see cref="T:System.String" /> Service Fabric-Diensttypname darstellt.</span><span class="sxs-lookup"><span data-stu-id="7502d-117">The <see cref="T:System.String" /> representing Service Fabric service type name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>