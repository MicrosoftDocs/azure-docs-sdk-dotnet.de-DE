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
            Die <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> bietet einen Mechanismus zum Senden von Benachrichtigungen für mobile Anwendungen über einen Benachrichtigungs-Hub.
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
            Die <see cref="T:System.Web.Http.HttpConfiguration" /> für den aktuellen Dienst.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> mit einem bestimmten
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
        <param name="message">Die <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" /> zum Erstellen der <see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> aus.</param>
        <summary>
            Erstellt ein <see cref="T:Microsoft.Azure.NotificationHubs.Notification" /> aus einem <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />.
            </summary>
        <returns>Das resultierende <see cref="T:Microsoft.Azure.NotificationHubs.Notification" />.</returns>
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
        <param name="connectionString">Die Verbindungszeichenfolge für die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</param>
        <param name="hubName">Der Name des Hubs.</param>
        <param name="enableTestSend">Gibt an, ob der Test sendet aktiviert werden soll.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> auf mockable Weise.
            </summary>
        <returns>Eine neue <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />-Instanz.</returns>
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
            Wenn Test senden aktiviert ist, erreichen alle Benachrichtigungen nur bis zu 10 Geräte für jede Sendeaufruf und die Rückgabe der SendNotificationAsync-Methode eine detaillierte Liste der Ergebnisse für alle diese Benachrichtigung-Übermittlungen (z. B. Authentifizierungsfehler, drosselungsfehlern, und so weiter).
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
            Ruft ab oder legt den <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> zum Senden von Benachrichtigungen verwendet werden soll.
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
        <param name="message">Die benachrichtigungsnutzlast ist einer der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</param>
        <summary>
            Sendet eine Benachrichtigung an den Benachrichtigungshub.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</returns>
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
        <param name="message">Die benachrichtigungsnutzlast ist einer der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</param>
        <param name="tags">Der Satz von Tags für diese Benachrichtigung.</param>
        <summary>
            Sendet eine Benachrichtigung an den Benachrichtigungshub mit einer bestimmten Tag-Ausdruck.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</returns>
        <remarks>Diese Methode ist veraltet. Sie sollten stattdessen die HubClient.SendNotificationAsync()-Methode verwenden.</remarks>
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
        <param name="message">Die benachrichtigungsnutzlast ist einer der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />.</param>
        <param name="tagExpression">Ein tagausdruck, der die Kombination aus Tags für diese Benachrichtigung darstellt.</param>
        <summary>
            Sendet eine Benachrichtigung an den Benachrichtigungshub mit einer bestimmten Tag-Ausdruck.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</returns>
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
        <param name="notification">Die Benachrichtigung zu senden.</param>
        <param name="tags">Der Satz von Tags für diese Benachrichtigung.</param>
        <summary>
            Macht <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> Sendevorgang mockable.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</returns>
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
        <param name="notification">Die Benachrichtigung zu senden.</param>
        <param name="tagExpression">Ein tagausdruck, der die Kombination aus Tags für diese Benachrichtigung darstellt.</param>
        <summary>
            Macht <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" /> Sendevorgang mockable.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Vorgang senden, die die Benachrichtigung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>