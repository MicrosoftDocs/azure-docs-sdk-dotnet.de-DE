<Type Name="DataLakeAnalyticsUSQLActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsUSQLActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsUSQLActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsUSQLActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsUSQLActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("DataLakeAnalyticsU-SQL")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Data Lake Analytics-U-SQL-Aktivität.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsUSQLActivity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string name, object scriptPath, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, object degreeOfParallelism = null, object priority = null, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, object runtimeVersion = null, object compilationMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object scriptPath, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference scriptLinkedService, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, object degreeOfParallelism, object priority, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, object runtimeVersion, object compilationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, scriptPath As Object, scriptLinkedService As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional degreeOfParallelism As Object = null, Optional priority As Object = null, Optional parameters As IDictionary(Of String, Object) = null, Optional runtimeVersion As Object = null, Optional compilationMode As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity : string * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity (name, scriptPath, scriptLinkedService, additionalProperties, description, dependsOn, linkedServiceName, policy, degreeOfParallelism, priority, parameters, runtimeVersion, compilationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="scriptPath" Type="System.Object" />
        <Parameter Name="scriptLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="degreeOfParallelism" Type="System.Object" />
        <Parameter Name="priority" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="runtimeVersion" Type="System.Object" />
        <Parameter Name="compilationMode" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Aktivität.</param>
        <param name="scriptPath">Groß-/Kleinschreibung Pfad zum Ordner, der das U-SQL-Skript enthält. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="scriptLinkedService">Dienstverweis Skript verknüpft.</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung der Aktivität.</param>
        <param name="dependsOn">Aktivität hängt vom Zustand ab.</param>
        <param name="linkedServiceName">Verknüpften Dienst verweisen.</param>
        <param name="policy">"Aktivitätsrichtlinie".</param>
        <param name="degreeOfParallelism">Die maximale Anzahl von Knoten, die zum Ausführen des Auftrags gleichzeitig verwendet werden. Der Standardwert ist 1. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimale:
            1.</param>
        <param name="priority">Bestimmt, welche der in der Warteschlange befindlichen Aufträge als erstes ausgeführt werden. Je niedriger die Zahl, desto höher die Priorität. Der Standardwert ist 1000. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 1.</param>
        <param name="parameters">Parameter für die Anforderung der U-SQL-Auftrag.</param>
        <param name="runtimeVersion">Common Language Runtime-Version des Moduls U-SQL verwenden. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="compilationMode">Der Kompilierungsmodus von U-SQL. Muss einen der folgenden Werte sein: semantische, vollständige Installation und SingleBox. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsUSQLActivity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationMode">
      <MemberSignature Language="C#" Value="public object CompilationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CompilationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CompilationMode As Object" />
      <MemberSignature Language="F#" Value="member this.CompilationMode : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.compilationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Kompilierungsmodus U-SQL. Muss einen der folgenden Werte sein: semantische, vollständige Installation und SingleBox. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public object DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Object" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.degreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Knoten, die zum Ausführen des Auftrags gleichzeitig verwendet. Der Standardwert ist 1. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 1.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Parameter für die Anforderung der U-SQL-Auftrag fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public object Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Object" />
      <MemberSignature Language="F#" Value="member this.Priority : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt bestimmt, welche in der Warteschlange eingereihten Aufträge zuerst ausgeführt ausgewählt werden sollen. Je niedriger die Zahl, desto höher die Priorität. Der Standardwert ist 1000. Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 1.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public object RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As Object" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.runtimeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Laufzeitversion von das U-SQL-Datenbankmodul verwenden. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ScriptLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.ScriptLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Dienstverweis Skript verknüpft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptPath">
      <MemberSignature Language="C#" Value="public object ScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptPath As Object" />
      <MemberSignature Language="F#" Value="member this.ScriptPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scriptPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Groß-/Kleinschreibung Pfad zum Ordner, der das U-SQL-Skript enthält. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DataLakeAnalyticsUSQLActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsUSQLActivity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>