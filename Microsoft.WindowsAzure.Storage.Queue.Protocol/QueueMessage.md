<Type Name="QueueMessage" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage">
  <TypeSignature Language="C#" Value="public class QueueMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueMessage" />
  <TypeSignature Language="F#" Value="type QueueMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Nachricht aus einer Warteschlange abgerufen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DequeueCount">
      <MemberSignature Language="C#" Value="public int DequeueCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.DequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DequeueCount : int" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.DequeueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Häufigkeit, mit die diese Nachricht aus der Warteschlange entfernt wurde.
            </summary>
        <value>Die Häufigkeit.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ablaufzeit der Nachricht ab.
            </summary>
        <value>Die Ablaufzeit für die Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Nachrichten-ID.
            </summary>
        <value>Die Meldungs-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; InsertionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; InsertionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.InsertionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InsertionTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.InsertionTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.InsertionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit ab, an die Nachricht zur Warteschlange hinzugefügt wurde.
            </summary>
        <value>Der Zeitpunkt der Einfügung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextVisibleTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; NextVisibleTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; NextVisibleTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.NextVisibleTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextVisibleTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.NextVisibleTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.NextVisibleTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit ab, die die Nachricht weiter ist sichtbar.
            </summary>
        <value>Der Zeitpunkt, zu die Nachricht als Nächstes angezeigt wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PopReceipt">
      <MemberSignature Language="C#" Value="public string PopReceipt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PopReceipt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.PopReceipt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PopReceipt As String" />
      <MemberSignature Language="F#" Value="member this.PopReceipt : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.PopReceipt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die abrufbestätigung der Nachricht ab.
            </summary>
        <value>Die POP-Bestätigung der Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Text" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueMessage.Text" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Text der Nachricht ab.
            </summary>
        <value>Der Meldungstext.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>