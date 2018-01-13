<Type Name="DataType" FullName="Microsoft.Azure.Search.Models.DataType">
  <TypeSignature Language="C#" Value="public sealed class DataType : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.DataType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DataType extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.DataType&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DataType&#xA;Inherits ExtensibleEnum(Of DataType)" />
  <TypeSignature Language="F#" Value="type DataType = class&#xA;    inherit ExtensibleEnum&lt;DataType&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.DataType&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.DataType</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.DataType&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Definiert den Datentyp eines Felds in einem Azure Search-Index.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Boolean">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Boolean;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Boolean" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Boolean" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Boolean As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Boolean : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Boolean" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass ein Feld einen booleschen Wert ("true" oder "false") enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataType Collection (Microsoft.Azure.Search.Models.DataType elementType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataType Collection(class Microsoft.Azure.Search.Models.DataType elementType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.Collection(Microsoft.Azure.Search.Models.DataType)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Collection (elementType As DataType) As DataType" />
      <MemberSignature Language="F#" Value="static member Collection : Microsoft.Azure.Search.Models.DataType -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Collection elementType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="elementType" Type="Microsoft.Azure.Search.Models.DataType" />
      </Parameters>
      <Docs>
        <param name="elementType">Der Datentyp der Elemente der Auflistung.</param>
        <summary>
            Erstellt einen Datentyp für eine Auflistung des angegebenen Typs.
            </summary>
        <returns>Einen neuen Datentyp für eine Sammlung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataType Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataType Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As DataType" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Datentyps.</param>
        <summary>
            Erstellt eine neue Datentypinstanz oder eine vorhandene Instanz zurückgegeben, wenn dem angegebenen Namen, die von einem bekannten-Datentyp übereinstimmt.
            </summary>
        <returns>Ein DataType-Instanz mit dem angegebenen Namen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateTimeOffset">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType DateTimeOffset;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType DateTimeOffset" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.DateTimeOffset" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DateTimeOffset As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable DateTimeOffset : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.DateTimeOffset" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass ein Feld einen Datum/Uhrzeit-Wert, z. B. die Zeitzoneninformationen enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Double">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Double;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Double" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Double" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Double As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Double : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Double" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass ein Feld eine IEEE mit doppelter Genauigkeit Gleitkommazahl enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeographyPoint">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType GeographyPoint;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType GeographyPoint" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.GeographyPoint" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly GeographyPoint As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable GeographyPoint : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.GeographyPoint" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass ein Feld einen geografischen Standort im Hinblick auf Längen- und Breitengrad enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Int32">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Int32;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Int32" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Int32" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Int32 As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Int32 : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Int32" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass ein Feld, eine 32-Bit-Ganzzahl mit Vorzeichen enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Int64">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType Int64;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType Int64" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.Int64" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Int64 As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable Int64 : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.Int64" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass ein Feld, eine 64-Bit-Ganzzahl mit Vorzeichen enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.DataType (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.DataType op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataType.op_Implicit(System.String)~Microsoft.Azure.Search.Models.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As DataType" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">zu konvertierende Zeichenfolge.</param>
        <summary>
            Definiert die implizite Konvertierung von Zeichenfolgen in Datentyp.
            </summary>
        <returns>Die Zeichenfolge als einen Datentyp aufweisen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="String">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.DataType String;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.DataType String" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.DataType.String" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly String As DataType " />
      <MemberSignature Language="F#" Value=" staticval mutable String : Microsoft.Azure.Search.Models.DataType" Usage="Microsoft.Azure.Search.Models.DataType.String" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, dass ein Feld eine Zeichenfolge enthält.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>