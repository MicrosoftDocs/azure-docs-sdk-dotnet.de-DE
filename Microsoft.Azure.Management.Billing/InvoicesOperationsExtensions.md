<Type Name="InvoicesOperationsExtensions" FullName="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InvoicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InvoicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InvoicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InvoicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für InvoicesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Billing.Models.Invoice Get (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Billing.Models.Invoice Get(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.Get(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInvoicesOperations, invoiceName As String) As Invoice" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Billing.IInvoicesOperations * string -&gt; Microsoft.Azure.Management.Billing.Models.Invoice" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.Get (operations, invoiceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.Invoice</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="invoiceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="invoiceName">
            Der Name einer Ressource Rechnung.
            </param>
        <summary>
            Ruft eine benannte Rechnung-Ressource ab. Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string invoiceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetAsync (operations, invoiceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="invoiceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="invoiceName">
            Der Name einer Ressource Rechnung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine benannte Rechnung-Ressource ab. Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLatest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Billing.Models.Invoice GetLatest (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Billing.Models.Invoice GetLatest(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatest(Microsoft.Azure.Management.Billing.IInvoicesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLatest (operations As IInvoicesOperations) As Invoice" />
      <MemberSignature Language="F#" Value="static member GetLatest : Microsoft.Azure.Management.Billing.IInvoicesOperations -&gt; Microsoft.Azure.Management.Billing.Models.Invoice" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatest operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Billing.Models.Invoice</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Ruft die letzten Rechnung ab. Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLatestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetLatestAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; GetLatestAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatestAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetLatestAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.GetLatestAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;GetLatestAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die letzten Rechnung ab. Beim Abrufen einer einzelnen Rechnung ist die Eigenschaft DownloadUrl automatisch erweitert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; List (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; List(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.List(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IInvoicesOperations, Optional expand As String = null, Optional filter As String = null, Optional skiptoken As String = null, Optional top As Nullable(Of Integer) = null) As IPage(Of Invoice)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.List (operations, expand, filter, skiptoken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="expand">
            Kann verwendet werden, um die DownloadUrl-Eigenschaft in einer Liste von Rechnungen zu erweitern.
            Dies ermöglicht Downloadlinks gleichzeitig für mehrere Rechnungen generiert werden.
            Standardmäßig sind DownloadURLs beim Auflisten von Rechnungen nicht enthalten.
            </param>
        <param name="filter">
            Kann verwendet werden, Rechnungen Filtern von InvoicePeriodEndDate. Der Filter unterstützt "Eq", "Lt", 'Gt', 'le', "ge", und "und". Es derzeit nicht unterstützt 'Ne', 'oder' oder 'nicht'.
            </param>
        <param name="skiptoken">
            Skiptoken wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.
            Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen Skiptoken-Parameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.
            </param>
        <param name="top">
            Kann verwendet werden, um die Anzahl der Ergebnisse in den letzten N Rechnungen zu beschränken.
            </param>
        <summary>
            Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung. In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListAsync (operations, expand, filter, skiptoken, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="expand">
            Kann verwendet werden, um die DownloadUrl-Eigenschaft in einer Liste von Rechnungen zu erweitern.
            Dies ermöglicht Downloadlinks gleichzeitig für mehrere Rechnungen generiert werden.
            Standardmäßig sind DownloadURLs beim Auflisten von Rechnungen nicht enthalten.
            </param>
        <param name="filter">
            Kann verwendet werden, Rechnungen Filtern von InvoicePeriodEndDate. Der Filter unterstützt "Eq", "Lt", 'Gt', 'le', "ge", und "und". Es derzeit nicht unterstützt 'Ne', 'oder' oder 'nicht'.
            </param>
        <param name="skiptoken">
            Skiptoken wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.
            Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen Skiptoken-Parameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.
            </param>
        <param name="top">
            Kann verwendet werden, um die Anzahl der Ergebnisse in den letzten N Rechnungen zu beschränken.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung. In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt; ListNext (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt; ListNext(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNext(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IInvoicesOperations, nextPageLink As String) As IPage(Of Invoice)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Billing.IInvoicesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung. In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Billing.IInvoicesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Billing.IInvoicesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Billing.IInvoicesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;" Usage="Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Billing</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Billing.InvoicesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Billing.Models.Invoice&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Billing.IInvoicesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die verfügbaren Rechnungen für ein Abonnement in umgekehrter chronologischer Reihenfolge ab, mit der letzten Rechnung. In der Vorschau werden Rechnungen verfügbar, die über diese API nur für Rechnung Zeiten, die enden am 1. Dezember 2016 oder höher.
            <see href="https://go.microsoft.com/fwlink/?linkid=842057" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>