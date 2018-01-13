<Type Name="EventHubDescription" FullName="Microsoft.ServiceBus.Messaging.EventHubDescription">
  <TypeSignature Language="C#" Value="public sealed class EventHubDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type EventHubDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="EventHubDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt die Metadatenbeschreibung eines Event Hubs.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.EventHubDescription : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="new Microsoft.ServiceBus.Messaging.EventHubDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Event Hubs relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> ab.</summary>
        <value>Die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die genaue Uhrzeit, die Erstellung die Nachricht, ab.</summary>
        <value>Die genaue Uhrzeit der Erstellung der Nachrichteninhalts.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageRetentionInDays">
      <MemberSignature Language="C#" Value="public long MessageRetentionInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageRetentionInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.MessageRetentionInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageRetentionInDays As Long" />
      <MemberSignature Language="F#" Value="member this.MessageRetentionInDays : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.MessageRetentionInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der Tage, die für diese Event Hub aufbewahrt.</summary>
        <value>Die Aufbewahrungsdauer der Daten für das Ereignis in Tagen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public int PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die aktuelle Anzahl von Shards auf dem Event Hub.</summary>
        <value>Gibt die Anzahl der Abonnements für den Event Hub zurück.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der Wert für die Partition negativ ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionIds">
      <MemberSignature Language="C#" Value="public string[] PartitionIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] PartitionIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionIds As String()" />
      <MemberSignature Language="F#" Value="member this.PartitionIds : string[]" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Bezeichner für für Event Hubs erstellten Partitionen ab.</summary>
        <value>Gibt <see cref="T:System.String" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den vollständigen Pfad des Event Hubs.</summary>
        <value>Der Pfad des Event Hubs.</value>
        <remarks>
              Dies ist ein relativer Pfad zu der <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.
            </remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn versucht wird, legen Sie den Wert dieser Eigenschaft ein, wenn die Instanz als schreibgeschützt markiert ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den aktuellen Status des Event Hubs (aktiviert oder deaktiviert) fest.</summary>
        <value>Der aktuelle Status des Event Hubs.</value>
        <remarks>Dieser Status ist nicht aktualisierte Echtzeit abgerufen werden.
            Zum aktuellen Status abrufen, aktualisieren Sie die Beschreibung mit dem <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHub(System.String)" /> Methode</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die genaue Uhrzeit, zu der die Nachricht aktualisiert wurde.</summary>
        <value>Der Zeitpunkt, zu die Nachricht aktualisiert wurde.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Benutzermetadaten.</summary>
        <value>Die Benutzermetadaten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>