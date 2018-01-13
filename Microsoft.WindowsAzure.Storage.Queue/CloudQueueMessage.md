<Type Name="CloudQueueMessage" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage">
  <TypeSignature Language="C#" Value="public sealed class CloudQueueMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudQueueMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudQueueMessage" />
  <TypeSignature Language="F#" Value="type CloudQueueMessage = class" />
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
            Stellt eine Nachricht im Microsoft Azure-Warteschlangendienst dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (byte[] content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : byte[] -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage content" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="content">Der Inhalt der Nachricht als Bytearray.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> Klasse mit dem angegebenen Bytearray.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (content As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage content" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content">Der Inhalt der Nachricht als Zeichenfolge bestehend aus Text.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> -Klasse mit der angegebenen Zeichenfolge.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueMessage (string messageId, string popReceipt);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string messageId, string popReceipt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageId As String, popReceipt As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage : string * string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage (messageId, popReceipt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="messageId">Eine Zeichenfolge, die Nachrichten-ID angibt</param>
        <param name="popReceipt">Eine Zeichenfolge, die das abrufbestätigungs-Token enthält.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> Klasse mit der vorgegebenen Nachrichten-ID und der abrufbestätigung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsBytes">
      <MemberSignature Language="C#" Value="public byte[] AsBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] AsBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsBytes As Byte()" />
      <MemberSignature Language="F#" Value="member this.AsBytes : byte[]" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Inhalt der Nachricht als Bytearray ab.
            </summary>
        <value>Der Inhalt der Nachricht als Bytearray.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsString">
      <MemberSignature Language="C#" Value="public string AsString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AsString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsString As String" />
      <MemberSignature Language="F#" Value="member this.AsString : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.AsString" />
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
            Ruft den Inhalt der Nachricht als Zeichenfolge ab.
            </summary>
        <value>Eine Zeichenfolge, die den Nachrichteninhalt enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DequeueCount">
      <MemberSignature Language="C#" Value="public int DequeueCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.DequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DequeueCount : int" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.DequeueCount" />
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
        <value>Gibt an, wie oft diese Nachricht aus der Warteschlange entfernt wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.ExpirationTime" />
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
            Ruft die Zeit ab, der die Nachricht abläuft.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> , der angibt, der Zeit, die die Nachricht abläuft.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.Id" />
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
        <value>Eine Zeichenfolge, enthält die Nachrichten-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; InsertionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; InsertionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.InsertionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InsertionTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.InsertionTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.InsertionTime" />
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
            Ruft die Zeit ab, der die Nachricht zur Warteschlange hinzugefügt wurde.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> , der angibt, der Zeit, die die Nachricht der Warteschlange hinzugefügt wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public static long MaxMessageSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Nachrichtengröße in Bytes ab.
            </summary>
        <value>Die maximale Nachrichtengröße in Byte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfMessagesToPeek">
      <MemberSignature Language="C#" Value="public static int MaxNumberOfMessagesToPeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int32 MaxNumberOfMessagesToPeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxNumberOfMessagesToPeek" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxNumberOfMessagesToPeek As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfMessagesToPeek : int" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxNumberOfMessagesToPeek" />
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
            Ruft die maximale Anzahl von Nachrichten, die zu einem bestimmten Zeitpunkt eingesehen werden können.
            </summary>
        <value>Die maximale Anzahl der Nachrichten, die zu einem bestimmten Zeitpunkt eingesehen werden können.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTimeToLive">
      <MemberSignature Language="C#" Value="public static TimeSpan MaxTimeToLive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property valuetype System.TimeSpan MaxTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MaxTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxTimeToLive : TimeSpan" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.MaxTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Zeitspanne, die eine Nachricht in der Warteschlange beibehalten wird.
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> angeben die maximale Zeitspanne, die eine Nachricht in der Warteschlange beibehalten wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextVisibleTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; NextVisibleTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; NextVisibleTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.NextVisibleTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextVisibleTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.NextVisibleTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.NextVisibleTime" />
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
            Ruft die Zeit ab, der die Nachricht als Nächstes angezeigt werden.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> , der angibt, der Zeit, die die Nachricht als Nächstes angezeigt werden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PopReceipt">
      <MemberSignature Language="C#" Value="public string PopReceipt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PopReceipt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.PopReceipt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PopReceipt As String" />
      <MemberSignature Language="F#" Value="member this.PopReceipt : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.PopReceipt" />
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
        <value>Eine Zeichenfolge, die den abrufbestätigungswert enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMessageContent">
      <MemberSignature Language="C#" Value="public void SetMessageContent (byte[] content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMessageContent(unsigned int8[] content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.SetMessageContent(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMessageContent (content As Byte())" />
      <MemberSignature Language="F#" Value="member this.SetMessageContent : byte[] -&gt; unit" Usage="cloudQueueMessage.SetMessageContent content" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="content">Der Inhalt der Nachricht als Bytearray.</param>
        <summary>
            Legt den Inhalt dieser Nachricht fest.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMessageContent">
      <MemberSignature Language="C#" Value="public void SetMessageContent (string content);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetMessageContent(string content) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage.SetMessageContent(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetMessageContent (content As String)" />
      <MemberSignature Language="F#" Value="member this.SetMessageContent : string -&gt; unit" Usage="cloudQueueMessage.SetMessageContent content" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content">Eine Zeichenfolge, die den Inhalt der neuen Nachricht enthält.</param>
        <summary>
            Legt den Inhalt dieser Nachricht fest.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>