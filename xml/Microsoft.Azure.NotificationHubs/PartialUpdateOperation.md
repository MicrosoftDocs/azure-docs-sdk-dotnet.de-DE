<Type Name="PartialUpdateOperation" FullName="Microsoft.Azure.NotificationHubs.PartialUpdateOperation">
  <TypeSignature Language="C#" Value="public class PartialUpdateOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartialUpdateOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.PartialUpdateOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class PartialUpdateOperation" />
  <TypeSignature Language="F#" Value="type PartialUpdateOperation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject(ItemRequired=Newtonsoft.Json.Required.Default, MemberSerialization=Newtonsoft.Json.MemberSerialization.OptOut)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="215f8-101">Patch für eine Installation mit diesem Objekt</span><span class="sxs-lookup"><span data-stu-id="215f8-101">Patch an installation with this object</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartialUpdateOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.PartialUpdateOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.UpdateOperationType Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.UpdateOperationType Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.PartialUpdateOperation.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As UpdateOperationType" />
      <MemberSignature Language="F#" Value="member this.Operation : Microsoft.Azure.NotificationHubs.UpdateOperationType with get, set" Usage="Microsoft.Azure.NotificationHubs.PartialUpdateOperation.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="op")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.UpdateOperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="215f8-102">Abrufen oder Festlegen des Update-Vorgang-Typs</span><span class="sxs-lookup"><span data-stu-id="215f8-102">Get or set the update operation type</span></span>
            </summary>
        <value>
            <span data-ttu-id="215f8-103">Aktualisieren Sie Vorgangstyp an.</span><span class="sxs-lookup"><span data-stu-id="215f8-103">Update operation type.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.PartialUpdateOperation.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.NotificationHubs.PartialUpdateOperation.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="215f8-104">Abrufen Sie oder festlegen Sie des Pfads in der die zu aktualisierenden json</span><span class="sxs-lookup"><span data-stu-id="215f8-104">Get or set the path to the json which is to be updated</span></span>
            </summary>
        <value>
            <span data-ttu-id="215f8-105">Pfad zur Installation json</span><span class="sxs-lookup"><span data-stu-id="215f8-105">Path to the installation json</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.PartialUpdateOperation.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.NotificationHubs.PartialUpdateOperation.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="215f8-106">Abrufen oder Festlegen des Werts auf die aktualisierte mit</span><span class="sxs-lookup"><span data-stu-id="215f8-106">Get or set the Value to the updated with</span></span> 
            </summary>
        <value>
            <span data-ttu-id="215f8-107">Wert</span><span class="sxs-lookup"><span data-stu-id="215f8-107">Value</span></span> 
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>