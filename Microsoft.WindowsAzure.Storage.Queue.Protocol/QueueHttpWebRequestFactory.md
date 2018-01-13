<Type Name="QueueHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class QueueHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type QueueHttpWebRequestFactory = class" />
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
            Eine Factoryklasse zum Erstellen einer webanforderung zum Verwalten von Warteschlangen im Warteschlangendienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, operationContext)" />
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
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="timeToLiveInSeconds">Die Meldung, die Time-to-live, in Sekunden.</param>
        <param name="visibilityTimeoutInSeconds">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Hinzufügen einer Nachricht für eine Warteschlange.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
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
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="timeToLiveInSeconds">Die Meldung, die Time-to-live, in Sekunden.</param>
        <param name="visibilityTimeoutInSeconds">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Hinzufügen einer Nachricht für eine Warteschlange.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Löschen alle Nachrichten in der Warteschlange an.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Löschen alle Nachrichten in der Warteschlange an.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Erstellen einer neuen Warteschlange an.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Erstellen einer neuen Warteschlange an.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die Warteschlange und alle darin enthaltenen Nachrichten löschen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die Warteschlange und alle darin enthaltenen Nachrichten löschen.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="popReceipt">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung um eine Nachricht zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, useVersionHeader, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="popReceipt">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung um eine Nachricht zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung, die ACL für eine Warteschlange zurückgeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung, die ACL für eine Warteschlange zurückgeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="numberOfMessages">Eine ganze Zahl, die die Anzahl der abzurufenden Nachrichten angeben.</param>
        <param name="visibilityTimeout">Ein <see cref="T:System.TimeSpan" /> Wert, der das sichtbarkeitstimeout angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Abrufen von Nachrichten aus einer Warteschlange.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="numberOfMessages">Eine ganze Zahl, die die Anzahl der abzurufenden Nachrichten angeben.</param>
        <param name="visibilityTimeout">Ein <see cref="T:System.TimeSpan" /> Wert, der das sichtbarkeitstimeout angibt.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Abrufen von Nachrichten aus einer Warteschlange.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung, die benutzerdefinierten Metadaten für diese Warteschlange zurückgegeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung, die benutzerdefinierten Metadaten für diese Warteschlange zurückgegeben.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</param>
        <param name="builder">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Abrufen der Eigenschaften des warteschlangendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
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
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</param>
        <param name="builder">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Abrufen von Statistiken zum Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, operationContext)" />
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
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="listingContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</param>
        <param name="detailsIncluded">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumerationswert ab, der angibt, ob warteschlangenmetadaten mit der Auflistung zurück.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an eine Liste aller Warteschlangen, die in diesem Speicherkonto zurück.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
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
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="listingContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />-Objekt.</param>
        <param name="detailsIncluded">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumerationswert ab, der angibt, ob warteschlangenmetadaten mit der Auflistung zurück.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an eine Liste aller Warteschlangen, die in diesem Speicherkonto zurück.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="numberOfMessages">Eine ganze Zahl Festlegen der Anzahl von Nachrichten einsehen.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Einsehen von Nachrichten aus einer Warteschlange.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, useVersionHeader, operationContext)" />
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
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="numberOfMessages">Eine ganze Zahl Festlegen der Anzahl von Nachrichten einsehen.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Einsehen von Nachrichten aus einer Warteschlange.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die ACL für eine Warteschlange festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung an die ACL für eine Warteschlange festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung benutzerdefinierte Metadaten für die Warteschlange festgelegt werden.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zur Warteschlange angibt.</param>
        <param name="timeout">Eine ganze Zahl, die das Servertimeout-Intervall angeben.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Generiert eine webanforderung benutzerdefinierte Metadaten für die Warteschlange festgelegt werden.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> den Warteschlangendienst-Endpunkt angeben.</param>
        <param name="builder">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> Objekt angeben zusätzlicher Parameter an die URI-Abfragezeichenfolge hinzufügen.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung zum Festlegen der Eigenschaften des warteschlangendiensts an.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="popReceipt">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</param>
        <param name="visibilityTimeoutInSeconds">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung um eine Nachricht zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
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
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri">Ein <see cref="T:System.Uri" /> , den absoluten URI auf die zu aktualisierende Nachricht angibt.</param>
        <param name="timeout">Das Servertimeout-Intervall, in Sekunden.</param>
        <param name="popReceipt">Eine Zeichenfolge, die abrufbestätigung der Nachricht angeben.</param>
        <param name="visibilityTimeoutInSeconds">Die Zeitdauer, die Nachricht in Sekunden nicht sichtbar sein soll.</param>
        <param name="useVersionHeader">Ein boolescher Wert, der angibt, gibt an, ob die <i>X-ms-Version</i> HTTP-Header.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine webanforderung um eine Nachricht zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Net.HttpWebRequest" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="outputStream">Die <see cref="T:System.IO.Stream" /> auf das sind die formatierte Eigenschaften geschrieben werden.</param>
        <summary>
            Schreibt warteschlangendiensteigenschaften in einen Stream, in XML formatiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>