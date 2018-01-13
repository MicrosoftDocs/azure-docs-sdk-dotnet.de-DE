<Type Name="AzureMLUpdateResourceActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity">
  <TypeSignature Language="C#" Value="public class AzureMLUpdateResourceActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLUpdateResourceActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLUpdateResourceActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLUpdateResourceActivity = class&#xA;    inherit ActivityTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureMLUpdateResource")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Für das Aktualisieren von Trained Model-Moduls von einem Azure ML-Webdienst-Endpunkt mit einem neuen trainierten Modell ADF-Aktivität. Zum Erstellen von retrainable Azure Machine Learning-Diensten finden Sie unter https://azure.microsoft.com/documentation/articles/machine-learning-retrain-models-programmatically/ Informationen. Können Sie eine Pipeline ADF mit erstellen eine <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLBatchExecutionActivity" /> durchführen, Umschulung und erzeugen eine neue iLearner in eine Ausgabe Dataset, verwenden Sie dieses Dataset als Eingabe für diese Aktivität einen Batch bewertungsendpunkt gepatcht.
            
            Die Azure ML Linked Service für die Aktivität muss den Management-URL und API-Schlüssel enthalten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLUpdateResourceActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity.#ctor" />
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLUpdateResourceActivity (string trainedModelDatasetName, string trainedModelName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string trainedModelDatasetName, string trainedModelName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (trainedModelDatasetName As String, trainedModelName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity (trainedModelDatasetName, trainedModelName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="trainedModelDatasetName" Type="System.String" />
        <Parameter Name="trainedModelName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="trainedModelDatasetName">To be added.</param>
        <param name="trainedModelName">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelDatasetName">
      <MemberSignature Language="C#" Value="public string TrainedModelDatasetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrainedModelDatasetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity.TrainedModelDatasetName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelDatasetName As String" />
      <MemberSignature Language="F#" Value="member this.TrainedModelDatasetName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity.TrainedModelDatasetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Name des ADF-Blobdataset an, das die iLearner-Datei, die durch den Aktualisierungsvorgang hochgeladen werden.
            Das Dataset muss in der Pipelineeingabe dieser Aktivität enthalten sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelName">
      <MemberSignature Language="C#" Value="public string TrainedModelName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrainedModelName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity.TrainedModelName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelName As String" />
      <MemberSignature Language="F#" Value="member this.TrainedModelName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity.TrainedModelName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Namen des Trained Model-Moduls in das Diagramm des trainingsexperiments aktualisiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>