<Type Name="Property" FullName="Microsoft.Azure.Graphs.Elements.Property">
  <TypeSignature Language="C#" Value="public sealed class Property : IEquatable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Property extends System.Object implements class System.IEquatable`1&lt;class Microsoft.Azure.Graphs.Elements.Property&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.Property" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Property&#xA;Implements IEquatable(Of Property)" />
  <TypeSignature Language="F#" Value="type Property = class&#xA;    interface IEquatable&lt;Property&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.PropertyConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Der Speichercontainer für eine Eigenschaft.
            Unterstützt die Deserialisierung von GraphSON-Format.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Graphs.Elements.Property other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Graphs.Elements.Property other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Property.Equals(Microsoft.Azure.Graphs.Elements.Property)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Property) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Graphs.Elements.Property -&gt; bool" Usage="property.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Graphs.Elements.Property" />
      </Parameters>
      <Docs>
        <param name="other">Ein Objekt, das mit diesem Objekt verglichen werden soll.</param>
        <summary>
            Gibt an, ob das aktuelle Objekt gleich einem anderen Objekt des gleichen Typs ist.
            </summary>
        <returns>
            "true", wenn das aktuelle Objekt gleich dem <paramref name="other" />-Parameter ist, andernfalls "false".
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Property.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string" Usage="Microsoft.Azure.Graphs.Elements.Property.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schlüssel fest.
            </summary>
        <value>
            Der Schlüssel.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Property.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Validate ()" />
      <MemberSignature Language="F#" Value="member this.Validate : unit -&gt; unit" Usage="property.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Diese Instanz wird überprüft.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Eigenschaft, die einen gültigen Schlüssel aufweisen muss.
            oder die Eigenschaft muss einen gültigen Wert aufweisen.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Property.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj" Usage="Microsoft.Azure.Graphs.Elements.Property.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wert fest.
            </summary>
        <value>
            Der Wert.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>