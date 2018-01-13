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
            Eine Factoryklasse zum Erstellen einer webanforderung zum Verwalten von Tabellen in der Tabelle.
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</param>
        <param name="builder">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung, die ACL für eine Tabelle zurückgeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</param>
        <param name="builder">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung, die ACL für eine Tabelle zurückgeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , das den tabellendienstendpunkt angibt.</param>
        <param name="builder">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Abrufen der Eigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , das den tabellendienstendpunkt angibt.</param>
        <param name="builder">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die Statistiken des tabellendiensts abrufen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</param>
        <param name="builder">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die ACL für eine Tabelle festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI für die Tabelle angibt.</param>
        <param name="builder">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die ACL für eine Tabelle festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , das den tabellendienstendpunkt angibt.</param>
        <param name="builder">Ein <see cref="T:Microsoft.Azure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Festlegen der Eigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
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
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> Objekt, das die Diensteigenschaften für das Formatieren und Schreiben in den Stream enthält.</param>
        <param name="outputStream">Die <see cref="T:System.IO.Stream" /> auf das sind die formatierte Eigenschaften geschrieben werden.</param>
        <summary>
            Schreibt tabellendiensteigenschaften in einen Stream, in XML formatiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>