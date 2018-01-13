<Type Name="CaffeSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings">
  <TypeSignature Language="C#" Value="public class CaffeSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CaffeSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class CaffeSettings" />
  <TypeSignature Language="F#" Value="type CaffeSettings = class" />
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
            Gibt die Einstellungen für Caffe Auftrag an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaffeSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CaffeSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaffeSettings (string configFilePath = null, string pythonScriptFilePath = null, string pythonInterpreterPath = null, string commandLineArgs = null, Nullable&lt;int&gt; processCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configFilePath, string pythonScriptFilePath, string pythonInterpreterPath, string commandLineArgs, valuetype System.Nullable`1&lt;int32&gt; processCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional configFilePath As String = null, Optional pythonScriptFilePath As String = null, Optional pythonInterpreterPath As String = null, Optional commandLineArgs As String = null, Optional processCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.CaffeSettings : string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.CaffeSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.CaffeSettings (configFilePath, pythonScriptFilePath, pythonInterpreterPath, commandLineArgs, processCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configFilePath" Type="System.String" />
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="commandLineArgs" Type="System.String" />
        <Parameter Name="processCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="configFilePath">Gibt den Pfad der Datei "App.config".</param>
        <param name="pythonScriptFilePath">Der Pfad und Dateiname der Name des Python-Skript zum Ausführen des Auftrags.</param>
        <param name="pythonInterpreterPath">Der Pfad zur Python-Interpreter.</param>
        <param name="commandLineArgs">Befehlszeilenargumente, die dem Auftrag Caffe übergeben werden muss.</param>
        <param name="processCount">Anzahl der Prozesse-Parameter, um MPI-Runtime übergeben wird.</param>
        <summary>
            Initialisiert eine neue Instanz der CaffeSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLineArgs">
      <MemberSignature Language="C#" Value="public string CommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.CommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.CommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.CommandLineArgs" />
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
            Ruft ab oder legt Befehlszeilenargumente, die dem Auftrag Caffe übergeben werden muss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigFilePath">
      <MemberSignature Language="C#" Value="public string ConfigFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ConfigFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigFilePath As String" />
      <MemberSignature Language="F#" Value="member this.ConfigFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ConfigFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="configFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Pfad der Datei "App.config".
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft nicht angegeben, wenn PythonScriptFilePath angegeben ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ProcessCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ProcessCount" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonInterpreterPath" />
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
        <remarks>
            Diese Eigenschaft kann nur angegeben werden, wenn die PythonScriptFilePath angegeben wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonScriptFilePath" />
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
        <remarks>
            Diese Eigenschaft nicht angegeben, wenn Konfigurationsdateipfad angegeben ist.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>