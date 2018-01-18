<Type Name="SasQueryBuilder" FullName="Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder">
  <TypeSignature Language="C#" Value="public class SasQueryBuilder : Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SasQueryBuilder extends Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class SasQueryBuilder&#xA;Inherits UriQueryBuilder" />
  <TypeSignature Language="F#" Value="type SasQueryBuilder = class&#xA;    inherit UriQueryBuilder" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ef4e3-101">Eine Vereinfachung-Klasse zum Erstellen von SAS-spezifische URI-Abfrage-Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-101">A convenience class for constructing SAS-specific URI query strings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasQueryBuilder (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sasToken As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder : string -&gt; Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder" Usage="new Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder sasToken" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken"><span data-ttu-id="ef4e3-102">Der ASA-Token verwendet, um die Anforderung zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-102">The ASA token used to authenticate request.</span></span></param>
        <summary>
            <span data-ttu-id="ef4e3-103">Öffentliche SasQueryBuilder-Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-103">Public SasQueryBuilder constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public override void Add (string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Add(string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.Add(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Add (name As String, value As String)" />
      <MemberSignature Language="F#" Value="override this.Add : string * string -&gt; unit" Usage="sasQueryBuilder.Add (name, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ef4e3-104">Der Zeichenfolgenname der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-104">The query string name.</span></span></param>
        <param name="value"><span data-ttu-id="ef4e3-105">Der Wert der Abfragezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-105">The query string value.</span></span></param>
        <summary>
            <span data-ttu-id="ef4e3-106">Fügen Sie den Wert der Abfragezeichenfolge mit URI Escapezeichen hinzu.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-106">Add the query string value with URI escaping.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddToUri">
      <MemberSignature Language="C#" Value="public override Uri AddToUri (Uri uri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Uri AddToUri(class System.Uri uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.AddToUri(System.Uri)" />
      <MemberSignature Language="F#" Value="override this.AddToUri : Uri -&gt; Uri" Usage="sasQueryBuilder.AddToUri uri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="ef4e3-107">Ein <see cref="T:System.Uri" /> Objekt, das den ursprünglichen URI einschließlich vorhandene Abfrageparameter enthält.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-107">A <see cref="T:System.Uri" /> object containing the original URI, including any existing query parameters.</span></span></param>
        <summary>
            <span data-ttu-id="ef4e3-108">Fügt einen Abfrageparameter an einen URI an.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-108">Adds a query parameter to a URI.</span></span>
            </summary>
        <returns><span data-ttu-id="ef4e3-109">Ein <see cref="T:System.Uri" /> Objekt mit dem neuen Abfrageparameter angefügt.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-109">A <see cref="T:System.Uri" /> object with the new query parameter appended.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireHttps">
      <MemberSignature Language="C#" Value="public bool RequireHttps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequireHttps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.RequireHttps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequireHttps As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequireHttps : bool" Usage="Microsoft.WindowsAzure.Storage.Core.SasQueryBuilder.RequireHttps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ef4e3-110">Gibt True zurück, wenn einer der Parameter angibt, dass Https:.</span><span class="sxs-lookup"><span data-stu-id="ef4e3-110">Returns True if any of the parameters specifies https:.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>