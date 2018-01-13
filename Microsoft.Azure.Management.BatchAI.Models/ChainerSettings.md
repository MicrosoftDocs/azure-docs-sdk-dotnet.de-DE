<Type Name="ChainerSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings">
  <TypeSignature Language="C#" Value="public class ChainerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChainerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ChainerSettings" />
  <TypeSignature Language="F#" Value="type ChainerSettings = class" />
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
            Gibt die Einstellungen für Chainer-Auftrag an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChainerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ChainerSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChainerSettings (string pythonScriptFilePath, string pythonInterpreterPath = null, string commandLineArgs = null, Nullable&lt;int&gt; processCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string pythonScriptFilePath, string pythonInterpreterPath, string commandLineArgs, valuetype System.Nullable`1&lt;int32&gt; processCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pythonScriptFilePath As String, Optional pythonInterpreterPath As String = null, Optional commandLineArgs As String = null, Optional processCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ChainerSettings : string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.ChainerSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.ChainerSettings (pythonScriptFilePath, pythonInterpreterPath, commandLineArgs, processCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="commandLineArgs" Type="System.String" />
        <Parameter Name="processCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pythonScriptFilePath">Der Pfad und Dateiname der Name des Python-Skript zum Ausführen des Auftrags.</param>
        <param name="pythonInterpreterPath">Der Pfad zur Python-Interpreter.</param>
        <param name="commandLineArgs">Befehlszeilenargumente, die an die Python-Skript übergeben werden muss</param>
        <param name="processCount">Anzahl der Prozesse-Parameter, um MPI-Runtime übergeben wird.</param>
        <summary>
            Initialisiert eine neue Instanz der ChainerSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLineArgs">
      <MemberSignature Language="C#" Value="public string CommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.CommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.CommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.CommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Befehlszeilenargumente, die an die Python-Skript übergeben werden muss
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.ProcessCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.ProcessCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Prozesse-Parameter, um MPI-Runtime übergeben wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert für diese Eigenschaft ist gleich NodeCount-Eigenschaft
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonInterpreterPath" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonScriptFilePath" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="chainerSettings.Validate " />
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
  </Members>
</Type>