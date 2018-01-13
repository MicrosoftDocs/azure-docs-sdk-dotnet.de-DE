<Type Name="ConditionalValue&lt;TValue&gt;" FullName="Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;">
  <TypeSignature Language="C#" Value="public struct ConditionalValue&lt;TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit ConditionalValue`1&lt;TValue&gt; extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" />
  <TypeSignature Language="VB.NET" Value="Public Structure ConditionalValue(Of TValue)" />
  <TypeSignature Language="F#" Value="type ConditionalValue&lt;'Value&gt; = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TValue">Der Typ des von dieser zurückgegebene Wert <cref name="ConditionalValue{TValue}" />.</typeparam>
    <summary>
            Ergebnis-Klasse zurückgegebene zuverlässige Sammlungen-APIs, die möglicherweise möglicherweise keinen Wert zurück.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConditionalValue (bool hasValue, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool hasValue, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ConditionalValue`1.#ctor(System.Boolean,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hasValue As Boolean, value As TValue)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt; : bool * 'Value -&gt; Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt; (hasValue, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hasValue" Type="System.Boolean" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="hasValue">Gibt an, ob der Wert gültig ist.</param>
        <param name="value">Der Wert.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <cref name="ConditionalValue{TValue}" /> Klasse mit dem angegebenen Wert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasValue">
      <MemberSignature Language="C#" Value="public bool HasValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ConditionalValue`1.HasValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasValue As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasValue : bool" Usage="Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;.HasValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert ab, der angibt, ob das aktuelle <cref name="ConditionalValue{TValue}" />-Objekt einen gültigen Wert des zugrunde liegenden Typs hat.
            </summary>
        <value>
          <languageKeyword>"true"</languageKeyword>: Wert ist gültig, <languageKeyword>"false"</languageKeyword> andernfalls.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public TValue Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ConditionalValue`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As TValue" />
      <MemberSignature Language="F#" Value="member this.Value : 'Value" Usage="Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Wert des aktuellen <cref name="ConditionalValue{TValue}" />-Objekts ab, wenn ihm ein gültiger zugrunde liegender Wert zugewiesen wurde.
            </summary>
        <value>Der Wert des Objekts. Wenn HasValue ist <languageKeyword>"false"</languageKeyword>, der Standardwert für den Typ des Parameters TValue zurückgegeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>