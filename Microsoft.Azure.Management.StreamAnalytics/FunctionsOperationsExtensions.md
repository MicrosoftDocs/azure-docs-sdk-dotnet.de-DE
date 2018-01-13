<Type Name="FunctionsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FunctionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FunctionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FunctionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FunctionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für FunctionsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="function">
            Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll. Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.
            </param>
        <summary>
            Testet, ob die Informationen für eine Funktion ungültig ist. Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;BeginTestAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="function">
            Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll. Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testet, ob die Informationen für eine Funktion ungültig ist. Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="function">
            Die Definition der Funktion, die zum Erstellen Sie eine neue Funktion, oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="ifMatch">
            Das ETag der Funktion. Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Funktion erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Funktion zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <summary>
            Erstellt eine Funktion oder eine bereits vorhandene Funktion unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="function">
            Die Definition der Funktion, die zum Erstellen Sie eine neue Funktion, oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="ifMatch">
            Das ETag der Funktion. Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Funktion erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Funktion zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Funktion oder eine bereits vorhandene Funktion unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <summary>
            Löscht eine Funktion aus den streamingauftrag an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Funktion aus den streamingauftrag an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Get (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Get(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String) As Function" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <summary>
            Ruft Details über die angegebene Funktion ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Details über die angegebene Funktion ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="select">
            Der $select OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der strukturellen Eigenschaften in die Antwort eingeschlossen werden sollen oder "*" alle Eigenschaften eingeschlossen. Standardmäßig werden alle Eigenschaften außer Diagnose zurückgegeben. Derzeit sind nur Werte "*" als gültiger Wert.
            </param>
        <summary>
            Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="select">
            Der $select OData-Abfrageparameter. Dies ist eine durch Trennzeichen getrennte Liste der strukturellen Eigenschaften in die Antwort eingeschlossen werden sollen oder "*" alle Eigenschaften eingeschlossen. Standardmäßig werden alle Eigenschaften außer Diagnose zurückgegeben. Derzeit sind nur Werte "*" als gültiger Wert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IFunctionsOperations, nextPageLink As String) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
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
            Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
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
            Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinition : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            Der Parameter verwendet, um den Typ der Funktion das Default-Definition für die abzurufenden anzugeben.
            </param>
        <summary>
            Ruft die Default-Definition einer Funktion, die basierend auf den angegebenen Parametern ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinitionAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;RetrieveDefaultDefinitionAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            Der Parameter verwendet, um den Typ der Funktion das Default-Definition für die abzurufenden anzugeben.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Default-Definition einer Funktion, die basierend auf den angegebenen Parametern ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="function">
            Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll. Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.
            </param>
        <summary>
            Testet, ob die Informationen für eine Funktion ungültig ist. Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="function">
            Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll. Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testet, ob die Informationen für eine Funktion ungültig ist. Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Update (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Update(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update (operations, function, resourceGroupName, jobName, functionName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="function">
            Ein Funktionsobjekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen-Funktion (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in die vorhandene Funktion gleich bleiben und nicht als Ergebnis dieser PATCH-Vorgang geändert wird.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="ifMatch">
            Das ETag der Funktion. Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <summary>
            Aktualisiert eine vorhandene Funktion unter einer vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) einer Funktion ohne den Rest der Auftrag oder Funktionsdefinition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="function">
            Ein Funktionsobjekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen-Funktion (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in die vorhandene Funktion gleich bleiben und nicht als Ergebnis dieser PATCH-Vorgang geändert wird.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="functionName">
            Der Name der Funktion.
            </param>
        <param name="ifMatch">
            Das ETag der Funktion. Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine vorhandene Funktion unter einer vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) einer Funktion ohne den Rest der Auftrag oder Funktionsdefinition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>