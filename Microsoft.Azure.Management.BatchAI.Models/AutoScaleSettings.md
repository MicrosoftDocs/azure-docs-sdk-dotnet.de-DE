<Type Name="AutoScaleSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings">
  <TypeSignature Language="C#" Value="public class AutoScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleSettings" />
  <TypeSignature Language="F#" Value="type AutoScaleSettings = class" />
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
            Das System wird automatisch den Cluster nach oben oder unten (innerhalb des MinimumNodeCount und MaximumNodeCount) basierend auf den ausstehenden und ausgeführten Aufträgen im Cluster skaliert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AutoScaleSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleSettings (int minimumNodeCount, int maximumNodeCount, Nullable&lt;int&gt; initialNodeCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 minimumNodeCount, int32 maximumNodeCount, valuetype System.Nullable`1&lt;int32&gt; initialNodeCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.#ctor(System.Int32,System.Int32,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimumNodeCount As Integer, maximumNodeCount As Integer, Optional initialNodeCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings : int * int * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings (minimumNodeCount, maximumNodeCount, initialNodeCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimumNodeCount" Type="System.Int32" />
        <Parameter Name="maximumNodeCount" Type="System.Int32" />
        <Parameter Name="initialNodeCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="minimumNodeCount">Gibt die minimale Anzahl von Serverknoten, die der Cluster enthalten kann.</param>
        <param name="maximumNodeCount">Gibt die maximale Anzahl von Serverknoten, die der Cluster enthalten kann.</param>
        <param name="initialNodeCount">Gibt die Anzahl von Serverknoten auf Clustererstellung zugewiesen. Beachten Sie, dass dieser Wert nur während der Clustererstellung verwendet wird.</param>
        <summary>
            Initialisiert eine neue Instanz der AutoScaleSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialNodeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; InitialNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; InitialNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.InitialNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialNodeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.InitialNodeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.InitialNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="initialNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Anzahl der Serverknoten auf Clustererstellung zugewiesen. Beachten Sie, dass dieser Wert nur während der Clustererstellung verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodeCount">
      <MemberSignature Language="C#" Value="public int MaximumNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaximumNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MaximumNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaximumNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MaximumNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximumNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die maximale Anzahl von Serverknoten, die der Cluster enthalten kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodeCount">
      <MemberSignature Language="C#" Value="public int MinimumNodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MinimumNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MinimumNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MinimumNodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.MinimumNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimumNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die minimale Anzahl von Serverknoten, die der Cluster enthalten kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.AutoScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoScaleSettings.Validate " />
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