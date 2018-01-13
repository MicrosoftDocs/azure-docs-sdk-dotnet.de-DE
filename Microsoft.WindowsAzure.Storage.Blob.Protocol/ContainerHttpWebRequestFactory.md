<Type Name="ContainerHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class ContainerHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ContainerHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type ContainerHttpWebRequestFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Factoryklasse zum Erstellen einer webanforderung zum Verwalten von Containern im Blob-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="request">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</param>
        <param name="metadata">Ein <see cref="T:System.Collections.Generic.Dictionary`2" /> Objekt, das die benutzerdefinierten Metadaten enthält.</param>
        <summary>
            Fügt benutzerdefinierte Metadaten für die Anforderung als ein oder mehrere Name-Wert-Paare hinzu.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request">Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</param>
        <param name="name">Eine Zeichenfolge, enthält der Name der Metadaten.</param>
        <param name="value">Eine Zeichenfolge, die den Metadatenwert enthält.</param>
        <summary>
            Fügt benutzerdefinierte Metadaten für die Anforderung als ein einzelnes Name-Wert-Paar hinzu.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an einen neuen Container erstellen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext,Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, operationContext, accessType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="accessType">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und die Ebene des Zugriffs.</param>
        <summary>
            Erstellt eine webanforderung an einen neuen Container erstellen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an einen neuen Container erstellen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType accessType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext,Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext, accessType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="accessType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="accessType">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" /> Objekt, das angibt, ob die Daten im Container öffentlich zugegriffen werden können und die Ebene des Zugriffs.</param>
        <summary>
            Erstellt eine webanforderung an einen neuen Container erstellen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete (uri, timeout, accessCondition, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an den Container und alle darin enthaltenen Blobs zu löschen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an den Container und alle darin enthaltenen Blobs zu löschen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl (uri, timeout, accessCondition, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung, die ACL für einen Container zurückgeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetAcl (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung, die ACL für einen Container zurückgeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung an die benutzerdefinierten Metadaten für diesen Container zurückzugeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung an die benutzerdefinierten Metadaten für diesen Container zurückzugeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung zum Zurückgeben von Eigenschaften und benutzerdefinierte Metadaten für diesen Container.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung zum Zurückgeben von Eigenschaften und benutzerdefinierte Metadaten für diesen Container.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="action">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> -Enumerationswert, der angibt, der Lease auszuführende Aktion.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die Angabe der Lease-ID zum vorschlagen, die für das Ergebnis einer abrufen oder Ändern der Vorgang, oder <c>null</c> , wenn keine ID für den Abrufvorgang vorgeschlagen wird. Dieser Parameter muss <c>null</c> für erneuern, Freigabe und Break-Vorgänge.</param>
        <param name="leaseDuration">Die Leasedauer in Sekunden, erwerben Sie für Vorgänge.
            Wenn dies-1 ist, wird eine unbegrenzte Dauer angegeben. Dies dürfte <c>null</c> für verlängern, ändern, freigeben und Vorgänge unterbrochen.</param>
        <param name="leaseBreakPeriod">Die Menge der Wartezeit in Sekunden, nach einem Vorgang unterbrechen, bevor die Lease unterbrochen wird, werden soll.
            Ist dies <c>null</c> und dann die Standardzeit verwendet wird. Dies dürfte <c>null</c> für abrufen, erneuern, ändern und Freigeben von Vorgängen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung zum Abrufen, verlängern, ändern, freigeben oder Unterbrechen der Leases für den Container.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="action">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> -Enumerationswert, der angibt, der Lease auszuführende Aktion.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die Angabe der Lease-ID zum vorschlagen, die für das Ergebnis einer abrufen oder Ändern der Vorgang, oder <c>null</c> , wenn keine ID für den Abrufvorgang vorgeschlagen wird. Dieser Parameter muss <c>null</c> für erneuern, Freigabe und Break-Vorgänge.</param>
        <param name="leaseDuration">Die Leasedauer in Sekunden, erwerben Sie für Vorgänge.
            Wenn dies-1 ist, wird eine unbegrenzte Dauer angegeben. Dies dürfte <c>null</c> für verlängern, ändern, freigeben und Vorgänge unterbrochen.</param>
        <param name="leaseBreakPeriod">Die Menge der Wartezeit in Sekunden, nach einem Vorgang unterbrechen, bevor die Lease unterbrochen wird, werden soll.
            Ist dies <c>null</c> und dann die Standardzeit verwendet wird. Dies dürfte <c>null</c> für abrufen, erneuern, ändern und Freigeben von Vorgängen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung zum Abrufen, verlängern, ändern, freigeben oder Unterbrechen der Leases für den Container.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , den Blob-Dienstendpunkt angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="listingContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</param>
        <param name="detailsIncluded">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> -Enumerationswert ab, der angibt, ob die Metadaten des Containers mit der Auflistung zurück.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die in diesem Speicherkonto gibt eine Liste aller Container zurück.
            </summary>
        <returns>Eine webanforderung für den angegebenen Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , den Blob-Dienstendpunkt angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="listingContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</param>
        <param name="detailsIncluded">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ContainerListingDetails" /> -Enumerationswert ab, der angibt, ob die Metadaten des Containers mit der Auflistung zurück.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die in diesem Speicherkonto gibt eine Liste aller Container zurück.
            </summary>
        <returns>Eine webanforderung für den angegebenen Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobs">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListBlobs (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListBlobs(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListBlobs : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs (uri, timeout, listingContext, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="listingContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung um eine Liste aller Blobs im Container zurück.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBlobs">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListBlobs (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListBlobs(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext listingContext, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListBlobs : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.ListBlobs (uri, timeout, listingContext, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="listingContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung um eine Liste aller Blobs im Container zurück.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl (uri, timeout, publicAccess, accessCondition, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="publicAccess" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="publicAccess">Der Typ des öffentlichen Zugriff auf den Container zu ermöglichen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die ACL für einen Container festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType publicAccess, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetAcl (uri, timeout, publicAccess, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="publicAccess" Type="Microsoft.WindowsAzure.Storage.Blob.BlobContainerPublicAccessType" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="publicAccess">Der Typ des öffentlichen Zugriff auf den Container zu ermöglichen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die ACL für einen Container festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung benutzerdefinierte Metadaten für den Container festlegen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ContainerHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den absoluten URI zum Container angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung benutzerdefinierte Metadaten für den Container festlegen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>