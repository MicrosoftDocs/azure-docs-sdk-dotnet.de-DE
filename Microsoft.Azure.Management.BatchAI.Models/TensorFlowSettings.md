<Type Name="TensorFlowSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings">
  <TypeSignature Language="C#" Value="public class TensorFlowSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TensorFlowSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TensorFlowSettings" />
  <TypeSignature Language="F#" Value="type TensorFlowSettings = class" />
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
            Gibt die Einstellungen für TensorFlow Auftrag an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TensorFlowSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TensorFlowSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TensorFlowSettings (string pythonScriptFilePath, string masterCommandLineArgs, string pythonInterpreterPath = null, string workerCommandLineArgs = null, string parameterServerCommandLineArgs = null, Nullable&lt;int&gt; workerCount = null, Nullable&lt;int&gt; parameterServerCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string pythonScriptFilePath, string masterCommandLineArgs, string pythonInterpreterPath, string workerCommandLineArgs, string parameterServerCommandLineArgs, valuetype System.Nullable`1&lt;int32&gt; workerCount, valuetype System.Nullable`1&lt;int32&gt; parameterServerCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pythonScriptFilePath As String, masterCommandLineArgs As String, Optional pythonInterpreterPath As String = null, Optional workerCommandLineArgs As String = null, Optional parameterServerCommandLineArgs As String = null, Optional workerCount As Nullable(Of Integer) = null, Optional parameterServerCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings : string * string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings (pythonScriptFilePath, masterCommandLineArgs, pythonInterpreterPath, workerCommandLineArgs, parameterServerCommandLineArgs, workerCount, parameterServerCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="masterCommandLineArgs" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="workerCommandLineArgs" Type="System.String" />
        <Parameter Name="parameterServerCommandLineArgs" Type="System.String" />
        <Parameter Name="workerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="parameterServerCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pythonScriptFilePath">Der Pfad und Dateiname der Name des Python-Skript zum Ausführen des Auftrags.</param>
        <param name="masterCommandLineArgs">Gibt die Befehlszeilenargumente für die master-Aufgabe.</param>
        <param name="pythonInterpreterPath">Der Pfad zur Python-Interpreter.</param>
        <param name="workerCommandLineArgs">Gibt die Befehlszeilenargumente für den Worker-Vorgang an.</param>
        <param name="parameterServerCommandLineArgs">Gibt die Befehlszeilenargumente für den Parameter-Server-Task.</param>
        <param name="workerCount">Die Anzahl der Worker-Aufgaben.</param>
        <param name="parameterServerCount">Die Anzahl der-Parameters Server-Tasks.</param>
        <summary>
            Initialisiert eine neue Instanz der TensorFlowSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MasterCommandLineArgs">
      <MemberSignature Language="C#" Value="public string MasterCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MasterCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.MasterCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property MasterCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.MasterCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.MasterCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="masterCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Befehlszeilenargumente für die master-Aufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParameterServerCommandLineArgs">
      <MemberSignature Language="C#" Value="public string ParameterServerCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParameterServerCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property ParameterServerCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.ParameterServerCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameterServerCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Befehlszeilenargumente für den Parameter-Server-Task.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist optional für das Training der einzelnen Computer.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParameterServerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ParameterServerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ParameterServerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ParameterServerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ParameterServerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameterServerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der-Parameters Servertasks.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn angegeben, muss der Wert kleiner als oder gleich angegeben sind. Wenn nicht angegeben, ist der Standardwert gleich 1 für verteilte TensorFlow Training (diese Eigenschaft gilt nicht für das Training einzelner Computer). Diese Eigenschaft kann nur für verteilte TensorFlow Training angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonInterpreterPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonInterpreterPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pfad zu den Python-Interpreter fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonScriptFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonScriptFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pfad und den Namen der Python-Skript zum Ausführen des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tensorFlowSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="WorkerCommandLineArgs">
      <MemberSignature Language="C#" Value="public string WorkerCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.WorkerCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Befehlszeilenargumente für den Worker-Vorgang an.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist optional für das Training der einzelnen Computer.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Worker-Aufgaben.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn angegeben, der Wert muss kleiner als oder gleich (NodeCount * NumberOfGPUs pro virtueller Maschine). Wenn nicht angegeben, entspricht der Standardwert angegeben sind. Diese Eigenschaft kann nur für verteilte TensorFlow Training angegeben werden
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>