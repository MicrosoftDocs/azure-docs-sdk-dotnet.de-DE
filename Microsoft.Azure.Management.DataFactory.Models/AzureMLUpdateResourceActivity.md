<Type Name="AzureMLUpdateResourceActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity">
  <TypeSignature Language="C#" Value="public class AzureMLUpdateResourceActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLUpdateResourceActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLUpdateResourceActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type AzureMLUpdateResourceActivity = class&#xA;    inherit ExecutionActivity" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureMLUpdateResource")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure ML Update Ressource Management-Aktivität.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLUpdateResourceActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.#ctor" />
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
            Initialisiert eine neue Instanz der AzureMLUpdateResourceActivity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLUpdateResourceActivity (string name, object trainedModelName, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference trainedModelLinkedServiceName, object trainedModelFilePath, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object trainedModelName, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference trainedModelLinkedServiceName, object trainedModelFilePath, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.#ctor(System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, trainedModelName As Object, trainedModelLinkedServiceName As LinkedServiceReference, trainedModelFilePath As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity : string * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity (name, trainedModelName, trainedModelLinkedServiceName, trainedModelFilePath, additionalProperties, description, dependsOn, linkedServiceName, policy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="trainedModelName" Type="System.Object" />
        <Parameter Name="trainedModelLinkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="trainedModelFilePath" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Aktivität.</param>
        <param name="trainedModelName">Namen des Trained Model-Moduls in dem webdienstexperiment aktualisiert werden. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="trainedModelLinkedServiceName">Name des Azure-Speicher verknüpfter Dienst, die mit der .ilearner-Datei, die durch den Aktualisierungsvorgang hochgeladen werden.</param>
        <param name="trainedModelFilePath">Den relativen Dateipfad in TrainedModelLinkedService .ilearner Datei darstellt, die durch den Aktualisierungsvorgang hochgeladen wird.  Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung der Aktivität.</param>
        <param name="dependsOn">Aktivität hängt vom Zustand ab.</param>
        <param name="linkedServiceName">Verknüpften Dienst verweisen.</param>
        <param name="policy">"Aktivitätsrichtlinie".</param>
        <summary>
            Initialisiert eine neue Instanz der AzureMLUpdateResourceActivity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelFilePath">
      <MemberSignature Language="C#" Value="public object TrainedModelFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrainedModelFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelFilePath As Object" />
      <MemberSignature Language="F#" Value="member this.TrainedModelFilePath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trainedModelFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ein, oder legt den relativen Pfad in TrainedModelLinkedService .ilearner Datei darstellt, die durch den Aktualisierungsvorgang hochgeladen wird.  Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelLinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference TrainedModelLinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference TrainedModelLinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelLinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelLinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.TrainedModelLinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelLinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trainedModelLinkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Name des verknüpften Azure Storage-Diensts, halten die .ilearner-Datei, die durch den Aktualisierungsvorgang hochgeladen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrainedModelName">
      <MemberSignature Language="C#" Value="public object TrainedModelName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TrainedModelName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelName" />
      <MemberSignature Language="VB.NET" Value="Public Property TrainedModelName As Object" />
      <MemberSignature Language="F#" Value="member this.TrainedModelName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.TrainedModelName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.trainedModelName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Namen des Trained Model-Moduls in dem webdienstexperiment aktualisiert werden. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureMLUpdateResourceActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureMLUpdateResourceActivity.Validate " />
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