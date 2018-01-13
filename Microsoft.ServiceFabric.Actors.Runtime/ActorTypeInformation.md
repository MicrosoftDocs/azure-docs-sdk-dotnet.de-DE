<Type Name="ActorTypeInformation" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation">
  <TypeSignature Language="C#" Value="public sealed class ActorTypeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorTypeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorTypeInformation" />
  <TypeSignature Language="F#" Value="type ActorTypeInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1ba1e-101">Enthält Informationen über den Typ, der einen Akteur implementieren.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-101">Contains the information about the type implementing an actor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorTypeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-102">Initialisiert eine neue Instanz der ActorTypeInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-102">Initializes a new instance of the ActorTypeInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventInterfaceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Type&gt; EventInterfaceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; EventInterfaceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.EventInterfaceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventInterfaceTypes As IEnumerable(Of Type)" />
      <MemberSignature Language="F#" Value="member this.EventInterfaceTypes : seq&lt;Type&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.EventInterfaceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Type&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-103">Ruft der Akteur Ereignisschnittstelle, die die Akteurklasse implementiert.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-103">Gets the actor event interface which the actor class implements.</span></span>
            </summary>
        <value><span data-ttu-id="1ba1e-104">Ein Enumerator, der verwendet werden kann, durchlaufen über Ereignisschnittstelle Akteur die die Akteurklasse implementiert.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-104">An enumerator that can be used to iterate through the actor event interface which the actor class implements.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation Get (Type actorType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation Get(class System.Type actorType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.Get(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Get (actorType As Type) As ActorTypeInformation" />
      <MemberSignature Language="F#" Value="static member Get : Type -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.Get actorType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorType"><span data-ttu-id="1ba1e-105">Der Typ der Klasse, die den Akteur zum Erstellen von ActorTypeInforamtion für implementiert.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-105">The type of class implementing the actor to create ActorTypeInforamtion for.</span></span></param>
        <summary>
            <span data-ttu-id="1ba1e-106">Erstellt eine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> aus ActorType.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-106">Creates an <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> from actorType.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="1ba1e-107"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />aus ActorType erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-107"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> created from actorType.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="1ba1e-108">Wenn <see cref="P:System.Type.BaseType" /> für ActorType nicht vom Typ ist <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-108">When <see cref="P:System.Type.BaseType" /> for actorType is not of type <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span></span></para>
          <para><span data-ttu-id="1ba1e-109">Wenn ActorType keine Schnittstelle ableiten von implementiert <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und ist nicht als abstrakt gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-109">When actorType does not implement an interface deriving from <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> and is not marked as abstract.</span></span></para>
          <para><span data-ttu-id="1ba1e-110">Wenn ActorType implementiert mehrere Schnittstellen abgeleitet von <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> jedoch keine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-110">When actorType implements more than one interface which derives from <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> but doesn't have <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ImplementationType">
      <MemberSignature Language="C#" Value="public Type ImplementationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ImplementationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ImplementationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImplementationType As Type" />
      <MemberSignature Language="F#" Value="member this.ImplementationType : Type" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ImplementationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-111">Ruft den Typ der Klasse, die den Akteur implementieren.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-111">Gets the type of the class implementing the actor.</span></span>
            </summary>
        <value><span data-ttu-id="1ba1e-112">Die <see cref="T:System.Type" /> der Implementierung des Akteurs-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-112">The <see cref="T:System.Type" /> of the class implementing the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Type&gt; InterfaceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; InterfaceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.InterfaceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InterfaceTypes As IEnumerable(Of Type)" />
      <MemberSignature Language="F#" Value="member this.InterfaceTypes : seq&lt;Type&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.InterfaceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Type&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-113">Ruft den Akteur Schnittstellentypen die Ableitung <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und vom Akteurklasse implementiert werden.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-113">Gets the actor interface types which derive from <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> and implemented by actor class.</span></span>
            </summary>
        <value><span data-ttu-id="1ba1e-114">Ein Enumerator, der zum Durchlaufen des Akteur Schnittstellentyps verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-114">An enumerator that can be used to iterate through the actor interface type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAbstract">
      <MemberSignature Language="C#" Value="public bool IsAbstract { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAbstract" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsAbstract" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAbstract As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAbstract : bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsAbstract" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-115">Ruft einen Wert ab, ob die implementierende Klasse Akteur abstrakt ist.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-115">Gets a value whether the class implementing actor is abstract.</span></span>
            </summary>
        <value><span data-ttu-id="1ba1e-116">"true", wenn die implementierende Klasse Akteur abstrakt, andernfalls "false ist".</span><span class="sxs-lookup"><span data-stu-id="1ba1e-116">true if the class implementing actor is abstract, otherwise false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRemindable">
      <MemberSignature Language="C#" Value="public bool IsRemindable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRemindable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsRemindable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsRemindable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRemindable : bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.IsRemindable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-117">Ruft einen Wert ab, ob die Akteurklasse implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-117">Gets a value whether the actor class implements <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />.</span></span>
            </summary>
        <value><span data-ttu-id="1ba1e-118">"true", wenn die Akteurklasse implementiert <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="1ba1e-118">true if the actor class implements <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" />, otherwise false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public string ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceName : string" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-119">Ruft den Dienstnamen ab, falls angegeben, mit <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> für Akteurklasse.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-119">Gets the service name if specified using <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> for actor class.</span></span>
            </summary>
        <value><span data-ttu-id="1ba1e-120">Der Dienstname angegeben mit <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> für Akteurklasse, null, wenn das Attribut nicht verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-120">The service name if specified using <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" /> for actor class, null if attribute is not used.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatePersistence">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.StatePersistence StatePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.StatePersistence" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatePersistence As StatePersistence" />
      <MemberSignature Language="F#" Value="member this.StatePersistence : Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.StatePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.StatePersistence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba1e-121">Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" /> Enum-Typ von Statuspersistenz für den Akteur darstellt.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-121">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" /> enum representing type of state persistence for the actor.</span></span>
            </summary>
        <value><span data-ttu-id="1ba1e-122">Die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" /> , der Typ des Sitzungszustands für der Akteur darstellt.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-122">The <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StatePersistence" /> representing type of state persistence for the actor.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public static bool TryGet (Type actorType, out Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGet(class System.Type actorType, [out] class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation&amp; actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.TryGet(System.Type,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryGet (actorType As Type, ByRef actorTypeInformation As ActorTypeInformation) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryGet : Type *  -&gt; bool" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation.TryGet (actorType, actorTypeInformation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorType" Type="System.Type" />
        <Parameter Name="actorTypeInformation" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="actorType"><span data-ttu-id="1ba1e-123">Der Typ der Klasse, die den Akteur zum Erstellen von ActorTypeInforamtion für implementiert.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-123">The type of class implementing the actor to create ActorTypeInforamtion for.</span></span></param>
        <param name="actorTypeInformation"><span data-ttu-id="1ba1e-124">Diese Methode zurückgibt, enthält ActorTypeInformation, wenn die Erstellung von ActorTypeInformation aus ActorType erfolgreich war, oder Null, wenn Fehler beim Erstellen.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-124">When this method returns, contains ActorTypeInformation, if the creation of ActorTypeInformation from actorType succeeded, or null if the creation failed.</span></span>
            <span data-ttu-id="1ba1e-125">Die Erstellung schlägt fehl, wenn der ActorType-Parameter null ist oder einen Akteur wird nicht implementiert.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-125">The creation fails if the actorType parameter is null or it does not implement an actor.</span></span></param>
        <summary>
            <span data-ttu-id="1ba1e-126">Erstellt die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> aus ActorType.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-126">Creates the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> from actorType.</span></span>
            </summary>
        <returns><span data-ttu-id="1ba1e-127">"true", wenn ActorTypeInformation für ActorType erfolgreich erstellt wurde; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="1ba1e-127">true if ActorTypeInformation was successfully created for actorType; otherwise, false.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="1ba1e-128">Erstellung von ActorTypeInformation aus ActorType fehl, wenn</span><span class="sxs-lookup"><span data-stu-id="1ba1e-128">Creation of ActorTypeInformation from actorType will fail when</span></span> </para>
          <para>1. <span data-ttu-id="1ba1e-129"><see cref="P:System.Type.BaseType" />für ActorType nicht vom Typ ist <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-129"><see cref="P:System.Type.BaseType" /> for actorType is not of type <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />.</span></span></para>
          <para>2. <span data-ttu-id="1ba1e-130">ActorType implementiert eine Schnittstelle ableiten von nicht <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> und ist nicht als abstrakt gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-130">actorType does not implement an interface deriving from <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> and is not marked as abstract.</span></span></para>
          <para>3. <span data-ttu-id="1ba1e-131">ActorType implementiert mehrere Schnittstellen abgeleitet von <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> jedoch keine <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</span><span class="sxs-lookup"><span data-stu-id="1ba1e-131">actorType implements more than one interface which derives from <see cref="T:Microsoft.ServiceFabric.Actors.IActor" /> but doesn't have <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorServiceAttribute" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>