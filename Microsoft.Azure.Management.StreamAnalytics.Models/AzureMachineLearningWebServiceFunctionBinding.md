<Type Name="AzureMachineLearningWebServiceFunctionBinding" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding">
  <TypeSignature Language="C#" Value="public class AzureMachineLearningWebServiceFunctionBinding : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMachineLearningWebServiceFunctionBinding extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMachineLearningWebServiceFunctionBinding&#xA;Inherits FunctionBinding" />
  <TypeSignature Language="F#" Value="type AzureMachineLearningWebServiceFunctionBinding = class&#xA;    inherit FunctionBinding" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionBinding</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.MachineLearning/WebService")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Bindung an ein Azure Machine Learning-Webdienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceFunctionBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureMachineLearningWebServiceFunctionBinding-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceFunctionBinding (string endpoint = null, string apiKey = null, Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs inputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; outputs = null, Nullable&lt;int&gt; batchSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string apiKey, class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs inputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; outputs, valuetype System.Nullable`1&lt;int32&gt; batchSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.#ctor(System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs,System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional endpoint As String = null, Optional apiKey As String = null, Optional inputs As AzureMachineLearningWebServiceInputs = null, Optional outputs As IList(Of AzureMachineLearningWebServiceOutputColumn) = null, Optional batchSize As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding : string * string * Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding (endpoint, apiKey, inputs, outputs, batchSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="apiKey" Type="System.String" />
        <Parameter Name="inputs" Type="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs" />
        <Parameter Name="outputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt;" />
        <Parameter Name="batchSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="endpoint">Die Anforderung-Antwort führen Endpunkt des Azure Machine Learning-Webdiensts. Informieren Sie sich über weitere hier: https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-consume-web-services#request-response-service-rrs</param>
        <param name="apiKey">Der API-Schlüssel für die Authentifizierung bei Anforderung-Antwort-Endpunkt verwendet.</param>
        <param name="inputs">Die Eingaben für den Webdienst Azure Machine Learning-Endpunkt.</param>
        <param name="outputs">Eine Liste der Ausgaben von Azure Machine Learning Web-Dienst-Endpunkt-Ausführung.</param>
        <param name="batchSize">Zahl zwischen 1 und 10.000 liegen, die maximale Anzahl von Zeilen für jede Azure ML-Ressourceneinträge beschreibt führen-Anforderung.
            Der Standard ist 1000.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureMachineLearningWebServiceFunctionBinding-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public string ApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiKey As String" />
      <MemberSignature Language="F#" Value="member this.ApiKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apiKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den API-Schlüssel für die Authentifizierung bei Anforderung-Antwort-Endpunkt verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.BatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BatchSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.BatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.batchSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Zahl zwischen 1 und 10.000 liegen, die maximale Anzahl von Zeilen für jede Azure ML RRS führen Anforderung beschreibt. Der Standard ist 1000.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anforderung-Antwort führen Sie den Azure Machine Learning-Webdienst-Endpunkt. Informieren Sie sich über weitere hier: https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-consume-web-services#request-response-service-rrs
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As AzureMachineLearningWebServiceInputs" />
      <MemberSignature Language="F#" Value="member this.Inputs : Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceInputs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die Eingaben für den Webdienst Azure Machine Learning-Endpunkt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of AzureMachineLearningWebServiceOutputColumn)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionBinding.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceOutputColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Ausgaben von der Azure Machine Learning Web-Dienst-Endpunkt-Ausführung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>