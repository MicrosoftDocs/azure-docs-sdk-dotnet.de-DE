<Type Name="CheckValuePropertyOperation" FullName="System.Fabric.CheckValuePropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class CheckValuePropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CheckValuePropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CheckValuePropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CheckValuePropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type CheckValuePropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
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
      <para>Stellt eine <see cref="T:System.Fabric.PropertyBatchOperation" /> , vergleicht den Wert der Eigenschaft mit dem erwarteten Wert.  </para>
    </summary>
    <remarks>
      <para>Der Vergleich schlägt fehl, wenn der Wert der Eigenschaft und dem erwarteten Wert nicht gleich sind. Die <see cref="T:System.Fabric.CheckValuePropertyOperation" /> wird im Allgemeinen als Voraussetzung für die Write-Vorgänge im Batch verwendet. Beachten Sie, dass, wenn mindestens eine <see cref="T:System.Fabric.PropertyBatchOperation" /> ein Fehler auftritt, der gesamte Batch schlägt fehl, und kann nicht übertragen werden.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * byte[] -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
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
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Byte" />[]-Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Double)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * double -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
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
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Double" /> Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * Guid -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
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
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Guid" /> Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As Long)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * int64 -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
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
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.Int64" /> Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckValuePropertyOperation (string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckValuePropertyOperation.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, value As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckValuePropertyOperation : string * string -&gt; System.Fabric.CheckValuePropertyOperation" Usage="new System.Fabric.CheckValuePropertyOperation (propertyName, value)" />
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
          <para>Der Name der Eigenschaft.</para>
        </param>
        <param name="value">
          <para>Der Wert der Eigenschaft.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.CheckValuePropertyOperation" /> -Klasse mit angegebenen <paramref name="propertyName" /> und <see cref="T:System.String" /> Wert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyType">
      <MemberSignature Language="C#" Value="public System.Fabric.PropertyTypeId PropertyType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PropertyTypeId PropertyType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckValuePropertyOperation.PropertyType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyType As PropertyTypeId" />
      <MemberSignature Language="F#" Value="member this.PropertyType : System.Fabric.PropertyTypeId" Usage="System.Fabric.CheckValuePropertyOperation.PropertyType" />
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
          <para>Ruft den Typ der Eigenschaft ab.</para>
        </summary>
        <value>
          <para>Der Typ der Eigenschaft.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyValue">
      <MemberSignature Language="C#" Value="public object PropertyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object PropertyValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckValuePropertyOperation.PropertyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyValue As Object" />
      <MemberSignature Language="F#" Value="member this.PropertyValue : obj" Usage="System.Fabric.CheckValuePropertyOperation.PropertyValue" />
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
          <para>Der Wert der Eigenschaft.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>