<Type Name="TableHttpWebRequestFactory" FullName="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class TableHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class TableHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type TableHttpWebRequestFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="da7d6-101">Eine Factoryklasse zum Erstellen einer webanforderung zum Verwalten von Tabellen in der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="da7d6-101">A factory class for constructing a web request to manage tables in the Table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="da7d6-102">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-102">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="da7d6-103">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-103">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="da7d6-104">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="da7d6-104">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="da7d6-105">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-105">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-106">Erstellt eine webanforderung, die ACL für eine Tabelle zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="da7d6-106">Constructs a web request to return the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="da7d6-107">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-107">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetAcl (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="da7d6-108">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-108">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="da7d6-109">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-109">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="da7d6-110">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="da7d6-110">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="da7d6-111">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="da7d6-111">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="da7d6-112">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-112">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-113">Erstellt eine webanforderung, die ACL für eine Tabelle zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="da7d6-113">Constructs a web request to return the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="da7d6-114">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-114">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="da7d6-115">Ein <see cref="T:System.Uri" /> , das den tabellendienstendpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-115">A <see cref="T:System.Uri" /> specifying the Table service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="da7d6-116">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-116">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="da7d6-117">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="da7d6-117">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="da7d6-118">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-118">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-119">Erstellt eine webanforderung zum Abrufen der Eigenschaften des tabellendiensts.</span><span class="sxs-lookup"><span data-stu-id="da7d6-119">Creates a web request to get the properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="da7d6-120">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-120">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="da7d6-121">Ein <see cref="T:System.Uri" /> , das den tabellendienstendpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-121">A <see cref="T:System.Uri" /> specifying the Table service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="da7d6-122">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-122">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="da7d6-123">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="da7d6-123">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="da7d6-124">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-124">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-125">Erstellt eine webanforderung an die Statistiken des tabellendiensts abrufen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-125">Creates a web request to get the stats of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="da7d6-126">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-126">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="da7d6-127">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-127">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="da7d6-128">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-128">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="da7d6-129">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="da7d6-129">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="da7d6-130">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-130">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-131">Erstellt eine webanforderung an die ACL für eine Tabelle festgelegt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-131">Constructs a web request to set the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="da7d6-132">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-132">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetAcl (uri, builder, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="da7d6-133">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-133">A <see cref="T:System.Uri" /> specifying the absolute URI for the table.</span></span></param>
        <param name="builder"><span data-ttu-id="da7d6-134">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-134">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="da7d6-135">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</span><span class="sxs-lookup"><span data-stu-id="da7d6-135">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="da7d6-136">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="da7d6-136">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="da7d6-137">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-137">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-138">Erstellt eine webanforderung an die ACL für eine Tabelle festgelegt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-138">Constructs a web request to set the ACL for a table.</span></span>
            </summary>
        <returns><span data-ttu-id="da7d6-139">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-139">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.Azure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.Azure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.Azure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.Azure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.Azure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.Azure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="da7d6-140">Ein <see cref="T:System.Uri" /> , das den tabellendienstendpunkt angibt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-140">A <see cref="T:System.Uri" /> specifying the Table service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="da7d6-141">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="da7d6-141">A <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="da7d6-142">Das Servertimeout-Intervall, in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="da7d6-142">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="da7d6-143">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-143">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-144">Erstellt eine webanforderung zum Festlegen der Eigenschaften des tabellendiensts.</span><span class="sxs-lookup"><span data-stu-id="da7d6-144">Creates a web request to set the properties of the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="da7d6-145">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="da7d6-145">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.WriteServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.Azure.CosmosDB.Table.Protocol.TableHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="da7d6-146">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> Objekt, das die Diensteigenschaften für das Formatieren und Schreiben in den Stream enthält.</span><span class="sxs-lookup"><span data-stu-id="da7d6-146">A <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> object containing the service properties to format and write to the stream.</span></span></param>
        <param name="outputStream"><span data-ttu-id="da7d6-147">Die <see cref="T:System.IO.Stream" /> auf das sind die formatierte Eigenschaften geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="da7d6-147">The <see cref="T:System.IO.Stream" /> object to which the formatted properties are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="da7d6-148">Schreibt tabellendiensteigenschaften in einen Stream, in XML formatiert.</span><span class="sxs-lookup"><span data-stu-id="da7d6-148">Writes Table service properties to a stream, formatted in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>