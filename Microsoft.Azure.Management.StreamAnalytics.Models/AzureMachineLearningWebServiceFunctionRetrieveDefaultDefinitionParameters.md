<Type Name="AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters">
  <TypeSignature Language="C#" Value="public class AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters : Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters extends Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters&#xA;Inherits FunctionRetrieveDefaultDefinitionParameters" />
  <TypeSignature Language="F#" Value="type AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters = class&#xA;    inherit FunctionRetrieveDefaultDefinitionParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters</BaseTypeName>
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
            Die Parameter benötigt, um die Funktion-Standarddefinition für ein Azure Machine Learning-Webdienstfunktion abzurufen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters (string executeEndpoint = null, Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; udfType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string executeEndpoint, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; udfType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.StreamAnalytics.Models.UdfType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional executeEndpoint As String = null, Optional udfType As Nullable(Of UdfType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters : string * Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters (executeEndpoint, udfType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="executeEndpoint" Type="System.String" />
        <Parameter Name="udfType" Type="System.Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt;" />
      </Parameters>
      <Docs>
        <param name="executeEndpoint">Die Anforderung-Antwort führen Endpunkt des Azure Machine Learning-Webdiensts. Informieren Sie sich über weitere hier: https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-consume-web-services#request-response-service-rrs</param>
        <param name="udfType">Der Funktionstyp. Folgende Werte sind möglich: "Scalar"</param>
        <summary>
            Initialisiert eine neue Instanz der AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteEndpoint">
      <MemberSignature Language="C#" Value="public string ExecuteEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExecuteEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters.ExecuteEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecuteEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ExecuteEndpoint : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters.ExecuteEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bindingRetrievalProperties.executeEndpoint")</AttributeName>
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
    <Member MemberName="UdfType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; UdfType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; UdfType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters.UdfType" />
      <MemberSignature Language="VB.NET" Value="Public Property UdfType As Nullable(Of UdfType)" />
      <MemberSignature Language="F#" Value="member this.UdfType : Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureMachineLearningWebServiceFunctionRetrieveDefaultDefinitionParameters.UdfType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bindingRetrievalProperties.udfType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StreamAnalytics.Models.UdfType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Funktion. Folgende Werte sind möglich: "Scalar"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>