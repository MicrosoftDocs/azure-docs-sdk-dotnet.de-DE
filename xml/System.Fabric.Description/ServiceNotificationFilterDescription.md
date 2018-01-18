<Type Name="ServiceNotificationFilterDescription" FullName="System.Fabric.Description.ServiceNotificationFilterDescription">
  <TypeSignature Language="C#" Value="public class ServiceNotificationFilterDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceNotificationFilterDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceNotificationFilterDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceNotificationFilterDescription" />
  <TypeSignature Language="F#" Value="type ServiceNotificationFilterDescription = class" />
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
      <para><span data-ttu-id="4347b-101">Stellt eine Klasse, die verwendet wird, um einen Filter für die Übermittlung der Benachrichtigung Service, beschreiben registriert über <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</span><span class="sxs-lookup"><span data-stu-id="4347b-101">Represents a class that is used to describe a filter for service notification delivery, registered via <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="4347b-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4347b-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription (Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor(System.Uri,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As Uri, matchNamePrefix As Boolean, matchPrimaryChangeOnly As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceNotificationFilterDescription : Uri * bool * bool -&gt; System.Fabric.Description.ServiceNotificationFilterDescription" Usage="new System.Fabric.Description.ServiceNotificationFilterDescription (name, matchNamePrefix, matchPrimaryChangeOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="matchNamePrefix" Type="System.Boolean" />
        <Parameter Name="matchPrimaryChangeOnly" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="4347b-103">Der Name, für welchen Dienst Benachrichtigungen übermittelt werden soll.</span><span class="sxs-lookup"><span data-stu-id="4347b-103">The name for which service notifications should be delivered.</span></span></para>
        </param>
        <param name="matchNamePrefix">
          <para><span data-ttu-id="4347b-104">Flag, die angibt, ob alle Benachrichtigungen service für die Namen ein Präfix ist wird übermittelt.</span><span class="sxs-lookup"><span data-stu-id="4347b-104">Flag that indicates whether all service notifications for which Name is a prefix will be delivered.</span></span></para>
        </param>
        <param name="matchPrimaryChangeOnly">
          <para><span data-ttu-id="4347b-105">Flag, die angibt, ob entsprechend der Anzahl der Übermittlung der Benachrichtigung durch Herausfiltern von Benachrichtigungen, die in denen das primäre Replikat-Endpunkts nicht geändert hat.</span><span class="sxs-lookup"><span data-stu-id="4347b-105">Flag that indicates whether to match the service notification delivery by filtering out notifications in which the primary replica endpoint has not changed.</span></span> <span data-ttu-id="4347b-106">Dieses Flag hat keine Auswirkungen für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="4347b-106">This flag has no effect for stateless services.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="4347b-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4347b-107">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchNamePrefix">
      <MemberSignature Language="C#" Value="public bool MatchNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchNamePrefix" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchNamePrefix As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchNamePrefix : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4347b-108">Ruft einen Wert, der angibt, ob alle dienstbenachrichtigungen, die für die Namen ein Präfix ist übermittelt werden soll.</span><span class="sxs-lookup"><span data-stu-id="4347b-108">Gets a value that indicates whether all service notifications for which Name is a prefix will be delivered.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="4347b-109"><languageKeyword>"true"</languageKeyword> Wenn alle Service-Benachrichtigung für den Namen ein Präfix ist geliefert wurde, andernfalls wird <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="4347b-109"><languageKeyword>true</languageKeyword> if all service notification for which Name is a prefix will be delivered; otherwise, <languageKeyword>false</languageKeyword>.</span></span> <span data-ttu-id="4347b-110">Die Standardeinstellung ist <languageKeyword>false</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="4347b-110">The default is <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
            <span data-ttu-id="4347b-111">Der Präfix-Vergleich tritt auf, als Dienstnamen ein zeichenfolgenpräfix, anstatt eine URI-Segment Präfix Übereinstimmung verglichen.</span><span class="sxs-lookup"><span data-stu-id="4347b-111">The prefix match occurs as a URI segment prefix match rather than a string prefix match against service names.</span></span> <span data-ttu-id="4347b-112">Ein Filter mit dem Namen "Fabric: / Abc" wird als Präfix Übereinstimmung Dienste mit dem Namen "Fabric: / Abc" und "Fabric: / Abc/Def", jedoch nicht um einen Dienst mit dem Namen "Fabric: / Abc_def".</span><span class="sxs-lookup"><span data-stu-id="4347b-112">A filter with the name "fabric:/abc" will prefix match services named "fabric:/abc" and "fabric:/abc/def", but not a service named "fabric:/abc_def".</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchPrimaryChangeOnly">
      <MemberSignature Language="C#" Value="public bool MatchPrimaryChangeOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchPrimaryChangeOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchPrimaryChangeOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchPrimaryChangeOnly : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4347b-113">Ruft einen Wert, der angibt, ob die Anzahl der Übermittlung der Benachrichtigung abgeglichen, indem Herausfiltern von Benachrichtigungen, die in denen das primäre Replikat-Endpunkts nicht geändert hat.</span><span class="sxs-lookup"><span data-stu-id="4347b-113">Gets a value that indicates whether to match the service notification delivery by filtering out notifications in which the primary replica endpoint has not changed.</span></span> <span data-ttu-id="4347b-114">Dieses Flag hat keine Auswirkungen für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="4347b-114">This flag has no effect for stateless services.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="4347b-115"><languageKeyword>"true"</languageKeyword> , wenn die Filterung mit primären Änderung, andernfalls übereinstimmt <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="4347b-115"><languageKeyword>true</languageKeyword> if the filtering matches primary change only; otherwise, <languageKeyword>false</languageKeyword>.</span></span> <span data-ttu-id="4347b-116">Die Standardeinstellung ist <languageKeyword>false</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="4347b-116">The default is <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Uri Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Uri" />
      <MemberSignature Language="F#" Value="member this.Name : Uri with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
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
          <para><span data-ttu-id="4347b-117">Ruft den Namen für die, den Service Benachrichtigungen übermittelt werden soll.</span><span class="sxs-lookup"><span data-stu-id="4347b-117">Gets the name for which service notifications should be delivered.</span></span> <span data-ttu-id="4347b-118">Der Name muss im Fabric: Schema.</span><span class="sxs-lookup"><span data-stu-id="4347b-118">The name must be in the fabric: scheme.</span></span> <span data-ttu-id="4347b-119">Der Stammname ("Fabric:") ist zulässig.</span><span class="sxs-lookup"><span data-stu-id="4347b-119">The root name ("fabric:") is allowed.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4347b-120">Der Name, für welchen Dienst Benachrichtigungen übermittelt werden soll.</span><span class="sxs-lookup"><span data-stu-id="4347b-120">The name for which service notifications should be delivered.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>