<Type Name="RecommendedDatabaseProperties" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties">
  <TypeSignature Language="C#" Value="public class RecommendedDatabaseProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedDatabaseProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedDatabaseProperties" />
  <TypeSignature Language="F#" Value="type RecommendedDatabaseProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="612e3-101">Stellt die Eigenschaften einer empfohlene Azure SQL-Datenbank aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="612e3-101">Represents the properties of a recommended Azure SQL Database being upgraded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedDatabaseProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="612e3-102">Initialisiert eine neue Instanz der RecommendedDatabaseProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="612e3-102">Initializes a new instance of the RecommendedDatabaseProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedDatabaseProperties (string name = null, string targetEdition = null, string targetServiceLevelObjective = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string targetEdition, string targetServiceLevelObjective) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional targetEdition As String = null, Optional targetServiceLevelObjective As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties (name, targetEdition, targetServiceLevelObjective)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="targetEdition" Type="System.String" />
        <Parameter Name="targetServiceLevelObjective" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="612e3-103">Der Name der zu aktualisierenden Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="612e3-103">The name of the Azure SQL database being upgraded.</span></span></param>
        <param name="targetEdition"><span data-ttu-id="612e3-104">Die Zieledition für die Azure SQL-Datenbank aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="612e3-104">The target edition for the Azure SQL database being upgraded.</span></span> <span data-ttu-id="612e3-105">Folgende Werte sind möglich: "Basic", "Standard", "Premium", "Frei", "Stretch", "Data Warehouse"</span><span class="sxs-lookup"><span data-stu-id="612e3-105">Possible values include: 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse'</span></span></param>
        <param name="targetServiceLevelObjective"><span data-ttu-id="612e3-106">Das Ziel-SLO für die Azure SQL-Datenbank aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="612e3-106">The target Service Level Objective for the Azure SQL database being upgraded.</span></span></param>
        <summary>
            <span data-ttu-id="612e3-107">Initialisiert eine neue Instanz der RecommendedDatabaseProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="612e3-107">Initializes a new instance of the RecommendedDatabaseProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="612e3-108">Ruft ab oder legt den Namen der zu aktualisierenden Azure SQL-Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="612e3-108">Gets or sets the name of the Azure SQL database being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetEdition">
      <MemberSignature Language="C#" Value="public string TargetEdition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetEdition" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetEdition As String" />
      <MemberSignature Language="F#" Value="member this.TargetEdition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="612e3-109">Abrufen oder festlegen die Zieledition für die Azure SQL-Datenbank aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="612e3-109">Gets or sets the target edition for the Azure SQL database being upgraded.</span></span> <span data-ttu-id="612e3-110">Folgende Werte sind möglich: "Basic", "Standard", "Premium", "Frei", "Stretch", "Data Warehouse"</span><span class="sxs-lookup"><span data-stu-id="612e3-110">Possible values include: 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string TargetServiceLevelObjective { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.TargetServiceLevelObjective : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetServiceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="612e3-111">Ruft ab oder legt das Ziel-SLO für die Azure SQL-Datenbank, die zu aktualisierenden.</span><span class="sxs-lookup"><span data-stu-id="612e3-111">Gets or sets the target Service Level Objective for the Azure SQL database being upgraded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>