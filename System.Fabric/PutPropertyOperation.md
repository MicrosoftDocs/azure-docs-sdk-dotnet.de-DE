<Type Name="PutPropertyOperation" FullName="System.Fabric.PutPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class PutPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PutPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PutPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PutPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type PutPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
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
      <para>Setzt die angegebene Eigenschaft unter dem angegebenen Namen.</para>
    </summary>
    <remarks>
      <para>Beachten Sie, dass, wenn mindestens eine <see cref="T:System.Fabric.PropertyBatchOperation" /> ein Fehler auftritt, der gesamte Batch schlägt fehl und wird nicht ausgeführt.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * byte[] -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Ein <see cref="T:System.String" /> , der den Namen der Eigenschaft definiert.</para>
        </param>
        <param name="value">
          <para>Ein <see cref="T:System.Byte" /> Array, das der Wert für die Eigenschaft definiert.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutPropertyOperation" /> Klasse mit dem angegebenen Namen und Byte []-Eigenschaftswert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * double -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Ein <see cref="T:System.String" /> , der den Namen der Eigenschaft definiert.</para>
        </param>
        <param name="value">
          <para>Ein <see cref="T:System.Double" /> , der den Wert für die Eigenschaft definiert.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und die double-Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * Guid -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Ein <see cref="T:System.String" /> , der den Namen der Eigenschaft definiert.</para>
        </param>
        <param name="value">
          <para>Ein <see cref="T:System.Guid" /> , der den Wert für die Eigenschaft definiert.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und den GUID-Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * int64 -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Ein <see cref="T:System.String" /> , der den Namen der Eigenschaft definiert.</para>
        </param>
        <param name="value">
          <para>Ein <see cref="T:System.Int64" /> , der den Wert für die Eigenschaft definiert.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutPropertyOperation" /> Klasse mit dem angegebenen Eigenschaftennamen und Int64-Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutPropertyOperation (string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PutPropertyOperation.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PutPropertyOperation : string * string -&gt; System.Fabric.PutPropertyOperation" Usage="new System.Fabric.PutPropertyOperation (propertyName, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para>Ein <see cref="T:System.String" /> , der den Namen der Eigenschaft definiert.</para>
        </param>
        <param name="value">
          <para>Ein <see cref="T:System.String" /> , der den Wert für die Eigenschaft definiert.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.PutPropertyOperation" /> Klasse mit dem angegebenen Namen und der Eigenschaftswert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutPropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.PutPropertyOperation.PropertyType" />
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
          <para>Gibt <see cref="T:System.Fabric.PropertyTypeId" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PutPropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.PutPropertyOperation.PropertyValue" />
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
          <para>Gibt <see cref="T:System.Object" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>