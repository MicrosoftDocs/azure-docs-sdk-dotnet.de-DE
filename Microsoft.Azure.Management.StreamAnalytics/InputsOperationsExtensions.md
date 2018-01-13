<Type Name="InputsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InputsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InputsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InputsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InputsOperationsExtensions = class" />
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
            Erweiterungsmethoden für InputsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="input">
            Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten. Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.
            </param>
        <summary>
            Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;BeginTestAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="input">
            Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten. Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="input">
            Die Definition der Eingabe, die eine neue Eingabe erstellen oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="ifMatch">
            Das ETag der Eingabe. Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Eingabe erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Eingabe zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <summary>
            Erstellt eine Eingabe, oder eine bereits vorhandene Eingabe unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="input">
            Die Definition der Eingabe, die eine neue Eingabe erstellen oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="ifMatch">
            Das ETag der Eingabe. Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" um eine neue Eingabe erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Eingabe zu ermöglichen. Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Eingabe, oder eine bereits vorhandene Eingabe unter einem vorhandenen streaming Auftrag ersetzt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <summary>
            Löscht eine Eingabe aus der streaming-Auftrags an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine Eingabe aus der streaming-Auftrags an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Get (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Get(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String) As Input" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <summary>
            Ruft Details über die angegebene Eingabe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Details über die angegebene Eingabe ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IInputsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IInputsOperations, nextPageLink As String) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
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
            Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="input">
            Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten. Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.
            </param>
        <summary>
            Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
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
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="input">
            Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten. Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Update (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Update(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update (operations, input, resourceGroupName, jobName, inputName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="input">
            Ein Input-Objekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen Eingabe (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="ifMatch">
            Das ETag der Eingabe. Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <summary>
            Aktualisiert eine vorhandene Eingabe unter einem vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) Eingabe ohne den Rest der Auftrag oder die Eingabe-Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="input">
            Ein Input-Objekt. Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen Eingabe (d. h. Diese Eigenschaften werden aktualisiert). Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, die die Ressource enthält. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="jobName">
            Der Name des streamingauftrags.
            </param>
        <param name="inputName">
            Der Name der Eingabe.
            </param>
        <param name="ifMatch">
            Das ETag der Eingabe. Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben. Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert eine vorhandene Eingabe unter einem vorhandenen streaming-Auftrags an. Dies kann verwendet werden, aktualisieren Sie teilweise (d. h. Aktualisieren Sie eine oder zwei Eigenschaften) Eingabe ohne den Rest der Auftrag oder die Eingabe-Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>