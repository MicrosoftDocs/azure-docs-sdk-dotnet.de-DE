<Type Name="ServiceFromTemplateDescription" FullName="System.Fabric.Description.ServiceFromTemplateDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceFromTemplateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceFromTemplateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceFromTemplateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceFromTemplateDescription" />
  <TypeSignature Language="F#" Value="type ServiceFromTemplateDescription = class" />
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
            <span data-ttu-id="b33fb-101">Beschreibt einen Service Fabric-Dienst aus der Dienstvorlage erstellt werden, die in das aktuelle Anwendungsmanifest vordefiniert ist.</span><span class="sxs-lookup"><span data-stu-id="b33fb-101">Describes a Service Fabric service to be created from Service Template that is pre-defined in the current Application Manifest.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceFromTemplateDescription (Uri applicationName, Uri serviceName, string serviceDnsName, string serviceTypeName, System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, class System.Uri serviceName, string serviceDnsName, string serviceTypeName, valuetype System.Fabric.Description.ServicePackageActivationMode servicePackageActivationMode, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceFromTemplateDescription.#ctor(System.Uri,System.Uri,System.String,System.String,System.Fabric.Description.ServicePackageActivationMode,System.Byte[])" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceFromTemplateDescription : Uri * Uri * string * string * System.Fabric.Description.ServicePackageActivationMode * byte[] -&gt; System.Fabric.Description.ServiceFromTemplateDescription" Usage="new System.Fabric.Description.ServiceFromTemplateDescription (applicationName, serviceName, serviceDnsName, serviceTypeName, servicePackageActivationMode, initializationData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceDnsName" Type="System.String" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="servicePackageActivationMode" Type="System.Fabric.Description.ServicePackageActivationMode" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="b33fb-102">Der Service Fabric-Name der Anwendung unter der der Dienst erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="b33fb-102">The Service Fabric Name of the application under which the service will be created.</span></span></param>
        <param name="serviceName"><span data-ttu-id="b33fb-103">Der Name des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b33fb-103">Name of the service to create.</span></span></param>
        <param name="serviceDnsName"><span data-ttu-id="b33fb-104">DNS-Name des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b33fb-104">DNS name of the service to create.</span></span></param>
        <param name="serviceTypeName"><span data-ttu-id="b33fb-105">Name des ServiceType.</span><span class="sxs-lookup"><span data-stu-id="b33fb-105">Name of ServiceType.</span></span> <span data-ttu-id="b33fb-106">Dies ist identisch mit der ServiceTypeName in das Dienstmanifest angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="b33fb-106">This has to be same as the ServiceTypeName specified in the Service Manifest.</span></span></param>
        <param name="servicePackageActivationMode">
          <span data-ttu-id="b33fb-107"><see cref="T:System.Fabric.Description.ServicePackageActivationMode" />für die diensterstellung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="b33fb-107"><see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> to use for service creation.</span></span>
            </param>
        <param name="initializationData"><span data-ttu-id="b33fb-108">Die Initialisierungsdaten, die an den Dienst übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="b33fb-108">Initialization data that will be passed to service.</span></span></param>
        <summary>
            <span data-ttu-id="b33fb-109">Erstellt eine Instanz des <see cref="T:System.Fabric.Description.ServiceFromTemplateDescription" /> mit angegebenen Parameter.</span><span class="sxs-lookup"><span data-stu-id="b33fb-109">Creates an instance of <see cref="T:System.Fabric.Description.ServiceFromTemplateDescription" /> with specified parameter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ApplicationName" />
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
            <span data-ttu-id="b33fb-110">Der Service Fabric-Name der Anwendung unter der der Dienst erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="b33fb-110">The Service Fabric Name of the application under which the service will be created.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b33fb-111">Gibt <see cref="T:System.Uri" /> Service Fabric-Anwendungsnamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="b33fb-111">Returns <see cref="T:System.Uri" /> representing Service Fabric application name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.Description.ServiceFromTemplateDescription.InitializationData" />
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
            <span data-ttu-id="b33fb-112">Ruft ab oder legt ihn fest die Initialisierungsdaten, die übergeben werden Gruppe Dienstinstanzen oder Replikate bei ihrer Erstellung.</span><span class="sxs-lookup"><span data-stu-id="b33fb-112">Gets or sets the initialization data that will be passed to service group instances or replicas when they are created.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="b33fb-113">Gibt ein Array von <see cref="T:System.Byte" /> zurück.</span><span class="sxs-lookup"><span data-stu-id="b33fb-113">Returns an array of <see cref="T:System.Byte" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDnsName">
      <MemberSignature Language="C#" Value="public string ServiceDnsName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceDnsName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceDnsName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceDnsName : string" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceDnsName" />
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
            <span data-ttu-id="b33fb-114">Der DNS-Name des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b33fb-114">The DNS name of the service to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b33fb-115">Gibt <see cref="T:System.String" /> Service Fabric-Dienst-DNS-Namen darstellt.</span><span class="sxs-lookup"><span data-stu-id="b33fb-115">Returns <see cref="T:System.String" /> representing Service Fabric service DNS name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceName" />
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
            <span data-ttu-id="b33fb-116">Der Name des Diensts zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b33fb-116">Name of the service to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b33fb-117">Gibt <see cref="T:System.Uri" /> , Name des Service Fabric-Dienst darstellt.</span><span class="sxs-lookup"><span data-stu-id="b33fb-117">Returns <see cref="T:System.Uri" /> representing Service Fabric service name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServicePackageActivationMode" />
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
            <span data-ttu-id="b33fb-118">Ruft ab oder legt die <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> des Diensts.</span><span class="sxs-lookup"><span data-stu-id="b33fb-118">Gets or sets the <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> of service.</span></span>
            </summary>
        <value>
             <span data-ttu-id="b33fb-119">Eine <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="b33fb-119">An <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceFromTemplateDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Description.ServiceFromTemplateDescription.ServiceTypeName" />
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
            <span data-ttu-id="b33fb-120">Der Name des Diensttyps zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b33fb-120">Name of the service type to create.</span></span>
            </summary>
        <value>
            <span data-ttu-id="b33fb-121">Gibt <see cref="T:System.String" /> Service Fabric-Diensttypname darstellt.</span><span class="sxs-lookup"><span data-stu-id="b33fb-121">Returns <see cref="T:System.String" /> representing Service Fabric service type name.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>