<Type Name="ActorNameFormat" FullName="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat">
  <TypeSignature Language="C#" Value="public static class ActorNameFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActorNameFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorNameFormat" />
  <TypeSignature Language="F#" Value="type ActorNameFormat = class" />
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
            <span data-ttu-id="8b43d-101">Enthält statische Methoden zum Generieren von Namen wie der Dienstname, Namen Anwendungsformular den Schnittstellentyp Akteur.</span><span class="sxs-lookup"><span data-stu-id="8b43d-101">Contains static methods for generating names like service name, application name form the actor interface type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetActorStateProviderSettingsSectionName">
      <MemberSignature Language="C#" Value="public static string GetActorStateProviderSettingsSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetActorStateProviderSettingsSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetActorStateProviderSettingsSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetActorStateProviderSettingsSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetActorStateProviderSettingsSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetActorStateProviderSettingsSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">
            <span data-ttu-id="8b43d-102">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-102">Type of class implementing the actor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b43d-103">Ruft die <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> Konfigurationsabschnittsname im Konfigurationspaket für den Dienst Akteur angegeben.</span><span class="sxs-lookup"><span data-stu-id="8b43d-103">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> configuration section name specified in configuration package for the actor service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b43d-104">Der Konfigurationsabschnittsname ActorStateProvider.</span><span class="sxs-lookup"><span data-stu-id="8b43d-104">ActorStateProvider configuration section name.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="8b43d-105">Im Konfigurationsabschnitt ActorStateProvider angegebenen Werte werden verwendet, um konfigurieren<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /></span><span class="sxs-lookup"><span data-stu-id="8b43d-105">Values specified in ActorStateProvider configuration section are used to configure <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageName">
      <MemberSignature Language="C#" Value="public static string GetCodePackageName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetCodePackageName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetCodePackageName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetCodePackageName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetCodePackageName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetCodePackageName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-106">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-106">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-107">Ruft ab, der codepaketname im Dienstpaket für der Akteur verwendet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-107">Gets the code package name used in service package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-108">der codepaketname.</span><span class="sxs-lookup"><span data-stu-id="8b43d-108">code package name.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-109">Codepaketname kann über einen Dienst als zugegriffen werden<see cref="P:System.Fabric.CodePackageActivationContext.CodePackageName" /></span><span class="sxs-lookup"><span data-stu-id="8b43d-109">Code package name can be accessed from within a service as <see cref="P:System.Fabric.CodePackageActivationContext.CodePackageName" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigPackageName">
      <MemberSignature Language="C#" Value="public static string GetConfigPackageName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetConfigPackageName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetConfigPackageName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetConfigPackageName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetConfigPackageName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetConfigPackageName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-110">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-110">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-111">Ruft das Paket im Dienstpaket für der Akteur verwendete Name.</span><span class="sxs-lookup"><span data-stu-id="8b43d-111">Gets the configuration package name used in service package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-112">Konfiguration der Paketname.</span><span class="sxs-lookup"><span data-stu-id="8b43d-112">configuration package name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix"><span data-ttu-id="8b43d-113">Präfix für den Namen der Anwendung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b43d-113">Prefix to be used for the application name.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-114">Ruft den Namen der Anwendung verwendet, um die Anwendung in Service Fabric-Cluster zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="8b43d-114">Gets the application name used to create application in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-115">Name der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="8b43d-115">Application name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationPackageName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationPackageName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationPackageName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationPackageName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationPackageName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationPackageName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationPackageName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix"><span data-ttu-id="8b43d-116">Präfix für den Anwendungsnamen des Pakets verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b43d-116">Prefix to be used for the application package name.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-117">Ruft ab, Paketname, die zum Erstellen von Service Fabric-Anwendungspaket für der Akteur verwendet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-117">Gets package name used to create Service Fabric Application package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-118">Name des Anwendungspakets.</span><span class="sxs-lookup"><span data-stu-id="8b43d-118">Application package name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationTypeName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationTypeName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationTypeName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationTypeName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationTypeName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationTypeName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix"><span data-ttu-id="8b43d-119">Präfix der Name des Anwendungstyps verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b43d-119">Prefix to be used for the application type name.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-120">Ruft ab, der Name des Anwendungstyps in Anwendungsmanifest verwendet werden, wenn Service Fabric-Anwendungspaket für der Akteur erstellen.</span><span class="sxs-lookup"><span data-stu-id="8b43d-120">Gets the application type name used in application manifest when creating Service Fabric Application package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-121">Name des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="8b43d-121">Application type name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceEndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceEndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceEndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceEndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceEndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-122">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-122">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-123">Ruft den Dienstendpunkt für die der Akteurtyp, der im Dienstmanifest für den Dienst Akteur angegeben ist.</span><span class="sxs-lookup"><span data-stu-id="8b43d-123">Gets the service endpoint for the actor type which is specified in service manifest for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-124">Ein Name mit dem Endpunkt des Diensts.</span><span class="sxs-lookup"><span data-stu-id="8b43d-124">Service endpoint name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceName (Type actorInterfaceType, string serviceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceName(class System.Type actorInterfaceType, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceName (actorInterfaceType As Type, Optional serviceName As String = null) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceName : Type * string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName (actorInterfaceType, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="8b43d-125">Der Typ der Akteur-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8b43d-125">Type of the actor interface.</span></span></param>
        <param name="serviceName"><span data-ttu-id="8b43d-126">Name des Diensts hosten des Akteur-Typs.</span><span class="sxs-lookup"><span data-stu-id="8b43d-126">Name of service hosting the actor type.</span></span> <span data-ttu-id="8b43d-127">Wenn dieser Wert null ist Dienstnamen mithilfe der ActorInterfaceType erstellt.</span><span class="sxs-lookup"><span data-stu-id="8b43d-127">If this value is null then service name is constructed using the actorInterfaceType.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-128">Ruft die Namen des Diensts, dem Akteur-Datentyp in der Service Fabric-Cluster hostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-128">Gets name of service which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-129">Service Fabric-Dienstname hosting des Akteur-Typs.</span><span class="sxs-lookup"><span data-stu-id="8b43d-129">Service Fabric service name hosting the actor type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServicePackageName">
      <MemberSignature Language="C#" Value="public static string GetFabricServicePackageName (string servicePackageNamePrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServicePackageName(string servicePackageNamePrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServicePackageName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServicePackageName (servicePackageNamePrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServicePackageName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServicePackageName servicePackageNamePrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="servicePackageNamePrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="servicePackageNamePrefix"><span data-ttu-id="8b43d-130">Präfix für den Dienstnamen für das Paket verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b43d-130">Prefix to be used for the service package name.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-131">Ruft die dienstpaketnamens die im Service Fabric-Anwendungspaket für die der Akteur verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="8b43d-131">Gets service package name which is used in Service Fabric Application package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-132">Der dienstpaketname.</span><span class="sxs-lookup"><span data-stu-id="8b43d-132">Service package name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-133">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-133">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-134">Ruft die Replikator Konfiguration im Abschnitt im Konfigurationspaket für den Dienst Akteur angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="8b43d-134">Gets the replicator configuration section name specified in configuration package for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-135">Der Konfigurationsabschnittsname Replikator.</span><span class="sxs-lookup"><span data-stu-id="8b43d-135">Replicator configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-136">Im Konfigurationsabschnitt Replikator angegebenen Werte werden verwendet, um konfigurieren <see cref="T:System.Fabric.ReplicatorSettings" /> für die Replikation des actorzustands zwischen primären und sekundären Replikaten.</span><span class="sxs-lookup"><span data-stu-id="8b43d-136">Values specified in replicator configuration section are used to configure <see cref="T:System.Fabric.ReplicatorSettings" /> for the replication of actor state between primary and secondary replicas.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorEndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorEndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorEndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorEndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorEndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-137">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-137">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-138">Ruft den Replikator-Endpunkt im Dienstmanifest für den Dienst Akteur angegebene ab.</span><span class="sxs-lookup"><span data-stu-id="8b43d-138">Gets the replicator endpoint which is specified in service manifest for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-139">Name des Diensts Replikator Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="8b43d-139">Service replicator endpoint name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorSecurityConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorSecurityConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorSecurityConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorSecurityConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorSecurityConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-140">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-140">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-141">Ruft die Sicherheitskonfiguration Replikator Abschnitt im Konfigurationspaket für den Dienst Akteur angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="8b43d-141">Gets the replicator security configuration section name specified in configuration package for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-142">Sicherheit Konfigurationsabschnittsname Replikator.</span><span class="sxs-lookup"><span data-stu-id="8b43d-142">Replicator security configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-143">Im Konfigurationsabschnitt für Replikator Sicherheit angegebenen Werte werden verwendet, um konfigurieren <see cref="P:System.Fabric.ReplicatorSettings.SecurityCredentials" /> für die Replikation des actorzustands zwischen primären und sekundären Replikaten.</span><span class="sxs-lookup"><span data-stu-id="8b43d-143">Values specified in replicator security configuration section are used to configure <see cref="P:System.Fabric.ReplicatorSettings.SecurityCredentials" /> for the replication of actor state between primary and secondary replicas.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorSecurityCredentialTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorSecurityCredentialTypeName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorSecurityCredentialTypeName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityCredentialTypeName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorSecurityCredentialTypeName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorSecurityCredentialTypeName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityCredentialTypeName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-144">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-144">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-145">Ruft die im Abschnitt für die Konfiguration von Replikator Sicherheit im Konfigurationspaket für den Akteur-Dienst verwendete Anmeldeinformationen Typnamen ab.</span><span class="sxs-lookup"><span data-stu-id="8b43d-145">Gets the credential type name used in replicator security configuration section in configuration package for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-146">Replikator Sicherheit Anmeldeinformationen-Typname.</span><span class="sxs-lookup"><span data-stu-id="8b43d-146">Replicator security credential type name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceTransportSettingsSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceTransportSettingsSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceTransportSettingsSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTransportSettingsSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceTransportSettingsSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceTransportSettingsSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTransportSettingsSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-147">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-147">Type of class implementing the actor.</span></span></param>
        <summary>
             <span data-ttu-id="8b43d-148">Ruft den Fabrictransport Konfigurationsabschnittsnamen im Konfigurationspaket für den Dienst Akteur angegeben.</span><span class="sxs-lookup"><span data-stu-id="8b43d-148">Gets the fabrictransport configuration section name specified in configuration package for the actor service.</span></span>
             </summary>
        <returns><span data-ttu-id="8b43d-149">Der Konfigurationsabschnittsname FabricTransport.</span><span class="sxs-lookup"><span data-stu-id="8b43d-149">FabricTransport configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-150">Im Konfigurationsabschnitt FabricTransport angegebenen Werte werden verwendet, um konfigurieren <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> für die Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="8b43d-150">Values specified in FabricTransport configuration section are used to configure <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> for the communication.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceTypeName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceTypeName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTypeName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceTypeName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceTypeName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTypeName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-151">Typ der Akteur-Implementierung.</span><span class="sxs-lookup"><span data-stu-id="8b43d-151">Actor implementation type.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-152">Ruft Dienst-Typnamen für den Akteur ab.</span><span class="sxs-lookup"><span data-stu-id="8b43d-152">Gets service type name for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-153">Der Diensttypname.</span><span class="sxs-lookup"><span data-stu-id="8b43d-153">Service type name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="8b43d-154">Der Typ der Akteur-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8b43d-154">Type of the actor interface.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-155">Ruft-service-Uri, der dem Akteur-Datentyp in der Service Fabric-Cluster hostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-155">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-156">Service Fabric-Dienst-Uri, die den Akteurtyp gehostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-156">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-157">Methode zum Abrufen der Anwendungsname aus versucht <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-157">Method will try to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            <span data-ttu-id="8b43d-158">Wenn die Methode weiterhin Anwendungsnamen ermitteln kann <see cref="T:System.ArgumentException" /> ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="8b43d-158">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="8b43d-159">Wenn Anwendungsname bestimmt werden kann, mithilfe von <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-159">When application name cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, Uri applicationUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, class System.Uri applicationUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, applicationUri As Uri) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * Uri -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="8b43d-160">Der Typ der Akteur-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8b43d-160">Type of the actor interface.</span></span></param>
        <param name="applicationUri"><span data-ttu-id="8b43d-161">Service Fabric-Anwendungs-Uri, die den Akteur-Dienst enthält.</span><span class="sxs-lookup"><span data-stu-id="8b43d-161">Service Fabric application Uri containing the actor service.</span></span>
            <span data-ttu-id="8b43d-162">Wenn dieser Wert null ist abgerufenes Anwendungsname <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-162">If this value is null application name is obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-163">Ruft-service-Uri, der dem Akteur-Datentyp in der Service Fabric-Cluster hostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-163">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-164">Service Fabric-Dienst-Uri, die den Akteurtyp gehostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-164">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-165">Methode erstellt mithilfe der ActorInterfaceType Dienstnamen.</span><span class="sxs-lookup"><span data-stu-id="8b43d-165">Method will create service name using the actorInterfaceType.</span></span> <span data-ttu-id="8b43d-166">Wenn ApplicationUri als Null übergeben wird, wird ein Versuch unternommen, Anwendungsname von abzurufenden <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-166">If applicationUri is passed as null, an attempt is made to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span> <span data-ttu-id="8b43d-167">Wenn die Methode weiterhin Anwendungsnamen ermitteln kann <see cref="T:System.ArgumentException" /> ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="8b43d-167">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="8b43d-168">Wenn Anwendungsname bestimmt werden kann, mithilfe von <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-168">When application name cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, string applicationName = null, string serviceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, string applicationName, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, Optional applicationName As String = null, Optional serviceName As String = null) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * string * string -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationName, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="8b43d-169">Der Typ der Akteur-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8b43d-169">Type of the actor interface.</span></span></param>
        <param name="applicationName"><span data-ttu-id="8b43d-170">Name der Service Fabric-Anwendung, die den Akteur-Dienst enthält.</span><span class="sxs-lookup"><span data-stu-id="8b43d-170">Service Fabric application name containing the actor service.</span></span>
            <span data-ttu-id="8b43d-171">Wenn dieser Wert null ist abgerufenes Anwendungsname <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-171">If this value is null application name is obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span></span></param>
        <param name="serviceName"><span data-ttu-id="8b43d-172">Name des Diensts hosten des Akteur-Typs.</span><span class="sxs-lookup"><span data-stu-id="8b43d-172">Name of service hosting the actor type.</span></span> <span data-ttu-id="8b43d-173">Wenn dieser Wert null ist Dienstnamen mithilfe der ActorInterfaceType erstellt.</span><span class="sxs-lookup"><span data-stu-id="8b43d-173">If this value is null then service name is constructed using the actorInterfaceType.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-174">Ruft-service-Uri, der dem Akteur-Datentyp in der Service Fabric-Cluster hostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-174">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-175">Service Fabric-Dienst-Uri, die den Akteurtyp gehostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-175">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-176">Wenn Parameter "ApplicationName" als null- bzw. leere Zeichenfolge übergeben wird, wird ein Versuch unternommen, Anwendungsname von abzurufenden <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-176">If applicationName is passed as null or empty string, an attempt is made to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span> <span data-ttu-id="8b43d-177">Wenn die Methode weiterhin Anwendungsnamen ermitteln kann <see cref="T:System.ArgumentException" /> ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="8b43d-177">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="8b43d-178">Wenn der Parameter "ApplicationName" mit nicht bestimmt werden kann <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-178">When applicationName cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, Uri applicationUri, string serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, class System.Uri applicationUri, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, applicationUri As Uri, serviceName As String) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * Uri * string -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationUri, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationUri" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="8b43d-179">Der Typ der Akteur-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8b43d-179">Type of the actor interface.</span></span></param>
        <param name="applicationUri"><span data-ttu-id="8b43d-180">Service Fabric-Anwendungs-Uri, die den Akteur-Dienst enthält.</span><span class="sxs-lookup"><span data-stu-id="8b43d-180">Service Fabric application Uri containing the actor service.</span></span>
            <span data-ttu-id="8b43d-181">Wenn dieser Wert null ist abgerufenes Anwendungsname <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-181">If this value is null application name is obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span></span></param>
        <param name="serviceName"><span data-ttu-id="8b43d-182">Name des Diensts hosten des Akteur-Typs.</span><span class="sxs-lookup"><span data-stu-id="8b43d-182">Name of service hosting the actor type.</span></span> <span data-ttu-id="8b43d-183">Wenn dieser Wert null ist Dienstnamen mithilfe der ActorInterfaceType erstellt.</span><span class="sxs-lookup"><span data-stu-id="8b43d-183">If this value is null then service name is constructed using the actorInterfaceType.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-184">Ruft-service-Uri, der dem Akteur-Datentyp in der Service Fabric-Cluster hostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-184">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-185">Service Fabric-Dienst-Uri, die den Akteurtyp gehostet.</span><span class="sxs-lookup"><span data-stu-id="8b43d-185">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-186">Wenn ApplicationUri als Null übergeben wird, wird ein Versuch unternommen, Anwendungsname von abzurufenden <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-186">If applicationUri is passed as null, an attempt is made to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span> <span data-ttu-id="8b43d-187">Wenn die Methode weiterhin Anwendungsnamen ermitteln kann <see cref="T:System.ArgumentException" /> ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="8b43d-187">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="8b43d-188">Wenn Anwendungsname bestimmt werden kann, mithilfe von <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="8b43d-188">When application name cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceV2EndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceV2EndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceV2EndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceV2EndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceV2EndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceV2EndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceV2EndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-189">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-189">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-190">Ruft den Dienstendpunkt für die der Akteurtyp, der im Dienstmanifest für den Dienst Akteur angegeben ist.</span><span class="sxs-lookup"><span data-stu-id="8b43d-190">Gets the service endpoint for the actor type which is specified in service manifest for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-191">Ein Name mit dem Endpunkt des Diensts.</span><span class="sxs-lookup"><span data-stu-id="8b43d-191">Service endpoint name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLocalEseStoreConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetLocalEseStoreConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetLocalEseStoreConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetLocalEseStoreConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLocalEseStoreConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetLocalEseStoreConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetLocalEseStoreConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="8b43d-192">Der Typ der Klasse, die den Akteur implementiert.</span><span class="sxs-lookup"><span data-stu-id="8b43d-192">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-193">Ruft die lokalen Speicher Konfigurationsabschnittsname im Konfigurationspaket für den Dienst Akteur angegeben.</span><span class="sxs-lookup"><span data-stu-id="8b43d-193">Gets local store configuration section name specified in configuration package for the actor service.</span></span> 
            </summary>
        <returns><span data-ttu-id="8b43d-194">Der Konfigurationsabschnittsname lokalen Speicher.</span><span class="sxs-lookup"><span data-stu-id="8b43d-194">Local store configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="8b43d-195">In lokalen ESE-Konfigurationsabschnitt angegebenen Werte werden verwendet, um konfigurieren <see cref="T:System.Fabric.LocalEseStoreSettings" /> zum Speichern des Status der Akteur.</span><span class="sxs-lookup"><span data-stu-id="8b43d-195">Values specified in local ESE configuration section are used to configure <see cref="T:System.Fabric.LocalEseStoreSettings" /> for storing the state of actor.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetName">
      <MemberSignature Language="C#" Value="public static string GetName (Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetName(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetName (actorInterfaceType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetName actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="8b43d-196">Der Typ der Akteur-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8b43d-196">Type of the actor interface.</span></span></param>
        <summary>
            <span data-ttu-id="8b43d-197">Ruft den Namen der Akteur aus ActorInterfaceType ab.</span><span class="sxs-lookup"><span data-stu-id="8b43d-197">Gets name of Actor from actorInterfaceType.</span></span>
            </summary>
        <returns><span data-ttu-id="8b43d-198">Name des Darstellers.</span><span class="sxs-lookup"><span data-stu-id="8b43d-198">Name of Actor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>