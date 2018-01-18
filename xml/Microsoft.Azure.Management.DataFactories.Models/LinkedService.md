<Type Name="LinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.LinkedService">
  <TypeSignature Language="C#" Value="public class LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinkedService extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.LinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class LinkedService" />
  <TypeSignature Language="F#" Value="type LinkedService = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="13554-101">Der Data Factory des verknüpften Diensts.</span><span class="sxs-lookup"><span data-stu-id="13554-101">The data factory Linked Service.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.LinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="13554-102">Initialisiert eine neue Instanz der LinkedService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="13554-102">Initializes a new instance of the LinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinkedService (string name, Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.LinkedService.#ctor(System.String,Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, properties As LinkedServiceProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.LinkedService : string * Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties -&gt; Microsoft.Azure.Management.DataFactories.Models.LinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.LinkedService (name, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="properties">To be added.</param>
        <summary>
            <span data-ttu-id="13554-103">Initialisiert eine neue Instanz der LinkedService-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="13554-103">Initializes a new instance of the LinkedService class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedService.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedService.Name" />
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
            <span data-ttu-id="13554-104">Der Name des der LinkedService.</span><span class="sxs-lookup"><span data-stu-id="13554-104">Name of the LinkedService.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.LinkedService.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As LinkedServiceProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.LinkedService.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13554-105">Der LinkedService-Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="13554-105">LinkedService properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>