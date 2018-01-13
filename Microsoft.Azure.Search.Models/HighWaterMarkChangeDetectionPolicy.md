<Type Name="HighWaterMarkChangeDetectionPolicy" FullName="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy">
  <TypeSignature Language="C#" Value="public class HighWaterMarkChangeDetectionPolicy : Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HighWaterMarkChangeDetectionPolicy extends Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class HighWaterMarkChangeDetectionPolicy&#xA;Inherits DataChangeDetectionPolicy" />
  <TypeSignature Language="F#" Value="type HighWaterMarkChangeDetectionPolicy = class&#xA;    inherit DataChangeDetectionPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.DataChangeDetectionPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.HighWaterMarkChangeDetectionPolicy")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="67160-101">Definiert eine Erkennungsrichtlinie für, die Änderungen anhand des Werts von einer Spalte mit oberen Grenzen erfasst.</span><span class="sxs-lookup"><span data-stu-id="67160-101">Defines a data change detection policy that captures changes based on the value of a high water mark column.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HighWaterMarkChangeDetectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="67160-102">Initialisiert eine neue Instanz der "highwatermarkchangedetectionpolicy"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="67160-102">Initializes a new instance of the HighWaterMarkChangeDetectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HighWaterMarkChangeDetectionPolicy (string highWaterMarkColumnName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string highWaterMarkColumnName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (highWaterMarkColumnName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy : string -&gt; Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" Usage="new Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy highWaterMarkColumnName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="highWaterMarkColumnName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="highWaterMarkColumnName"><span data-ttu-id="67160-103">Der Name der Spalte obere Grenze.</span><span class="sxs-lookup"><span data-stu-id="67160-103">The name of the high water mark column.</span></span></param>
        <summary>
            <span data-ttu-id="67160-104">Initialisiert eine neue Instanz der "highwatermarkchangedetectionpolicy"-Klasse.</span><span class="sxs-lookup"><span data-stu-id="67160-104">Initializes a new instance of the HighWaterMarkChangeDetectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighWaterMarkColumnName">
      <MemberSignature Language="C#" Value="public string HighWaterMarkColumnName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighWaterMarkColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy.HighWaterMarkColumnName" />
      <MemberSignature Language="VB.NET" Value="Public Property HighWaterMarkColumnName As String" />
      <MemberSignature Language="F#" Value="member this.HighWaterMarkColumnName : string with get, set" Usage="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy.HighWaterMarkColumnName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highWaterMarkColumnName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67160-105">Ruft ab oder legt den Namen der Spalte obere Grenze.</span><span class="sxs-lookup"><span data-stu-id="67160-105">Gets or sets the name of the high water mark column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="highWaterMarkChangeDetectionPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="67160-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="67160-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="67160-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="67160-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>