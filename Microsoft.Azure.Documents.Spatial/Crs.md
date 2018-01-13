<Type Name="Crs" FullName="Microsoft.Azure.Documents.Spatial.Crs">
  <TypeSignature Language="C#" Value="public abstract class Crs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Crs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Crs" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Crs" />
  <TypeSignature Language="F#" Value="type Crs = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.CrsJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Referenzsystem koordinieren darstellt in der Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Crs (Microsoft.Azure.Documents.Spatial.CrsType type);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.Spatial.CrsType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.#ctor(Microsoft.Azure.Documents.Spatial.CrsType)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (type As CrsType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Crs : Microsoft.Azure.Documents.Spatial.CrsType -&gt; Microsoft.Azure.Documents.Spatial.Crs" Usage="new Microsoft.Azure.Documents.Spatial.Crs type" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Documents.Spatial.CrsType" />
      </Parameters>
      <Docs>
        <param name="type">
            CR-Typ.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.Crs Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Documents.Spatial.Crs Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As Crs" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.Documents.Spatial.Crs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.Crs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die standardmäßigen CRS im Azure-Cosmos-DB-Dienst ab. Standardmäßige CRS wird CRS mit dem Namen "Urn: Ogc:def:crs:OGC:1.3:CRS84" benannt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linked">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.LinkedCrs Linked (string href);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.LinkedCrs Linked(string href) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Linked(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Linked (href As String) As LinkedCrs" />
      <MemberSignature Language="F#" Value="static member Linked : string -&gt; Microsoft.Azure.Documents.Spatial.LinkedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Linked href" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.LinkedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="href" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="href">
            CR-Link.
            </param>
        <summary>
            Erstellt verknüpften CRS im Azure-Cosmos-DB-Dienst an.
            </summary>
        <returns>
            Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linked">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.LinkedCrs Linked (string href, string type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.LinkedCrs Linked(string href, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Linked(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Linked (href As String, type As String) As LinkedCrs" />
      <MemberSignature Language="F#" Value="static member Linked : string * string -&gt; Microsoft.Azure.Documents.Spatial.LinkedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Linked (href, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.LinkedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="href" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="href">
            CR-Link.
            </param>
        <param name="type">
            CRS Linktyp.
            </param>
        <summary>
            Verknüpfte CRS erstellt mit optional in der Azure-Cosmos-DB-Dienst angegebenen Typs.
            </summary>
        <returns>
            Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Named">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.NamedCrs Named (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.NamedCrs Named(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Named(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Named (name As String) As NamedCrs" />
      <MemberSignature Language="F#" Value="static member Named : string -&gt; Microsoft.Azure.Documents.Spatial.NamedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Named name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.NamedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">CR-Name.</param>
        <summary>
            Erstellt benannte CRS mit dem Namen in der Azure-Cosmos-DB-Dienst angegeben.
            </summary>
        <returns>Instanz des <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Klasse.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.CrsType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.Spatial.CrsType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As CrsType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Documents.Spatial.CrsType" Usage="Microsoft.Azure.Documents.Spatial.Crs.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.CrsType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den CRS-Typ in der Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Typ des CRS.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unspecified">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.Crs Unspecified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Documents.Spatial.Crs Unspecified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Unspecified" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Unspecified As Crs" />
      <MemberSignature Language="F#" Value="member this.Unspecified : Microsoft.Azure.Documents.Spatial.Crs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Unspecified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.Crs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "Nicht angegeben" CR im Azure-Cosmos-DB-Dienst. Keine CRS können für Geometrien müssen "nicht angegeben" CR davon ausgegangen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>