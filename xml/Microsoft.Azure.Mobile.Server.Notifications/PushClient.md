<Type Name="PushClient" FullName="Microsoft.Azure.Mobile.Server.Notifications.PushClient">
  <TypeSignature Language="C#" Value="public class PushClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PushClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />
  <TypeSignature Language="VB.NET" Value="Public Class PushClient" />
  <TypeSignature Language="F#" Value="type PushClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="73a1e-101">Die <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> bietet einen Mechanismus zum Senden von Benachrichtigungen für mobile Anwendungen über einen Benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="73a1e-101">The <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> provides a mechanism for sending notifications to mobile applications through a Notification Hub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PushClient (System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.#ctor(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (config As HttpConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Notifications.PushClient : System.Web.Http.HttpConfiguration -&gt; Microsoft.Azure.Mobile.Server.Notifications.PushClient" Usage="new Microsoft.Azure.Mobile.Server.Notifications.PushClient config" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" />
      </Parameters>
      <Docs>
        <param name="config">
            <span data-ttu-id="73a1e-102">Die <see cref="T:System.Web.Http.HttpConfiguration" /> für den aktuellen Dienst.</span><span class="sxs-lookup"><span data-stu-id="73a1e-102">The <see cref="T:System.Web.Http.HttpConfiguration" /> for the current service.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73a1e-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> mit einem bestimmten</span><span class="sxs-lookup"><span data-stu-id="73a1e-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> with a given</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotification">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Azure.NotificationHubs.Notification CreateNotification (Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.NotificationHubs.Notification CreateNotification(class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.CreateNotification(Microsoft.Azure.Mobile.Server.Notifications.IPushMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateNotification (message As IPushMessage) As Notification" />
      <MemberSignature Language="F#" Value="abstract member CreateNotification : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage -&gt; Microsoft.Azure.NotificationHubs.Notification&#xA;override this.CreateNotification : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage -&gt; Microsoft.Azure.NotificationHubs.Notification" Usage="pushClient.CreateNotification message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Notification</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="73a1e-104">Die <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" /> zum Erstellen der <see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> aus.</span><span class="sxs-lookup"><span data-stu-id="73a1e-104">The <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" /> to create the <see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> from.</span></span></param>
        <summary>
            <span data-ttu-id="73a1e-105">Erstellt ein <see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> aus einem <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />.</span><span class="sxs-lookup"><span data-stu-id="73a1e-105">Creates a <see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> from a <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />.</span></span>
            </summary>
        <returns><span data-ttu-id="73a1e-106">Das resultierende <see cref="T:Microsoft.Azure.NotificationHubs.Notification" />.</span><span class="sxs-lookup"><span data-stu-id="73a1e-106">The resulting <see cref="T:Microsoft.Azure.NotificationHubs.Notification" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHubClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Azure.NotificationHubs.NotificationHubClient CreateNotificationHubClient (string connectionString, string hubName, bool enableTestSend);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.NotificationHubs.NotificationHubClient CreateNotificationHubClient(string connectionString, string hubName, bool enableTestSend) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.CreateNotificationHubClient(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateNotificationHubClient (connectionString As String, hubName As String, enableTestSend As Boolean) As NotificationHubClient" />
      <MemberSignature Language="F#" Value="abstract member CreateNotificationHubClient : string * string * bool -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient&#xA;override this.CreateNotificationHubClient : string * string * bool -&gt; Microsoft.Azure.NotificationHubs.NotificationHubClient" Usage="pushClient.CreateNotificationHubClient (connectionString, hubName, enableTestSend)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="enableTestSend" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="73a1e-107">Die Verbindungszeichenfolge für die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span><span class="sxs-lookup"><span data-stu-id="73a1e-107">The connection string for the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</span></span></param>
        <param name="hubName"><span data-ttu-id="73a1e-108">Der Name des Hubs.</span><span class="sxs-lookup"><span data-stu-id="73a1e-108">The name of the hub.</span></span></param>
        <param name="enableTestSend"><span data-ttu-id="73a1e-109">Gibt an, ob der Test sendet aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="73a1e-109">Indicates whether test sends should be enabled.</span></span></param>
        <summary>
            <span data-ttu-id="73a1e-110">Erstellt eine <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> auf mockable Weise.</span><span class="sxs-lookup"><span data-stu-id="73a1e-110">Creates a <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> in a mockable manner.</span></span>
            </summary>
        <returns><span data-ttu-id="73a1e-111">Eine neue <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />-Instanz.</span><span class="sxs-lookup"><span data-stu-id="73a1e-111">A new <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateInstallationAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateOrUpdateInstallationAsync (Microsoft.Azure.NotificationHubs.Installation installation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateOrUpdateInstallationAsync(class Microsoft.Azure.NotificationHubs.Installation installation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.CreateOrUpdateInstallationAsync(Microsoft.Azure.NotificationHubs.Installation)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateInstallationAsync : Microsoft.Azure.NotificationHubs.Installation -&gt; System.Threading.Tasks.Task&#xA;override this.CreateOrUpdateInstallationAsync : Microsoft.Azure.NotificationHubs.Installation -&gt; System.Threading.Tasks.Task" Usage="pushClient.CreateOrUpdateInstallationAsync installation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installation" Type="Microsoft.Azure.NotificationHubs.Installation" />
      </Parameters>
      <Docs>
        <param name="installation">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstallationAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteInstallationAsync (string installationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteInstallationAsync(string installationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.DeleteInstallationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteInstallationAsync (installationId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteInstallationAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteInstallationAsync : string -&gt; System.Threading.Tasks.Task" Usage="pushClient.DeleteInstallationAsync installationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="installationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="installationId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableTestSend">
      <MemberSignature Language="C#" Value="public virtual bool EnableTestSend { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableTestSend" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.PushClient.EnableTestSend" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property EnableTestSend As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableTestSend : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.PushClient.EnableTestSend" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73a1e-112">Wenn Test senden aktiviert ist, erreichen alle Benachrichtigungen nur bis zu 10 Geräte für jede Sendeaufruf und die Rückgabe der SendNotificationAsync-Methode eine detaillierte Liste der Ergebnisse für alle diese Benachrichtigung-Übermittlungen (z. B. Authentifizierungsfehler, drosselungsfehlern, und so weiter).</span><span class="sxs-lookup"><span data-stu-id="73a1e-112">When test send is enabled, all notifications only reach up to 10 devices for each send call and the SendNotificationAsync method return a detailed list of the outcomes for all those notification deliveries (for example, authentication errors, throttling errors, and so on).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistrationsByTagAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync (string tag, string continuationToken, int top);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.CollectionQueryResult`1&lt;class Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt; GetRegistrationsByTagAsync(string tag, string continuationToken, int32 top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.GetRegistrationsByTagAsync(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetRegistrationsByTagAsync (tag As String, continuationToken As String, top As Integer) As Task(Of CollectionQueryResult(Of RegistrationDescription))" />
      <MemberSignature Language="F#" Value="abstract member GetRegistrationsByTagAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;&#xA;override this.GetRegistrationsByTagAsync : string * string * int -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.CollectionQueryResult&lt;Microsoft.Azure.NotificationHubs.RegistrationDescription&gt;&gt;" Usage="pushClient.GetRegistrationsByTagAsync (tag, continuationToken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
        <param name="tag">To be added.</param>
        <param name="continuationToken">To be added.</param>
        <param name="top">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HubClient">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.NotificationHubs.NotificationHubClient HubClient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.NotificationHubClient HubClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.PushClient.HubClient" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property HubClient As NotificationHubClient" />
      <MemberSignature Language="F#" Value="member this.HubClient : Microsoft.Azure.NotificationHubs.NotificationHubClient with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.PushClient.HubClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73a1e-113">Ruft ab oder legt den <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> zum Senden von Benachrichtigungen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="73a1e-113">Gets or sets the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> to use for sending notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAsync (Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAsync(class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.SendAsync(Microsoft.Azure.Mobile.Server.Notifications.IPushMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SendAsync (message As IPushMessage) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;&#xA;override this.SendAsync : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="pushClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="73a1e-114">Die benachrichtigungsnutzlast ist einer der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</span><span class="sxs-lookup"><span data-stu-id="73a1e-114">The notification payload is one of <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, or <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="73a1e-115">Sendet eine Benachrichtigung an den Benachrichtigungshub.</span><span class="sxs-lookup"><span data-stu-id="73a1e-115">Sends a notification to the Notification Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="73a1e-116">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</span><span class="sxs-lookup"><span data-stu-id="73a1e-116">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the notification send operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAsync (Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAsync(class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.SendAsync(Microsoft.Azure.Mobile.Server.Notifications.IPushMessage,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SendAsync (message As IPushMessage, tags As IEnumerable(Of String)) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;&#xA;override this.SendAsync : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="pushClient.SendAsync (message, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete. You should use the HubClient.SendNotificationAsync() method instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="73a1e-117">Die benachrichtigungsnutzlast ist einer der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</span><span class="sxs-lookup"><span data-stu-id="73a1e-117">The notification payload is one of <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, or <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</span></span></param>
        <param name="tags"><span data-ttu-id="73a1e-118">Der Satz von Tags für diese Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="73a1e-118">The set of tags to use for this notification.</span></span></param>
        <summary>
            <span data-ttu-id="73a1e-119">Sendet eine Benachrichtigung an den Benachrichtigungshub mit einer bestimmten Tag-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="73a1e-119">Sends a notification to the Notification Hub with a given tag expression.</span></span>
            </summary>
        <returns><span data-ttu-id="73a1e-120">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</span><span class="sxs-lookup"><span data-stu-id="73a1e-120">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the notification send operation.</span></span></returns>
        <remarks><span data-ttu-id="73a1e-121">Diese Methode ist veraltet.</span><span class="sxs-lookup"><span data-stu-id="73a1e-121">This method is obsolete.</span></span> <span data-ttu-id="73a1e-122">Sie sollten stattdessen die HubClient.SendNotificationAsync()-Methode verwenden.</span><span class="sxs-lookup"><span data-stu-id="73a1e-122">You should use the HubClient.SendNotificationAsync() method instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAsync (Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendAsync(class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage message, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.SendAsync(Microsoft.Azure.Mobile.Server.Notifications.IPushMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SendAsync (message As IPushMessage, tagExpression As String) As Task(Of NotificationOutcome)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;&#xA;override this.SendAsync : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="pushClient.SendAsync (message, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="73a1e-123">Die benachrichtigungsnutzlast ist einer der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</span><span class="sxs-lookup"><span data-stu-id="73a1e-123">The notification payload is one of <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, or <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="73a1e-124">Ein tagausdruck, der die Kombination aus Tags für diese Benachrichtigung darstellt.</span><span class="sxs-lookup"><span data-stu-id="73a1e-124">A tag expression representing the combination of tags to use for this notification.</span></span></param>
        <summary>
            <span data-ttu-id="73a1e-125">Sendet eine Benachrichtigung an den Benachrichtigungshub mit einer bestimmten Tag-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="73a1e-125">Sends a notification to the Notification Hub with a given tag expression.</span></span>
            </summary>
        <returns><span data-ttu-id="73a1e-126">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</span><span class="sxs-lookup"><span data-stu-id="73a1e-126">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the notification send operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, System.Collections.Generic.IEnumerable&lt;string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, class System.Collections.Generic.IEnumerable`1&lt;string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="F#" Value="abstract member SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;&#xA;override this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="pushClient.SendNotificationAsync (notification, tags)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tags" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="73a1e-127">Die Benachrichtigung zu senden.</span><span class="sxs-lookup"><span data-stu-id="73a1e-127">The notification to send.</span></span></param>
        <param name="tags"><span data-ttu-id="73a1e-128">Der Satz von Tags für diese Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="73a1e-128">The set of tags to use for this notification.</span></span></param>
        <summary>
            <span data-ttu-id="73a1e-129">Macht <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> Sendevorgang mockable.</span><span class="sxs-lookup"><span data-stu-id="73a1e-129">Makes <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> send operation mockable.</span></span>
            </summary>
        <returns><span data-ttu-id="73a1e-130">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</span><span class="sxs-lookup"><span data-stu-id="73a1e-130">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the notification send operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendNotificationAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync (Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationOutcome&gt; SendNotificationAsync(class Microsoft.Azure.NotificationHubs.Notification notification, string tagExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.PushClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification,System.String)" />
      <MemberSignature Language="F#" Value="abstract member SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;&#xA;override this.SendNotificationAsync : Microsoft.Azure.NotificationHubs.Notification * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;" Usage="pushClient.SendNotificationAsync (notification, tagExpression)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationOutcome&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notification" Type="Microsoft.Azure.NotificationHubs.Notification" />
        <Parameter Name="tagExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notification"><span data-ttu-id="73a1e-131">Die Benachrichtigung zu senden.</span><span class="sxs-lookup"><span data-stu-id="73a1e-131">The notification to send.</span></span></param>
        <param name="tagExpression"><span data-ttu-id="73a1e-132">Ein tagausdruck, der die Kombination aus Tags für diese Benachrichtigung darstellt.</span><span class="sxs-lookup"><span data-stu-id="73a1e-132">A tag expression representing the combination of tags to use for this notification.</span></span></param>
        <summary>
            <span data-ttu-id="73a1e-133">Macht <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> Sendevorgang mockable.</span><span class="sxs-lookup"><span data-stu-id="73a1e-133">Makes <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> send operation mockable.</span></span>
            </summary>
        <returns><span data-ttu-id="73a1e-134">Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</span><span class="sxs-lookup"><span data-stu-id="73a1e-134">A <see cref="T:System.Threading.Tasks.Task`1" /> representing the notification send operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>