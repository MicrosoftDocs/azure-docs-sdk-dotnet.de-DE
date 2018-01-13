<Type Name="AzureMLBatchExecutionActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity">
  <TypeSignature Language="C#" Value="public class AzureMLBatchExecutionActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLBatchExecutionActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLBatchExecutionActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLBatchExecutionActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureMLBatchExecution")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure ML Batch Execution Service-Aktivität.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLBatchExecutionActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GlobalParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; GlobalParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GlobalParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property GlobalParameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GlobalParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.GlobalParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Schlüssel-Wert-Paare an die Azure ML-Batch-Ausführung-Dienstendpunkt übergeben werden. Schlüssel müssen mit den Webdienstparametern übereinstimmen, die im veröffentlichten Azure ML-Webdienst definiert sind. Werte eventuell Azure Data Factory-Funktionen zum Ausführungszeitpunkt jedes Segment (siehe http://go.microsoft.com/fwlink/?LinkId=823697) aufgelöst werden. Werte werden in der Eigenschaft ' globalparameters ' die ausführungsanforderung für Azure ML-Batch übergeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInput">
      <MemberSignature Language="C#" Value="public string WebServiceInput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WebServiceInput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInput As String" />
      <MemberSignature Language="F#" Value="member this.WebServiceInput : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Der Name der Data Factory-Dataset ermöglicht die Eingabe für die Batchausführung. Diese Informationen werden in der WebServiceInput-Eigenschaft, die Azure ML-Batchanforderung Ausführung übergeben. WebServiceInput kann nicht gleichzeitig mit WebServiceInputs verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceInputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceInputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceInputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceInputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceInputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceInputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Schlüssel-Wert-Paaren, die Zuordnung der Namen von Azure ML Web service Eingaben für den Namen der Data Factory-Datasets.
            Die Eingabe der Batch-Ausführung wird in diesen Datasets gespeichert.
            Diese Informationen werden in der WebServiceInputs-Eigenschaft, die Azure ML-Batchanforderung Ausführung übergeben.
            Zugeordnete Datasets muss in der Aktivität Eingaben enthalten sein. WebServiceInputs können nicht gleichzeitig mit WebServiceInput verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebServiceOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; WebServiceOutputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; WebServiceOutputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberSignature Language="VB.NET" Value="Public Property WebServiceOutputs As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.WebServiceOutputs : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity.WebServiceOutputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Schlüssel, Wert-Paare, die Namen der Data Factory-Datasets die Namen von Azure ML Web Service Ausgaben zuordnen.
            Die Ausgabe der Batch-Ausführung wird in diese Datasets nicht geschrieben.
            Diese Informationen werden in der Eigenschaft "webserviceoutputs" der Batchanforderung Ausführung Azure ML übergeben.
            In der Aktivität Ausgaben müssen zugeordneten Datasets enthalten sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>