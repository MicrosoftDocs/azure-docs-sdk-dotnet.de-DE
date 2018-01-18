<Type Name="SerializePropertyNamesAsCamelCaseAttribute" FullName="Microsoft.Azure.Search.Models.SerializePropertyNamesAsCamelCaseAttribute">
  <TypeSignature Language="C#" Value="public class SerializePropertyNamesAsCamelCaseAttribute : Attribute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SerializePropertyNamesAsCamelCaseAttribute extends System.Attribute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SerializePropertyNamesAsCamelCaseAttribute" />
  <TypeSignature Language="VB.NET" Value="Public Class SerializePropertyNamesAsCamelCaseAttribute&#xA;Inherits Attribute" />
  <TypeSignature Language="F#" Value="type SerializePropertyNamesAsCamelCaseAttribute = class&#xA;    inherit Attribute" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Attribute</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.AttributeUsage(System.AttributeTargets.Class, AllowMultiple=false, Inherited=true)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5780d-101">Gibt an, dass die öffentlichen Eigenschaften des eine Modellklasse als binnenversalien serialisiert werden soll, um die Feldnamen von Azure Search-Index übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="5780d-101">Indicates that the public properties of a model class should be serialized as camel-case in order to match the field names of an Azure Search index.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="5780d-102">Klassen ohne dieses Attribut erwartungsgemäß Eigenschaftennamen aufweisen, die die entsprechenden Feldnamen in Azure Search genau entsprechen.</span><span class="sxs-lookup"><span data-stu-id="5780d-102">Classes without this attribute are expected to have property names that exactly match their corresponding fields names in Azure Search.</span></span> <span data-ttu-id="5780d-103">Andernfalls würde es möglich, Instanzen der Klasse zu verwenden, zum Auffüllen des Indexes nicht.</span><span class="sxs-lookup"><span data-stu-id="5780d-103">Otherwise, it would not be possible to use instances of the class to populate the index.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SerializePropertyNamesAsCamelCaseAttribute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SerializePropertyNamesAsCamelCaseAttribute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>