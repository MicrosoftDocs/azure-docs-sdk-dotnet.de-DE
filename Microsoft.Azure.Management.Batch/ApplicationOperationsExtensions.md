<Type Name="ApplicationOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ApplicationOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Application Create (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Application Create(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Create(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String, Optional parameters As ApplicationCreateParameters = null) As Application" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters -&gt; Microsoft.Azure.Management.Batch.Models.Application" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Create (operations, resourceGroupName, accountName, applicationId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Application</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <param name="parameters">
            Die Parameter für die Anforderung.
            </param>
        <summary>
            Fügt eine Anwendung für das angegebene Batch-Konto hinzu.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; CreateAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; CreateAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, applicationId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <param name="parameters">
            Die Parameter für die Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt eine Anwendung für das angegebene Batch-Konto hinzu.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Delete (operations, resourceGroupName, accountName, applicationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <summary>
            Löscht eine Anwendung an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, applicationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Anwendung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Application Get (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Application Get(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Get(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String) As Application" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Application" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Get (operations, resourceGroupName, accountName, applicationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Application</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <summary>
            Ruft Informationen über die angegebene Anwendung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; GetAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; GetAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, applicationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über die angegebene Anwendung ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; List (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; List(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.List(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IApplicationOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null) As IPage(Of Application)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.List (operations, resourceGroupName, accountName, maxresults)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="maxresults">
            Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.
            </param>
        <summary>
            Zeigt eine Liste aller Anwendungen in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListAsync (operations, resourceGroupName, accountName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="maxresults">
            Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Anwendungen in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt; ListNext (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt; ListNext(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNext(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IApplicationOperations, nextPageLink As String) As IPage(Of Application)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Batch.IApplicationOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
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
            Zeigt eine Liste aller Anwendungen in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Application&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Application&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
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
            Zeigt eine Liste aller Anwendungen in das angegebene Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Update(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Update (operations As IApplicationOperations, resourceGroupName As String, accountName As String, applicationId As String, parameters As ApplicationUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.Update (operations, resourceGroupName, accountName, applicationId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <param name="parameters">
            Die Parameter für die Anforderung.
            </param>
        <summary>
            Aktualisiert die Einstellungen für die angegebene Anwendung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.Batch.IApplicationOperations operations, string resourceGroupName, string accountName, string applicationId, class Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.IApplicationOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.IApplicationOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, applicationId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.ApplicationOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.IApplicationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.ApplicationUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die das Batch-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Batch-Konto.
            </param>
        <param name="applicationId">
            Die ID der Anwendung.
            </param>
        <param name="parameters">
            Die Parameter für die Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Einstellungen für die angegebene Anwendung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>