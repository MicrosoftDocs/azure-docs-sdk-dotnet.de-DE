<Type Name="ApplicationType" FullName="System.Fabric.Query.ApplicationType">
  <TypeSignature Language="C#" Value="public sealed class ApplicationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationType" />
  <TypeSignature Language="F#" Value="type ApplicationType = class" />
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
      <para><span data-ttu-id="3c01e-101">Stellt einen Anwendungstyp dar.</span><span class="sxs-lookup"><span data-stu-id="3c01e-101">Represents an application type.</span></span></para>
    </summary>
    <remarks>
      <para>
                    <span data-ttu-id="3c01e-102">Ein Anwendungstyp ist eine Kategorisierung einer Anwendung und besteht aus einem Bündel von Diensttypen.</span><span class="sxs-lookup"><span data-stu-id="3c01e-102">An application type is a categorization of an application and consists of a bundle of service types.</span></span>
                    <span data-ttu-id="3c01e-103">Details finden Sie in diesem <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model">Dokument</see>.</span><span class="sxs-lookup"><span data-stu-id="3c01e-103">Details are described in this <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model">document</see>.</span></span>
                </para>
      <para>
                    <span data-ttu-id="3c01e-104">Anwendungstyp enthält alle, die für eine funktionierende Anwendung, z. B. der Codepakete für die Dienste erforderlich ist, die sie umfasst.</span><span class="sxs-lookup"><span data-stu-id="3c01e-104">An application type contains all that is needed for a functioning application, such as the code packages for the services it encompasses.</span></span> <span data-ttu-id="3c01e-105">Außerdem enthält es ein Anwendungsmanifest.</span><span class="sxs-lookup"><span data-stu-id="3c01e-105">It also contains an application manifest.</span></span> <span data-ttu-id="3c01e-106">Wenn eine Anwendung aus einer Anwendung vom Typ instanziiert wird, kann das Anwendungsmanifest, das mit der Anwendung verknüpft sind, überschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="3c01e-106">When an application is instantiated from an application type, the application manifest associated with the application type can be overridden.</span></span> <span data-ttu-id="3c01e-107">Der Anwendungstyp muss hochgeladen werden, bevor eine Anwendung erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="3c01e-107">The application type must be uploaded before an application can be created.</span></span>
                    </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationTypeDefinitionKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeDefinitionKind As ApplicationTypeDefinitionKind" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKind : System.Fabric.Query.ApplicationTypeDefinitionKind" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeDefinitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3c01e-108">Ruft die definitionsart.</span><span class="sxs-lookup"><span data-stu-id="3c01e-108">Gets the definition kind.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c01e-109">Der definitionsart enthält einen der Werte in der Enumeration definierten <see cref="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />.</span><span class="sxs-lookup"><span data-stu-id="3c01e-109">The definition kind which contains one of the values defined in the enumeration <see cref="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />.</span></span></para>
          <para><span data-ttu-id="3c01e-110">Gibt den Mechanismus der Benutzer Benutzer um einen Anwendungstyp Service Fabric zu definieren.</span><span class="sxs-lookup"><span data-stu-id="3c01e-110">Specifies the mechanism the user userd to define a Service Fabric application type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeName" />
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
          <para><span data-ttu-id="3c01e-111">Ruft den Typnamen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="3c01e-111">Gets the application type name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c01e-112">Der Name des Anwendungstyps die im Manifest Anwendung definiert ist.</span><span class="sxs-lookup"><span data-stu-id="3c01e-112">The application type name which is defined in the application manifest.</span></span> <span data-ttu-id="3c01e-113">Dieser Wert in Verbindung mit die Version der Anwendung erstellen einen eindeutigen Bezeichner für den Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="3c01e-113">This value, in conjunction with the application type version create a unique identifier for the application type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
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
          <para><span data-ttu-id="3c01e-114">Ruft die Version der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="3c01e-114">Gets the application type version.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c01e-115">Die anwendungstypversion, die im Manifest Anwendung definiert ist.</span><span class="sxs-lookup"><span data-stu-id="3c01e-115">The application type version which is defined in the application manifest.</span></span> <span data-ttu-id="3c01e-116">Dieser Wert in Verbindung mit der Name des Anwendungstyps erstellen einen eindeutigen Bezeichner für den Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="3c01e-116">This value, in conjunction with the application type name create a unique identifier for the application type.</span></span> <span data-ttu-id="3c01e-117">Dieser Wert muss nicht numerischen Wert sein.</span><span class="sxs-lookup"><span data-stu-id="3c01e-117">This value need not be numerical in value.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList DefaultParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList DefaultParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.DefaultParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.DefaultParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.ApplicationType.DefaultParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationParameterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3c01e-118">Ruft die Parameter der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="3c01e-118">Gets the default application parameters.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c01e-119">Die Anwendung-Standardparameter, im Manifest Anwendung definiert.</span><span class="sxs-lookup"><span data-stu-id="3c01e-119">The default application parameters defined in the application manifest.</span></span> <span data-ttu-id="3c01e-120">Wenn eine Anwendung aus diesen Anwendungstyp instanziiert wird, sind diese Parameter verwendet, es sei denn, sie außer Kraft gesetzt werden.</span><span class="sxs-lookup"><span data-stu-id="3c01e-120">When an application is instantiated from this application type, these are the parameters used unless they are overridden.</span></span> <span data-ttu-id="3c01e-121">Die instanziierte Anwendung möglicherweise auch weitere Anwendungsparameter definiert, zusätzlich zu den in dieser Eigenschaft definiert.</span><span class="sxs-lookup"><span data-stu-id="3c01e-121">The instantiated application may also have more application parameters defined in addition to the ones defined in this property.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As ApplicationTypeStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.Query.ApplicationTypeStatus" Usage="System.Fabric.Query.ApplicationType.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3c01e-122">Ruft den Status der Anwendung-Typ ab.</span><span class="sxs-lookup"><span data-stu-id="3c01e-122">Gets the application type status.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c01e-123">Enthält einen der Werte in der Enumeration definierten Typ Anwendungsstatus <see cref="M:System.Fabric.Query.ApplicationTypeStatus.#ctor" />.</span><span class="sxs-lookup"><span data-stu-id="3c01e-123">The application type status which contains one of the values defined in the enumeration <see cref="M:System.Fabric.Query.ApplicationTypeStatus.#ctor" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="System.Fabric.Query.ApplicationType.StatusDetails" />
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
          <para><span data-ttu-id="3c01e-124">Ruft den Anwendungstyp Statusdetails an.</span><span class="sxs-lookup"><span data-stu-id="3c01e-124">Gets the application type status details.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3c01e-125">Die Anwendung Typ Statusdetails.</span><span class="sxs-lookup"><span data-stu-id="3c01e-125">The application type status details.</span></span> <span data-ttu-id="3c01e-126">Dieses Objekt enthält Informationen zu diesen Anwendungstyp Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="3c01e-126">This contains information pertaining to provisioning of this application type.</span></span>
            <span data-ttu-id="3c01e-127">Während der Bereitstellung enthält diese Statusinformationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="3c01e-127">During provision, this contains progress information.</span></span> <span data-ttu-id="3c01e-128">Bereitstellung sollte nicht ausgeführt werden, dadurch wird die Fehlermeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="3c01e-128">Should provisioning fail, this provides the error message.</span></span>
            <span data-ttu-id="3c01e-129">Andernfalls wird dieses Feld leer gelassen.</span><span class="sxs-lookup"><span data-stu-id="3c01e-129">This field is left blank otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>