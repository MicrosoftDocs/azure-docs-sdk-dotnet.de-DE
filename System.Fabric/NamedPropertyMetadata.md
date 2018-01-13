<Type Name="NamedPropertyMetadata" FullName="System.Fabric.NamedPropertyMetadata">
  <TypeSignature Language="C#" Value="public sealed class NamedPropertyMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamedPropertyMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NamedPropertyMetadata" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamedPropertyMetadata" />
  <TypeSignature Language="F#" Value="type NamedPropertyMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Die zugeordneten Metadaten einer <see cref="T:System.Fabric.NamedProperty" />, einschließlich der Name der Eigenschaft.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomTypeId">
      <MemberSignature Language="C#" Value="public string CustomTypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomTypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.CustomTypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomTypeId As String" />
      <MemberSignature Language="F#" Value="member this.CustomTypeId : string" Usage="System.Fabric.NamedPropertyMetadata.CustomTypeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Id des benutzerdefinierten Typs.</para>
        </summary>
        <value>
          <para>Die Id des benutzerdefinierten Typs.</para>
        </value>
        <remarks>
          <para>Diese Eigenschaft verwenden, ist der Benutzer in der Lage, kennzeichnen den Typ des Werts der Eigenschaft. Im folgenden werden häufige Anwendungsfall für diese Eigenschaft ist. Angenommen Sie, Sie Eigenschaft mit dem Namen der Konfiguration. Der Wert dieser Eigenschaft kann JSON oder XML sein, je nachdem, wer die Eigenschaft zuletzt aktualisiert. In diesem Szenario können die Updater benutzerdefinierten Typ-Id-Eigenschaft Sie um den Typ der Eigenschaft an den Consumer der Eigenschaft zu kommunizieren.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtc">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.LastModifiedUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtc : DateTime" Usage="System.Fabric.NamedPropertyMetadata.LastModifiedUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Eigenschaft zuletzt geändert wurde. Nur Schreibvorgänge führt dazu, dass dieses Feld aktualisiert werden.</para>
        </summary>
        <value>
          <para>Der Zeitpunkt der letzten, an die Eigenschaft geändert wurde, UTC.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Uri Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Parent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As Uri" />
      <MemberSignature Language="F#" Value="member this.Parent : Uri" Usage="System.Fabric.NamedPropertyMetadata.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen des übergeordneten Elements Service Fabric-Namen für die Eigenschaft ab. Sie können als der namespacetabelle betrachtet werden unter dem die Eigenschaft vorhanden ist.</para>
        </summary>
        <value>
          <para>Der Name des übergeordneten Elements Service Fabric-Namen für die Eigenschaft.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyName">
      <MemberSignature Language="C#" Value="public string PropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PropertyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.PropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PropertyName : string" Usage="System.Fabric.NamedPropertyMetadata.PropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen der Eigenschaft ab. Sie können der als Schlüssel für ein Schlüssel-Wert-Paar betrachtet werden.</para>
        </summary>
        <value>
          <para>Der Eigenschaftenname.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="System.Fabric.NamedPropertyMetadata.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Version der Eigenschaft ab. Jedes Mal, wenn eine Eigenschaft geändert wird, wird seine Sequenznummer erhöht.</para>
        </summary>
        <value>
          <para>Die Version der Eigenschaft.</para>
        </value>
        <remarks>
          <para>Sequenznummern werden garantiert werden, um immer zu erhöhen. Allerdings die Erhöhung der monoton möglicherweise nicht.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeId">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId TypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId TypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.TypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeId As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.TypeId : System.Fabric.PropertyTypeId" Usage="System.Fabric.NamedPropertyMetadata.TypeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PropertyTypeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt an, ob der Wert der Eigenschaft eine Binärdatei <see cref="T:System.Int64" />, <see cref="T:System.Double" />, <see cref="T:System.String" /> oder <see cref="T:System.Guid" />. Eine häufige Verwendung dieses Feld ist zum Bestimmen des Typs mit dem <see cref="M:System.Fabric.NamedProperty.GetValue``1" />.</para>
        </summary>
        <value>
          <para>Die Eigenschaftentyp der Eigenschaft.</para>
        </value>
        <remarks>
          <para>Alle Service Fabric-Enumerationen haben einen ungültige reservierten Wert.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValueSize">
      <MemberSignature Language="C#" Value="public int ValueSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ValueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NamedPropertyMetadata.ValueSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValueSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ValueSize : int" Usage="System.Fabric.NamedPropertyMetadata.ValueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt die Länge des Werts der serialisierten an.</para>
        </summary>
        <value>
          <para>Die Länge des Werts der serialisiert werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>