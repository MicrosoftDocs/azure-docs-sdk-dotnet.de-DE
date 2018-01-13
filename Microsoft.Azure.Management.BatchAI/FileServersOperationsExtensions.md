<Type Name="FileServersOperationsExtensions" FullName="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FileServersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileServersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FileServersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FileServersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für FileServersOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.FileServer BeginCreate (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.FileServer BeginCreate(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreate(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String, parameters As FileServerCreateParameters) As FileServer" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreate (operations, resourceGroupName, fileServerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <param name="parameters">
            Die Parameter, die zur Erstellung von Datei-Server bereit.
            </param>
        <summary>
            Erstellt einen Dateiserver an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; BeginCreateAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; BeginCreateAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, fileServerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;BeginCreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <param name="parameters">
            Die Parameter, die zur Erstellung von Datei-Server bereit.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen Dateiserver an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDelete (operations, resourceGroupName, fileServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <summary>
            Löschen einer Datei, die Server an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, fileServerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löschen einer Datei, die Server an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.FileServer Create (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.FileServer Create(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Create(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String, parameters As FileServerCreateParameters) As FileServer" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Create (operations, resourceGroupName, fileServerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <param name="parameters">
            Die Parameter, die zur Erstellung von Datei-Server bereit.
            </param>
        <summary>
            Erstellt einen Dateiserver an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; CreateAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; CreateAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.CreateAsync (operations, resourceGroupName, fileServerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <param name="parameters">
            Die Parameter, die zur Erstellung von Datei-Server bereit.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen Dateiserver an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Delete(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Delete (operations, resourceGroupName, fileServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <summary>
            Löschen einer Datei, die Server an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.DeleteAsync (operations, resourceGroupName, fileServerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löschen einer Datei, die Server an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.FileServer Get (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.FileServer Get(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Get(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFileServersOperations, resourceGroupName As String, fileServerName As String) As FileServer" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.Get (operations, resourceGroupName, fileServerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <summary>
            Ruft Informationen zu dem angegebenen Cluster ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; GetAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; GetAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, string fileServerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.GetAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.GetAsync (operations, resourceGroupName, fileServerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServerName">
            Der Name des Dateiservers innerhalb der angegebenen Ressourcengruppe. Dateinamen-Server können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten. Der Name muss zwischen 1 und 64 Zeichen lang sein.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen zu dem angegebenen Cluster ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; List (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; List(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.List(Microsoft.Azure.Management.BatchAI.IFileServersOperations,Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BatchAI.IFileServersOperations * Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.List (operations, fileServersListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="fileServersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="fileServersListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Alle Dateiserver verfügbar, unter dem angegebenen Abonnement (und ressourcengruppenübergreifenden innerhalb dieses Abonnements) aufgelistet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, class Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListAsync (operations, fileServersListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="fileServersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="fileServersListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Alle Dateiserver verfügbar, unter dem angegebenen Abonnement (und ressourcengruppenübergreifenden innerhalb dieses Abonnements) aufgelistet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroup (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroup(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, fileServersListByResourceGroupOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServersListByResourceGroupOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft eine formatierte Liste von Dateiservern und deren Eigenschaften, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, fileServersListByResourceGroupOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="fileServersListByResourceGroupOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine formatierte Liste von Dateiservern und deren Eigenschaften, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IFileServersOperations, nextPageLink As String) As IPage(Of FileServer)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
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
            Ruft eine formatierte Liste von Dateiservern und deren Eigenschaften, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
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
            Ruft eine formatierte Liste von Dateiservern und deren Eigenschaften, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListNext (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt; ListNext(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNext(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IFileServersOperations, nextPageLink As String) As IPage(Of FileServer)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
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
            Alle Dateiserver verfügbar, unter dem angegebenen Abonnement (und ressourcengruppenübergreifenden innerhalb dieses Abonnements) aufgelistet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.BatchAI.IFileServersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.BatchAI.IFileServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.BatchAI.IFileServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.FileServersOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IFileServersOperations" RefType="this" />
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
            Alle Dateiserver verfügbar, unter dem angegebenen Abonnement (und ressourcengruppenübergreifenden innerhalb dieses Abonnements) aufgelistet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>