<Type Name="OutputsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OutputsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OutputsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OutputsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type OutputsOperationsExtensions = class" />
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
            Erweiterungsmethoden für OutputsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, outputName, output)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="output">
            Wenn die angegebene Ausgabe nicht bereits vorhanden ist, darf dieser Parameter die vollständige Ausgabe-Definition, die getestet werden soll. Wenn die Ausgabe, die bereits vorhanden ist, diesen Parameter, kann so testen Sie die vorhandenen Ausgabe wie ist null gelassen werden, oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandenen Ausgabe (genau wie ein PATCH-Vorgang) und die resultierende Ausgabe wird getestet werden.
            </param>
        <summary>
            Testet, ob eine Ausgabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, outputName, output, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;BeginTestAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="output">
            Wenn die angegebene Ausgabe nicht bereits vorhanden ist, darf dieser Parameter die vollständige Ausgabe-Definition, die getestet werden soll. Wenn die Ausgabe, die bereits vorhanden ist, diesen Parameter, kann so testen Sie die vorhandenen Ausgabe wie ist null gelassen werden, oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandenen Ausgabe (genau wie ein PATCH-Vorgang) und die resultierende Ausgabe wird getestet werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testet, ob eine Ausgabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Output CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Output CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplace (operations, output, resourceGroupName, jobName, outputName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Output</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="output">
            Die Definition der Ausgabe, die verwendet werden soll, erstellen eine neue Ausgabe oder Ersetzen von vorhandenen Knoten unter der streaming-Auftrags.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="ifMatch">
            Das ETag der Ausgabe. Lassen Sie diesen Wert, um die aktuelle Ausgabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Ausgabe erstellt werden, aber nicht zu eine vorhandene Ausgabe aktualisieren zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <summary>
            Erstellt eine Ausgabedatei oder eine bereits vorhandene Ausgabe unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.CreateOrReplaceAsync (operations, output, resourceGroupName, jobName, outputName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="output">
            Die Definition der Ausgabe, die verwendet werden soll, erstellen eine neue Ausgabe oder Ersetzen von vorhandenen Knoten unter der streaming-Auftrags.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="ifMatch">
            Das ETag der Ausgabe. Lassen Sie diesen Wert, um die aktuelle Ausgabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Ausgabe erstellt werden, aber nicht zu eine vorhandene Ausgabe aktualisieren zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Ausgabedatei oder eine bereits vorhandene Ausgabe unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IOutputsOperations, resourceGroupName As String, jobName As String, outputName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Delete (operations, resourceGroupName, jobName, outputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <summary>
            Löscht eine Ausgabe aus den streamingauftrag an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, outputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Ausgabe aus den streamingauftrag an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Output Get (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Output Get(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IOutputsOperations, resourceGroupName As String, jobName As String, outputName As String) As Output" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Get (operations, resourceGroupName, jobName, outputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Output</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <summary>
            Ruft Details zu der angegebenen Ausgabe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, outputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Details zu der angegebenen Ausgabe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IOutputsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Output)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
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
            Listet alle Ausgaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
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
            Listet alle Ausgaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IOutputsOperations, nextPageLink As String) As IPage(Of Output)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
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
            Listet alle Ausgaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
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
            Listet alle Ausgaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Test (operations, resourceGroupName, jobName, outputName, output)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="output">
            Wenn die angegebene Ausgabe nicht bereits vorhanden ist, darf dieser Parameter die vollständige Ausgabe-Definition, die getestet werden soll. Wenn die Ausgabe, die bereits vorhanden ist, diesen Parameter, kann so testen Sie die vorhandenen Ausgabe wie ist null gelassen werden, oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandenen Ausgabe (genau wie ein PATCH-Vorgang) und die resultierende Ausgabe wird getestet werden.
            </param>
        <summary>
            Testet, ob eine Ausgabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, Microsoft.Azure.Management.StreamAnalytics.Models.Output output = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, string resourceGroupName, string jobName, string outputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Output * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, outputName, output, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
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
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="output">
            Wenn die angegebene Ausgabe nicht bereits vorhanden ist, darf dieser Parameter die vollständige Ausgabe-Definition, die getestet werden soll. Wenn die Ausgabe, die bereits vorhanden ist, diesen Parameter, kann so testen Sie die vorhandenen Ausgabe wie ist null gelassen werden, oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandenen Ausgabe (genau wie ein PATCH-Vorgang) und die resultierende Ausgabe wird getestet werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testet, ob eine Ausgabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Output Update (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Output Update(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Output" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.Update (operations, output, resourceGroupName, jobName, outputName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Output</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="output">
            Ein Output-Objekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen Ausgabe (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Ausgabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="ifMatch">
            Das ETag der Ausgabe. Lassen Sie diesen Wert, um die aktuelle Ausgabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <summary>
            Aktualisiert eine vorhandene Ausgabe unter einem vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) eine Ausgabe ohne den Rest der Auftrag oder Ausgabe-Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Output output, string resourceGroupName, string jobName, string outputName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Output,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Output * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions.UpdateAsync (operations, output, resourceGroupName, jobName, outputName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.OutputsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IOutputsOperations" RefType="this" />
        <Parameter Name="output" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Output" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="outputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="output">
            Ein Output-Objekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen Ausgabe (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Ausgabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="outputName">
            Der Name der Ausgabe.
            </param>
        <param name="ifMatch">
            Das ETag der Ausgabe. Lassen Sie diesen Wert, um die aktuelle Ausgabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine vorhandene Ausgabe unter einem vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) eine Ausgabe ohne den Rest der Auftrag oder Ausgabe-Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>