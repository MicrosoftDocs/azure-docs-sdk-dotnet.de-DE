<Type Name="Lease" FullName="Microsoft.ServiceBus.Messaging.Lease">
  <TypeSignature Language="C#" Value="public class Lease" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Lease extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Lease" />
  <TypeSignature Language="VB.NET" Value="Public Class Lease" />
  <TypeSignature Language="F#" Value="type Lease = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Enthält Partitionsinformationen für den Besitz an.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Lease ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.Lease" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Lease (Microsoft.ServiceBus.Messaging.Lease source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Lease source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As Lease)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.Lease : Microsoft.ServiceBus.Messaging.Lease -&gt; Microsoft.ServiceBus.Messaging.Lease" Usage="new Microsoft.ServiceBus.Messaging.Lease source" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.ServiceBus.Messaging.Lease" />
      </Parameters>
      <Docs>
        <param name="source">Das angegebene <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> Instanz, in denen ihre Eigenschaftswerte aus kopiert werden.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.Lease" /> Klasse mit dem angegebenen <see cref="M:Microsoft.ServiceBus.Messaging.Lease.#ctor(Microsoft.ServiceBus.Messaging.Lease)" /> Wert als Verweis.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public long Epoch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public Property Epoch As Long" />
      <MemberSignature Language="F#" Value="member this.Epoch : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder Festlegen des Jahres Epoche die Lease, d. h. ein Wert, den Sie verwenden können, um die neuesten Besitzer einer Partition zwischen konkurrierende Knoten zu bestimmen.</summary>
        <value>Das Jahr Epoche der Lease.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="lease.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Das zu vergleichende Objekt.</param>
        <summary>Bestimmt, ob diese Instanz mit dem angegebenen Objekt identisch ist.</summary>
        <returns>"true", wenn diese Instanz gleich dem angegebenen Objekt ist; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="lease.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt den Hashcode der aktuellen Instanz zurück.</summary>
        <returns>Der Hashcode der aktuellen Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public virtual bool IsExpired ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsExpired() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Lease.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsExpired () As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsExpired : unit -&gt; bool&#xA;override this.IsExpired : unit -&gt; bool" Usage="lease.IsExpired " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Bestimmt, ob die Lease abgelaufen ist.</summary>
        <returns>"true", wenn die Lease abgelaufen ist; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Offset">
      <MemberSignature Language="C#" Value="public string Offset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Offset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />
      <MemberSignature Language="VB.NET" Value="Public Property Offset As String" />
      <MemberSignature Language="F#" Value="member this.Offset : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Offset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den aktuellen Wert für den Offset in den Stream.</summary>
        <value>Der Lease-Offset.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Owner">
      <MemberSignature Language="C#" Value="public string Owner { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Owner" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Owner" />
      <MemberSignature Language="VB.NET" Value="Public Property Owner As String" />
      <MemberSignature Language="F#" Value="member this.Owner : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Owner" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Besitzer der Host für die Partition fest.</summary>
        <value>Der Host Besitzer der Partition.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die ID der Partition, zu der diese Lease gehört.</summary>
        <value>Die Partitions-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die letzte geprüften Sequenznummer im Datenstrom.</summary>
        <value>Gibt <see cref="T:System.Int64" />zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Lease.Token" />
      <MemberSignature Language="VB.NET" Value="Public Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string with get, set" Usage="Microsoft.ServiceBus.Messaging.Lease.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Abrufen oder Festlegen der Lease-Token, das Verwaltung der Parallelität zwischen Hosts. Können Sie dieses Token garantieren einzelnen Zugriff auf alle Ressourcen, die erforderlich sind, indem Sie die <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> Objekt.</summary>
        <value>Die Lease-Token.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>