<Type Name="NotificationHubClient" FullName="Microsoft.Azure.NotificationHubs.NotificationHubClient">
  <TypeSignature Language="C#" Value="public class NotificationHubClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotificationHubClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />
  <TypeSignature Language="VB.NET" Value="Public Class NotificationHubClient" />
  <TypeSignature Language="F#" Value="type NotificationHubClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="6d3a3-101">Stellt einen Notification Hub-Clients dar.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-101">Represents a notification hub client.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelNotificationAsync (string scheduledNotificationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelNotificationAsync(string scheduledNotificationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CancelNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelNotificationAsync (scheduledNotificationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelNotificationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.CancelNotificationAsync scheduledNotificationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheduledNotificationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheduledNotificationId"><span data-ttu-id="6d3a3-102">Der Bezeichner für geplante Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-102">The scheduled notification identifier.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-103">Die Benachrichtigung asynchron abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-103">Cancels the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-104">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-104">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync (string admRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync(string admRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmNativeRegistrationAsync (admRegistrationId As String) As Task(Of AdmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmNativeRegistrationAsync admRegistrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="6d3a3-105">Der administrative registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-105">The administrative registration identifier.</span></span></param>
        <summary><span data-ttu-id="6d3a3-106">Erstellt asynchron eine systemeigene administrative-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-106">Asynchronously creates a native administrative registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-107">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-107">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync (string admRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt; CreateAdmNativeRegistrationAsync(string admRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmNativeRegistrationAsync (admRegistrationId As String, tags As IEnumerable(Of String)) As Task(Of AdmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmNativeRegistrationAsync (admRegistrationId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="6d3a3-108">Der administrative registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-108">The administrative registration identifier.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-109">Die Tags für die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-109">The tags for the registration.</span></span></param>
        <summary><span data-ttu-id="6d3a3-110">Erstellt asynchron eine systemeigene administrative-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-110">Asynchronously creates a native administrative registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-111">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-111">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync (string admRegistrationId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync(string admRegistrationId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmTemplateRegistrationAsync (admRegistrationId As String, jsonPayload As String) As Task(Of AdmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmTemplateRegistrationAsync (admRegistrationId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="6d3a3-112">Der administrative registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-112">The administrative registration identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-113">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-113">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-114">Erstellt asynchron eine administrative Vorlage-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-114">Asynchronously creates an administrative template registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-115">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-115">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAdmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync (string admRegistrationId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt; CreateAdmTemplateRegistrationAsync(string admRegistrationId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAdmTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAdmTemplateRegistrationAsync (admRegistrationId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of AdmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAdmTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAdmTemplateRegistrationAsync (admRegistrationId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="admRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="admRegistrationId"><span data-ttu-id="6d3a3-116">Der administrative registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-116">The administrative registration identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-117">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-117">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-118">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-118">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-119">Erstellt asynchron eine administrative Vorlage-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-119">Asynchronously creates an administrative template registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-120">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-120">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync (string deviceToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync(string deviceToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleNativeRegistrationAsync (deviceToken As String) As Task(Of AppleRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleNativeRegistrationAsync deviceToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="6d3a3-121">Das gerätetoken.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-121">The device token.</span></span></param>
        <summary><span data-ttu-id="6d3a3-122">Erstellt asynchron eine systemeigene Apple-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-122">Asynchronously creates an Apple native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-123">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-123">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync (string deviceToken, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt; CreateAppleNativeRegistrationAsync(string deviceToken, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleNativeRegistrationAsync (deviceToken As String, tags As IEnumerable(Of String)) As Task(Of AppleRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleNativeRegistrationAsync (deviceToken, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="6d3a3-124">Das gerätetoken.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-124">The device token.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-125">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-125">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-126">Erstellt asynchron eine systemeigene Apple-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-126">Asynchronously creates an Apple native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-127">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-127">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync (string deviceToken, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync(string deviceToken, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleTemplateRegistrationAsync (deviceToken As String, jsonPayload As String) As Task(Of AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleTemplateRegistrationAsync (deviceToken, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="6d3a3-128">Das gerätetoken.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-128">The device token.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-129">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-129">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-130">Erstellt asynchron eine Apple-vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-130">Asynchronously creates an Apple template registration.</span></span> <span data-ttu-id="6d3a3-131">Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-131">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-132">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-132">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAppleTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync (string deviceToken, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt; CreateAppleTemplateRegistrationAsync(string deviceToken, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateAppleTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAppleTemplateRegistrationAsync (deviceToken As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of AppleTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateAppleTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateAppleTemplateRegistrationAsync (deviceToken, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceToken" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceToken"><span data-ttu-id="6d3a3-133">Das gerätetoken.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-133">The device token.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-134">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-134">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-135">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-135">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-136">Erstellt asynchron eine Apple-vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-136">Asynchronously creates an Apple template registration.</span></span> <span data-ttu-id="6d3a3-137">Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-137">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-138">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-138">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync (string userId, string channelId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync(string userId, string channelId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduNativeRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduNativeRegistrationAsync (userId As String, channelId As String) As Task(Of BaiduRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduNativeRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduNativeRegistrationAsync (userId, channelId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="6d3a3-139">Die Benutzer-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-139">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="6d3a3-140">Die Kanal-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-140">The channel identifier.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-141">Die systemeigene Baidu-Registrierung erstellt asynchron.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-141">Creates the baidu native registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-142">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-142">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync (string userId, string channelId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt; CreateBaiduNativeRegistrationAsync(string userId, string channelId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduNativeRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduNativeRegistrationAsync (userId As String, channelId As String, tags As IEnumerable(Of String)) As Task(Of BaiduRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduNativeRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduNativeRegistrationAsync (userId, channelId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="6d3a3-143">Die Benutzer-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-143">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="6d3a3-144">Die Kanal-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-144">The channel identifier.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-145">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-145">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-146">Die systemeigene Baidu-Registrierung erstellt asynchron.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-146">Creates the baidu native registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-147">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-147">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync (string userId, string channelId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync(string userId, string channelId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduTemplateRegistrationAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduTemplateRegistrationAsync (userId As String, channelId As String, jsonPayload As String) As Task(Of BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduTemplateRegistrationAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduTemplateRegistrationAsync (userId, channelId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="6d3a3-148">Die Benutzer-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-148">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="6d3a3-149">Die Kanal-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-149">The channel identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-150">Die Json-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-150">The json payload.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-151">Baidu-vorlagenregistrierung erstellt asynchron.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-151">Creates the baidu template registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-152">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-152">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBaiduTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync (string userId, string channelId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt; CreateBaiduTemplateRegistrationAsync(string userId, string channelId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateBaiduTemplateRegistrationAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBaiduTemplateRegistrationAsync (userId As String, channelId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of BaiduTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateBaiduTemplateRegistrationAsync : string * string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateBaiduTemplateRegistrationAsync (userId, channelId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="channelId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="6d3a3-153">Die Benutzer-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-153">The user identifier.</span></span></param>
        <param name="channelId"><span data-ttu-id="6d3a3-154">Die Kanal-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-154">The channel identifier.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-155">Die Json-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-155">The json payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-156">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-156">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-157">Baidu-vorlagenregistrierung erstellt asynchron.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-157">Creates the baidu template registration asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-158">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-158">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString (string connectionString, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString(string connectionString, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClientFromConnectionString (connectionString As String, notificationHubPath As String) As NotificationHubClient" />
      <MemberSignature Language="F#" Value="static member CreateClientFromConnectionString : string * string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString (connectionString, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="6d3a3-159">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-159">The connection string.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="6d3a3-160">Der Notification Hub-Pfad.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-160">The notification hub path.</span></span></param>
        <summary><span data-ttu-id="6d3a3-161">Erstellt einen Client aus der Verbindungszeichenfolge an.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-161">Creates a client from connection string.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-162">Der erstellte <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-162">The created <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateClientFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString (string connectionString, string notificationHubPath, bool enableTestSend);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NotificationHubClient CreateClientFromConnectionString(string connectionString, string notificationHubPath, bool enableTestSend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateClientFromConnectionString (connectionString As String, notificationHubPath As String, enableTestSend As Boolean) As NotificationHubClient" />
      <MemberSignature Language="F#" Value="static member CreateClientFromConnectionString : string * string * bool -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateClientFromConnectionString (connectionString, notificationHubPath, enableTestSend)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
        <Parameter Name="enableTestSend" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="6d3a3-163">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-163">The connection string.</span></span></param>
        <param name="notificationHubPath"><span data-ttu-id="6d3a3-164">Der Notification Hub-Pfad.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-164">The notification hub path.</span></span></param>
        <param name="enableTestSend"><span data-ttu-id="6d3a3-165">"true" aktiviert – testsendevorgang; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6d3a3-165">true to enable test send; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="6d3a3-166">Erstellt einen Client aus der Verbindungszeichenfolge an.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-166">Creates a client from connection string.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-167">Der erstellte <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-167">The created <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync (string gcmRegistrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync(string gcmRegistrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmNativeRegistrationAsync (gcmRegistrationId As String) As Task(Of GcmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmNativeRegistrationAsync gcmRegistrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="6d3a3-168">Die GCM-Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-168">The GCM registration ID.</span></span></param>
        <summary><span data-ttu-id="6d3a3-169">Erstellt asynchron systemeigene GCM-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-169">Asynchronously creates GCM native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-170">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-170">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync (string gcmRegistrationId, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt; CreateGcmNativeRegistrationAsync(string gcmRegistrationId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmNativeRegistrationAsync (gcmRegistrationId As String, tags As IEnumerable(Of String)) As Task(Of GcmRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmNativeRegistrationAsync (gcmRegistrationId, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="6d3a3-171">Die GCM-Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-171">The GCM registration ID.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-172">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-172">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-173">Erstellt asynchron systemeigene GCM-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-173">Asynchronously creates GCM native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-174">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-174">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync (string gcmRegistrationId, string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync(string gcmRegistrationId, string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmTemplateRegistrationAsync (gcmRegistrationId As String, jsonPayload As String) As Task(Of GcmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmTemplateRegistrationAsync (gcmRegistrationId, jsonPayload)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="6d3a3-175">Die GCM-Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-175">The GCM registration ID.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-176">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-176">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-177">Erstellt asynchron GCM-vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-177">Asynchronously creates GCM template registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-178">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-178">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGcmTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync (string gcmRegistrationId, string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt; CreateGcmTemplateRegistrationAsync(string gcmRegistrationId, string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateGcmTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateGcmTemplateRegistrationAsync (gcmRegistrationId As String, jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of GcmTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateGcmTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateGcmTemplateRegistrationAsync (gcmRegistrationId, jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="gcmRegistrationId" Type="System.String" />
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="gcmRegistrationId"><span data-ttu-id="6d3a3-179">Die GCM-Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-179">The GCM registration ID.</span></span></param>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-180">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-180">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-181">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-181">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-182">Erstellt asynchron GCM-vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-182">Asynchronously creates GCM template registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-183">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-183">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync (string channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync(string channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsNativeRegistrationAsync (channelUri As String) As Task(Of MpnsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsNativeRegistrationAsync channelUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-184">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-184">The channel URI.</span></span></param>
        <summary><span data-ttu-id="6d3a3-185">Erstellt asynchron systemeigene MPNS-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-185">Asynchronously creates MPNS native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-186">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-186">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync (string channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt; CreateMpnsNativeRegistrationAsync(string channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsNativeRegistrationAsync (channelUri As String, tags As IEnumerable(Of String)) As Task(Of MpnsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsNativeRegistrationAsync (channelUri, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-187">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-187">The channel URI.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-188">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-188">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-189">Erstellt asynchron systemeigene MPNS-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-189">Asynchronously creates MPNS native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-190">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-190">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync (string channelUri, string xmlTemplate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync(string channelUri, string xmlTemplate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String) As Task(Of MpnsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsTemplateRegistrationAsync (channelUri, xmlTemplate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-191">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-191">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="6d3a3-192">Die XML-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-192">The XML template.</span></span></param>
        <summary><span data-ttu-id="6d3a3-193">Erstellt asynchron MPNS-vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-193">Asynchronously creates MPNS template registration.</span></span> <span data-ttu-id="6d3a3-194">Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-194">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-195">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-195">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMpnsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync (string channelUri, string xmlTemplate, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt; CreateMpnsTemplateRegistrationAsync(string channelUri, string xmlTemplate, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateMpnsTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMpnsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String, tags As IEnumerable(Of String)) As Task(Of MpnsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateMpnsTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateMpnsTemplateRegistrationAsync (channelUri, xmlTemplate, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-196">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-196">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="6d3a3-197">Die XML-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-197">The XML template.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-198">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-198">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-199">Erstellt asynchron MPNS-vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-199">Asynchronously creates MPNS template registration.</span></span> <span data-ttu-id="6d3a3-200">Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-200">To specify additional properties at creation, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-201">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-201">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateInstallation">
      <MemberSignature Language="C#" Value="public void CreateOrUpdateInstallation (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CreateOrUpdateInstallation(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateInstallation(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateInstallation : Microsoft.Azure.NotificationHubs.Installation -&gt; unit" Usage="notificationHubClient.CreateOrUpdateInstallation installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation"><span data-ttu-id="6d3a3-202">Das Gerät Installation-Objekt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-202">The device installation object.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-203">Erstellt oder aktualisiert eine Geräteinstallation.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-203">Creates or updates a device installation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateOrUpdateInstallationAsync (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateOrUpdateInstallationAsync(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateInstallationAsync(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateInstallationAsync : Microsoft.Azure.NotificationHubs.Installation -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.CreateOrUpdateInstallationAsync installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation"><span data-ttu-id="6d3a3-204">Das Gerät Installation-Objekt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-204">The device installation object.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-205">Erstellt oder eine Geräteinstallation asynchron aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-205">Creates or updates a device installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-206">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-206">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-207">Wird ausgelöst, wenn die Installation Objekt null ist</span><span class="sxs-lookup"><span data-stu-id="6d3a3-207">Thrown when the installation object is null</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6d3a3-208">"Installationid" muss angegeben werden</span><span class="sxs-lookup"><span data-stu-id="6d3a3-208">InstallationId must be specified</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; CreateOrUpdateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; CreateOrUpdateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateOrUpdateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateOrUpdateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.CreateOrUpdateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.CreateOrUpdateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="6d3a3-209">Der Typ der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-209">The type of registration.</span></span></typeparam>
        <param name="registration"><span data-ttu-id="6d3a3-210">Die Registrierung erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-210">The registration to be created or updated.</span></span></param>
        <summary><span data-ttu-id="6d3a3-211">Asynchron erstellt oder aktualisiert die Clientregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-211">Asynchronously creates or updates the client registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-212">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-212">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-213">Wird ausgelöst, wenn RegistrationId Objekt null ist</span><span class="sxs-lookup"><span data-stu-id="6d3a3-213">Thrown when RegistrationId object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; CreateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; CreateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.CreateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.CreateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="6d3a3-214">Der Typ der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-214">The type of registration.</span></span></typeparam>
        <param name="registration"><span data-ttu-id="6d3a3-215">Die Registrierung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-215">The registration to create.</span></span></param>
        <summary><span data-ttu-id="6d3a3-216">Erstellt asynchron eine Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-216">Asynchronously creates a registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-217">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-217">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="6d3a3-218">NotificationHubPath in RegistrationDescription ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-218">NotificationHubPath in RegistrationDescription is not valid.</span></span>
            <span data-ttu-id="6d3a3-219">oder RegistrationId muss null oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-219">or RegistrationId should be null or empty</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateRegistrationIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; CreateRegistrationIdAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; CreateRegistrationIdAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationIdAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRegistrationIdAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.CreateRegistrationIdAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="notificationHubClient.CreateRegistrationIdAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6d3a3-220">Erstellt asynchron einen registrierungsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-220">Asynchronously creates a registration identifier.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-221">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-221">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync (string channelUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync(string channelUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsNativeRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsNativeRegistrationAsync (channelUri As String) As Task(Of WindowsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsNativeRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsNativeRegistrationAsync channelUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-222">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-222">The channel URI.</span></span></param>
        <summary><span data-ttu-id="6d3a3-223">Erstellt asynchron systemeigene Windows-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-223">Asynchronously creates Windows native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-224">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-224">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsNativeRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync (string channelUri, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt; CreateWindowsNativeRegistrationAsync(string channelUri, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsNativeRegistrationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsNativeRegistrationAsync (channelUri As String, tags As IEnumerable(Of String)) As Task(Of WindowsRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsNativeRegistrationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsNativeRegistrationAsync (channelUri, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-225">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-225">The channel URI.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-226">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-226">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-227">Erstellt asynchron systemeigene Windows-Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-227">Asynchronously creates Windows native registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-228">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-228">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync (string channelUri, string xmlTemplate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync(string channelUri, string xmlTemplate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsTemplateRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String) As Task(Of WindowsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsTemplateRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsTemplateRegistrationAsync (channelUri, xmlTemplate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-229">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-229">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="6d3a3-230">Die XML-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-230">The XML template.</span></span></param>
        <summary><span data-ttu-id="6d3a3-231">Erstellt asynchron Windows vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-231">Asynchronously creates Windows template registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-232">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-232">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWindowsTemplateRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync (string channelUri, string xmlTemplate, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt; CreateWindowsTemplateRegistrationAsync(string channelUri, string xmlTemplate, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateWindowsTemplateRegistrationAsync(System.String,System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateWindowsTemplateRegistrationAsync (channelUri As String, xmlTemplate As String, tags As IEnumerable(Of String)) As Task(Of WindowsTemplateRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateWindowsTemplateRegistrationAsync : string * string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;" Usage="notificationHubClient.CreateWindowsTemplateRegistrationAsync (channelUri, xmlTemplate, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="channelUri" Type="System.String" />
        <Parameter Name="xmlTemplate" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="channelUri"><span data-ttu-id="6d3a3-233">Die Kanal-URI.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-233">The channel URI.</span></span></param>
        <param name="xmlTemplate"><span data-ttu-id="6d3a3-234">Die XML-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-234">The XML template.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-235">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-235">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-236">Erstellt asynchron Windows vorlagenregistrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-236">Asynchronously creates Windows template registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-237">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-237">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallation">
      <MemberSignature Language="C#" Value="public void DeleteInstallation (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteInstallation(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteInstallation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteInstallation (installationId As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteInstallation : string -&gt; unit" Usage="notificationHubClient.DeleteInstallation installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="6d3a3-238">Der Installations-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-238">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-239">Löscht die Installation.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-239">Deletes the installation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteInstallationAsync (installationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteInstallationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="6d3a3-240">Der Installations-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-240">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-241">Löscht die Installation asynchron an.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-241">Deletes the installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-242">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-242">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-243">Wird ausgelöst, wenn das Objekt "installationid" null ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-243">Thrown when the installationId object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (Microsoft.Azure.NotificationHubs.RegistrationDescription registration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(class Microsoft.Azure.NotificationHubs.RegistrationDescription registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(Microsoft.Azure.NotificationHubs.RegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registration As RegistrationDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : Microsoft.Azure.NotificationHubs.RegistrationDescription -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registration" Type="Microsoft.Azure.NotificationHubs.RegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="registration"><span data-ttu-id="6d3a3-244">Die zu löschende Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-244">The registration to delete.</span></span></param>
        <summary><span data-ttu-id="6d3a3-245">Löscht asynchron die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-245">Asynchronously deletes the registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-246">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-246">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-247">Wird ausgelöst, wenn Registrierungsobjekt null ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-247">Thrown when registration object is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registrationId As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId"><span data-ttu-id="6d3a3-248">Die Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-248">The registration ID.</span></span></param>
        <summary><span data-ttu-id="6d3a3-249">Löscht asynchron die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-249">Asynchronously deletes the registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-250">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-250">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationAsync (string registrationId, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationAsync(string registrationId, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationAsync (registrationId As String, etag As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationAsync (registrationId, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId"><span data-ttu-id="6d3a3-251">Die Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-251">The registration ID.</span></span></param>
        <param name="etag"><span data-ttu-id="6d3a3-252">Das Entitätstag.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-252">The entity tag.</span></span></param>
        <summary><span data-ttu-id="6d3a3-253">Löscht asynchron die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-253">Asynchronously deletes the registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-254">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-254">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-255">registrationId</span><span class="sxs-lookup"><span data-stu-id="6d3a3-255">registrationId</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRegistrationsByChannelAsync (string pnsHandle);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRegistrationsByChannelAsync(string pnsHandle) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.DeleteRegistrationsByChannelAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRegistrationsByChannelAsync (pnsHandle As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRegistrationsByChannelAsync : string -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.DeleteRegistrationsByChannelAsync pnsHandle" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pnsHandle"><span data-ttu-id="6d3a3-256">Das PNS behandeln.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-256">The PNS handle.</span></span></param>
        <summary><span data-ttu-id="6d3a3-257">Löscht asynchron die Registrierungen vom Kanal an.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-257">Asynchronously deletes the registrations by channel.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-258">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-258">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-259">pnshandle-Objekt</span><span class="sxs-lookup"><span data-stu-id="6d3a3-259">pnsHandle</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnableTestSend">
      <MemberSignature Language="C#" Value="public bool EnableTestSend { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableTestSend" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubClient.EnableTestSend" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnableTestSend As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableTestSend : bool" Usage="Microsoft.Azure.NotificationHubs.NotificationHubClient.EnableTestSend" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6d3a3-260">Ruft ab oder legt einen Wert, der angibt, ob der Client einen Test senden kann.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-260">Gets or sets a value indicating whether the client enables a test send.</span></span></summary>
        <value><span data-ttu-id="6d3a3-261">"true", wenn der Client einen Test kann senden. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6d3a3-261">true if the client enables a test send; otherwise, false.</span></span></value>
        <remarks>
            <span data-ttu-id="6d3a3-262">Wenn Test senden aktiviert ist, geschieht Folgendes:</span><span class="sxs-lookup"><span data-stu-id="6d3a3-262">When test send is enabled, the following occurs:</span></span>
            <ul><li><span data-ttu-id="6d3a3-263">Alle Benachrichtigungen erreichen nur bis zu 10 Geräte für jeden Sendeaufruf.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-263">All notifications only reach up to 10 devices for each send call.</span></span></li><li><span data-ttu-id="6d3a3-264">Die <b>senden \*</b> Methoden zurückgeben einer Liste der Ergebnisse für alle Übermittlungen für diese Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-264">The <b>Send\*</b> methods return a list of the outcomes for all those notification deliveries.</span></span> <span data-ttu-id="6d3a3-265">Die möglichen Ergebnisse sind identisch mit der im Telemetrie angezeigt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-265">The possible outcomes are the same as displayed in telemetry.</span></span> <span data-ttu-id="6d3a3-266">Ergebnisse enthält, z. B. Authentifizierungsfehler, Einschränkung, Fehler, erfolgreich Übermittlungen und So weiter.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-266">Outcomes includes things like authentication errors, throttling errors, successful deliveries, and so on.</span></span></li></ul><p><span data-ttu-id="6d3a3-267">In diesem Modus wird nur zu Testzwecken nicht für die Produktion und eingeschränkt wird.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-267">This mode is for test purposes only, not for production, and is throttled.</span></span></p></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllRegistrationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync (int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync(int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetAllRegistrationsAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllRegistrationsAsync (top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetAllRegistrationsAsync : int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetAllRegistrationsAsync top" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="top"><span data-ttu-id="6d3a3-268">Der Speicherort der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-268">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="6d3a3-269">Ruft Sie alle Registrierungen in diesem benachrichtigungshub asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-269">Asynchronously retrieves all registrations in this notification hub.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-270">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-270">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllRegistrationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync (string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetAllRegistrationsAsync(string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetAllRegistrationsAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllRegistrationsAsync (continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetAllRegistrationsAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetAllRegistrationsAsync (continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="6d3a3-271">Das Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-271">The continuation token.</span></span></param>
        <param name="top"><span data-ttu-id="6d3a3-272">Der Speicherort der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-272">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="6d3a3-273">Ruft Sie alle Registrierungen in diesem benachrichtigungshub asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-273">Asynchronously retrieves all registrations in this notification hub.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-274">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-274">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBaseUri">
      <MemberSignature Language="C#" Value="public Uri GetBaseUri ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri GetBaseUri() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetBaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBaseUri () As Uri" />
      <MemberSignature Language="F#" Value="member this.GetBaseUri : unit -&gt; Uri" Usage="notificationHubClient.GetBaseUri " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6d3a3-275">Ruft den Wert der Eigenschaft BaseUri angefügt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-275">Gets the value of the BaseUri attached property.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-276">Die Basis-URI eines bestimmten Elements.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-276">The base URI of a given element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstallation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Installation GetInstallation (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.Installation GetInstallation(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetInstallation(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInstallation (installationId As String) As Installation" />
      <MemberSignature Language="F#" Value="member this.GetInstallation : string -&gt; Microsoft.Azure.NotificationHubs.Installation" Usage="notificationHubClient.GetInstallation installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Installation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="6d3a3-277">Der Installations-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-277">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-278">Ruft ein Geräteobjekt für die Installation ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-278">Gets a device installation object.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-279">Die Installation Geräteobjekt</span><span class="sxs-lookup"><span data-stu-id="6d3a3-279">The device installation object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt; GetInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.Installation&gt; GetInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetInstallationAsync (installationId As String) As Task(Of Installation)" />
      <MemberSignature Language="F#" Value="member this.GetInstallationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt;" Usage="notificationHubClient.GetInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.Installation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="6d3a3-280">Der Installations-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-280">The installation identifier.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-281">Ruft die Installation asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-281">Gets the installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-282">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-282">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-283">Wird ausgelöst, wenn das Objekt "installationid" null ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-283">Thrown when the installationId object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationHubJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobAsync (jobId As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="notificationHubClient.GetNotificationHubJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="6d3a3-284">Der "JobID"-Wert wird zurückgegeben, nachdem Sie erstellen einen neuen Auftrag mit <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-284">The jobId is returned after creating a new job using <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-285">Ein "JobID"-Wert, gibt zurück, wenn die zugeordnete <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-285">Given a jobId, returns the associated <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />.</span></span> <span data-ttu-id="6d3a3-286">Diese Methode wird verwendet, um den Status des Auftrags, um festzustellen, ob dieser Auftrag abgeschlossen, fehlgeschlagen ist oder noch in Bearbeitung abzurufen.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-286">This method is used to get the status of the job to see if that job completed, failed, or is still in progress.</span></span>
            <span data-ttu-id="6d3a3-287">Diese API ist nur für Standard-Namespaces verfügbar.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-287">This API is only available for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d3a3-288">Den aktuellen Status des der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-288">The current state of the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationHubJobsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobsAsync () As Task(Of IEnumerable(Of NotificationHubJob))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;" Usage="notificationHubClient.GetNotificationHubJobsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d3a3-289">Gibt alle bekannten <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-289">Returns all known <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span></span> <span data-ttu-id="6d3a3-290">Diese Methode wird verwendet, um den Status des alle-Auftrags, um festzustellen, ob die Aufträge abgeschlossen, fehlgeschlagen oder noch in Bearbeitung sind abzurufen.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-290">This method is used to get the status of all job to see if those jobs completed, failed, or are still in progress.</span></span>
            <span data-ttu-id="6d3a3-291">Diese API ist nur für Standard-Namespaces verfügbar.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-291">This API is only available for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d3a3-292">Den aktuellen Status des der <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-292">The current state of the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationOutcomeDetailsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt; GetNotificationOutcomeDetailsAsync (string notificationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationDetails&gt; GetNotificationOutcomeDetailsAsync(string notificationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetNotificationOutcomeDetailsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationOutcomeDetailsAsync (notificationId As String) As Task(Of NotificationDetails)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationOutcomeDetailsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt;" Usage="notificationHubClient.GetNotificationOutcomeDetailsAsync notificationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notificationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notificationId">
          <span data-ttu-id="6d3a3-293"><see cref="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" />der beim Aufrufen von Send \* zurückgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-293"><see cref="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" /> which was returned when calling Send\*.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-294">Ruft die Ergebnisse eines Sendeports \*-Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-294">Retrieves the results of a Send\* operation.</span></span> <span data-ttu-id="6d3a3-295">Dies kann Zwischenergebnisse, wenn der Send-Anweisung verarbeitet wird oder Endergebnisse abrufen, wenn der Sendeport \* abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-295">This can retrieve intermediate results if the send is being processed or final results if the Send\* has completed.</span></span> <span data-ttu-id="6d3a3-296">Diese API kann nur für Standard-Namespaces aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-296">This API can only be called for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d3a3-297">Das Ergebnis des Sendevorgangs durch ausgedrückt eine <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-297">The result of the Send operation, as expressed by a <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-298">notificationId</span><span class="sxs-lookup"><span data-stu-id="6d3a3-298">notificationId</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationAsync&lt;TRegistrationDescription&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TRegistrationDescription&gt; GetRegistrationAsync&lt;TRegistrationDescription&gt; (string registrationId) where TRegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!TRegistrationDescription&gt; GetRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) TRegistrationDescription&gt;(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationAsync(Of TRegistrationDescription As RegistrationDescription) (registrationId As String) As Task(Of TRegistrationDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationAsync : string -&gt; System.Threading.Tasks.Task&lt;'RegistrationDescription (requires 'RegistrationDescription :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'RegistrationDescription :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.GetRegistrationAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TRegistrationDescription&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRegistrationDescription">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TRegistrationDescription"><span data-ttu-id="6d3a3-299">Der Typ der Beschreibung der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-299">The type of registration description.</span></span></typeparam>
        <param name="registrationId"><span data-ttu-id="6d3a3-300">Die Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-300">The registration ID.</span></span></param>
        <summary><span data-ttu-id="6d3a3-301">Ruft asynchron eine Registrierung mit einer angegebenen ID ab</span><span class="sxs-lookup"><span data-stu-id="6d3a3-301">Asynchronously retrieves a registration with a given ID.</span></span> <span data-ttu-id="6d3a3-302">Der Typ der Registrierung hängt von der angegebenen <paramref name="TRegistrationDescription" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-302">The type of the registration depends upon the specified <paramref name="TRegistrationDescription" /> parameter.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-303">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-303">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-304">Wird ausgelöst, wenn RegistrationId null ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-304">Thrown when registrationId is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync (string pnsHandle, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync(string pnsHandle, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByChannelAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByChannelAsync (pnsHandle As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByChannelAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByChannelAsync (pnsHandle, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="pnsHandle"><span data-ttu-id="6d3a3-305">Das PNS behandeln.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-305">The PNS handle.</span></span></param>
        <param name="top"><span data-ttu-id="6d3a3-306">Der Speicherort der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-306">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="6d3a3-307">Ruft asynchron die Registrierungen Kanal ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-307">Asynchronously gets the registrations by channel.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-308">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-308">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByChannelAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync (string pnsHandle, string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByChannelAsync(string pnsHandle, string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByChannelAsync(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByChannelAsync (pnsHandle As String, continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByChannelAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByChannelAsync (pnsHandle, continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pnsHandle" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="pnsHandle"><span data-ttu-id="6d3a3-309">Das PNS behandeln.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-309">The PNS handle.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="6d3a3-310">Das Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-310">The continuation token.</span></span></param>
        <param name="top"><span data-ttu-id="6d3a3-311">Der Speicherort der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-311">The location of the registration.</span></span></param>
        <summary><span data-ttu-id="6d3a3-312">Ruft asynchron die Registrierungen Kanal ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-312">Asynchronously gets the registrations by channel.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-313">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-313">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-314">pnshandle-Objekt</span><span class="sxs-lookup"><span data-stu-id="6d3a3-314">pnsHandle</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync (string tag, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync(string tag, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByTagAsync(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByTagAsync (tag As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByTagAsync : string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByTagAsync (tag, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="tag"><span data-ttu-id="6d3a3-315">Das Tag.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-315">The tag.</span></span></param>
        <param name="top"><span data-ttu-id="6d3a3-316">Der Speicherort, wo Sie die Registrierungen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-316">The location where to get the registrations.</span></span></param>
        <summary><span data-ttu-id="6d3a3-317">Ruft asynchron die Registrierungen Tag ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-317">Asynchronously gets the registrations by tag.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-318">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-318">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync (string tag, string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync(string tag, string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.GetRegistrationsByTagAsync(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRegistrationsByTagAsync (tag As String, continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRegistrationsByTagAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="notificationHubClient.GetRegistrationsByTagAsync (tag, continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="tag"><span data-ttu-id="6d3a3-319">Das Tag.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-319">The tag.</span></span></param>
        <param name="continuationToken"><span data-ttu-id="6d3a3-320">Das Fortsetzungstoken.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-320">The continuation token.</span></span></param>
        <param name="top"><span data-ttu-id="6d3a3-321">Der Speicherort, wo Sie die Registrierungen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-321">The location where to get the registrations.</span></span></param>
        <summary><span data-ttu-id="6d3a3-322">Ruft asynchron die Registrierungen Tag ab.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-322">Asynchronously gets the registrations by tag.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-323">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-323">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-324">Wird ausgelöst, wenn der Tag-Objekt null ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-324">Thrown when tag object is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PatchInstallation">
      <MemberSignature Language="C#" Value="public void PatchInstallation (string installationId, System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void PatchInstallation(string installationId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.PatchInstallation(System.String,System.Collections.Generic.IList{Microsoft.Azure.NotificationHubs.PartialUpdateOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub PatchInstallation (installationId As String, operations As IList(Of PartialUpdateOperation))" />
      <MemberSignature Language="F#" Value="member this.PatchInstallation : string * System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; -&gt; unit" Usage="notificationHubClient.PatchInstallation (installationId, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
        <Parameter Name="operations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="6d3a3-325">Der Installations-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-325">The installation identifier.</span></span></param>
        <param name="operations"><span data-ttu-id="6d3a3-326">Die Auflistung der Update-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-326">The collection of update operations.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-327">Patches für die Installation.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-327">Patches the installation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchInstallationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PatchInstallationAsync (string installationId, System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PatchInstallationAsync(string installationId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.PatchInstallationAsync(System.String,System.Collections.Generic.IList{Microsoft.Azure.NotificationHubs.PartialUpdateOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Function PatchInstallationAsync (installationId As String, operations As IList(Of PartialUpdateOperation)) As Task" />
      <MemberSignature Language="F#" Value="member this.PatchInstallationAsync : string * System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt; -&gt; System.Threading.Tasks.Task" Usage="notificationHubClient.PatchInstallationAsync (installationId, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
        <Parameter Name="operations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.NotificationHubs.PartialUpdateOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="installationId"><span data-ttu-id="6d3a3-328">Der Installations-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-328">The installation identifier.</span></span></param>
        <param name="operations"><span data-ttu-id="6d3a3-329">Die Auflistung der Update-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-329">The collection of update operations.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-330">Patches für die Installation asynchron.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-330">Patches the installation asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-331">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-331">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6d3a3-332">Wird ausgelöst, wenn das Objekt "installationid" oder die Operationen null ist</span><span class="sxs-lookup"><span data-stu-id="6d3a3-332">Thrown when the installationId or operations object is null</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="6d3a3-333">Wird ausgelöst, wenn die Liste der Vorgänge leer ist</span><span class="sxs-lookup"><span data-stu-id="6d3a3-333">Thrown when the operations list is empty</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegistrationExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RegistrationExistsAsync (string registrationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; RegistrationExistsAsync(string registrationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.RegistrationExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegistrationExistsAsync (registrationId As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RegistrationExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="notificationHubClient.RegistrationExistsAsync registrationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registrationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="registrationId"><span data-ttu-id="6d3a3-334">Die Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-334">The registration ID.</span></span></param>
        <summary><span data-ttu-id="6d3a3-335">Gibt asynchron an, dass die Registrierung bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-335">Asynchronously indicates that the registration already exists.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-336">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-336">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="6d3a3-337">Die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-337">The notification.</span></span></param>
        <param name="scheduledTime"><span data-ttu-id="6d3a3-338">Die geplante Zeit.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-338">The scheduled time.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-339">Die Benachrichtigung asynchron geplant.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-339">Schedules the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-340">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-340">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="6d3a3-341">Die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-341">The notification.</span></span></param>
        <param name="scheduledTime"><span data-ttu-id="6d3a3-342">Die geplante Zeit.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-342">The scheduled time.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-343">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-343">The tags.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-344">Die Benachrichtigung asynchron geplant.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-344">Schedules the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-345">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-345">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-346">Wird ausgelöst, wenn der RFID-Transponder Objekt null ist</span><span class="sxs-lookup"><span data-stu-id="6d3a3-346">Thrown when tags object is null</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="6d3a3-347">RFID-Transponder-Argument muss mindestens ein Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-347">tags argument should contain atleast one tag</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ScheduleNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, DateTimeOffset scheduledTime, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.ScheduledNotification&gt; ScheduleNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, valuetype System.DateTimeOffset scheduledTime, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.ScheduleNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.DateTimeOffset,System.String)" />
      <MemberSignature Language="F#" Value="member this.ScheduleNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * DateTimeOffset * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;" Usage="notificationHubClient.ScheduleNotificationAsync (notification, scheduledTime, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.ScheduledNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="scheduledTime" Type="System.DateTimeOffset" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="6d3a3-348">Die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-348">The notification.</span></span></param>
        <param name="scheduledTime"><span data-ttu-id="6d3a3-349">Die geplante Zeit.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-349">The scheduled time.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-350">Der tagausdruck.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-350">The tag expression.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-351">Die Benachrichtigung asynchron geplant.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-351">Schedules the notification asynchronously.</span></span>
            </summary>
        <returns><span data-ttu-id="6d3a3-352">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-352">A task that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-353">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-353">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-354">Die administrative systemeigene Benachrichtigung asynchron gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-354">Asynchronously sends the administrative native notification.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-355">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-355">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-356">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-356">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-357">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-357">The tags.</span></span></param>
        <summary><span data-ttu-id="6d3a3-358">Die administrative systemeigene Benachrichtigung asynchron gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-358">Asynchronously sends the administrative native notification.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-359">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-359">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAdmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAdmNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAdmNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAdmNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAdmNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAdmNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-360">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-360">The JSON payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-361">Der tagausdruck.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-361">The tag expression.</span></span></param>
        <summary><span data-ttu-id="6d3a3-362">Die administrative systemeigene Benachrichtigung asynchron gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-362">Asynchronously sends the administrative native notification.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-363">Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-363">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-364">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-364">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-365">Sendet asynchron eine systemeigene Apple-Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-365">Asynchronously sends an Apple native notification.</span></span> <span data-ttu-id="6d3a3-366">Verwenden Sie zum Angeben einer ablaufangabe die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-366">To specify an expiry, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-367">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-367">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-368">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-368">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-369">Ein nicht leerer Satz von Tags (maximal 20 Tags).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-369">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="6d3a3-370">Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-370">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="6d3a3-371">Asynchron sendet eine systemeigene Apple-Benachrichtigung an ein nicht leerer Satz von Tags (maximal 20).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-371">Asynchronously sends an Apple native notification to a non-empty set of tags (maximum 20).</span></span> <span data-ttu-id="6d3a3-372">Dies ist gleichbedeutend mit einer markierten Ausdruck mit booleschen oder-Operatoren ("||").</span><span class="sxs-lookup"><span data-stu-id="6d3a3-372">This is equivalent to a tagged expression with boolean ORs ("||").</span></span> <span data-ttu-id="6d3a3-373">Verwenden Sie zum Angeben einer ablaufangabe die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-373">To specify an expiry, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-374">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-374">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAppleNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAppleNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendAppleNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAppleNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendAppleNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendAppleNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-375">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-375">The JSON payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-376">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-376">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="6d3a3-377">Zum Beispiel: (A || (B) &amp; &amp; ! C.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-377">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="6d3a3-378">Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-378">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="6d3a3-379">Andere Ausdrücke werden auf 6 Tags eingeschränkt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-379">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="6d3a3-380">Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-380">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="6d3a3-381">Sendet asynchron eine systemeigene Apple-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-381">Asynchronously sends an Apple native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span> <span data-ttu-id="6d3a3-382">Verwenden Sie zum Angeben einer ablaufangabe die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-382">To specify an expiry, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-383">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-383">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="6d3a3-384">Dies ist eine Json-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-384">This is a json request.</span></span> <span data-ttu-id="6d3a3-385">Baidu dokumentiert das Format für die Json <a href="http://push.baidu.com/doc/restapi/restapi">hier</a>.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-385">Baidu documents the format for the json <a href="http://push.baidu.com/doc/restapi/restapi">here</a>.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-386">Sendet eine systemeigene Baidu-Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-386">Sends a Baidu native notification.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="6d3a3-387"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />Das Ergebnis des Sendevorgangs beschreibt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-387"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> which describes the result of the Send operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync (message, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="6d3a3-388">Dies ist eine Json-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-388">This is a json request.</span></span> <span data-ttu-id="6d3a3-389">Baidu dokumentiert das Format für die Json <a href="http://push.baidu.com/doc/restapi/restapi">hier</a>.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-389">Baidu documents the format for the json <a href="http://push.baidu.com/doc/restapi/restapi">here</a>.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-390">Ein nicht leerer Satz von Tags (maximal 20 Tags).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-390">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="6d3a3-391">Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-391">Each string in the set can contain a single tag.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-392">Systemeigene Baidu-Benachrichtigung an einem Tag-Ausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck) gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-392">Sends Baidu native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span>
            </summary>
        <returns>
          <span data-ttu-id="6d3a3-393"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />Das Ergebnis des Sendevorgangs beschreibt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-393"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> which describes the result of the Send operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBaiduNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync (string message, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendBaiduNativeNotificationAsync(string message, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendBaiduNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBaiduNativeNotificationAsync (message As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendBaiduNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendBaiduNativeNotificationAsync (message, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="6d3a3-394">Dies ist eine Json-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-394">This is a json request.</span></span> <span data-ttu-id="6d3a3-395">Baidu dokumentiert das Format für die Json <a href="http://push.baidu.com/doc/restapi/restapi">hier</a>.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-395">Baidu documents the format for the json <a href="http://push.baidu.com/doc/restapi/restapi">here</a>.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-396">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-396">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="6d3a3-397">Zum Beispiel: (A || (B) &amp; &amp; ! C.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-397">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="6d3a3-398">Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-398">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="6d3a3-399">Andere Ausdrücke werden auf 6 Tags eingeschränkt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-399">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="6d3a3-400">Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-400">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-401">Systemeigene Baidu-Benachrichtigung an einem Tag-Ausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck) gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-401">Sends Baidu native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span>
            </summary>
        <returns>
          <span data-ttu-id="6d3a3-402"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />Das Ergebnis des Sendevorgangs beschreibt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-402"><see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" /> which describes the result of the Send operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync jsonPayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-403">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-403">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-404">Sendet asynchron systemeigene GCM-Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-404">Asynchronously sends GCM native notification.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-405">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-405">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync (jsonPayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-406">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-406">The JSON payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-407">Ein nicht leerer Satz von Tags (maximal 20 Tags).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-407">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="6d3a3-408">Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-408">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="6d3a3-409">Asynchron sendet eine systemeigene GCM-Benachrichtigung an ein nicht leerer Satz von Tags (max. 20).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-409">Asynchronously sends a GCM native notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="6d3a3-410">Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</span><span class="sxs-lookup"><span data-stu-id="6d3a3-410">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="6d3a3-411">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-411">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendGcmNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync (string jsonPayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendGcmNativeNotificationAsync(string jsonPayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendGcmNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendGcmNativeNotificationAsync (jsonPayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendGcmNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendGcmNativeNotificationAsync (jsonPayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6d3a3-412">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-412">The JSON payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-413">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-413">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="6d3a3-414">Zum Beispiel: (A || (B) &amp; &amp; ! C.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-414">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="6d3a3-415">Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-415">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="6d3a3-416">Andere Ausdrücke werden auf 6 Tags eingeschränkt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-416">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="6d3a3-417">Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-417">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="6d3a3-418">Sendet asynchron systemeigene GCM-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-418">Asynchronously sends GCM native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span></summary>
        <returns><span data-ttu-id="6d3a3-419">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-419">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync nativePayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nativePayload"><span data-ttu-id="6d3a3-420">Die systemeigene Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-420">The native payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-421">Sendet asynchron systemeigene MPNS-Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-421">Asynchronously sends MPNS native notification.</span></span> <span data-ttu-id="6d3a3-422">Verwenden Sie zum Festlegen von Headern für MPNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-422">To specify headers for MPNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-423">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-423">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync (nativePayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nativePayload"><span data-ttu-id="6d3a3-424">Die benachrichtigungsnutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-424">The notification payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-425">Ein nicht leerer Satz von Tags (maximal 20 Tags).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-425">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="6d3a3-426">Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-426">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="6d3a3-427">Systemeigene MPNS-Benachrichtigung sendet asynchron auf ein nicht leerer Satz von Tags (maximal 20).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-427">Asynchronously sends MPNS native notification to a non-empty set of tags (maximum 20).</span></span> <span data-ttu-id="6d3a3-428">Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</span><span class="sxs-lookup"><span data-stu-id="6d3a3-428">This is equivalent to a tag expression with boolean ORs ("||").</span></span> <span data-ttu-id="6d3a3-429">Verwenden Sie zum Festlegen von Headern für MPNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-429">To specify headers for MPNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-430">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-430">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendMpnsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync (string nativePayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendMpnsNativeNotificationAsync(string nativePayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendMpnsNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendMpnsNativeNotificationAsync (nativePayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendMpnsNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendMpnsNativeNotificationAsync (nativePayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nativePayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nativePayload"><span data-ttu-id="6d3a3-431">Die systemeigene Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-431">The native payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-432">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-432">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="6d3a3-433">Zum Beispiel: (A || (B) &amp; &amp; ! C.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-433">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="6d3a3-434">Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-434">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="6d3a3-435">Andere Ausdrücke werden auf 6 Tags eingeschränkt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-435">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="6d3a3-436">Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-436">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="6d3a3-437">Sendet asynchron systemeigene MPNS-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-437">Asynchronously sends MPNS native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span> <span data-ttu-id="6d3a3-438">Verwenden Sie zum Festlegen von Headern für MPNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-438">To specify headers for MPNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-439">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-439">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync notification" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="6d3a3-440">Die Benachrichtigung zu senden.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-440">The notification to send.</span></span></param>
        <summary><span data-ttu-id="6d3a3-441">Asynchron sendet eine Benachrichtigung an ein nicht leerer Satz von Tags (max. 20).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-441">Asynchronously sends a notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="6d3a3-442">Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</span><span class="sxs-lookup"><span data-stu-id="6d3a3-442">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="6d3a3-443">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-443">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-444">Benachrichtigung</span><span class="sxs-lookup"><span data-stu-id="6d3a3-444">notification</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync (notification, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="6d3a3-445">Die Benachrichtigung zu senden.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-445">The notification to send.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-446">Ein nicht leerer Satz von Tags (max. 20 Tags).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-446">A non-empty set of tags (max 20 tags).</span></span> <span data-ttu-id="6d3a3-447">Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-447">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="6d3a3-448">Asynchron sendet eine Benachrichtigung an ein nicht leerer Satz von Tags (max. 20).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-448">Asynchronously sends a notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="6d3a3-449">Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</span><span class="sxs-lookup"><span data-stu-id="6d3a3-449">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="6d3a3-450">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-450">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6d3a3-451">Wird ausgelöst, wenn die Benachrichtigung oder Tag Objekt null ist</span><span class="sxs-lookup"><span data-stu-id="6d3a3-451">Thrown when notification or tag object is null</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="6d3a3-452">Benachrichtigung. Tag-Eigenschaft darf nicht null sein oder Tags-Argument sollte einen Transponder Atleat enthalten</span><span class="sxs-lookup"><span data-stu-id="6d3a3-452">notification.Tag property should not be null or tags argument should contain atleat one tag</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.String)" />
      <MemberSignature Language="F#" Value="member this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendNotificationAsync (notification, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="6d3a3-453">Die Benachrichtigung zu senden.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-453">The notification to send.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-454">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-454">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="6d3a3-455">Zum Beispiel: (A || (B) &amp; &amp; ! C.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-455">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="6d3a3-456">Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-456">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="6d3a3-457">Andere Ausdrücke werden auf 6 Tags eingeschränkt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-457">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="6d3a3-458">Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-458">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="6d3a3-459">Sendet asynchron eine Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-459">Asynchronously sends a notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span></summary>
        <returns><span data-ttu-id="6d3a3-460">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-460">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="6d3a3-461">Benachrichtigung</span><span class="sxs-lookup"><span data-stu-id="6d3a3-461">notification</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="6d3a3-462">Benachrichtigung. Tag-Eigenschaft darf null sein.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-462">notification.Tag property should be null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="6d3a3-463">Die Eigenschaften der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-463">The properties of the template.</span></span></param>
        <summary><span data-ttu-id="6d3a3-464">Sendet asynchron eine vorlagenbenachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-464">Asynchronously sends a template notification.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-465">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-465">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String), tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync (properties, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="6d3a3-466">Die Eigenschaften der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-466">The properties of the template.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-467">Ein nicht leerer Satz von Tags (maximal 20 Tags).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-467">A non-empty set of tags (maximum 20 tags).</span></span> <span data-ttu-id="6d3a3-468">Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-468">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="6d3a3-469">Asynchron sendet eine vorlagenbenachrichtigung auf ein nicht leerer Satz von Tags (maximal 20).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-469">Asynchronously sends a template notification to a non-empty set of tags (maximum 20).</span></span> <span data-ttu-id="6d3a3-470">Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</span><span class="sxs-lookup"><span data-stu-id="6d3a3-470">This is equivalent to a tag expression with boolean ORs ("||").</span></span></summary>
        <returns><span data-ttu-id="6d3a3-471">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-471">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendTemplateNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; properties, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendTemplateNotificationAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendTemplateNotificationAsync(System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendTemplateNotificationAsync (properties As IDictionary(Of String, String), tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendTemplateNotificationAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendTemplateNotificationAsync (properties, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="6d3a3-472">Die Eigenschaften der Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-472">The properties of the template.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-473">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-473">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="6d3a3-474">Zum Beispiel: (A || (B) &amp; &amp; ! C.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-474">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="6d3a3-475">Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-475">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="6d3a3-476">Andere Ausdrücke werden auf 6 Tags eingeschränkt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-476">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="6d3a3-477">Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-477">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="6d3a3-478">Sendet asynchron eine vorlagenbenachrichtigung in einem Tag-Ausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-478">Asynchronously sends a template notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span></summary>
        <returns><span data-ttu-id="6d3a3-479">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-479">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync windowsNativePayload" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload"><span data-ttu-id="6d3a3-480">Die systemeigene Windows-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-480">The Windows native payload.</span></span></param>
        <summary><span data-ttu-id="6d3a3-481">Sendet asynchron eine systemeigene Windows-Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-481">Asynchronously sends a Windows native notification.</span></span> <span data-ttu-id="6d3a3-482">Verwenden Sie zum Festlegen von Headern für WNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-482">To specify headers for WNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-483">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-483">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync (windowsNativePayload, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload"><span data-ttu-id="6d3a3-484">Die systemeigene Windows-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-484">The Windows native payload.</span></span></param>
        <param name="tags"><span data-ttu-id="6d3a3-485">Ein nicht leerer Satz von Tags (max. 20 Tags).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-485">A non-empty set of tags (max 20 tags).</span></span> <span data-ttu-id="6d3a3-486">Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-486">Each string in the set can contain a single tag.</span></span></param>
        <summary><span data-ttu-id="6d3a3-487">Asynchron sendet eine systemeigene Windows-Benachrichtigung an ein nicht leerer Satz von Tags (max. 20).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-487">Asynchronously sends a Windows native notification to a non-empty set of tags (max 20).</span></span> <span data-ttu-id="6d3a3-488">Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</span><span class="sxs-lookup"><span data-stu-id="6d3a3-488">This is equivalent to a tag expression with boolean ORs ("||").</span></span> <span data-ttu-id="6d3a3-489">Verwenden Sie zum Festlegen von Headern für WNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-489">To specify headers for WNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-490">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-490">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendWindowsNativeNotificationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync (string windowsNativePayload, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendWindowsNativeNotificationAsync(string windowsNativePayload, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendWindowsNativeNotificationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendWindowsNativeNotificationAsync (windowsNativePayload As String, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="member this.SendWindowsNativeNotificationAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="notificationHubClient.SendWindowsNativeNotificationAsync (windowsNativePayload, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="windowsNativePayload" Type="System.String" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="windowsNativePayload"><span data-ttu-id="6d3a3-491">Die systemeigene Windows-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-491">The Windows native payload.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="6d3a3-492">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-492">A tag expression is any boolean expression constructed using the logical operators AND (&amp;&amp;), OR (||), NOT (!), and round parentheses.</span></span> <span data-ttu-id="6d3a3-493">Zum Beispiel: (A || (B) &amp; &amp; ! C.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-493">For example: (A || B) &amp;&amp; !C.</span></span> <span data-ttu-id="6d3a3-494">Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-494">If an expression uses only ORs, it can contain at most 20 tags.</span></span> <span data-ttu-id="6d3a3-495">Andere Ausdrücke werden auf 6 Tags eingeschränkt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-495">Other expressions are limited to 6 tags.</span></span> <span data-ttu-id="6d3a3-496">Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-496">Note that a single tag "A" is a valid expression.</span></span></param>
        <summary><span data-ttu-id="6d3a3-497">Sendet asynchron eine systemeigene Windows-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</span><span class="sxs-lookup"><span data-stu-id="6d3a3-497">Asynchronously sends a Windows native notification to a tag expression (a single tag "tag" is a valid tag expression).</span></span> <span data-ttu-id="6d3a3-498">Verwenden Sie zum Festlegen von Headern für WNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-498">To specify headers for WNS, use the <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> method.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-499">Die Aufgabe, die den asynchronen Vorgang abschließt.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-499">The task that completes the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync (Microsoft.Azure.NotificationHubs.NotificationHubJob job);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync(class Microsoft.Azure.NotificationHubs.NotificationHubJob job) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitNotificationHubJobAsync (job As NotificationHubJob) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.SubmitNotificationHubJobAsync : Microsoft.Azure.NotificationHubs.NotificationHubJob -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="notificationHubClient.SubmitNotificationHubJobAsync job" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.NotificationHubs.NotificationHubJob" />
      </Parameters>
      <Docs>
        <param name="job"><span data-ttu-id="6d3a3-500">Die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> um Registrierungen zu exportieren, importieren Sie Registrierungen oder Registrierungen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-500">The <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> to export registrations, import registrations, or create registrations.</span></span></param>
        <summary>
            <span data-ttu-id="6d3a3-501">Erstellt eine <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-501">Creates a <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />.</span></span> <span data-ttu-id="6d3a3-502">Diese API ist nur für Standard-Namespaces verfügbar.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-502">This API is only available for Standard namespaces.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d3a3-503">Die übermittelte <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-503">The submitted <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRegistrationAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; UpdateRegistrationAsync&lt;T&gt; (T registration) where T : Microsoft.Azure.NotificationHubs.RegistrationDescription;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;!!T&gt; UpdateRegistrationAsync&lt;(class Microsoft.Azure.NotificationHubs.RegistrationDescription) T&gt;(!!T registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.UpdateRegistrationAsync``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRegistrationAsync(Of T As RegistrationDescription) (registration As T) As Task(Of T)" />
      <MemberSignature Language="F#" Value="member this.UpdateRegistrationAsync : 'T -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)&gt; (requires 'T :&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription)" Usage="notificationHubClient.UpdateRegistrationAsync registration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.Azure.NotificationHubs.RegistrationDescription</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="registration" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="6d3a3-504">Der Typ der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-504">The type of registration.</span></span></typeparam>
        <param name="registration"><span data-ttu-id="6d3a3-505">Die zu aktualisierende Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-505">The registration to update.</span></span></param>
        <summary><span data-ttu-id="6d3a3-506">Aktualisiert asynchron die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-506">Asynchronously updates the registration.</span></span></summary>
        <returns><span data-ttu-id="6d3a3-507">Eine Aufgabe, die abgeschlossen wird, wenn der Aktualisierungsvorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="6d3a3-507">A task that will complete when the update finishes.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="6d3a3-508">Wird ausgelöst, wenn RegistrationId oder ETag Objekt null ist</span><span class="sxs-lookup"><span data-stu-id="6d3a3-508">Thrown when RegistrationId or ETag object is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>