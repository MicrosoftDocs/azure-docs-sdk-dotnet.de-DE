<Type Name="MessagingFactorySettings" FullName="Microsoft.ServiceBus.Messaging.MessagingFactorySettings">
  <TypeSignature Language="C#" Value="public class MessagingFactorySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessagingFactorySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MessagingFactorySettings" />
  <TypeSignature Language="F#" Value="type MessagingFactorySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die messaging Factory-Einstellungen.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingFactorySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessagingFactorySettings (Microsoft.ServiceBus.Messaging.MessagingFactorySettings other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.MessagingFactorySettings other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.#ctor(Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As MessagingFactorySettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.MessagingFactorySettings : Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="new Microsoft.ServiceBus.Messaging.MessagingFactorySettings other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="other">Die angegebene messaging Factory-Einstellungen.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> Klasse mit den angegebenen messaging Factory-Einstellungen für das Klonen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AmqpTransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings AmqpTransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings AmqpTransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.AmqpTransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AmqpTransportSettings As AmqpTransportSettings" />
      <MemberSignature Language="F#" Value="member this.AmqpTransportSettings : Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.AmqpTransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legen Sie für den Transport für das Advanced Message Queuing Protocol (AMQP).</summary>
        <value>Die transporteinstellungen für das Advanced Message Queuing Protocol (AMQP).</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public virtual Microsoft.ServiceBus.Messaging.MessagingFactorySettings Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessagingFactorySettings Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Clone () As MessagingFactorySettings" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings&#xA;override this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="messagingFactorySettings.Clone " />
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
        <summary>Erstellt eine Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</summary>
        <returns>Eine erstellte Kopie des <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableEntityLevelPerformanceCounters">
      <MemberSignature Language="C#" Value="public bool DisableEntityLevelPerformanceCounters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.DisableEntityLevelPerformanceCounters" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableEntityLevelPerformanceCounters As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableEntityLevelPerformanceCounters : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.DisableEntityLevelPerformanceCounters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert anzugeben, ob die Entität auf Leistungsindikatoren im Arbeitsspeicher gesammelt werden sollen. Beachten Sie, dass dies nur Einfluss auf die Entität auf Leistungsindikatoren und Namespace-Ebene Leistungsindikatoren werden immer gesammelt.
            </summary>
        <value>To be added.</value>
        <remarks>Dies ist standardmäßig auf "false" festgelegt: Standardmäßig bedeutet wir Entität Ebene Leistungsindikatoren sammeln. Das Festlegen dieses Werts wirkt sich nicht auf vorhandene erfassten Leistungsindikatoren und hält sich nur auf neue Entität erfassten Leistungsindikatoren.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAdditionalClientTimeout">
      <MemberSignature Language="C#" Value="public bool EnableAdditionalClientTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableAdditionalClientTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.EnableAdditionalClientTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAdditionalClientTimeout As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableAdditionalClientTimeout : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.EnableAdditionalClientTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die messaging-Vorgang zusätzliche ClientTimeout ermöglicht.</summary>
        <value>"true", wenn der messaging-Vorgang zusätzliche ClientTimeout aktiviert; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetMessagingTransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings NetMessagingTransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings NetMessagingTransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.NetMessagingTransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property NetMessagingTransportSettings As NetMessagingTransportSettings" />
      <MemberSignature Language="F#" Value="member this.NetMessagingTransportSettings : Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.NetMessagingTransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder festlegen die transporteinstellungen für die net-messaging erforderlich.</summary>
        <value>Die transporteinstellungen für die net-messaging erforderlich.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateFactory">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateFactory (System.Collections.Generic.IEnumerable&lt;Uri&gt; uriAddresses, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateFactory(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; uriAddresses, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OnBeginCreateFactory(System.Collections.Generic.IEnumerable{System.Uri},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnBeginCreateFactory (uriAddresses As IEnumerable(Of Uri), callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateFactory : seq&lt;Uri&gt; * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateFactory : seq&lt;Uri&gt; * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactorySettings.OnBeginCreateFactory (uriAddresses, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uriAddresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="uriAddresses">Die Auflistung der uniform Resource Identifier.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</param>
        <summary>Führt den asynchronen Begin Factory Aktion zu erstellen.</summary>
        <returns>Eine <see cref="T:System.IAsyncResult" /> , die auf die asynchrone Anforderung zum Erstellen der Factory verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateFactory">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateFactory (Uri uri, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateFactory(class System.Uri uri, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OnBeginCreateFactory(System.Uri,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateFactory : Uri * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateFactory : Uri * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactorySettings.OnBeginCreateFactory (uri, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="uri">Der uniform Resource Identifier.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Informationen zu den Empfangsvorgang enthält.</param>
        <summary>Führt den asynchronen Begin Factory Aktion zu erstellen.</summary>
        <returns>Eine <see cref="T:System.IAsyncResult" /> , die auf die asynchrone Anforderung zum Erstellen der Factory verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateFactory">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessagingFactory OnEndCreateFactory (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessagingFactory OnEndCreateFactory(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OnEndCreateFactory(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnEndCreateFactory (result As IAsyncResult) As MessagingFactory" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateFactory : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory&#xA;override this.OnEndCreateFactory : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="messagingFactorySettings.OnEndCreateFactory result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Eine <see cref="T:System.IAsyncResult" /> , die auf die asynchrone Anforderung zum Erstellen der Factory verweist.</param>
        <summary>Beendet eine asynchrone Anforderung an die Factory zu erstellen.</summary>
        <returns>Die neu erstellte messaging Factory.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die <see cref="T:System.TimeSpan" /> , die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt.</summary>
        <value>Die <see cref="T:System.TimeSpan" /> , die angibt, wie viel Zeit für der messaging-Vorgang bleibt, bevor ein Timeout eintritt. Der Standardwert ist eine Minute.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Ein NULL-Wert wird festgelegt. Angenommen, ein NULL-Werte zulassen <see cref="T:System.TimeSpan" />.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Eine 0 (null) oder ein negativer Wert <see cref="T:System.TimeSpan" /> festgelegt ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TokenProvider TokenProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.ServiceBus.TokenProvider with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert den Tokenanbieter, der die werkseitigen Standardeinstellungen.</summary>
        <value>Der Tokenanbieter für die werkseitigen Standardeinstellungen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TransportType TransportType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.TransportType TransportType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TransportType" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportType As TransportType" />
      <MemberSignature Language="F#" Value="member this.TransportType : Microsoft.ServiceBus.Messaging.TransportType with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactorySettings.TransportType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TransportType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert den Transporttyp messaging.</summary>
        <value>Der messaging-Transporttyp.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>