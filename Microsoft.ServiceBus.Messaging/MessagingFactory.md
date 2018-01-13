<Type Name="MessagingFactory" FullName="Microsoft.ServiceBus.Messaging.MessagingFactory">
  <TypeSignature Language="C#" Value="public abstract class MessagingFactory : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessagingFactory extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessagingFactory&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessagingFactory = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> Die MessagingFactory-Klasse ist der Premium-Klasse, die für Vorgänge zur Laufzeit verwendet wird, zum Senden und empfangen zu und von Warteschlangen, Themen und Abonnements. </summary>
    <remarks>Beachten Sie, dass alle Membermethode mit CreateXXXClient, z. B. CreateQueueClient, keine neue Entität im Namespace erstellt wird. IT nur ruft zu behandeln, um eine vorhandene Entität, die zuvor mit erstellt die <see cref="T:Microsoft.ServiceBus.NamespaceManager" />. Wenn diese Entitäten ist nicht im Namespace vorhanden, erhalten Sie eine Ausnahme.</remarks>
    <altmember cref="T:Microsoft.ServiceBus.NamespaceManager" />
    <example>
      <code>
            String-Adresse = "sb://myapp.WindowsAzure.com/"; die Basisadresse des Namespace, um die Verbindung hergestellt werden.
            MessagingFactorySettings MsgFactorySettings = neue MessagingFactorySettings(); Betriebsmodus Timeout angeben (optional) MessagingFactory MsgFactory = MessagingFactory.Create (Adresse, MsgFactorySettings);
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt die verfügbaren Sitzungen in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace zurück.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">Der Timeout für die Verarbeitung.</param>
        <summary>Gibt die verfügbaren Sitzungen in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace zurück.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Gruppierung verwandter Nachrichten zur Verarbeitung in einer einzelnen Transaktion ermöglicht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt asynchron zurück verfügbaren Sitzungen, in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Vorgang für den Accept-meldungssitzung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">Der Timeout für die Verarbeitung.</param>
        <summary>Gibt asynchron zurück verfügbaren Sitzungen, in allen Abonnements sitzungsfähigen und Warteschlangen im Dienstnamespace.</summary>
        <returns>Eine Taskinstanz, die den asynchronen Vorgang für den Accept-meldungssitzung darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Basisadresse der messaging-Factory ab.</summary>
        <value>Ein URI, der die Basisadresse der messaging-Factory darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt ein neues messaging Factoryobjekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration von Basisadressen.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration der Adresse.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des dienstnamespaces.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des Namespace.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration von Basisadressen.</param>
        <param name="factorySettings">Die werkseitigen Standardeinstellungen.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration von Basisadressen.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration der Adresse.</param>
        <param name="factorySettings">Die werkseitigen Standardeinstellungen.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration der Adresse.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des dienstnamespaces.</param>
        <param name="factorySettings">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UriFormatException">Wird ausgelöst, wenn <paramref name="address" /> ist leer.</exception>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="factorySettings" /> oder <paramref name="address" /> null sind.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des Namespaces.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
        <exception cref="T:System.UriFormatException">Wird ausgelöst, wenn <paramref name="address" /> ist leer.</exception>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="tokenProvider" /> oder <paramref name="address" /> null sind.</exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des Namespace.</param>
        <param name="factorySettings">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="address" /> oder <paramref name="factorySettings" /> ist null.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des Namespaces.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />-Objekt.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="tokenProvider" /> oder <paramref name="address" /> null sind.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration von Basisadressen.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration der Adresse.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des dienstnamespaces.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des Namespace.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration von Basisadressen.</param>
        <param name="factorySettings">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration von Basisadressen.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration der Adresse.</param>
        <param name="factorySettings">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Eine Enumeration der Adresse.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des dienstnamespaces.</param>
        <param name="factorySettings">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des dienstnamespaces.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des Namespace.</param>
        <param name="factorySettings">Die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Einstellungen.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die Basisadresse des Namespace.</param>
        <param name="tokenProvider">Der Tokenanbieter.</param>
        <summary>Erstellt asynchron ein neue messaging Factory-Objekt.</summary>
        <returns>Erstellungsvorgang für eine Aufgabeninstanz, die den asynchronen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.CreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> -Objekt unter Verwendung des angegebenen Pfads.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> Objekt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="path" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindungszeichenfolge.</param>
        <summary>Erstellt ein neues <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt von einer Verbindungszeichenfolge.</summary>
        <returns>Das neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiver (entityPath As String) As MessageReceiver" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Der Pfad der Entität.</param>
        <summary>Erstellt einen Empfänger einer Nachricht an.</summary>
        <returns>Die neu erstellte Nachrichtenempfänger.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath">Der Pfad der Entität.</param>
        <param name="receiveMode">Der Receive-Modus.</param>
        <summary>Erstellt einen Empfänger einer Nachricht an.</summary>
        <returns>Die neu erstellte Nachrichtenempfänger.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiverAsync (entityPath As String) As Task(Of MessageReceiver)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Der Pfad der Entität.</param>
        <summary>Erstellt asynchron einen Empfänger einer Nachricht ein.</summary>
        <returns>Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Empfänger darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath">Der Pfad der Entität.</param>
        <param name="receiveMode">Der Receive-Modus.</param>
        <summary>Erstellt asynchron einen Empfänger einer Nachricht ein.</summary>
        <returns>Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Empfänger darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (entityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Der Pfad der Entität.</param>
        <summary>Erstellt den Absender einer Nachricht an.</summary>
        <returns>Der Absender der neu erstellte Nachricht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (transferDestinationEntityPath As String, viaEntityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string * string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath">Der Pfad der Übertragung Ziel-Entität.</param>
        <param name="viaEntityPath">Der Pfad über Entität.</param>
        <summary>Erstellt den Absender einer Nachricht an.</summary>
        <returns>Das erstellte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (entityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Der Pfad der Entität.</param>
        <summary>Erstellt asynchron den Absender einer Nachricht ein.</summary>
        <returns>Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Absender darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (transferDestinationEntityPath As String, viaEntityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath">Der Pfad der Übertragung Ziel-Entität.</param>
        <param name="viaEntityPath">Der Pfad über Entität.</param>
        <summary>Erstellt asynchron den Absender einer Nachricht ein.</summary>
        <returns>Eine Taskinstanz, die der asynchrone Erstellvorgang Nachricht Absender darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueClient (path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Erstellt einen neue warteschlangenclient.</summary>
        <returns>Die neu erstellte Anwendungswarteschlangen-Client.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <paramref name="path" />Länge ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
        <exception cref="T:System.OperationCanceledException">Die Factory wurde geschlossen oder abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="receiveMode">Der Receive-Modus.</param>
        <summary>Erstellt einen neue warteschlangenclient.</summary>
        <returns>Die neu erstellte Anwendungswarteschlangen-Client.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <paramref name="path" />Länge ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
        <exception cref="T:System.OperationCanceledException">Die Factory wurde geschlossen oder abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionClient (topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zu den Dienstnamespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Erstellt einen abonnementclient.</summary>
        <returns>Der Client neu erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Die angegebene <paramref name="topicPath" /> ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Die Länge des <paramref name="topicPath" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
        <exception cref="T:System.OperationCanceledException">Die Factory wurde geschlossen oder abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zu den Dienstnamespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="receiveMode">Der Receive-Modus.</param>
        <summary>Erstellt einen neuen abonnementclient.</summary>
        <returns>Der Client neu erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Die angegebene <paramref name="topicPath" /> ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Die Länge des <paramref name="topicPath" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
        <exception cref="T:System.OperationCanceledException">Die Factory wurde geschlossen oder abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="member this.CreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.CreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Erstellt einen neuen themenclient.</summary>
        <returns>Die neu erstellte themenclient.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Die angegebene <paramref name="path" /> ist null.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Objekt. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
        <exception cref="T:System.OperationCanceledException">Die Factory wurde geschlossen oder abgebrochen.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.GetSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSettings () As MessagingFactorySettings" />
      <MemberSignature Language="F#" Value="member this.GetSettings : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="messagingFactory.GetSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactorySettings</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft eine Kopie der Einstellungen der messaging-Factory.</summary>
        <returns>Eine Kopie des messaging Factory-Einstellungen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncrementConnectionResetCount">
      <MemberSignature Language="C#" Value="protected void IncrementConnectionResetCount (Uri endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void IncrementConnectionResetCount(class System.Uri endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.IncrementConnectionResetCount(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub IncrementConnectionResetCount (endpoint As Uri)" />
      <MemberSignature Language="F#" Value="member this.IncrementConnectionResetCount : Uri -&gt; unit" Usage="messagingFactory.IncrementConnectionResetCount endpoint" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="endpoint"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Uri&gt; NamespaceEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; NamespaceEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NamespaceEndpoints As IEnumerable(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.NamespaceEndpoints : seq&lt;Uri&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft eine Liste der Endpunkte des Namespace ab.</summary>
        <value>Eine Liste von Namespace-Endpunkten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messagingFactory.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Führt die Aktion abbrechen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptMessageSession (receiveMode, serverWaitTime, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="receiveMode">Die Nachricht Empfangsmodus.</param>
        <param name="serverWaitTime">Die Wartezeit des Servers.</param>
        <param name="timeout">Das Timeout für den Vorgang.</param>
        <summary>Führt der meldungssitzung akzeptieren.</summary>
        <returns>Die nachrichtensitzung ausgeführten.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <param name="sessionId">Die Sitzungs-ID.</param>
        <param name="receiveMode">Die Nachricht Empfangsmodus.</param>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <summary>Führt eine Aktion Empfänger Sitzung annehmen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen verweist akzeptieren Sitzung Empfänger Aktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptMessageSession (receiveMode, serverWaitTime, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="receiveMode">Der Receive-Modus.</param>
        <param name="serverWaitTime">Die Wartezeit des Servers.</param>
        <param name="timeout">Das Timeout für den Vorgang.</param>
        <param name="callback">Der asynchrone Rückruf.</param>
        <param name="state">der Sitzungsstatus.</param>
        <summary>Führt die Begin Sitzung Nachrichtenaktion akzeptieren.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <param name="sessionId">Die Sitzungs-ID.</param>
        <param name="receiveMode">Die Nachricht Empfangsmodus.</param>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</param>
        <summary>Führt die Begin Sitzung Empfänger Aktion annehmen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen verweist akzeptieren Sitzung Empfänger Aktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout">Das Timeout.</param>
        <param name="callback">Der Rückruf.</param>
        <param name="state">Der Zustand.</param>
        <summary>Führt die Aktion "Schließen" beginnen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Aktion "Schließen" verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageReceiver (entityName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <param name="receiveMode">Die Nachricht Empfangsmodus.</param>
        <param name="timeout">Die Wartezeit vor dem Vorgang ein Timeout eintritt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</param>
        <summary>Führt die Begin Empfänger Nachrichtenaktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Empfänger Erstellungsaktion verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateMessageSender (string entityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string entityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnBeginCreateMessageSender (entityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (entityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <param name="timeout">Das Timeout.</param>
        <param name="callback">Der Rückruf.</param>
        <param name="state">Der Zustand.</param>
        <summary>Führt die Begin Absender Nachrichtenaktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Absender Erstellungsaktion verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName">Der Name der Zielentität übertragen.</param>
        <param name="viaEntityName">Der Name des via-Entität.</param>
        <param name="timeout">Das Timeout.</param>
        <param name="callback">Die Rückruf-Meldung.</param>
        <param name="state">Der Zustand.</param>
        <summary>Führt die Begin Absender Nachrichtenaktion zu erstellen.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Absender Erstellungsaktion verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="messagingFactory.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">Das Timeout.</param>
        <summary>Führt die Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateEventHubClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient&#xA;override this.OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.OnCreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Event Hub-Clients.</param>
        <summary>Führt die Ereignis-Hub Client Erstellungsaktion.</summary>
        <returns>Der erstellte <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver&#xA;override this.OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnCreateMessageReceiver (entityName, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <param name="receiveMode">Die Nachricht Empfangsmodus.</param>
        <param name="timeout">Das Timeout.</param>
        <summary>Führt die Message-Empfänger Erstellungsaktion.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Empfänger Erstellungsaktion verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string entityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string entityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (entityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (entityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <param name="timeout">Das Timeout.</param>
        <summary>Führt die Nachrichten-Absender Erstellungsaktion.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das die asynchrone Nachricht Absender Erstellungsaktion verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName">Der Name der Zielentität übertragen.</param>
        <param name="viaEntityName">Der Name des via-Entität.</param>
        <param name="timeout">Das Timeout der Nachricht.</param>
        <summary>Führt die Nachrichten-Absender Erstellungsaktion.</summary>
        <returns>Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> Aktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateQueueClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient&#xA;override this.OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.OnCreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="receiveMode">Der Receive-Modus.</param>
        <summary>Führt eine Aktion Client Warteschlange erstellen.</summary>
        <returns>Die neu erstellte Anwendungswarteschlangen-Client.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string subscriptionPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string subscriptionPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (subscriptionPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subscriptionPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="subscriptionPath">Der Pfad des Abonnements.</param>
        <param name="receiveMode">Der Receive-Modus.</param>
        <summary>Führt eine Abonnement-Client Erstellungsaktion.</summary>
        <returns>Ein Client neu erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Abonnements relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="receiveMode">Der Receive-Modus.</param>
        <summary>Führt eine Abonnement-Client Erstellungsaktion.</summary>
        <returns>Ein Client neu erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateTopicClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient&#xA;override this.OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.OnCreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Führt eine Aktion Client Thema erstellen.</summary>
        <returns>Die neu erstellte themenclient.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptMessageSession result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Das Ergebnis des Vorgangs.</param>
        <summary>Führt die End-Sitzung Nachrichtenaktion akzeptieren.</summary>
        <returns>Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Aktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptSessionReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptSessionReceiver (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptSessionReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptSessionReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> -Objekt, das Zustandsinformationen und benutzerdefinierte Daten für diesen asynchronen Vorgang speichert.</param>
        <summary>Führt das Ende Sitzung Empfänger Aktion annehmen.</summary>
        <returns>Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messagingFactory.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Das Ergebnis.</param>
        <summary>Führt die End-Aktion "Schließen".</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnEndCreateMessageReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Das Ergebnis.</param>
        <summary>Führt das Ende Empfänger Nachrichtenaktion zu erstellen.</summary>
        <returns>Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> Aktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnEndCreateMessageSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Das Ergebnis.</param>
        <summary>Führt das Ende Absender Nachrichtenaktion zu erstellen.</summary>
        <returns>Die ausgeführte <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> Aktion.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairNamespaceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PairNamespaceAsync (Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PairNamespaceAsync(class Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.PairNamespaceAsync(Microsoft.ServiceBus.Messaging.PairedNamespaceOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function PairNamespaceAsync (options As PairedNamespaceOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.PairNamespaceAsync : Microsoft.ServiceBus.Messaging.PairedNamespaceOptions -&gt; System.Threading.Tasks.Task" Usage="messagingFactory.PairNamespaceAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
      </Parameters>
      <Docs>
        <param name="options">Die ereignispaarbildung Optionen.</param>
        <summary>Asynchron einen Namespace-Paaren.</summary>
        <returns>Das Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public virtual int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</summary>
        <value>Die Anzahl der Nachrichten, die der Nachrichtenempfänger gleichzeitig anfordern kann.</value>
        <remarks> Wirkt sich auf die nächste Acceptmessagesession-Aufruf an den server </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetConnection">
      <MemberSignature Language="C#" Value="public virtual void ResetConnection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ResetConnection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.ResetConnection" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub ResetConnection ()" />
      <MemberSignature Language="F#" Value="abstract member ResetConnection : unit -&gt; unit&#xA;override this.ResetConnection : unit -&gt; unit" Usage="messagingFactory.ResetConnection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>