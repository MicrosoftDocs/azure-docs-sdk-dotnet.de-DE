<Type Name="GetPropertyOperation" FullName="System.Fabric.GetPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class GetPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GetPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.GetPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GetPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type GetPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="f4453-101">Stellt eine <see cref="T:System.Fabric.PropertyBatchOperation" /> , die Ruft die angegebene Eigenschaft ab, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="f4453-101">Represents a <see cref="T:System.Fabric.PropertyBatchOperation" /> that gets the specified property if it exists.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="f4453-102">Beachten Sie, dass, wenn mindestens eine <see cref="T:System.Fabric.PropertyBatchOperation" /> ein Fehler auftritt, der gesamte Batch fehlschlagen und nicht übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="f4453-102">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> fails, the entire batch will fail and not be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPropertyOperation (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.GetPropertyOperation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.GetPropertyOperation : string -&gt; System.Fabric.GetPropertyOperation" Usage="new System.Fabric.GetPropertyOperation propertyName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="f4453-103">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f4453-103">The name of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f4453-104">Instanziiert eine neue Instanz der <see cref="T:System.Fabric.GetPropertyOperation" /> -Klasse mit dem angegebenen Eigenschaftsnamen.</span><span class="sxs-lookup"><span data-stu-id="f4453-104">Instantiates a new instance of the <see cref="T:System.Fabric.GetPropertyOperation" /> class with specified property name.</span></span></para>
        </summary>
        <remarks>
          <para>
            <span data-ttu-id="f4453-105"><see cref="P:System.Fabric.GetPropertyOperation.IncludeValue" />wird festgelegt, um <languageKeyword>"true"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="f4453-105"><see cref="P:System.Fabric.GetPropertyOperation.IncludeValue" /> is set to <languageKeyword>true</languageKeyword>.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPropertyOperation (string propertyName, bool includeValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, bool includeValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.GetPropertyOperation.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, includeValue As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.GetPropertyOperation : string * bool -&gt; System.Fabric.GetPropertyOperation" Usage="new System.Fabric.GetPropertyOperation (propertyName, includeValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="includeValue" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="f4453-106">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="f4453-106">The name of the property.</span></span></para>
        </param>
        <param name="includeValue">
          <para><span data-ttu-id="f4453-107">Gibt an, ob Werte in der Rückgabe eingeschlossen werden soll, oder nur Metadaten zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="f4453-107">Specifies whether values should be included in the return or only metadata should be returned.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f4453-108">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.GetPropertyOperation" /> mit angegebenen Eigenschaftsnamen und-Wert Flag einschließen.</span><span class="sxs-lookup"><span data-stu-id="f4453-108">Initializes a new instance of the <see cref="T:System.Fabric.GetPropertyOperation" /> with specified property name and include value flag.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeValue">
      <MemberSignature Language="C#" Value="public bool IncludeValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GetPropertyOperation.IncludeValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncludeValue As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeValue : bool" Usage="System.Fabric.GetPropertyOperation.IncludeValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f4453-109">Ruft einen Wert, der angibt, ob der Wert der Eigenschaft zusammen mit den Metadaten zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="f4453-109">Gets a value indicating whether the value of the property is returned together with the metadata.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="f4453-110"><languageKeyword>"true"</languageKeyword> , wenn der Wert der Eigenschaft enthalten; liegen <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="f4453-110"><languageKeyword>true</languageKeyword> if the value of the property should be included; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>