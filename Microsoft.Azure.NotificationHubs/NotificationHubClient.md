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
    <summary>Stellt einen Notification Hub-Clients dar.</summary>
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
        <param name="scheduledNotificationId">Der Bezeichner für geplante Benachrichtigung.</param>
        <summary>
            Die Benachrichtigung asynchron abgebrochen.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
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
        <param name="admRegistrationId">Der administrative registrierungsbezeichner.</param>
        <summary>Erstellt asynchron eine systemeigene administrative-Registrierung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="admRegistrationId">Der administrative registrierungsbezeichner.</param>
        <param name="tags">Die Tags für die Registrierung.</param>
        <summary>Erstellt asynchron eine systemeigene administrative-Registrierung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="admRegistrationId">Der administrative registrierungsbezeichner.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <summary>Erstellt asynchron eine administrative Vorlage-Registrierung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="admRegistrationId">Der administrative registrierungsbezeichner.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron eine administrative Vorlage-Registrierung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="deviceToken">Das gerätetoken.</param>
        <summary>Erstellt asynchron eine systemeigene Apple-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="deviceToken">Das gerätetoken.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron eine systemeigene Apple-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="deviceToken">Das gerätetoken.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <summary>Erstellt asynchron eine Apple-vorlagenregistrierung. Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="deviceToken">Das gerätetoken.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron eine Apple-vorlagenregistrierung. Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="userId">Die Benutzer-ID.</param>
        <param name="channelId">Die Kanal-ID.</param>
        <summary>
            Die systemeigene Baidu-Registrierung erstellt asynchron.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
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
        <param name="userId">Die Benutzer-ID.</param>
        <param name="channelId">Die Kanal-ID.</param>
        <param name="tags">Die Tags.</param>
        <summary>
            Die systemeigene Baidu-Registrierung erstellt asynchron.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
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
        <param name="userId">Die Benutzer-ID.</param>
        <param name="channelId">Die Kanal-ID.</param>
        <param name="jsonPayload">Die Json-Nutzlast.</param>
        <summary>
            Baidu-vorlagenregistrierung erstellt asynchron.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
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
        <param name="userId">Die Benutzer-ID.</param>
        <param name="channelId">Die Kanal-ID.</param>
        <param name="jsonPayload">Die Json-Nutzlast.</param>
        <param name="tags">Die Tags.</param>
        <summary>
            Baidu-vorlagenregistrierung erstellt asynchron.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
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
        <param name="connectionString">Verbindungszeichenfolge.</param>
        <param name="notificationHubPath">Der Notification Hub-Pfad.</param>
        <summary>Erstellt einen Client aus der Verbindungszeichenfolge an.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</returns>
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
        <param name="connectionString">Verbindungszeichenfolge.</param>
        <param name="notificationHubPath">Der Notification Hub-Pfad.</param>
        <param name="enableTestSend">"true" aktiviert – testsendevorgang; andernfalls "false".</param>
        <summary>Erstellt einen Client aus der Verbindungszeichenfolge an.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubClient" />.</returns>
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
        <param name="gcmRegistrationId">Die GCM-Registrierungs-ID.</param>
        <summary>Erstellt asynchron systemeigene GCM-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="gcmRegistrationId">Die GCM-Registrierungs-ID.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron systemeigene GCM-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="gcmRegistrationId">Die GCM-Registrierungs-ID.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <summary>Erstellt asynchron GCM-vorlagenregistrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="gcmRegistrationId">Die GCM-Registrierungs-ID.</param>
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron GCM-vorlagenregistrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <summary>Erstellt asynchron systemeigene MPNS-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron systemeigene MPNS-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <param name="xmlTemplate">Die XML-Vorlage.</param>
        <summary>Erstellt asynchron MPNS-vorlagenregistrierung. Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <param name="xmlTemplate">Die XML-Vorlage.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron MPNS-vorlagenregistrierung. Verwenden Sie zum Angeben zusätzlicher Eigenschaften bei der Erstellung der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.CreateRegistrationAsync``1(``0)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="installation">Das Gerät Installation-Objekt.</param>
        <summary>
            Erstellt oder aktualisiert eine Geräteinstallation.
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
        <param name="installation">Das Gerät Installation-Objekt.</param>
        <summary>
            Erstellt oder eine Geräteinstallation asynchron aktualisiert.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn die Installation Objekt null ist</exception>
        <exception cref="T:System.InvalidOperationException">"Installationid" muss angegeben werden</exception>
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
        <typeparam name="T">Der Typ der Registrierung.</typeparam>
        <param name="registration">Die Registrierung erstellt oder aktualisiert werden.</param>
        <summary>Asynchron erstellt oder aktualisiert die Clientregistrierung.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn RegistrationId Objekt null ist</exception>
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
        <typeparam name="T">Der Typ der Registrierung.</typeparam>
        <param name="registration">Die Registrierung zu erstellen.</param>
        <summary>Erstellt asynchron eine Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            NotificationHubPath in RegistrationDescription ist ungültig.
            oder RegistrationId muss null oder leer sein.
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
        <summary>Erstellt asynchron einen registrierungsbezeichner.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <summary>Erstellt asynchron systemeigene Windows-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron systemeigene Windows-Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <param name="xmlTemplate">Die XML-Vorlage.</param>
        <summary>Erstellt asynchron Windows vorlagenregistrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="channelUri">Die Kanal-URI.</param>
        <param name="xmlTemplate">Die XML-Vorlage.</param>
        <param name="tags">Die Tags.</param>
        <summary>Erstellt asynchron Windows vorlagenregistrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="installationId">Der Installations-ID.</param>
        <summary>
            Löscht die Installation.
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
        <param name="installationId">Der Installations-ID.</param>
        <summary>
            Löscht die Installation asynchron an.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn das Objekt "installationid" null ist.</exception>
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
        <param name="registration">Die zu löschende Registrierung.</param>
        <summary>Löscht asynchron die Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Registrierungsobjekt null ist.</exception>
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
        <param name="registrationId">Die Registrierungs-ID.</param>
        <summary>Löscht asynchron die Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="registrationId">Die Registrierungs-ID.</param>
        <param name="etag">Das Entitätstag.</param>
        <summary>Löscht asynchron die Registrierung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">registrationId</exception>
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
        <param name="pnsHandle">Das PNS behandeln.</param>
        <summary>Löscht asynchron die Registrierungen vom Kanal an.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">pnshandle-Objekt</exception>
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
        <summary>Ruft ab oder legt einen Wert, der angibt, ob der Client einen Test senden kann.</summary>
        <value>"true", wenn der Client einen Test kann senden. andernfalls "false".</value>
        <remarks>
            Wenn Test senden aktiviert ist, geschieht Folgendes:
            <ul><li>Alle Benachrichtigungen erreichen nur bis zu 10 Geräte für jeden Sendeaufruf.</li><li>Die <b>senden *</b> Methoden zurückgeben einer Liste der Ergebnisse für alle Übermittlungen für diese Benachrichtigung. Die möglichen Ergebnisse sind identisch mit der im Telemetrie angezeigt. Ergebnisse enthält, z. B. Authentifizierungsfehler, Einschränkung, Fehler, erfolgreich Übermittlungen und So weiter.</li></ul><p>In diesem Modus wird nur zu Testzwecken nicht für die Produktion und eingeschränkt wird.</p></remarks>
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
        <param name="top">Der Speicherort der Registrierung.</param>
        <summary>Ruft Sie alle Registrierungen in diesem benachrichtigungshub asynchron ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="continuationToken">Das Fortsetzungstoken.</param>
        <param name="top">Der Speicherort der Registrierung.</param>
        <summary>Ruft Sie alle Registrierungen in diesem benachrichtigungshub asynchron ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <summary>Ruft den Wert der Eigenschaft BaseUri angefügt.</summary>
        <returns>Die Basis-URI eines bestimmten Elements.</returns>
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
        <param name="installationId">Der Installations-ID.</param>
        <summary>
            Ruft ein Geräteobjekt für die Installation ab.
            </summary>
        <returns>Die Installation Geräteobjekt</returns>
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
        <param name="installationId">Der Installations-ID.</param>
        <summary>
            Ruft die Installation asynchron ab.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn das Objekt "installationid" null ist.</exception>
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
        <param name="jobId">Der "JobID"-Wert wird zurückgegeben, nachdem Sie erstellen einen neuen Auftrag mit <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.</param>
        <summary>
            Ein "JobID"-Wert, gibt zurück, wenn die zugeordnete <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />. Diese Methode wird verwendet, um den Status des Auftrags, um festzustellen, ob dieser Auftrag abgeschlossen, fehlgeschlagen ist oder noch in Bearbeitung abzurufen.
            Diese API ist nur für Standard-Namespaces verfügbar.
            </summary>
        <returns>
            Den aktuellen Status des der <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob)" />.
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
            Gibt alle bekannten <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s. Diese Methode wird verwendet, um den Status des alle-Auftrags, um festzustellen, ob die Aufträge abgeschlossen, fehlgeschlagen oder noch in Bearbeitung sind abzurufen.
            Diese API ist nur für Standard-Namespaces verfügbar.
            </summary>
        <returns>
            Den aktuellen Status des der <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.
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
          <see cref="P:Microsoft.Azure.NotificationHubs.NotificationOutcome.NotificationId" />der beim Aufrufen von Send * zurückgegeben wurde.</param>
        <summary>
            Ruft die Ergebnisse eines Sendeports *-Vorgangs ab. Dies kann Zwischenergebnisse, wenn der Send-Anweisung verarbeitet wird oder Endergebnisse abrufen, wenn der Sendeport * abgeschlossen wurde. Diese API kann nur für Standard-Namespaces aufgerufen werden.
            </summary>
        <returns>
            Das Ergebnis des Sendevorgangs durch ausgedrückt eine <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />.
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">notificationId</exception>
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
        <typeparam name="TRegistrationDescription">Der Typ der Beschreibung der Registrierung.</typeparam>
        <param name="registrationId">Die Registrierungs-ID.</param>
        <summary>Ruft asynchron eine Registrierung mit einer angegebenen ID ab Der Typ der Registrierung hängt von der angegebenen <paramref name="TRegistrationDescription" /> Parameter.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn RegistrationId null ist.</exception>
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
        <param name="pnsHandle">Das PNS behandeln.</param>
        <param name="top">Der Speicherort der Registrierung.</param>
        <summary>Ruft asynchron die Registrierungen Kanal ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="pnsHandle">Das PNS behandeln.</param>
        <param name="continuationToken">Das Fortsetzungstoken.</param>
        <param name="top">Der Speicherort der Registrierung.</param>
        <summary>Ruft asynchron die Registrierungen Kanal ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">pnshandle-Objekt</exception>
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
        <param name="tag">Das Tag.</param>
        <param name="top">Der Speicherort, wo Sie die Registrierungen zu erhalten.</param>
        <summary>Ruft asynchron die Registrierungen Tag ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="tag">Das Tag.</param>
        <param name="continuationToken">Das Fortsetzungstoken.</param>
        <param name="top">Der Speicherort, wo Sie die Registrierungen zu erhalten.</param>
        <summary>Ruft asynchron die Registrierungen Tag ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn der Tag-Objekt null ist.</exception>
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
        <param name="installationId">Der Installations-ID.</param>
        <param name="operations">Die Auflistung der Update-Vorgänge.</param>
        <summary>
            Patches für die Installation.
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
        <param name="installationId">Der Installations-ID.</param>
        <param name="operations">Die Auflistung der Update-Vorgänge.</param>
        <summary>
            Patches für die Installation asynchron.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn das Objekt "installationid" oder die Operationen null ist
            </exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die Liste der Vorgänge leer ist</exception>
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
        <param name="registrationId">Die Registrierungs-ID.</param>
        <summary>Gibt asynchron an, dass die Registrierung bereits vorhanden ist.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="notification">Die Benachrichtigung.</param>
        <param name="scheduledTime">Die geplante Zeit.</param>
        <summary>
            Die Benachrichtigung asynchron geplant.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
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
        <param name="notification">Die Benachrichtigung.</param>
        <param name="scheduledTime">Die geplante Zeit.</param>
        <param name="tags">Die Tags.</param>
        <summary>
            Die Benachrichtigung asynchron geplant.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn der RFID-Transponder Objekt null ist</exception>
        <exception cref="T:System.ArgumentException">RFID-Transponder-Argument muss mindestens ein Tag enthalten.</exception>
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
        <param name="notification">Die Benachrichtigung.</param>
        <param name="scheduledTime">Die geplante Zeit.</param>
        <param name="tagExpression">Der tagausdruck.</param>
        <summary>
            Die Benachrichtigung asynchron geplant.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Vorgang darstellt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <summary>Die administrative systemeigene Benachrichtigung asynchron gesendet.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tags">Die Tags.</param>
        <summary>Die administrative systemeigene Benachrichtigung asynchron gesendet.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tagExpression">Der tagausdruck.</param>
        <summary>Die administrative systemeigene Benachrichtigung asynchron gesendet.</summary>
        <returns>Das Aufgabenobjekt, das den asynchronen Vorgang darstellt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <summary>Sendet asynchron eine systemeigene Apple-Benachrichtigung. Verwenden Sie zum Angeben einer ablaufangabe die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tags">Ein nicht leerer Satz von Tags (maximal 20 Tags). Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</param>
        <summary>Asynchron sendet eine systemeigene Apple-Benachrichtigung an ein nicht leerer Satz von Tags (maximal 20). Dies ist gleichbedeutend mit einer markierten Ausdruck mit booleschen oder-Operatoren ("||"). Verwenden Sie zum Angeben einer ablaufangabe die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tagExpression">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern. Zum Beispiel: (A || (B) &amp; &amp; ! C. Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten. Andere Ausdrücke werden auf 6 Tags eingeschränkt. Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</param>
        <summary>Sendet asynchron eine systemeigene Apple-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck). Verwenden Sie zum Angeben einer ablaufangabe die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="message">Dies ist eine Json-Anforderung. Baidu dokumentiert das Format für die Json <a href="http://push.baidu.com/doc/restapi/restapi">hier</a>.</param>
        <summary>
            Sendet eine systemeigene Baidu-Benachrichtigung.
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />Das Ergebnis des Sendevorgangs beschreibt.
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
        <param name="message">Dies ist eine Json-Anforderung. Baidu dokumentiert das Format für die Json <a href="http://push.baidu.com/doc/restapi/restapi">hier</a>.</param>
        <param name="tags">Ein nicht leerer Satz von Tags (maximal 20 Tags). Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</param>
        <summary>
            Systemeigene Baidu-Benachrichtigung an einem Tag-Ausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck) gesendet.
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />Das Ergebnis des Sendevorgangs beschreibt.
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
        <param name="message">Dies ist eine Json-Anforderung. Baidu dokumentiert das Format für die Json <a href="http://push.baidu.com/doc/restapi/restapi">hier</a>.</param>
        <param name="tagExpression">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern. Zum Beispiel: (A || (B) &amp; &amp; ! C. Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten. Andere Ausdrücke werden auf 6 Tags eingeschränkt. Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</param>
        <summary>
            Systemeigene Baidu-Benachrichtigung an einem Tag-Ausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck) gesendet.
            </summary>
        <returns>
          <see cref="T:Microsoft.Azure.NotificationHubs.NotificationOutcome" />Das Ergebnis des Sendevorgangs beschreibt.
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <summary>Sendet asynchron systemeigene GCM-Benachrichtigung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tags">Ein nicht leerer Satz von Tags (maximal 20 Tags). Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</param>
        <summary>Asynchron sendet eine systemeigene GCM-Benachrichtigung an ein nicht leerer Satz von Tags (max. 20). Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="jsonPayload">Die JSON-Nutzlast.</param>
        <param name="tagExpression">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern. Zum Beispiel: (A || (B) &amp; &amp; ! C. Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten. Andere Ausdrücke werden auf 6 Tags eingeschränkt. Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</param>
        <summary>Sendet asynchron systemeigene GCM-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="nativePayload">Die systemeigene Nutzlast.</param>
        <summary>Sendet asynchron systemeigene MPNS-Benachrichtigung. Verwenden Sie zum Festlegen von Headern für MPNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="nativePayload">Die benachrichtigungsnutzlast.</param>
        <param name="tags">Ein nicht leerer Satz von Tags (maximal 20 Tags). Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</param>
        <summary>Systemeigene MPNS-Benachrichtigung sendet asynchron auf ein nicht leerer Satz von Tags (maximal 20). Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||"). Verwenden Sie zum Festlegen von Headern für MPNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="nativePayload">Die systemeigene Nutzlast.</param>
        <param name="tagExpression">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern. Zum Beispiel: (A || (B) &amp; &amp; ! C. Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten. Andere Ausdrücke werden auf 6 Tags eingeschränkt. Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</param>
        <summary>Sendet asynchron systemeigene MPNS-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck). Verwenden Sie zum Festlegen von Headern für MPNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="notification">Die Benachrichtigung zu senden.</param>
        <summary>Asynchron sendet eine Benachrichtigung an ein nicht leerer Satz von Tags (max. 20). Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Benachrichtigung</exception>
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
        <param name="notification">Die Benachrichtigung zu senden.</param>
        <param name="tags">Ein nicht leerer Satz von Tags (max. 20 Tags). Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</param>
        <summary>Asynchron sendet eine Benachrichtigung an ein nicht leerer Satz von Tags (max. 20). Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn die Benachrichtigung oder Tag Objekt null ist
            </exception>
        <exception cref="T:System.ArgumentException">
            Benachrichtigung. Tag-Eigenschaft darf nicht null sein oder Tags-Argument sollte einen Transponder Atleat enthalten
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
        <param name="notification">Die Benachrichtigung zu senden.</param>
        <param name="tagExpression">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern. Zum Beispiel: (A || (B) &amp; &amp; ! C. Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten. Andere Ausdrücke werden auf 6 Tags eingeschränkt. Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</param>
        <summary>Sendet asynchron eine Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Benachrichtigung</exception>
        <exception cref="T:System.ArgumentException">Benachrichtigung. Tag-Eigenschaft darf null sein.</exception>
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
        <param name="properties">Die Eigenschaften der Vorlage.</param>
        <summary>Sendet asynchron eine vorlagenbenachrichtigung.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="properties">Die Eigenschaften der Vorlage.</param>
        <param name="tags">Ein nicht leerer Satz von Tags (maximal 20 Tags). Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</param>
        <summary>Asynchron sendet eine vorlagenbenachrichtigung auf ein nicht leerer Satz von Tags (maximal 20). Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||").</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="properties">Die Eigenschaften der Vorlage.</param>
        <param name="tagExpression">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern. Zum Beispiel: (A || (B) &amp; &amp; ! C. Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten. Andere Ausdrücke werden auf 6 Tags eingeschränkt. Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</param>
        <summary>Sendet asynchron eine vorlagenbenachrichtigung in einem Tag-Ausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck).</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="windowsNativePayload">Die systemeigene Windows-Nutzlast.</param>
        <summary>Sendet asynchron eine systemeigene Windows-Benachrichtigung. Verwenden Sie zum Festlegen von Headern für WNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="windowsNativePayload">Die systemeigene Windows-Nutzlast.</param>
        <param name="tags">Ein nicht leerer Satz von Tags (max. 20 Tags). Jede Zeichenfolge in der Gruppe kann ein einzelnes Tag enthalten.</param>
        <summary>Asynchron sendet eine systemeigene Windows-Benachrichtigung an ein nicht leerer Satz von Tags (max. 20). Dies entspricht dem eines tagausdrucks mit booleschen oder-Operatoren ("||"). Verwenden Sie zum Festlegen von Headern für WNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="windowsNativePayload">Die systemeigene Windows-Nutzlast.</param>
        <param name="tagExpression">Ein tagausdrucks ist ein beliebiger boolescher Ausdruck erstellt wird, verwenden die logischen Operatoren AND (&amp;&amp;), oder (|), nicht (!), und runden Klammern. Zum Beispiel: (A || (B) &amp; &amp; ! C. Wenn ein Ausdruck nur oder-Operatoren verwendet, kann es höchstens 20 Tags enthalten. Andere Ausdrücke werden auf 6 Tags eingeschränkt. Beachten Sie, dass ein einzelnes Tag "A" ein gültiger Ausdruck ist.</param>
        <summary>Sendet asynchron eine systemeigene Windows-Benachrichtigung zu einem tagausdruck (ein einzelnes Tag "Tag" ist ein gültiges Tag-Ausdruck). Verwenden Sie zum Festlegen von Headern für WNS die <see cref="M:Microsoft.Azure.NotificationHubs.NotificationHubClient.SendNotificationAsync(Microsoft.Azure.NotificationHubs.Notification)" /> Methode.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
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
        <param name="job">Die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> um Registrierungen zu exportieren, importieren Sie Registrierungen oder Registrierungen zu erstellen.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />. Diese API ist nur für Standard-Namespaces verfügbar.
            </summary>
        <returns>
            Die übermittelte <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />s.
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
        <typeparam name="T">Der Typ der Registrierung.</typeparam>
        <param name="registration">Die zu aktualisierende Registrierung.</param>
        <summary>Aktualisiert asynchron die Registrierung.</summary>
        <returns>Eine Aufgabe, die abgeschlossen wird, wenn der Aktualisierungsvorgang abgeschlossen ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn RegistrationId oder ETag Objekt null ist
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>