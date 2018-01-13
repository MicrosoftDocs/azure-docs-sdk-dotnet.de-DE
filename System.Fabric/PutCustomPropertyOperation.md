<Type Name="PutCustomPropertyOperation" FullName="System.Fabric.PutCustomPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class PutCustomPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PutCustomPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PutCustomPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PutCustomPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PutCustomPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Die angegebene Eigenschaft unter dem angegebenen Namen darstellt, und legt die benutzerdefinierte Typinformationen für benutzerdefinierte Interpretation des Eigenschaftswerts.</para>
    </summary>
    <remarks>
            Der benutzerdefinierte Typ ist Informationen, die nicht vom Service Fabric verarbeitet, jedoch kann von Benutzer verwendet werden, um die Serialisierung/Deserialisierung von benutzerdefinierten Objekten.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, byte[] value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte(), customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * byte[] * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="customTypeId">
          <para>Der benutzerdefinierte benutzerdefinierten Typs.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und Byte []-Wert, und legt der benutzerdefinierten Typ entsprechend.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, double value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Double,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * double * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="customTypeId">
          <para>Der benutzerdefinierte benutzerdefinierten Typs.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftsnamen, und doppelte Wert und legt der benutzerdefinierten Typ entsprechend.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, Guid value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * Guid * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="customTypeId">
          <para>Der benutzerdefinierte benutzerdefinierten Typs.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und GUID-Wert, und legt der benutzerdefinierten Typ entsprechend.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, long value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.Int64,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * int64 * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="customTypeId">
          <para>Der benutzerdefinierte benutzerdefinierten Typs.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und Int64-Wert, und legt der benutzerdefinierten Typ entsprechend.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutCustomPropertyOperation (string propertyName, string value, string customTypeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value, string customTypeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutCustomPropertyOperation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String, customTypeId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutCustomPropertyOperation : string * string * string -&gt; System.Fabric.PutCustomPropertyOperation" Usage="new System.Fabric.PutCustomPropertyOperation (propertyName, value, customTypeId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="customTypeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <param name="customTypeId">
          <para>Der benutzerdefinierte benutzerdefinierten Typs.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutCustomPropertyOperation" /> -Klasse mit dem angegebenen Eigenschaftennamen und String-Wert, und legt der benutzerdefinierten Typ entsprechend.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomTypeId">
      <MemberSignature Language="C#" Value="public string CustomTypeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomTypeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.CustomTypeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomTypeId As String" />
      <MemberSignature Language="F#" Value="member this.CustomTypeId : string" Usage="System.Fabric.PutCustomPropertyOperation.CustomTypeId" />
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
          <para>Ruft die benutzerdefinierten Informationen ab. Diese Informationen kann von Benutzern serialisieren/Deserialisieren benutzerdefinierten Objekten verwendet werden.</para>
        </summary>
        <value>
          <para>Die benutzerdefinierte Typinformationen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.PutCustomPropertyOperation.PropertyType" />
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
          <para>Ruft den Eigenschaftentyp ab.</para>
        </summary>
        <value>
          <para>Der Eigenschaftentyp.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.PutCustomPropertyOperation.PropertyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Wert der Eigenschaft ab.</para>
        </summary>
        <value>
          <para>Der Eigenschaftswert.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>