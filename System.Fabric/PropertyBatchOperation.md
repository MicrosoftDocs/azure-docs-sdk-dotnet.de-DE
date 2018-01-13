<Type Name="PropertyBatchOperation" FullName="System.Fabric.PropertyBatchOperation">
  <TypeSignature Language="C#" Value="public abstract class PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PropertyBatchOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PropertyBatchOperation = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckExistsPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckSequencePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.CheckValuePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.DeletePropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.GetPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.PutCustomPropertyOperation))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.PutPropertyOperation))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Stellt die Basisklasse für die Eigenschaft-Vorgänge, die in einem Batch abgelegt werden können, und übermittelt werden, über die <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" /> Methode.</para>
    </summary>
    <remarks>
      <para>Beachten Sie, dass, wenn ein <see cref="T:System.Fabric.PropertyBatchOperation" /> Objekt ein Fehler auftritt, wird der gesamte Batch schlägt fehl, und kann nicht übertragen werden.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PropertyBatchOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz des <see cref="T:System.Fabric.PropertyBatchOperation" />-Objekts.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PropertyBatchOperation (string propertyName, System.Fabric.PropertyBatchOperationKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Fabric.PropertyBatchOperationKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PropertyBatchOperation.#ctor(System.String,System.Fabric.PropertyBatchOperationKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (propertyName As String, kind As PropertyBatchOperationKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PropertyBatchOperation : string * System.Fabric.PropertyBatchOperationKind -&gt; System.Fabric.PropertyBatchOperation" Usage="new System.Fabric.PropertyBatchOperation (propertyName, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="kind" Type="System.Fabric.PropertyBatchOperationKind" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Der Zeichenfolgenname der Eigenschaft.</para>
        </param>
        <param name="kind">
          <para>
            <see cref="T:System.Fabric.PropertyBatchOperationKind" />definiert die Art von der <see cref="T:System.Fabric.PropertyBatchOperation" />.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PropertyBatchOperation" /> Objekt mit dem angegebenen Eigenschaftennamen und die Art.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyBatchOperationKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyBatchOperationKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchOperation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As PropertyBatchOperationKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.PropertyBatchOperationKind" Usage="System.Fabric.PropertyBatchOperation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PropertyBatchOperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.PropertyBatchOperationKind" /> , die gibt die Art von der <see cref="T:System.Fabric.PropertyBatchOperation" />.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.PropertyBatchOperationKind" />zurück.</para>
        </value>
        <remarks>
          <para>Alle Service Fabric-Enumerationen haben ein reserviertes Feld "Ungültig".</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyName">
      <MemberSignature Language="C#" Value="public string PropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PropertyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PropertyBatchOperation.PropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PropertyName : string" Usage="System.Fabric.PropertyBatchOperation.PropertyName" />
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
          <para>Gibt den Namen der Eigenschaft, die von diesem <see cref="T:System.Fabric.PropertyBatchOperation" /> zugreift.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.String" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>