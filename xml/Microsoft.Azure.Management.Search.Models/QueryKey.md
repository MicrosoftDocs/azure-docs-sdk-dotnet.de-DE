<Type Name="QueryKey" FullName="Microsoft.Azure.Management.Search.Models.QueryKey">
  <TypeSignature Language="C#" Value="public class QueryKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueryKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.QueryKey" />
  <TypeSignature Language="VB.NET" Value="Public Class QueryKey" />
  <TypeSignature Language="F#" Value="type QueryKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b7633-101">Beschreibt einen API-Schlüssel für einen bestimmten Azure Search-Dienst, der für Abfragevorgänge nur Berechtigungen verfügt.</span><span class="sxs-lookup"><span data-stu-id="b7633-101">Describes an API key for a given Azure Search service that has permissions for query operations only.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueryKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.QueryKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b7633-102">Initialisiert eine neue Instanz der Klasse QueryKey an.</span><span class="sxs-lookup"><span data-stu-id="b7633-102">Initializes a new instance of the QueryKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueryKey (string name = null, string key = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.QueryKey.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional key As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.QueryKey : string * string -&gt; Microsoft.Azure.Management.Search.Models.QueryKey" Usage="new Microsoft.Azure.Management.Search.Models.QueryKey (name, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="b7633-103">Der Name des abfrageschlüssels API; kann leer sein.</span><span class="sxs-lookup"><span data-stu-id="b7633-103">The name of the query API key; may be empty.</span></span></param>
        <param name="key"><span data-ttu-id="b7633-104">Der Wert des Abfrage-API-Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="b7633-104">The value of the query API key.</span></span></param>
        <summary>
            <span data-ttu-id="b7633-105">Initialisiert eine neue Instanz der Klasse QueryKey an.</span><span class="sxs-lookup"><span data-stu-id="b7633-105">Initializes a new instance of the QueryKey class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.QueryKey.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string" Usage="Microsoft.Azure.Management.Search.Models.QueryKey.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7633-106">Ruft den Wert des Abfrage-API-Schlüssels ab.</span><span class="sxs-lookup"><span data-stu-id="b7633-106">Gets the value of the query API key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.QueryKey.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Search.Models.QueryKey.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7633-107">Ruft den Namen des Abfrage-API-Schlüssels ab. kann leer sein.</span><span class="sxs-lookup"><span data-stu-id="b7633-107">Gets the name of the query API key; may be empty.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>